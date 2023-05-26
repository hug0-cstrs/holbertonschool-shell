# Shell, init files, variables and expansions

Project done during **Full Stack Software Engineering studies** at **Holberton School**. It aims to learn about alias builtin, help builtin, local, global and reserved variables (PATH, HOME and PS1), special parameters `$?` and single an double quotes in **Shell**.

# Technologies
* C files are compiled using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
* C files are written according to the `C89 standard`
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
* You are not allowed to use `sed` or `awk`
* All your files must be executable

## Files :scroll:
All of the following files are scripts:

|**Filename**|**Description**|
|:-------|:---------:|
| `0-alias` | Creates an alias |
| `1-hello_you` | Prints `hello user`, where user is the current Linux user |
| `2-path` | Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program |
| `3-paths` | Counts the number of the directories in the `PATH` |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists all local variables and environment variables, and functions |
| `6-create_local_variable` | Creates a new local variable named `BETTY` |
| `7-create_global_variable` | Creates a new global variable named `HOLBERTON` |
| `8-true_knowledge` | Prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line |
| `9-divide_and_rule` | Prints the result of `POWER` divided by `DIVIDE`, followed by a new line |
| `10-love_exponent_breath` | Displays the result of `BREATH` to the power `LOVE` |
| `11-binary_to_decimal` | Converts a number from base 2 to base 10 |
| `12-combinations` | Prints all possible combinations of two letters, except `oo` |
| `13-print_float` | Prints a number with two decimal places. The number is stored in the environment variable `NUM` |
| `14-decimal_to_hexadecimal` | Converts a number from base 10 to base 16 |
| `15-rot13` | Encodes and decodes text using the rot13 encryption |
| `16-odd` | Prints every other line from the input, starting with the first line |
| `17-water_and_stir` | Adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result |
