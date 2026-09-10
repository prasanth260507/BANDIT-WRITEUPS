## Bandit Level 10 → Level 11 Writeup

The password was stored in the data. txt file.

The content of the file was Base64 encoded.

First, I checked the file using:

cat data.txt

Then I decoded the Base64 content using:

cat data.txt

|

base64 -d

The base64 -d command decoded the encoded text.

The output displayed the password for the next Bandit level.
