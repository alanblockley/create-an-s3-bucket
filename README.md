# create-an-s3-bucket
Creating an S3 Bucket

# Intro
This repo is designed to hold methods of creating an S3 bucket.  
This repo can be both used independantly or in support of the originating blog post. 

## AWS Console

Follow the manual steps under aws-console/

## CloudFormation

Deploy the cloudformation templates, as relevant, either from the AWS Console or from the AWS CLI

### AWS Console

  1 - Log into the AWS console and open CloudFormation
  2 - Create new stack
  3 - Click "Our template is ready" and then click upload
  4 - Select the relevant template
  4 - Click next
  5 - Give the stack a name
  6 - Click Create Stack
  
### AWS CLI

Ensure you are authenticated on the command line.

`aws cloudformation deploy --template-file /path_to_template/template.json `

## Terraform

Ensure you have terraform installed on your machine and you are authenticated on the command line.

Once you have cloned this repo, change into the directory of the relevant example

```
 terraform init
 terraform plan
 terraform apply
```
