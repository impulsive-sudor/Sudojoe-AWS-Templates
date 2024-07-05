# Sudojoe-AWS-Templates
AWS Cloudformation templates to help deploy infrastructure faster.

## Deployment Notes

Most of my deployments are using AWS Git Sync with Cloudformation. To perform Git Sync, make sure you have the proper IAM Roles setup on your AWS account and the AWS Git Sync application configured with access to your repo.

### Core Infrastructure S3 Template

When first setting up an AWS account, it's best practice to create a centralized AWS S3 bucket for server access logging. This template should help you create a pretty secure S3 bucket for centralizng your access logs.