# What is the cloud? Minimal Terraform demo

Minimal demo of using Terraform to provision cloud resources and Checkov to check their security..

Requires [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) and [Checkov](https://www.checkov.io/2.Basics/Installing%20Checkov.html).

Init, validate and scan:

- `terraform init`
- `terraform validate`
- `checkov -d .`

More elaborate Terraform demo at [https://github.com/mikaelvesavuori/node-simple-webserver-gcp-terraform](https://github.com/mikaelvesavuori/node-simple-webserver-gcp-terraform).
