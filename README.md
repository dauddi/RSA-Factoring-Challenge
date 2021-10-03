### RSA Factoring Challenge
The file **factors** is a python executable that takes a file as a command line argument.
The file contains numbers to be factorized.

The script prints to the console a formatted string containing each number and its factors.
If script is run without passing a file, it prints:
#### "Error! File name required" and exits with status 1.
If script is run and a non-existent file is passed, it prints:
#### "Error! File not found" and exits with status 2.
If script is run and an empty file is passed, it prints:
#### "Error! File empty" and exits with status 3.
If script is run and other errors arise, it prints the error to the terminal and exits with status 4.
