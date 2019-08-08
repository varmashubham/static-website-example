Documentation on how to setup a S3 bucket for website hosting
https://docs.aws.amazon.com/AmazonS3/latest/dev//HostingWebsiteOnS3Setup.html

In the codebuild project :
- Disable Artifact encryption
- override Name in artifacts, set to /


Github Access with Token:
Github -> Settings -> Developer Settings : Generate new Token