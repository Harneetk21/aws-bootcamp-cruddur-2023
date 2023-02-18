# Week 0 — Billing and Architecture

## Homework for Week 0

### Installing AWS CLI 

I have installed AWS CLI in local environment as I was facing issue installing it using gitpod during my last few steps. Also, I was aware of Installing it locally so I tried following the same steps. 

Steps to Install AWS CLI on Local Machine (Windows) are as follows:

Go to https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html 

Install AWS CLI latest Version: https://awscli.amazonaws.com/AWSCLIV2.msi

Open Command Prompt on your Local Machine as  an Administrator
To confirm installation type following command 
```
aws --version
```

To confirm AWS Configuration type command
```
aws configure
```
For more clarity, I also Created an S3 bucket in AWS Console with name "mycodebootcampbucket12345" in ca-central-1 region. The proof is attached here:

(Insert Picture of S3 Bucket)


To visualise this bucket in AWS CLI, I type following command to list all teh buckets in the AWs Management console:
```
aws s3 ls
```

I was able to successfully Configure my credentials using Command Prompt

Proof that I install and configure AWS CLI Successfully ( Insert Picture)
