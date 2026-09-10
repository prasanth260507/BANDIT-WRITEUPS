## Bandit Level 2 → Level 3 Writeup
In this level, the password was stored in a file with a filename containing special characters and spaces. First I used the ls command to list the files in the directory. I then entered the inhere directory using:
cd inhere/
After listing the files, I found a hidden-looking filename:
...Hiding-From-You
At first, using the filename directly caused an error because the special characters were interpreted by the shell. To solve this, I used cat followed by the filename to display its contents:
cat ...Hiding-From-You
This command displayed the password required to log in to the next Bandit level.
