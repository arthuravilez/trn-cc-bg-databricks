# Databricks Terraform Provider
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
az login
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