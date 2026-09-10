## Bandit Level 4 → Level 5 Writeup
In this level, the password was stored in a file somewhere inside the inhere directory. The file had specific conditions: it was human-readable, 1033 bytes in size, and not executable.
To find the correct file, I used the find command:
find . -readable -size 1033c -not -executable
This command searched through the current directory and its subdirectories for a file matching those conditions. It returned the location of the required file.
Then, I used the cat command to read the file:
cat ./maybehere07/./file2
The output displayed the password required to log in to the next Bandit level.
