# Sudojoe-AWS-Templates
AWS Cloudformation templates to help deploy infrastructure faster.

## Template Notes

A word of caution, these templates are not meant to be used in an enterprise environment. I created these templates under the mindset of costs superseed security. I do however make an effort to try and be as secure as possible wherever possible. Always open to suggestions on how I can improve the code but may not change it due to the trade offs of costs vs security.

## Deployment Notes

Most of my deployments are using AWS Git Sync with Cloudformation. To perform Git Sync, make sure you have the proper IAM Roles setup on your AWS account and the AWS Git Sync application configured with access to your repo.

### Core Infrastructure S3 SAL Template

When first setting up an AWS account, it's best practice to create a centralized AWS S3 bucket for server access logging. This template should help you create a pretty secure S3 bucket for centralizng your access logs.

