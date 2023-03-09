su betty - switch user to betty

whoami - prints username of the current user

groups - print all groups of the current user 

sudo chown  betty hello - changes ownership of hello file to user betty

touch hello - create an empty file hello

chmod u+x hello - adds owner execute privilages

chmod ug+x,o+r hello - adds owner and owner execute privililages and other users read only

chmod ugo+x hello - grants owner group and others execute privilages 

chmod 007 hello - zero permissions to owner and group while granting rwx to other users

chmod 753 hello -grants owner rwx , group rx and only  write privilage to other users

chmod --reference=olleh hello - mirror permissions of file olleh on hello file

chmod -R a+X - recursive execute permissions to all subdirectorie

mkdir -m 751 my_dir - creates a directory with rwxr-x--x permissions

chgrp school hello - change group of hello to new group school
