0. "su" - Create a script that switches the current user to the user.
1. "id -un" - Write a script that prints the effective username of the current user.
2. "id -un" - Write a script that prints all the groups the current user is part of.
3. "sudo chown <user> <filename>" - Write a script that changes the owner of a file to another user.
4. "touch" - Write a script that creates an empty file.
5. "chmod 744" - Write a script that adds execute permission to the owner of a file.
6. "chmod 754" - Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to a file.
7. "chmod ugo+x" - Write a script that adds execution permission to the owner, the group owner and the other users, to a file.
8. "chmod 007" - Write a script that sets the permission to a file as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions.
9. "chmod 753" - Write a script that sets the mode of the file hello to this: -rwxr-x-wx
10. "chmod --reference=olleh hello" - Write a script that sets the mode of the file hello the same as olleh’s mode.
11. "chmod -R ugo+X  ." - Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12. "mkdir -m 751 my_dir" - Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13. "chgrp school hello" - Write a script that changes the group owner to school for the file hello.
14. "chown -hR vincent:staff ." - Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. "chown -h vincent:staff _hello" - Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link.
16. "chown --from=guillaume betty hello" - Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
17. "telnet towel.blinkenlights.nl" Write a script that will play the StarWars IV episode in the terminal.
