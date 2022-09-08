# Shell, init files, variables and expansions

This is a project done during **ALX Software Engineering Program**. 
* It aims to learn about shell initialization files (`/etc/profile`, `/etc/profile.d`, `~/.bashrc` and others), variables, expansions, shell arithmetic and the alias commmand
* Coomands studied include: `echo`, `printenv`, `set`, `unset`, `export`, `alias`, `unalias`, `source`, `printf` and others

## Technologies
* Scripts were written in Bash, version 5.0.17(1)-release.
* Tested on Ubuntu 20.04 LTS.

## Files
All of the following files are _shell_ scripts:

| Filename | Description |
| -------- | ----------- |
| `0-alias` | Creates an alias named `ls` with value `rm *`. |
| `1-hello_you` | Prints `hello user`, where user is the current Linux user |
| `2-path` | Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program |
| `3-paths` | Counts the number of the directories in the `PATH` |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists all local variables and environment variables, and functions |
| `6-create_local_variable` | Creates a new local variable named `BEST` with value `School` |
| `7-create_global_variable` | Creates a new global variable named `BEST` with value `School`|
| `8-true_knowledge` | Prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line |
| `9-divide_and_rule` | Prints the result of `POWER` divided by `DIVIDE`, followed by a new line |
| `10-love_exponent_breath` | Displays the result of `BREATH` to the power `LOVE` |
| `11-binary_to_decimal` | Converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable `BINARY` |
| `12-combinations` | Prints all possible combinations of two lowercase letters in alpha order, except `oo`. One combination per line |
| `13-print_float` | Prints a number with two decimal places. The number is stored in the environment variable `NUM` |
| `100-decimal_to_hexadecimal` | Converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable `DECIMAL` |
| `101-rot13` | Encodes and decodes text using the rot13 encryption |
| `102-odd` | Prints every other line from the input, starting with the first line |
| `103-water_and_stir` | Adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result. WATER is in base `water`. STIR is in base `stir.`. The result is in base `bestchol` |