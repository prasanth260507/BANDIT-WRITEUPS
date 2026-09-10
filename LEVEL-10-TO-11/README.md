## Bandit Level 10 → Level 11 Writeup
The password was stored in the data.txt file.
After viewing the file, I found that the text was encoded using ROT13.
ROT13 replaces each letter with another letter 13 positions away.
I decoded the text using the following command:
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
The tr command converted the ROT13 encoded text back to normal text.
The output displayed the password required for the next Bandit level.
