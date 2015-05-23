1. cd to the joe directory with one command.  
    - `cd chapter_4/temp/stuff/things/frank/joe`
2. cd back to temp with one command, but not further above that.
    - `cd ../../../..`
3. Find out how to cd to your "home directory" with one command.
    - `cd ~`
4. cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).
    - `cd Documents`
5. cd to your Downloads directory, then find it with your file browser.
    - `cd ../Downloads`
6. Find another directory with your file browser, then cd to it.
    - `cd ../workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_5/temp/`
7. Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you have a directory I Have Fun, then you can do: cd "I Have Fun"
    - `cd ../../chapter_4/"I Have Fun"`
    
    
---

>Can you cd into the temp directory?

I would run `pwd` and it shows that I am currently in /Users/rebecca/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_4/I Have Fun.
To get to the temp directory I would run `cd ../../chapter_5/temp/`.


>Why don't we go into the temp directory?

When I run `pwd` I get /Users/rebecca/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_5/temp, so by running the command from question 1 I did go into the temp directory.

>Can you go to the slash temp directory?
 
I would run `cd /tmp`.

>Can you go to the slash temp slash log directory?

I would run `cd /tmp/log`.

>What does the .. argument to cd do?

The argument .. brings you back to the previous directory.
For example, if I run `pwd` it would return that I am presetnly in /Users/rebecca/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_5.
If I then run `cd ..` and then `pwd` I see that I have gone back, or up in the directories and I am now in /Users/rebecca/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises.

