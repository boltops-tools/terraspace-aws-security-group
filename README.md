# Terraspace AWS Security Group Example

This project shows how to use the [Security Group Terraform registry module](https://registry.terraform.io/modules/terraform-aws-modules/security-group/aws) with [Terraspace](https://terraspace.cloud/).

* Thanks and credit goes to the author of this module: Anton B.
* Most contributors are doing this on their own free time. Please support them. Contribute back and send them a pull request. Some may ask for donations. Donate to them. Some are consultants. Hire them.

## Setup

    git clone https://github.com/boltops-tools/terraspace-aws-security-group
    cd terraspace-aws-security-group
    bundle

## Deploy

To deploy:

    terraspace up http

The security-group is created in the `eu-west-1` region.

## Updating

To update the modules to the latest version from the Terraform registry.

    terraspace bundle update

## More Examples

    $ terraspace list
    app/stacks/complete
    app/stacks/computed
    app/stacks/disabled
    app/stacks/dynamic
    app/stacks/http

## About

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[Terraspace](https://terraspace.cloud/) and this project was built by [BoltOps](https://www.boltops.com). We also offer:

* [Paid Consulting Services](https://www.boltops.com/consulting)
* [BoltOps Pro: Infrastructure Code as a Service](https://www.boltops.com/pro)
