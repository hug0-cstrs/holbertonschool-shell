# Shell, Basics

Project done during **Full Stack Software Engineering studies** at **Holberton School**. It aims to learn about basics commands, navigation, files and directories in **Shell**.

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
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use `backticks`, `&&`, `||` or `;`
* All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.

## Files :scroll:
All of the following files are scripts:

|**Filename**|**Description**|
|:-------|:---------:|
| `0-current_working_directory` | Prints the absolute path name of the current working directory |
| `1-listit` | Displays the content list of the current directory |
| `2-bring_me_home` | Changes the working directory to the user's home directory |
| `3-list_files` | Displays current directory contents in a long format |
| `4-listmorefiles` | Displays, in the long format, current directory contents, including hidden files |
| `5-listfilesdigitonly` | Displays current directory contents with user and group IDs |
| `6-firstdirectory` | Creates a directory named `holberton` in the `/tmp/` directory |
| `7-movethatfile` | Moves the file `betty` from `/tmp/` to `/tmp/holberton` |
| `8-firstdelete` | Deletes the file `betty` |
| `9-firstdirdeletion` | Deletes the directory `holberton` that is in the `/tmp` directory |
| `10-back` | Changes the working directory to the previous one |
| `11-lists` | Lists all files in the current directory and its parent directory and the `/boot` directory |
| `12-file_type` | Prints the type of the file named `iamafile` that is in the `/tmp` directory |
| `13-symbolic_link` | Creates a symbolic link to `/bin/ls`, named `__ls__` |
| `14-copy_html` | Copies all the HTML files from the current working directory to the parent directory, but only copies files that did not exist in the parent directory |
| `15-lets_move` | Moves all files beginning with an uppercase letter to the directory `/tmp/u` |
| `16-clean_emacs` | Deletes all files in the current working directory that end with the character `~` |
| `17-tree` | Creates the directories `welcome/`, `welcome/to/` and `welcome/to/holberton` in the current directory |
