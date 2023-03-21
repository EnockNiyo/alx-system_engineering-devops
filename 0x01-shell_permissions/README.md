# Shell Permissions

Task 0:
	 su betty
	 Script that switches the current user to the user betty.

Task 1:
	 whoami
	 script that prints the effective username of the current user.

Task 2:
	groups
	Script that prints all the groups the current user is part of.

Task 3:
	 chown betty hello
	 Script that changes the owner of the file `hello` to the user `betty`

Task 4:
	 touch hello
	 Script that creates an empty file called `hello`

Task 5:
	 chmod u+x hello
	 Script that adds execute permission to the owner of the file `hello`.

Task 6:
	 chmod ug+x,o+r hello
	 Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

Task 7:
	 chmod a+x hello
	 Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.

Task 8:
	 chmod 007 hello
	 Script that sets the permission to the file `hello` so owner and group don't have any permissions and other users have all permissions.

Task 9:
	 chmod 753 hello
	 Script that sets the mode of the file `hello` to `-rwxr-x-wx`

Task 10:
	 chmod --reference=olleh hello
	 Script that sets the mode of the file `hello` the same as `olleh`’s mode.

Task 11:
	 chmod a+X *
	 Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

Task 12:
	 mkdir -m 751 my_dir
	 Script that creates a directory called `my_dir` with permissions `751` in the working directory.

Task 13:
	 chgrp school hello
	 Script that changes the group owner to `school` for the file `hello`.

Task 14:
	 chown vincent:staff *
	 cript that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

Task 15:
	 chown -h vincent:staff _hello
	 Script that changes the owner and the group owner of _hello to `vincent` and `staff` respectively.

Task 16:
	 chown --from=guillaume betty hello
	 Script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

Task 17:
	 telnet towel.blinkenlights.nl
	 Script that will play the StarWars IV episode in the terminal.
