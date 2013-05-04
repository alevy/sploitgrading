# Sploits Grading Script

A set of simple scripts to test whether student sploits gain a root shell.

## Setup

The VM needs to be setup in the following way for the script to run correctly

  1. Replace `/bin/sh` with the script in `testsh` (as root):
      
      $ unlink /bin/sh
      $ cat testsh > /bin/sh
      $ chmod +x /bin/sh

  2. Stick `testall` and `test_sploit` in the `user` home directory and make
     sure they are runnable by `user`

  3. Prepare the targets in /tmp

## Running

Put the students submissions in `$HOME/pp1/sploits/` and compile them. Then,
from `$HOME`, simply run:

    
    $ ./testall

This will print out output like:
    
    sploit1,1
    sploit2,1
    sploit3,0
    sploit4,1
    ...
    
where 1 means the test passed (they got a shell) and 0 means they failed misseraly!


