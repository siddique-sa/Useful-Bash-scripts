## Steps to follow to upload files into S3 buckets 

- to run this sh script you require curl, openssl 1.x or newer, GNU sed, installed 
- Need to Export <br>
AWS_ACCESS_KEY_ID= ***<br>
AWS_SECRET_ACCESS_KEY= *** <br>
AWS_DEFAULT_REGION= ***

### to upload a single file 
run **`sh upload-single-file-s3.sh  <source file name with path> <bucket name>`**



### to upload a single file 
run **`sh upload-multi-files-s3.sh  <source directory with path> <bucket name>`**
