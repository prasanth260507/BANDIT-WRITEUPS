# Bandit Level 0 → Level 1
## Explanation
In this level I needed to find the password stored in a file named -.
First I used:
ls
to check the files available in the current directory.
Then, I used:
ls -al
to view all files with detailed information. I found a file named -.
Since - can be treated as a special character or option in Linux I used ./ before the filename to clearly specify the file from the current directory.
cat ./-
This command displayed the contents of the file, which was the password for the next level.
Commands Used
ls
ls -al
cat ./-
What I learned: Files with special names can be accessed by specifying their path using ./.
