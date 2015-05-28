> What is your shell set to?

I can run either `env | grep SHELL` or `echo $SHELL` to see what my shell is set to. Mine is set to /bin/bash.

> What directory are you in (don't use pwd this time)?

I would run `echo $PWD` and it returns my current directoy, /Users/rebecca/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_21

> What is your home directory set to?

I would run either `env | grep HOME` or `echo $HOME` and it would return /Users/rebecca

> Can you set your environment to have DEBUG set to true?

Yes, I would run `export DEBUG=true`.
Then I can run `echo $DEBUG` and see the return 'true'.