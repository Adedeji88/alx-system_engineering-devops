su betty is used to switch the current user to the user betty
whoami is used to print the effective username of the current user
groups is used to print all the group a user is part of
chown betty hello is used to change the owner of the file hello to the user betty
chmod u+x hello is used to add executive permission to the owner of the file hello
chmod u+x,g+x,o+r hello is used to give multiple permissions
chmod ugo+x hello is used to give executive permission to everybody
chmod 007 hello is used to give the owner and group no permission and all the permissios to other users
chmod 753 hello is used for setting the file mode to the given mode
chmod --reference olleh hello
chmod -R a+X ./ is used to add executive permissions to all the subdirectories of the current directory for everybody
mkdir -m 751 my_dir creates a directory my_dir with the permission 751 in the working directory
chgrp school hello changes the group owner to school for the file hello
chown -R vincent:staff ./ is used to change the owner to vincent and the group owner to staff for all files and directories in working directory
chown -h vincent:staff _hello is used for the symbolic link
chown --from=guillaume betty hello changes the owner of the file hello to betty only if it owned by guillaume
telnet towel.blinkenlights.nl is used to play Star Wars IV