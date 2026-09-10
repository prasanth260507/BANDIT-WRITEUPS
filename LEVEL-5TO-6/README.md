## Bandit Level 5 → Level 6 Writeup

In this level the password was stored somewhere on the server. The file had specific conditions: it was owned by user bandit7, belonged to group bandit6, and was 33 bytes in size.

To find the file, I used:

find / -user bandit7 -group bandit6 -size 33c 2>/dev/null

This command searched the entire system for a file matching the given conditions. The 2>/dev/ null part was used to hide permission-denied error messages.

The command returned the following file:

/var/lib/dpkg/info/bandit7.password
Then, I used the cat command to read the file:

cat /var/lib/dpkg/info/ bandit7.password

The output displayed the password required to log in to the next Bandit level.
