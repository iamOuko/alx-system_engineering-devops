Shell Scripts Permissions


su betty ===  switches the current user to the user betty.

whoami === Print the effective username of current user. 

groups === Prints all the groups the current user is part of.

chown betty hello === Changes the owner of the file hello to the user betty

touch hello === Create an empty file called hello

chmod u+x hello === Adds execute permission to the owner of the file hello

chmod ug+x,o+r hello === Adds execute permission to owner and group owner, and read permission to other users to the file hello

chmod ugo+x hello === adds execution permission to the owner, the group owner and the other users, to the file hello.

chmod 007 hello === Set permissions to the file hello so owner and group don't have any permissions but other users have all permissions.

chmod 753 hello === Set permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

chmod --reference=olleh hello === sets the mode of the file hello the same as olleh’s mode.

chmod -R +X . === Add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

mkdir -m 751 my_dir === Create a script that creates a directory called my_dir with permissions 751 in the working directory.

chgrp school hello  === changes the group owner to school for the file hello

chown vincent:staff * === changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

chown -h vincent:staff _hello === changes the owner and the group owner of _hello to vincent and staff respectively.

chown --from=guillaume betty hello === Change owner of the file hello to betty only if it is owned by the user guillaume.

telnet towel.blinkenlights.nl === Play the Star Wars IV episode in the terminal.

