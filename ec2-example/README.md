# Terraform + AWS 101
### Steps to do
* Install required software 
* Create AWS IAM user 
* Create AWS access key pair
* Configure AWS CLI
* Setup terraform repository and ifrastructure
* Apply terraform infrasture

### Installation
* [terraform](https://developer.hashicorp.com/terraform/downloads?product_intent=terraform) 
* [aws cli](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
* [aws user account](https://portal.aws.amazon.com/billing/signup#/start/email)

### Create EC2 instance 
* [terraform aws provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
* [terraform ec2 example](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance)



### AWS cli command
* `aws configure`
* `aws iam get-user`

### Usefull teffarorm commands

* `terraform init`- setup terraform
* `terraform validate` - validation  
* `terraform plan`- display  changes to be applied
* `terraform apply` - apply changes 
* `terraform state list` - check resourses in the state