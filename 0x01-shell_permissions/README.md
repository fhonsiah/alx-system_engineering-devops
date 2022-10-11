# 0x01.Shell, permissions
Tasks
# 0.A script that swithes the current user to the user betty.
  use the command # su betty
# 1.A script that the effective username of the current user
  use the command # whoami
# 2.A script that prints all the groups the current user is part of.
  use the command # groups
# 3.A script that changes to owner of the file hello to betty
  use the command # chown betty hello
# 4.A script that creates an empty file called hello
  use the command # touch hello
# 5.A script that adds execute permissions to the owner of the file hello
  use the command # chmod u+x hello
# 6.A script that adds execute permissions to the owner and the group owner, and read permissions to the user.
  use the command # chmod ug+x,o+r hello
# 7.A script that adds execute permisiions to the owner,the group owner and the other users, to the file hello
   use the command # chmod a+x hello
# 8.A script that adds permission to read,write and execute to other users, no permissions to the owner,the group owner.
   use the command # chmod 007 hello
# 9.A script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien 23 Sep 20 14:25 hello.
  use the command # chmod 753 hello
# 10.A script that sets the mode of the file hello the same as olleh's mode.
   use the command # chmod --reference=olleh hello
# 11.A script that adds execute permissions to all subdirectories of the current directory for the owner,the group owner and all the users.
  use the command # find . -type d -exec chmod ugo+x {} +
# 12.A script that creates a irectory callded my_dir with permissions 751 in the working directory.
  use the command # mkdir -m 751 my_dir
# 13. A script that changes the group owner to school of the file hello
  use the command # chgrp school hello
