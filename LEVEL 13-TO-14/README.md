## bandit 13 to 14
I listed the files using ls and found the private SSH key file sshkey.private.
I used the SSH command with the private key to log in as bandit14.
My first attempt used the default SSH port 22, which resulted in a permission error.
I then used the correct port 2220 with the -p option and successfully connected to the Bandit server.
After logging in as Bandit14, I read the password for the next level using the cat command.
Commands used:
ssh bandit14@localhost -i sshkey.private -p 2220
cat /etc/bandit_pass/bandit14
