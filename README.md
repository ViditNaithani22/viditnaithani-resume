# Hosting Vidit Naithani Portfolio Website 

### -> Hosting a static website on AWS S3 bucket without making it public, is a simple but very important concept to know as this is a very common demand from businesses.
### -> In this project we put the website front-end files on an S3 bucket, and then created an AWS Cloudfront network and gave it access to the bucket's contents.
### -> With the help of the cloudfront URL anyone can access the website even though the S3 bucket is private, but we also want URL to have our name as it is our website.
### -> So we purchase a URL from AWS Route53, and get a certificate for it from AWS Certificate Manager. We attatch that certificate and define our URL in the cloudfront network.
### -> Now we need to establish a CI/CD pipeline using Github Actions, as it will make it easier to make any changes in our website, otherwise to make any changes in our website we need to replace the files in the S3 bucket with the updated ones.
### -> So we create a github repo, upload all the front-end website files in it, then create a yml file inside the .github folder where we write a script to give this repo access to our S3 bucket, and give instructions to reflect the changes made to the repo inside the S3 bucket whenever we make a commit.

![Uploading 1_srnPC370Q44uMsKD6JSevw.jpg…]()

