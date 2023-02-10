file 0-iam_betty switches the current user to the user betty.

file 1-who_am_i prints the effective username of the current user.

file 2-groups prints all the groups the current user is part of.

file 3-new_owner changes the owner of the file hello to the user betty.

file 4-empty creates an empty file called hello.

file 5-execute adds execute permission to the owner of the file hello.

file 6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

file 7-everybody adds execution permission to the owner, the group owner and the other users, to the file hello

file 8-James_Bond sets the permission to the file hello to all permission for groups only and non to the rest

file 9-John_Doe sets the mode of the file hello to "-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello"

file 10-mirror_permissions sets the mode of the file hello the same as olleh’s mode 

file 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

file 12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory.

file 13-change_group changes the group owner to school for the file hello in the working directory.

file 100-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

file 101-symbolic_link_permissions changes the owner and the group owner of _hello to vincent and staff respectively.

file 102-if_only changes the owner of the file hello to betty only if it is owned by the user guillaume.

file 103-Star_Wars plays the StarWars IV episode in the terminal.
