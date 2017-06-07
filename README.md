# cloudformation-templates

AWS CloudFormation templates for common tasks.

## vpc.yaml

Create a functional VPC with three subnets, available to the public
internet.

```bash
aws cloudformation create-stack --stack-name test-vpc --template-body fileb:///<path-to-folder>/vpc.yaml
```
