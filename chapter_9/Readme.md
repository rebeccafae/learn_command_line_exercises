> Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

From the chapter_9 directory I ran `mkdir practice` and `cd practice`, then I ran `touch test.txt`.
To change one level up I ran `cd ..` which put me back in the chapter_9 directory.
I ran `rmdir practice/` and it returned an error that said "rmdir: practice/: Directory not empty".
I got this error because there is a file in the directory, and you cannot remove directories that are not empty using rmdir.

> Can you touch blah.txt?

Yes. I would run `touch blah.txt`

> Let's create foo.txt

I ran `touch foo.txt`

> Explain what happens if you touch an existing file:

I ran `touch foo.txt` again. I do not get an error message, it appears that nothign at all happens. When I `ls` and when I check the GUI, there is still only one foo.txt file.