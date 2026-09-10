## Bandit Level 3 → Level 4 Writeup
In this level, the password was stored inside a hidden file in the inhere directory.
First I listed the files using:
ls
Then I entered the inhere directory:
cd inhere/
Normally the ls command does not show hidden files. So, I used:
ls -al
This displayed all files including hidden files. I found several files whose names started with a -. To read such files, I used ./ before the filename so that Linux would not treat the - as an option.
like
cat ./-file00
After checking the files I found the readable file containing the password:
cat ./-file07
This displayed the password required to log in to the next Bandit level.
