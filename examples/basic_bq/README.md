# terraform-google-bigquery basic_bq
The basic_bq example uses the root terraform-google-bigquery module to deploy a single dataset and a table with a basic schema. This example is a good reference to understand and test the module usage.

## Setup
Copy `terraform.tfvars.example` to `terraform.tfvars` and update the contents to match your test environment.

## Run example
`terraform init`
`terraform plan`
`terraform apply -var-file terraform.tfvars`
