## Bandit Level 1 → Level 2

# explanation
The goal of this level is to find the password for the next level. The password is stored in a file named:
--spaces in this filename--
Steps I Used
First I listed the files in the current directory:
ls
The output showed the file:
--spaces in this filename--
Since the filename contains spaces and also starts with --, directly using cat caused an error. I used ls -al to inspect the exact filename:
ls -al
Then, I used ./ before the filename and escaped each space using a backslash (\):
cat ./--spaces\ in\ this\ filename--
This successfully displayed the password for the next level.
## Command Used
ls
ls -al
cat ./--spaces\ in\ this\ filename--
What I Learned
ls is used to list files and directories.
ls -al shows detailed information, including hidden files.
A backslash (\) can be used to escape spaces in filenames.
./ specifies that the file is located in the current directory.
Special filenames starting with -- may need ./ to avoid being interpreted as command options.
