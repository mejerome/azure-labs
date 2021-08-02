# Azure labs
- terraform is a tool for building, changing, and combining infrastructure safely and efficiently.
  The steps shown below are terraform cycle for local development:
  - Code development
  - Code formatting with "terraform fmt"
  - Initialization with "terraform init"
  - Code validation with terraform validate
  - Planning with terraform plan
  - Manual verification of Terraform changes on infrastructure

  however in a CI/CD pipeline, the steps are:
  - Retrieve the code from the repository
  - Code formatting with "terraform fmt"
  - Initialization with "terraform init"
  - Code validation with terraform validate
  - Plan with terraform plan
  - Apply with terraform apply --auto-approve
  
- ansible is a powerful automation and deployment tool that makes it easy to automate your entire infrastructure  lifecycle.
  

- azure-cli is a command-line tool for managing Azure resources.
- packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
  packer contains a builder, provisioner and variable section in it's configuration file structure.
  variables can be referenced as {{ user 'variable_name' }} in the template.
- git is a version control system that is used to store and manage your source code.
- azure devops is a tool for managing your Azure resources.

