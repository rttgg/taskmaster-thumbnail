# Create Thumbnail
## Feature Tasks

* A user should be able to upload an image at any size, and have both the original size and a thumbnail size associated with the task in question.

* When an image is uploaded to your S3 bucket, it should trigger a Lambda function. (That Lambda function may be written in any language.)
* That function should create a 50x50 pixel thumbnail version of that image, and save it to another S3 bucket. It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be.

# Credits and contributions
* https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html
* Manish
* Roman 

## Links
https://elasticbeanstalk-us-west-2-424220637898resized.s3-us-west-2.amazonaws.com/resized-flower.jpg