> Make 20 more directories and remove them all.

I ran `mkdir -p one/two/three/four/five/six/seven/eight/nine/ten` and `mkdir -p 11/12/13/14/15/16/17/18/19/20`.

Then I ran `cd one/two/three/four/five/six/seven/eight/nine`.

Next I ran `rmdir ten/`, `cd ..`, `rmdir nine/`, `cd ..`, `rmdir eight/`, `cd ..`, `rmdir seven/`, `cd ..`, `rmdir six/`, `cd ..`, `rmdir five/`, `cd ..`, `rmdir four/`, `cd ..`, `rmdir three/`, `cd ..`, `rmdir two/`, `cd ..`, `rmdir one/`, `cd ..`.

Last I ran `cd tmp` and `rmdir -p 11/12/13/14/15/16/17/18/19/20/`.

> Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

I ran `mkdir -p foo/blah/bored/alladin/aboo/carpet/genie/lamp/jasmin/jafar` (I was watching Alladin while doing this).

Then I removed them, one at a time, by doing the following:

`cd foo/blah/bored/alladin/aboo/carpet/genie/lamp/jasmin/`

`rmdir jafar/`

`cd ..`

`rmdir jasmin/`

`cd ..`

`rmdir lamp/`

`cd ..`

`rmdir genie/`

`cd ..`

`rmdir carpet/`

`cd ..`

`rmdir aboo/`

`cd ..`

`rmdir alladin/`

`cd ..`

`rmdir bored/`

`cd ..`

`rmdir blah/`

`cd ..`

`rmdir foo/`

`cd ..`

> Can you remove the tmp directory?

Yes, I am already in the chapter_7 directory, so I would run `rmdir tmp/`

> Let's remove the tmp directory.

Okay. I did what I said above. I checked that is was removed by running `ls`. It returned 'Readme.md'