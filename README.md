#GitOpds= subset of devops , changes only from git, 
## automation problems
1-automation and also manual
2-drift in infrastrucutre
3-no history of changes
4-Microservices complexity
5-No versioning of infra changes

## with GitOps
CODE: 
  CI/CD automation code
  infra automation code
Git:
  versioning of all the changes
  single place automation code tracking
  restricting users access to only git
Tools:
  tool read changes in git
  apply the differences
  
# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####
#####
![image](https://github.com/user-attachments/assets/f45d129f-c62f-4123-901d-c09a5b64a791)
