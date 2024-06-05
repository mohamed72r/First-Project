Example : -r--r-xr-x

"r" for read
"w" for write
"x" for execute
- is for a regular file, d for a directory (folder), l for symlink
the first 3 characters are for Owner Permissions.
In our case Owner can read only
the second 3 characters are for Group Permissions.
In our case Group can read and execute
the last 3 characters are for Everyone Permissions.
In our case everyone can read and execute.

A symlink is type of file which only contains a link to another file.
Reading a symlink reads the real file.
Writing to a symlink writes to the real file.
cd-ing to a symlink that is to a directory results in behaviour almost identical to what would happen if you had cd'd into the real directory.
