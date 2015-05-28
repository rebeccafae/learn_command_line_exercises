> Show me the lines in foo.txt that have "ERROR" in them.

I would run `grep ERROR foo.txt`. And it would return "I am an ERROR."

> Show me the lines in bar.txt that have "davinci" in them.

I would run `grep davinci bar.txt`

> Can you print all the lines in text files that have your first and last name in them?

I would run `grep "Rebecca Jackson" *.txt`. It would return "My name is Rebecca Jackson." from foo.txt.

> Explain what the -i option to grep accomplishes.

The -i ignores whether the letters are capitalized or not. If I run `grep -i this *.txt` it will return the lines with "This is a new file." and "This is an old file." because it ignores if it is this or This.