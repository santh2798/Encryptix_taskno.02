BASIC STATIC WEBSITE HOSTING ON S3

Steps 
1.	created a basic static website using HTML and CSS languages.
2.	Login to AWS console with IAM user and navigate to S3 service
3.	Create a S3 bucket with unique name in a particular region. 
4.	First disable the BLOCK ALL PUBLIC ACCESS at account level as well as bucket level to make it publicly accessable.
5.	For bucket permissions we use ACLs or Bucket policy. Got to permission tab under S3 bucket and write bucket policy with get actions “getObject” using Json format.
6.	Upload all the website files from upload tab “add file”. 
7.	Now go to properties tab under S3 bucket and edit the static website hosting section and enable it.  Now a http link will be generated and with that link one can access the website

