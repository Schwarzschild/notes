# Infrastructure as Code - Iac

Infrastructure as code (IaC)
* [Terraform](https://developer.hashicorp.com/terraform/docs)
* [Docker](https://docs.docker.com)
* CDK
* K8/Docker
* Ansible
* Zappa
* Nerveless Framework
* A+E Oyonys and Tom like Terraform, so does Jonathan Smith, and Jame

Terraform is better than CDK because it is data driven, coding errors cannot be introduced.




Terraform deploy Lambda
* [Terraform / Lambda Tutorial](https://developer.hashicorp.com/terraform/tutorials/aws/lambda-api-gateway) with python [here](https://medium.com/@haissamhammoudfawaz/create-a-aws-lambda-function-using-terraform-and-python-4e0c2816753a)
* [Deploy a python function to lambda](https://registry.terraform.io/modules/mineiros-io/lambda-function/aws/latest/examples/python-function) <<<< this one
* https://github.com/TheBrookhavenGroup/lambda_hello
* [Brian Caffey](https://briancaffey.github.io) - [deploy server less Django on lambda](https://briancaffey.github.io/2020/08/01/django-and-lambda-with-cdk-and-api-gateway.html/)

Terraform deploy Django to EC2
* https://dev.to/daiquiri_team/deploying-django-application-on-aws-with-terraform-minimal-working-setup-587g

Terraform with Azure
https://developer.hashicorp.com/terraform/tutorials/azure-get-started/azure-build


Terraform Language
```terraform
resource "aws_vpc" "main" {
  cidr_block = var.base_cidr_block
}
```

```terraform
<BLOCK TYPE> "<BLOCK LABEL>" "<BLOCK LABEL>" {
  # Block body
  <IDENTIFIER> = <EXPRESSION> # Argument
}
```

### Questions

Things to think about.

- What causes pip install to run?
- What is Fargate (ECS) - similar to lambda but up all the time.
- Multiple lambdas in one repo or not?

### To do

- [ ] [Read Deploy Django on Azure](https://learn.microsoft.com/en-us/azure/app-service/tutorial-python-postgresql-app?tabs=flask%2Cwindows&pivots=deploy-portal) or [this](https://stories.mlh.io/deploying-a-basic-django-app-using-azure-app-services-71ec3b21db08)
- [Atlantis](https://www.runatlantis.io) 
