> Explain what the pushd and popd commands do, in your own words.

`pushd` saves where you currently are and goes to the directory you ask it to take you to. If you don't specify where it should take you, it takes you to the last saved directory (the other one that appears in the output).

`popd` returns you to the saved directory, and it 'deletes' the directory you left from the saved directories (it won't be in the output anymore).

The output that appears after you run these commands shows you what directories are saved. This is really usful for knowing where you will be next if you popd or pushd with no other input.

> Directories I visited:

`pushd stuff/things/frank/joe/` (joe)

`popd` (tmp)

`pushd stuff/things` (things)

`pushd frank/joe/alex/john/` (john)

`pushd` (things)

`popd` (john)

`popd` (tmp)