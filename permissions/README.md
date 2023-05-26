# Shell, permissions
<p align="center"><img src="https://www.oreilly.com/api/v2/epubs/9781788993197/files/assets/99c02f63-3014-4df0-8990-b9474944f298.jpg" /></p>

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line (`why?`)
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use `backticks`, `&&`, `||` or `;`
* All your files must be executable

## Files :scroll:
All of the following files are programs written in Shell :

|**Filename**|**Description**|
|:-------|:---------:|
|`0-iam_betty`|Script that switches the current user to the user `betty`|
|`1-who_am_i`|Script that prints the effective username of the current user|
|`2-groups`|Script that prints all the groups the current user is part of|
|`3-new_owner`|Script that changes the owner of the file `hello` to the user `betty`|
|`4-empty`|Script that creates an empty file called `hello`|
|`5-execute`|Script that adds execute permission to the owner of the file `hello`|
|`6-multiple_permissions`|Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`|
|`7-everybody`|Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`|
|`8-James_Bond`|Script that sets the permission to the file hello as follows:<br>* Owner: no permission at all<br>* Group: no permission at all<br>* Other users: all the permissions|
|`9-John_Doe`|Script that sets the mode of the file `hello`|
|`10-mirror_permissions`|Script that sets the mode of the file `hello` the same as `olleh`’s mode|
|`11-directories_permissions`|Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed|
|`12-directory_permissions`|Script that creates a directory called `my_dir` with permissions 751 in the working directory|
|`13-change_group`|Script that changes the group owner to `school` for the file `hello`|
|`14-change_owner_and_group`|Script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory|
|`15-symbolic_link_permissions`|Script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively|
|`16-if_only`|Script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`|
|`README.md`|Readme file of this project|
