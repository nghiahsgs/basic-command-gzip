# basic-command-gzip
basic command gzip


### Compress a file using gzip:
```
gzip filename.txt
```
This command will compress the file filename.txt and create a new file called filename.txt.gz. The original file will be deleted, and only the compressed file will remain.

### Decompress a file using gzip:
```
gzip -d filename.txt.gz
```
This command will decompress the file filename.txt.gz and create a new file called filename.txt. The compressed file will be deleted, and only the decompressed file will remain.

### Compress a file and keep the original file:
```
gzip -k filename.txt
```
This command will compress the file filename.txt and create a new file called filename.txt.gz. However, the original file will not be deleted, and both the original file and the compressed file will remain.
