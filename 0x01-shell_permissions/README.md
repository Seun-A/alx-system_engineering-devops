# Shell: Permissions

## Table of Content: 
<br />

| File | Script Description | 
--- | ---
<br/><span style="font-size: 1.7rem">**Mandatory**</span>
[0-iam_betty](./0-iam_betty) | Switches the current user to the user `betty` <ul><li>You should use exactly 8 characters for your command (+1 character for the new line)</li><li>You can assume that the user `betty` will exist when we will run your script</li></ul>
[1-who_am_i](./1-who_am_i) | Prints the effective username of the current user
[2-groups](./2-groups) | Prints all the groups the current user is part of
[3-new_owner](./3-new_owner) | Changes the owner of the file `hello` to the user `betty`
[4-empty](./4-empty) | Creates an empty file called `hello`
[5-execute](./5-execute) | Adds execute permission to the owner of the file `hello` <ul><li>The file `hello` will be in the working directory</li></ul>
[6-multiple_permissions](./6-multiple_permissions) | Adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello` <ul><li>The file `hello` will be in the working directory</li></ul>
[7-everybody](./7-everybody) | Adds execution permission to the owner, the group owner and the other users, to the file `hello` <ul><li>The file `hello` will be in the working directory</li><li>You are not allowed to use commas for this script</li></ul>
[8-James_Bond](./8-James_Bond) | Sets the permission to the file `hello` as follows: <ul><li>Owner: no permission at all</li><li>Group: no permission at all</li><li>Other users: all the permissions</li></ul> <br />The file `hello` will be in the working directory You are not allowed to use commas for this script
[9-John_Doe](./9-John_Doe) | Sets the mode of the file `hello` to this
[10-mirror_permissions](./10-mirror_permissions) | Sets the mode of the file `hello` the same as `olleh`’s mode <br /><ul><li>The file `hello` will be in the working directory</li><li>The file `olleh` will be in the working directory</li></ul>
[11-directories_permissions](./11-directories_permissions) | Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
[12-directory_permissions](./12-directory_permissions) | Creates a directory called `my_dir` with permissions 751 in the working directory
[13-change_group](./13-change_group) | Changes the group owner to `school` for the file `hello` <ul><li>The file `hello` will be in the working directory</li></ul>
<br/><span style="font-size: 1.7rem">**Advanced** </span>
[100-change_owner_and_group](./100-change_owner_and_group) | Changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory
[101-symbolic_link_permissions](./101-symbolic_link_permissions) | Changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively <ul><li>The file `_hello` is in the working directory</li><li>The file `_hello` is a symbolic link</li></ul>
[102-if_only](./102-if_only) | Changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume` <ul><li>The file `hello` will be in the working directory</li></ul>
[103-Star_Wars](./103-Star_Wars) | Play the StarWars IV episode in the terminal

# 
<br>

## **Author:** [Seun Ajayi](https://github.com/Seun-A)