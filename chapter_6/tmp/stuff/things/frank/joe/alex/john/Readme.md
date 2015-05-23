> Describe what ls -lR does

ls -lR lists each directory and what is in that directory. It keeps going through all the directories in the branch until it gets to the end, in my case the Readme.md file in the john directory.

> Comments/Questions

- What is the total? It shows 0 for all directories, it then shows 8 for John.

- What is the number after the drwrx...? It shows 3 for all until it gets to john, and then shows 1.

---

> What's in the tmp directory?

I would run `ls chapter_6/tmp/` and it returns 'stuff'.

> Can you show me what files are in that directory?

I run `ls` and it returns 'stuff'. There are no files in the directory. If there were they would end with .md or something similar.


> What files are in your home directory?

I run `cd ~` to get to my home directory. Then I run `ls` and it returns Applications		Library			Programs
                                                                         Desktop			Movies			Public
                                                                         Documents		Music			RubymineProjects
                                                                         Downloads		Pictures		workspace

It appears I have no files in my home directory, only other directories.

> What's in slash temp?

If I run `ls /tmp` it returns 'KSOutOfProcessFetcher.501.qQkpPp2uZLdVc5pukHmfJMR4bkM=
                            com.apple.launchd.9cRuZZ9YCo
                            com.apple.launchd.KgNP2McTt8'
