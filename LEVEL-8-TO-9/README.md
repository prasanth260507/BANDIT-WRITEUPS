## Bandit Level 8 → Level 9 Writeup

The password was hidden inside the data. txt file.

The file contained many non-readable characters.

I used the strings command to extract readable text.

Then I used grep = to find lines containing the symbol.

strings data.txt

From the output, I found the line containing the password.

I used this password to log in to the next Bandit level.
