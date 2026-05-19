# Terraform 
- terraform is an IAC tool which is used to crete an aws infra

### Infrastructure 
- aws
- consol
- time consuming
- Human error
- No identical infra
- Task replacement
- no record of current infra
- Scripting : python, Ansibal, SDK, AWS Cli
- Current no record
- Documentation Heavy
- No management
- IAC - Infrastructure as code tool : Terraform - HCL ;  Cloudformation - AWS - JSON or YAML

---

What is IaC?
- Infrastructure as Code (IaC) is the managing and provisioning of infrastructure through code instead of manual processes.


What is Provider Block? 
- Use the provider block to declare and configure Terraform plugins, called providers. Providers let Terraform manage real-world infrastructure with provider-defined resources and data sources.
- menshion cloud provider and region in which you are working
```hcl
provider "aws" {
region = "ap-south-1"    ## use region
















