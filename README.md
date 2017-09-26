## idanenet-static
Static version of iDanenet

Upload to S3

`aws s3 sync . s3://idanenet.danebank.nsw.edu.au/ --acl public-read --exclude '.git/*'`
