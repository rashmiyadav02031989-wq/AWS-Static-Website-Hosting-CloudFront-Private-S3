# AWS-Static-Website-Hosting-CloudFront-Private-S3

**Project Overview:**.   
Built a secure static website hosting solution using Amazon S3 and Amazon CloudFront. The S3 bucket remains private and website content is delivered through CloudFront using Origin Access Control (OAC), ensuring secure and scalable content delivery over HTTPS.

**Architecture:**   
User    
⬇️  
CloudFront  
⬇️  
Private S3 Bucket  

**AWS Services Used:**.   
-Amazon S3.  
-Amazon CloudFront  
-Origin Access Control (OAC)  
-IAM   

**Features:**.   
-Static website hosting    
-Private S3 bucket  
-HTTPS access  
-Global content delivery through CloudFront   
-Reduced latency through caching  
-Secure access using OAC  

**Implementation Steps:**     
**Step 1:** Create S3 Bucket   
Created an S3 bucket.  
Uploaded website files.  
Kept bucket private.  
**Step 2:** Configure CloudFront  
Created CloudFront distribution.  
Selected S3 bucket as origin.  
Enabled OAC.  
**Step 3:** Configure Bucket Policy  
Allowed CloudFront to access bucket objects.  
**Step 4:** Deploy Website    
Waited for CloudFront deployment    
Accessed website through CloudFront URL.  

**Security Best Practices:**     
-S3 Block Public Access enabled.  
-No public object permissions.  
-Access restricted through CloudFront OAC.  
-HTTPS enforced.  

**Screenshots:**.   
## Website Homepage

![Website Homepage](screenshots/website-homepage.jpg)

## Bucket Contents  

![Bucket Policy](screenshots/s3-contents.jpg)

## Bucket Permission

![Bucket Permission](screenshots/s3-block-public-access.jpg)


## CloudFront Distribution

![CloudFront](screenshots/cloudfront-general.jpg)

## Bucket Policy

![Bucket Policy](screenshots/s3-bucket-policy.jpg)

## Origin Access Control

![OAC](screenshots/cloudfront-configuration.jpg)

## CloudFront Origin 

![CloudFront Origin](screenshots/cloudfront-origin.jpg)

**Project Outcome:**.   
Successfully deployed a secure and scalable static website using AWS services while preventing direct public access to S3 objects.  

**Skills Demonstrated:**.   
-AWS S3 
-AWS CloudFront  
-CDN Concepts  
-Origin Access Control (OAC)  
-IAM Policies  
-Static Website Hosting  
-Cloud Security  

**Repository Structure:**.   
aws-static-website-cloudfront-private-s3/ 
│  
├── index.html 
├── README.md  
└── screenshots/  
