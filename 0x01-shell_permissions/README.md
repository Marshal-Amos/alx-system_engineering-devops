# 0x01. Shell, Permissions

[0-iam_betty](/0x01-shell_permissions/0-iam_betty) - A script that switches the current user to the user *betty*. (Using exactly 8 characters for the command (+1 character for the new line)

[1-who_am_i](/0x01-shell_permissions/1-who_am_i) - A script that prints the effective username of the current user.

[2-groups](/0x01-shell_permissions/2-groups) - A script that prints all the groups the current user is part of.

[3-new_owner](/0x01-shell_permissions) - A script that changes the owner of the *hello* to the user *betty*.

[4-empty](/0x01-shell_permissions/4-empty) - A script that creates an empty file called *hello*.

[5-execute](/0x01-shell_permissions/5-execute) - A script that adds execute permission to the owner of the file *hello*. The file *hello* will be in the working directory.

[6-multiple_permissions](/0x01-shell_permissions/6-multiple_permissions) - A script that adds execute permission to the owner and the group owner, and read permission to other users, to thw file *hello*. The file *hello* will be in the working directory.

[7-everybody](/0x01-shell_permissions/7-everybody) - A script that adds execution permission to the owner, the group owner and the other users, to the file *hello*. Commas are not allowed for this script.

[8-James_Bond](/0x01-shell_permissions/8-James_Bond) - A script that sets permission to the file *hello* as follows:
> > > > > * Owner: no permission at all.
> > > > > * Group: no permission at all.
> > > > > * Other users: all the permissions.
The file *hello* will be in the working directgory. Commas are not allowed for this script.

[9-John_Doe](/0x01-shell_permissions/9-John_Doe) - A script that sets the mode of the file *hello* to this:
> > > > >	
		 ```
 		-rwxr-x-wx 1 julien juelien 23 Sep 20 14:25 hello
		 ```

[10-mirror_permissions](/0x01-shell_permissions/10-mirror_permissions) - A script that sets the mode of the file *hello* the same as *olleh*'s mode. The file *hello* and the file *olleh* will all be in the working directory.

