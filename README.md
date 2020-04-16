# terraform-aws-vm

Configuration in this directory creates a simple AWS EC2 instance by using the terraform [ec2-instance](https://registry.terraform.io/modules/terraform-aws-modules/ec2-instance/aws) module.

## Usage

Use `pre-commit` to check code quality (see [.pre-commit-config.yaml](./.pre-commit-config.yaml) for configuration)

```sh
pre-commit install
```

To run terraform you need to execute:

```sh
$ terraform init
$ terraform plan
$ terraform apply
```
