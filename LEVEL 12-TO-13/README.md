## Bandit level 12 to 13
I continued identifying the type of each extracted file using the file command.

When the file was a compressed archive, I renamed it with the correct extension and extracted/decompressed it using commands such as gzip -d, bzip2 -d, and tar -xvf.

After each extraction, I again used the file command to identify the next layer of compression.

I repeated this process until I finally obtained an ASCII text file containing the password for the next Bandit level.

I also corrected a small filename mistake when renaming the extracted data5. bin file to data5.bin.tar.
