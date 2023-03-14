# 0x03. Shell, init files, variables and expansions
### Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

   * What happens when you type $ ls -l *.txt

### Shell Initialization Files

   * What are the /etc/profile file and the /etc/profile.d directory
    * What is the ~/.bashrc file

###Variables

   * What is the difference between a local and a global variable
    * What is a reserved variable
   * How to create, update and delete shell variables
   * What are the roles of the following reserved variables: HOME, PATH, PS1
   * What are special parameters
   * What is the special parameter $??

###  Expansions

   * What is expansion and how to use them
   * What is the difference between single and double quotes and how to use them properly
   * How to do command substitution with $() and backticks

### Shell Arithmetic

    How to perform arithmetic operations with the shell

### The alias Command

   * How to create an alias
   * How to list aliases
   * How to temporarily disable an alias

### Other help pages

## files:

| Filename | Description |
| -------- | ----------- |
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
| `100-rot13` | Encodes and decodes text using the rot13 encryption |
| `101-odd` | Prints every other line from the input, starting with the first line |
| `102-water_and_str` | Adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result |

