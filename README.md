CUBEHASH 

-X11
-Ticker: CBH
-Block Mature: 40 
-Targetspacing: 60
-PoS: 50 % yearly
-Custom 0 block rewards during PoW
-Anti-hash renting
-supply: 410k


blocks structure:

Block: 0-10: 7000 CBH
Block: 0-60: 0 CBH
Block: 60-560: 400 CBH
Block: 560-760: 0 CBH
Block: 760-1060: 300 CBH
Block: 1060-1260: 0 CBH
Block: 1260-1560: 200 CBH
Block: 1560-1770: 0 CBH
Block: 1770-2060: 100 CBH
Block: 2060-2260: 0 CBH
Block: 2260-2560: 50 CBH
Block: 2560-2960: 20 CBH




Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of cubehash.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
