PERMISSIONS

su otheruser > switch the current user to other user
whoami > prints the effective username of the current user
groups > prints all the groups the current user is part of
sudo chown you some_file > changes the owner of the file hello to the user betty
touch some_file > creates an empty file
chmod u+x file > adds execute permission to the owner of the file
chmod 754 hello > adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod a+x hello > adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello > sets the permission to the file hello
chmod 753 hello > sets the mode of the file -rwxr-x-wx
chmod --reference=olleh hello > sets the mode of the file hello the same as olleh's mode
