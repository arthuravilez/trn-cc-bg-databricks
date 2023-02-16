# Databricks Terraform Provider
https://registry.terraform.io/providers/databricks/databricks/latest/docs  
https://github.com/databricks/terraform-provider-databricks  

### set up & configure terraform
```shell
# install & upgrade terraform cli
brew install terraform
brew upgrade terraform

# terraform cli access
terraform
```

### provision azure databricks env {script}
```shell
# log into azure account
# "id": "66389d29-a9b6-425b-b699-f6894520d87d"
az login
az account show
az account show --output table
```

### build workspace
```shell
# init terraform script process
# prepare working directory
terraform init

# build plan to build
# changes required
terraform plan

# apply creation iac code
# create resources
terraform apply -auto-approve

# remove resources [rg]
# destroy resources
terraform destroy -auto-approve
```