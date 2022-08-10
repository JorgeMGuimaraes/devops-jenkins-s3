# Deploying a Static Website to AWS S3 using Jenkins.

![Header][header-img]

In this project we will deploy a static website to AWS S3 using Jenkins pipelines and the infrastructure will be created using Terraform. This way, we can manage changes programatically. I assume Terraform is already installed, an AWS user is created and have right permissions (AmazonS3FullAccess).

## Summary

* Definitions
* Create a S3 bucket using Terraform;

## Definitions

### Terraform

Terraform is an infrastructure as code (IaC) tool made by Hashicorp tool that allows provisioning and version infrastructure in a descriptive manner. Users can plan and automate infrastructure implementation as well as document all the process.

### Jenkins

Jenkins is an automation server used to facilitate continuos integration and delivery (CI/CD).

### AWS S3

S3 is an object storage service. Data is stored in buckets, and can be retrieved from almost any service. It's usually very cost effective.

## Create a S3 bucket using Terraform

[header-img]: /docs/images/header.jpg