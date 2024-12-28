This project is a simple example of hosting a static website on AmazonS3.
First, we register the domain using Route53.
Then we create an S3 bucket, upload our .html file, make it available to public, enable static website hosting, and attach a bucket policy.
Then we have to direct our bucket, that has the same name as our domain, as alias to Route53. So, when users login to the website, they will see the actual domain name, but not the bucket url. 
I attached two snips of how redirected and unredirected urls would look like.
