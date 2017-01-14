# NGC Terraform Modules

This repo houses various modules used by Nextgear Capital.  In some cases these
repos were forked from the [Terraform Community Modules](https://github.com/terraform-community-modules) repo, and in other cases they are modules we either built ourselves or heavily modified versions of a module discovered elsewhere. It is our goal to give back to the communities from which we learn and we want to thank everyone else for doing the same.

## Modules
- [tf_aws_vpc](https://github.com/nextgearcapital/terraform/tf_aws_vpc)
  - This module will create the VPC, Internet Gateway, Public Subnets (spanned across available AZ's), Private subnets and NAT Gateways.
  
- [tf_aws_ubuntu_ami](https://github.com/nextgearcapital/terraform/tf_aws_ubuntu_ami)
  - This module selects the appropriate Ubuntu AMI ID for the region you are working in. Currently, if you wish to use an image other than Ubuntu's you will need to define that ID in your terraform.tfvars file.


## License

[Apache 2.0](https://github.com/nextgearcapital/terraform/blob/master/LICENSE) - see the included LICENSE file for more details.
