# SAM
## Commands
```sh
aws s3 mb s3://ytamang-20230718
sam package --template-file template.yml --output-template-file sam-template.yml --s3-bucket ytamang-20230718
sam deploy --template-file sam-template.yml --stack-name mystack --capabilities CAPABILITY_IAM
```