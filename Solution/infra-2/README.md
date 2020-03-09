This solution can - deploy 3 tier architecture which includes-
i) VPC
ii) Subnets in VPC
iii) Web instances in available subnets - created in step ii
iv) ELB with instances attached, created in step iii
v) App tier instances
vi)RDS database
This solution is basic setup and can be enhanced according to your requirements where other compenents - like route tables, security groups, security rules can be created and added as per requirement.

PRE-REQUISITE
------------------------------
Since terraform has complexity in handling dependency between modules - so I have used TERRAGRUNT.
Terragrunt is a thin wrapper for Terraform that provides extra tools for working with multiple Terraform modules.
https://terragrunt.gruntwork.io/
download and install - https://terragrunt.gruntwork.io/docs/getting-started/install/