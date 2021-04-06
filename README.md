# Amazon S3 Website Endpoints


## Website endpoint examples
The following examples show how you can access an Amazon S3 bucket that is configured as a static website.

### Example — Requesting an object at the root level

To request a specific object that is stored at the root level in the bucket, use the following URL structure.

http://bucket-name.s3-website.Region.amazonaws.com/object-name

For example, the following URL requests the photo.jpg object that is stored at the root level in the bucket.

http://example-bucket.s3-website.us-west-2.amazonaws.com/photo.jpg


### Example — Requesting an object in a prefix

To request an object that is stored in a folder in your bucket, use this URL structure.

http://bucket-name.s3-website.Region.amazonaws.com/folder-name/object-name

The following URL requests the docs/doc1.html object in your bucket.

http://example-bucket.s3-website.us-west-2.amazonaws.com/docs/doc1.html
