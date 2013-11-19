up
==

A bash script for moving up directories.


How to use
----------

Place this file somewhere in your PATH where bash will find it as a command, and make it executable (`chmod a+x up`).
Or, put an alias for it in your .bashrc. Either method should work.

Then, try opening a new bash terminal, and type the following:

    $ up

Your shell should move up a directory automatically (to `/home` if your bash is configured to start in your home folder), as if you'd typed `cd ..`.

If you're *really* deep in - say, in a directory called `/home/joe/files/data/junk/stuff/random/misc/garbage` - and want to jump out of multiple levels of directory at once - say, four levels - type:

    $ up 4
  
And your shell will move up four levels at once to `/home/joe/files/data/junk`, as if you'd typed `cd ../../../..`.
