# Shell permissions

Project done during **Full Stack Software Engineering studies** at **ALX**. It aims to learn about Linux file permissions, represent each of the three sets of permissions (owner, group, and other) as a single digit, change permissions and commands (`chmod`, `sudo`, `su`, `chown`, ... ).

## Files
All of the following files are scripts.


> * [0-iam_betty](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty)
>> A script that switches the current user to the user `betty`.
------------------
> * [1-who_am_i](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i)
>> A script that prints the effective username of the current user.
------------------
> * [2-groups](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups)
>> A script that prints all the groups the current user is part of.
------------------
> * [3-new_owner](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner)
>> A script that changes the owner of the file `hello` to the user `betty`.
------------------
> * [4-empty](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty)
>> A script that creates an empty file called `hello`.
------------------
> * [5-execute](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute)
>> A script that adds execute permission to the owner of the file `hello`.
------------------
> * [6-multiple_permissions](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions)
>> A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
------------------
> * [7-everybody](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody)
>> A script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
------------------
> * [8-James_Bond](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond)
>> A script that sets the permission to the file `hello` as follows:
>>> - _Owner_ : `No permission at all`.
>>> - _Group_ : `No permission at all`.
>>> - _Other users_ : `all the permissions`.
------------------
> * [9-John_Doe](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe)
>> A script that sets the mode of the file `hello` to this:
>>> `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`
------------------
> * [10-mirror_permissions](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions)
>> A script that sets the mode of the file `hello` the same as `olleh`’s mode.
------------------
> * [11-directories_permissions](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions)
>> A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
>> _Regular files will not be changed._
------------------
> * [12-directory_permissions](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions)
>> A script that creates a directory called `my_dir` with permissions `751` in the working directory.
------------------
> * [13-change_group](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group)
>> A script that changes the group owner to `school` for the file `hello`.
------------------
> * [100-change_owner_and_group](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/100-change_owner_and_group)
>> A script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.
------------------
> * [101-symbolic_link_permissions](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/101-symbolic_link_permissions)
>> A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.
>>> _The file `_hello` is a symbolic link_
------------------
> * [102-if_only](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/102-if_only)
>> A script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.
------------------
> * [103-Star_Wars](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/103-Star_Wars)
>> A script that will play the Star Wars IV episode in the terminal.
>>> _used to work :(_
