## bandit level 11 to 12
listed the files in the current directory using ls and found the data.txt file.
I checked the file using cat data.txt, but the content was Base64 encoded and not readable directly.
I used the base64 -d command to decode the contents of the file.
After decoding, the password for the next level was displayed.
Command used:
cat data.txt | base64 -d
