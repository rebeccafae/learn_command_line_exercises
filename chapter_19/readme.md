> What option to ls tells it to output file size in human readable form?

I would run `man ls` to find the correct option. `ls -lh` will output the size in human readable form (i.e. Byte, Kilobyte).

> Is there a case insensitive option to grep?

`grep -i`

> What does the -r and -f options to rm do exactly?

The -r option removes the file hierarchy rooted in each file argument (it deletes all the files recursively)

The -f option removes files without asking for confirmation, regardless of the file's permissions.

> What does the ifconfig command do?

`ifconfig` configures network interface parameters. It is used to assign an address and/or configure parameters to a network interface.