#!/bin/bash
Task 0 - The command 'su betty' is to switch user to betty
Task 1 - The command 'whoami' print the effective username of the user
Task 2 - The command 'groups' is to print all groups the current user is a part of
Task 3 - the command 'chown betty hello' to change ownership of hello to user betty
Task 4 - The command 'touch hello' is to create an empty file named hello
Task 5 - The command 'chmod u+x hello' is to make the file
Task 6 - The command 'chmod ug+x,o+r hello' to add exedcute permission to owner and group owner, and read permission for other users
Task 7 - The command 'chmod ugo+x hello' to add execute permission to owner , group owner and other users
Task 8 - The command 'chmod 007 hello' to change permission of owner and group owner to no permission and to change permission of other users to all permissions
Task 9 - The command to change the permission of hello to -rwxr-x-wx is chmod 753 hello
Task 10 - The command to copy permissions from olleh to hello 'chmod --reference=olleh hello'
Task 11 - command that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed 'chmod a+X *'
Task 12 - command to mkdir and set permissions 751 is' mkdir -m 751 my_dir'
Task 13 - 'chgrp school hello 'to change group to school for the file 'hello'
Task 14 - 'chown vincent:staff *' to change owner vincent to group owner staff
Task 15 - 'chown _hello:vincent,staff *' to change owner and group owner of _hello to vincent and staff
Task 16 - 'chown --from=guillaume betty hello' to change the owner of hello to betty only if its owned by guillaumei
Task 17 - 'vlc StarWars IV' to play StarWars IV from terminal
