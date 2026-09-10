## Bandit Level 6 → Level 7 Writeup
In this level, the password was stored in the data.txt file next to the word “millionth”.
I used the grep command to search for the word millionth inside the file:
cat data.txt | grep "millionth"
The grep command searched through the contents of data.txt and displayed the line containing the word millionth. The password was present on the same line which I used to log in to the next Bandit level.
