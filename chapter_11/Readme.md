> Move a file in the newplace directory to another directory then move it back.

I would run `mv newplace/example.txt example.txt`.

To move it back I would run `mv example.txt newplace/example.txt`

> Can you rename foo.txt to blah.txt?

Yes. I would run `mv foo.txt blah.txt`

> Can you move the production.log file in the log directory to slash temp?

Yes, I would run `mv log/production.log /tmp`

> Can you zero out that file?

Yes. Moving it to an existing file zero's it out. I ran `mv /tmp/production.log tmp/blah.txt` and now when I open blah.txt it is empty.

Another way is to run `cp /dev/null log/production.log`.