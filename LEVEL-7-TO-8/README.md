## Bandit Level 8 → Level 9 Writeup

In this level, the password was stored in the da ta. txt file and was the only line that appeared once.

To find it I used the following command: 

sort

uniq

cat data.txt

First, sort arranged all the lines in order so that duplicate lines came together. Then uniq -c counted how many times each line appeared.

By checking the output, I found the line with a count of 1, which was the unique line. That line contained the password required to log in to the next Bandit level.
