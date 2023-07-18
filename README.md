# Hands on with Cloudformation
- Stack_master
## Cloudformation
- VPC template: https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html
- https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/CHAP_TemplateQuickRef.html
## Deploy resources
```
alias sm="stack_master"
sm apply
sm delete us-east-1 server-dev
sm apply us-east-1 server-dev
```