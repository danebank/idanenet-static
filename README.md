## idanenet-static
Dev site for static version of iDanenet.

Upload to S3
`aws s3 sync . s3://idanenet-static.danebank.nsw.edu.au/ --acl public-read --exclude '.git/*'`
