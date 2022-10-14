# 0x01. Shell, permissions

**In this project, I leaned about:**

### **Permissions**

- What do the commands chmod, sudo, su, chown, chgrp do
- Linux file permissions
- How to represent each of the three sets of permissions (owner, group, and other) as a single digit
- How to change permissions, owner and group of a file
- Why can’t a normal user chown a file
- How to run a command with root privileges
- How to change user ID or become superuser

### **Other Man Pages**

- How to create a user
- How to create a group
- How to print real and effective user and group IDs
- How to print the groups a user is in
- How to print the effective userid

## Tasks

- **0. My name is Betty**
    * [0-iam_betty](/0x01-shell_permissions/0-iam_betty) : a script that switches the current user to the user betty
- **1.Who am I**
    * [1-who_am_i](/0x01-shell_permissions/1-who_am_i) : a script that prints the effective username of the current user
- **2.Groups**
    * [2-groups](/0x01-shell_permissions/2-groups) : a script that prints all the groups the current user is part of
- **3.New owner**
    * [3-new_owner](/0x01-shell_permissions/3-new_owner) : a script that changes the owner of the file hello to the user betty
- **4.Empty!**
    * [4-empty](/0x01-shell_permissions/4-empty) : a script that creates an empty file called hello
- **5.Execute**
    * [5-execute](/0x01-shell_permissions/5-execute) : a script that adds execute permission to the owner of the file hello
- **6.Multiple permissions**
    * [6-multiple_permissions](/0x01-shell_permissions/6-multiple_permissions) : a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
- **7.Everybody!**
    * [7-everybody](/0x01-shell_permissions/7-everybody) : a script that adds execution permission to the owner, the group owner and the other users, to the file hello
- **8.James Bond**
    * [8-James_Bond](/0x01-shell_permissions/8-James_Bond) : a script that sets the permission to the file hello as follows:
        - Owner: no permission at all
        - Group: no permission at all
        - Other users: all the permissions
- **9.John Doe**
    * [9-John_Doe](/0x01-shell_permissions/9-John_Doe) : a script that sets the mode of the file hello to this: _-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello_
- **10.Look in the mirror**
    * [10-mirror_permissions](/0x01-shell_permissions/10-mirror_permissions) - a script that sets the mode of the file hello the same as olleh’s mode
- **11.Directories**
    * [11-directories_permissions](/0x01-shell_permissions/11-directories_permissions) : a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
- **12.More directories**
    * [12-directory_permissions](/0x01-shell_permissions/12-directory_permissions) : a script that creates a directory called my_dir with permissions 751 in the working directory
- **13.Change group**
    * [13-change_group](/0x01-shell_permissions/13-change_group) :  a script that changes the group owner to school for the file hello
- **14.Owner and group**
    * [100-change_owner_and_group](/0x01-shell_permissions/100-change_owner_and_group) : a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
- **15.Symbolic links**
    * [101-symbolic_link_permissions](/0x01-shell_permissions/101-symbolic_link_permissions) : a script that changes the owner and the group owner of hello to vincent and staff respectively
-  **16.If only**
    * [102-if_only](/0x01-shell_permissions/102-if_only) : a script that changes the owner of the file hello to betty only if it is owned by the user guillaume
- **17.Star Wars**
    * [103-Star_Wars](/0x01-shell_permissions/103-Star_Wars) :  a script that will play the StarWars IV episode in the terminal

