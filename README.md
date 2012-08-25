git-sandbox
===========

sandbox for doing things with git.  Please ignore.

Here's an edit I made of README.md while in the develop branch!

This line is a further refinement to this already refined file.

I edited this line in the master branch, which is bad practice in my opinion.
do development in the develop branch, once refined, merge to master.  It helps
to think of master as the 'release' branch, software is only merged in when it
is considered complete for the end-user.  If any issues crop up, and the code
must be updated (for, say, security purposes), a new branch from master is
created, the code updated, then the security branch gets merged into master.
The developement branch must then merge the security branch into it, so that
the security fix is still there when dev. eventually gets merged to master.
/rambling
