# lambda-thumbnailer
AWS Lambda thumbnailer with support for GIFs and PDFs (first page/frame)

Saves the thumbnails to SOURCE_BUCKET/thumbnails/SOURCE_KEY.png

Can easily be modified to save thumbnails as a different format, bucket, etc

Adds some metadata, and enables public-read for the thumbnail. 

It comes from lessons learned in the walk through here:

http://docs.aws.amazon.com/lambda/latest/dg/walkthrough-s3-events-adminuser.html

This also helped:
https://alestic.com/2014/11/aws-lambda-cli/
