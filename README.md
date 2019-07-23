# aws-cfn-vpc

AWS CloudFormation Stack for VPC.

## Usage

### stack.json

This repo contains a standard AWS CloudFormation template `stack.json`
which can be deployed with AWS web console, AWS CLI or any other AWS
CloudFormation compitable tool.

This template will create an AWS CloudFormation stack, including
following resources:

* 1 VPC
* 2 public Subnets
* 2 private Subnets
* 1 Internet Gateway
* 1 Public Route Table

For the input parameters and the detail of the template, please check the template
file.

### sandbox.conf

`sandbox.conf` is a config file for stack.json, it's used by
`aws-cfn-deploy` which belongs to an AWS toolkit
[xsh-lib-aws](https://github.com/alexzhangs/xsh-lib-aws), to automate AWS
CloudFormation template deployment.
