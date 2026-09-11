## Bandit Level 10 → Level 11 Writeup
The password was stored in the data.txt file.
I checked the file using cat data.txt and found that the content was Base64 encoded.
I used the base64 -d command to decode the content.
cat data.txt | base64 -d
The decoded output displayed the password.
I used this password to log in to Bandit Level 11.
