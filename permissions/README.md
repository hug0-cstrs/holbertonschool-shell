# Shell, permissions
Project done during **Full Stack Software Engineering studies** at **Holberton School**. It aims to learn about man pages, permissions (owner, group and other) of files and directories in **Shell**.
<p align="center"><img src="https://www.oreilly.com/api/v2/epubs/9781788993197/files/assets/99c02f63-3014-4df0-8990-b9474944f298.jpg" /></p>

# Technologies
* Scripts written in Bash 5.0.17(1)
* Tested on Ubuntu 20.04 LTS

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
All of the following files are scripts:

| **Filename** | **Description** |
|:-------|:---------:|
| `0-iam_betty` | Changes your user ID to `betty` |
| `1-who_am_i` | Prints the effective userid of the current user |
| `2-groups` | Prints all the groups the current user is part of |
| `3-new_owner` | Changes the owner of the file `hello` to the user `betty` |
| `4-empty` | Creates an empty file called `hello` |
| `5-execute` | Adds execute permission to the owner of the file `hello` |
| `6-multiple_permissions` | Adds execute permission to the owner and the group owner, and reads permission to other users, to the file `hello` |
| `7-everybody` | Adds execution permission to the owner, the group owner and the other users, to the file `hello` |
| `8-James_Bond` | Write a script that sets the permission to the file `hello` to other users |
| `9-John_Doe` | Sets the `-rwxr-x-wx` permissions to the file `hello` |
| `10-mirror_permissions` | Sets the mode of the file `hello` the same as `olleh`'s mode |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory for the owner, the group of the owner and all the other users |
| `12-directory_permissions` | Creates a directory called `dir_holberton` with permissions 751 in the working directory |
| `13-change_group` | Changes the group owner to `holberton` for the file `hello` |
| `14-change_owner_and_group` | Changes the owner to `betty` and the group owner to `holberton` for all the files and directories in the working directory |
| `15-symbolic_link_permissions` | Changes the owner and the group owner of the file `_hello` to `betty` and `holberton` respectively |
| `16-if_only` | Changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume` |
|`README.md`|Readme file of this project|
