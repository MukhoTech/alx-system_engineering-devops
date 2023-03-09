su betty  =>  script that switches the current user to the use
id -u -n => a script that prints the effective username of the current user
id - Gn => a script that prints all the groups the current user is part of.
sudo chown betty hello => a script that changes the owner of the file
touch hello => a script that creates an empty file called hello
chmod u+x hello => a script that adds execute permission to the owner of the file
chmod u=x,g=x,o=r hello => a script that adds execute permission to owner,group and others 
chmod 111 hello => a script that adds execution permission to the owner,group and other
chmod 000 hello => a script that sets null permission to the file
