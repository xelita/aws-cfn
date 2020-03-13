# aws-cfn
Repository with all my personal AWS CloudFormation Template

To validate a template:
`aws cloudformation validate-template --template-body file://<path_to_the_file>`

To create a stack on AWS:
`aws cloudformation create-stack --stack-name <your_stack_name> --template-body file://<path_to_the_file>` + parameters + capabilities

To remove that stack on AWS:
`aws cloudformation delete-stack --stack-name <your_stack_name>`

## EC2
This folder contains all EC2 specific templates
