su betty  =>  script that switches the current user to the use
id -u -n => a script that prints the effective username of the current user
id - Gn => a script that prints all the groups the current user is part of.
sudo chown betty hello => a script that changes the owner of the file
touch hello => a script that creates an empty file called hello
chmod u+x hello => a script that adds execute permission to the owner of the file
chmod u=x,g=x,o=r hello => a script that adds execute permission to owner,group and others 
chmod 111 hello => a script that adds execution permission to the owner,group and other
chmod 000 hello => a script that sets null permission to the file
chmod 753 hello => a script that sets the mode of the file with given permissions
chmod -R u=rw,g=rw,o=r hello olleh => a script to set permission to two files in one directory
chmod a+x /var/0x01-shell_permissions => gives execution permission to the current directory and all subdirectrories
mkdir -m 751 my_dir => create new directory with predefined set of permission
chgrp school hello => a script that changes the group owner
chown -R vincent:staff 0x01-shell_permissions => change the owner and group owner
