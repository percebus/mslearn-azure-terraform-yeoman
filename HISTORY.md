# MSLearn Azure Terraform Yeoman example

## History

### Tutorial

[Create a Terraform base template in Azure using Yeoman](https://learn.microsoft.com/en-us/azure/developer/terraform/create-base-template-using-yeoman)

1. `npm init`
1. `npm install -g yo`
1. `npm install -g generator-az-terra-module`
1. `yo az-terra-module`

### Tweaks

1. Introduced `docker-compose.yml` to simplify `Dockerfile`
  1. Moved all `ENV` stuff to `docker-compose`
  1. Removed all `ARG`
  1. Created `env/` folder
