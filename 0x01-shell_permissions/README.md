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

		 ```
 		-rwxr-x-wx 1 julien juelien 23 Sep 20 14:25 hello
		 ```

[10-mirror_permissions](/0x01-shell_permissions/10-mirror_permissions) - A script that sets the mode of the file *hello* the same as *olleh*'s mode. The file *hello* and the file *olleh* will all be in the working directory.

[11-directories_permissions](/0x01-shell_permissions/11-directories_permissions) - A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files are not to be included.

[12-directory_permissions](/0x01-shell_permissions/12-directory_permissions) - A script that creates a directory called *my_dir* with permissions 751 in the working directory.

[13-change_group](/0x01-shell_permissions/13-change_group) - A script that changes the group owner to *school* for the file *hello*. The file *hello* will be in the working directory.

[100-change_owner_and_group](/0x01-shell_permissions/100-change_owner_and_group) - A script that changes the owner to *vincent* and the group owner to *staff* all the files and directories in the working directory.

[101-symbolic_link_permissions](/0x01-shell_permissions/101-symbolic_link_permissions) - A script that changes the owner and the group owner of *_hello* to *vincent* and *staff* respectively.

[102-if_only](/0x01-shell_permissions/102-if_only) - A script that changes the owner of the file *hello* to *betty* only if it is owned by the user *guillaume*. The file *hello* will be in the working directory.

[103-Star_Wars](/0x01-shell_permissions/103-Star_Wars) - A script that will play the StarWars IV episode in the terminal.

