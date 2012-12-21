#CCNET.CONFIG 

## Trigger, task and exec (`ccnet.a.config`)
Build is launched only if a change is detected in the SVN repository.
Use the SVN executable to commit and update files from a working copy on the server.
Run robocopy to copy the new files over to the inetpub directory.

## Trigger, sourcecontrol and exec (`ccnet.b.config`)
Build is launched only if a change is detected in the SVN repository.
Use the sourcecontrol tag to update a working copy on the server.
Run robocopy to copy the new files over to the inetpub directory.

## Trigger, exec (`ccnet.c.config`)
Build is launched and forced at a regular interval.
Use the SVN executable to commit and update files from a working copy on the server.
