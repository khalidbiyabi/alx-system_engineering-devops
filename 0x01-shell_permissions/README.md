Script that switches the current user to the user betty : command is su user

Script that prints the effective username of the current user : command is id -un

Script that prints all the groups the current user is part of : comamnd is is -Gn

Script that changes the owner of the file hello to the user betty : command is chown new_owner file_name

Script that creates an empty file called hello : command is touch file_name

Script that adds execute permission to the owner of the file hello : command is chmod u+x file_name

Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello : command is chmod ug+x,o+r file_name

Script that adds execution permission to the owner, the group owner and the other users, to the file hello : command is chmod ugo+x file_name

Script that sets the permission to the file hello Owner: no permission at all, Group: no permission at all & Other users: all the permissions : command is 007 file_name

Script that sets the mode of the file hello to rwxr-x-wx : command is chmod 753 file_name
