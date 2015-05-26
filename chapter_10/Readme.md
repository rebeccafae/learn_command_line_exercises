> Explain what Robocopy is:

Robocopy is "Robust File Copy." It is used to copy folders, keeping them in the same form ar they were (it copies everything).

> Do More Section:

- I ran `cp -r newplace/ do_more`

- I ran `cd ~`, then I ran ` cp workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_10/tmp/iamcool.txt Desktop/` to copy iamcool.txt to my Desktop.

- I found the files in in the GUI (Finder) and opened them in Ruby Mine, which I am already in writing this Readme.md

> Can you copy the foo.txt file to slash temp?

First I created the file in the chapter_10 directory by running `touch foo.txt`.
Then I ran `cp foo.txt /tmp`.

> Can you copy .bash_profile in your home directory to the current directory?

From the chapter_10 directory I would run `cp ~/.bash_profile .`

> Can you zero out a file?

Yes. I would run `cp /dev/null log/production.log`.