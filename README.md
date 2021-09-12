# Terraform Cloud VPC Setup Guide using Tailscale

This is an example Terraform configuration intended for use with the Tailscale networking across multiple clouds

## What will this do?

This is a simple Terraform configuration that will create the prerequisites to use distributed K3S machine-controller across multi-clouds

## What are the prerequisites?

You must have an AWS account and provide your AWS Access Key ID and AWS Secret Access Key to Terraform Cloud. Terraform Cloud encrypts and stores variables using [Vault](https://www.vaultproject.io/). For more information on how to store variables in Terraform Cloud, see [our variable documentation](https://www.terraform.io/docs/cloud/workspaces/variables.html).

The values for `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` should be saved as environment variables on your workspace.
