0-iam_betty switches the current user to the user betty
The 1-who_am_i prints the effective username of the current user.
The 2-groups prints all the groups the current user is part of
The 3-new_owner changes the owner of the file hello to the user betty
The 4-empty creates an empty file called hello
The 5-execute Write a script that adds execute permission to the owner of the file hello
The 6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
The 7-everybody adds execution permission to the owner, the group owner and the other users, to the file hello
The 8-James_Bond sets the permission to the file hello as Owner: no permission at all, Group: no permission at all and Other users: all the permissions
The 9-John_Doe sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
The 10-mirror_permissions sets the mode of the file hello the same as olleh’s mode
The 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
The 12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory
The 13-change_group changes the group owner to school for the file hello 
