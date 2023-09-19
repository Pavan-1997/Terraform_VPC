# Terraform VPC
 
We are created the below using Terraform  

![Terraform_Infra](https://github.com/Pavan-1997/Terraform_VPC/assets/32020205/13c2c175-0a2a-49dd-b650-a320114c906b)

---
# Implementation

1. Create Access Key and Secret Key from your Account -> Security credentials 


2. Terraform commands
```
terraform init
```
`Initialize Terraform configuration and providers in the current directory`
```
terraform validate
```
`Check and validate the syntax and configuration of Terraform files`
```
terraform plan 
```
`Generate an execution plan for applying Terraform configurations to infrastructure. Its like a dry run`
 ```
terraform apply
```
`Apply Terraform configurations to create or modify infrastructure as defined`
```
terraform fmt 
```
`Automatically format Terraform configuration files for consistent style`
```
terraform apply -auto-approve
```
`Apply Terraform configurations without interactive approval, automatically confirming changes`

3. Open the LB endpoint in the Terraform terminal and access the application


