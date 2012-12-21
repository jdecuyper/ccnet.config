## `ccnet.a.config`: trigger, task and exec
Build is launched only if a change is detected in the SVN repository.
Use the SVN executable to commit and update files from a working copy on the server.
Run robocopy to copy the new files over to the inetpub directory.

## `ccnet.b.config`: trigger, sourcecontrol and exec 
Build is launched only if a change is detected in the SVN repository.
Use the sourcecontrol tag to update a working copy on the server.
Run robocopy to copy the new files over to the inetpub directory.

## `ccnet.c.config`: trigger, exec
Build is launched and forced at a regular interval.
Use the SVN executable to commit and update files from a working copy on the server.

## `ccnet.d.config`: trigger, nant
Build is launched and forced at a regular interval.
Use the NANT task to launch a build process.
