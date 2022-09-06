
# Shell, I/O Redirections and filters

A Project done at ALX Software Engineering to learn about: 
What the commands echo, cat, head, tail, find, wc, sort, uniq, grep, tr, rev, cut do
How to redirect standard output to a file
How to get standard input from a file instead of the keyboard
How to send the output from one program to the input of another program
How to combine commands and filters with redirections

## Technologies
Scripts are written in Bash, version 5.0.17(1)-release
Tested on Ubuntu 20.04 LTS
All the files below are executable scripts:

|## Filename | Description |
| -------- | ----------- |
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
| `18-commas` | Lists all the files and directories of the current directory, separated by commas (`,`) |
| `holberton.mgc` | Magic file that can be used with the command `file` to detect `Holberton` data files. `Holberton` data files always contain the string `HOLBERTON` at offset 0 |
