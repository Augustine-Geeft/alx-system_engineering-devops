This directory contains the following files:

0-iam_betty
Script that switches the current user to a user named 'betty'

1-who_am_i
Script that prints the effective username of the current user.

2-groups
Script that prints all the groups the current user is part of.

3-new_owner
Script that changes the owner of a file (e.g: hello) to a different user (e.g: betty).

4-empty
Script that creates an empty file.

5-execute
Script that adds execute permission to the owner of the file.

6-multiple_permissions
Script that adds execute permission to the owner and the group owner, and read permission to other users of the file.

7-everybody
Script that adds execution permission to the owner, the group owner and the other users of a file.

8-James_Bond
Script that sets all the permission to only other users (owner and group gets no permission) of the file.

9-John_Doe
Script that sets the permission of the file to -rwxr-x-wx.

10-mirror_permissions
Script that sets the permission mode of a file, the same as another file.

11-directories_permissions
Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12-directory_permissions
Script that creates a directory with specific permissions in the working directory.

13-change_group
Script that changes the group owner of a file.

100-change_owner_and_group
Script that changes both the owner and group owner of all the files and directories in the working directory.