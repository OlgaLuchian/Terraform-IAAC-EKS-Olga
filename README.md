# Terraform-IaaC-EKS

Prerequisites:
Terraform 0.12.19


### Change the following lines         # Will be used to set backend.tf
s3_bucket = "your bucket name"                
vpc_id = "your VPC ID"
subnet1 = "your subnet ID 1" 
subnet2 = "your subnet ID 2"
subnet3 = "your subnet ID 3"



### If you get the following error 
Invalid choice: 'eks', maybe you meant:
Run:  sudo pip install awscli --ignore-installed six"

- Downloading plugin for provider "kubernetes"  (hashicorp/kubernetes) 1.11.1..
- Downloading plugin for provider "aws" (hashicorp/aws) 2.53.0...
- Downloading plugin for provider "null" (hashicorp/null) 2.1.2...
- Downloading plugin for provider "local" (hashicorp/local) 1.4.0...
- Downloading plugin for provider "template" (hashicorp/template) 2.1.2...
- Downloading plugin for provider "random" (hashicorp/random) 2.2.1...





### Install kubectl   and AWS CLI 

## yum install awscli -y 
## curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.14.0/bin/linux/amd64/kubectl
## chmod +x kubectl
## sudo mv kubectl  /bin/
## kubectl version
