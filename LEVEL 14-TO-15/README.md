## Bandit level 14 to 15
I logged in as Bandit14 and read the current password from /etc/bandit_pass/bandit14.

The level goal was to submit this password to port 30000 on localhost.

used the nc (Netcat) command to send the password to the specified port.

The server responded with the password for the next level, Bandit15.

Command used:

nc localhost

30000

Then I entered the Bandit14 password and pressed Enter to receive the next password.
