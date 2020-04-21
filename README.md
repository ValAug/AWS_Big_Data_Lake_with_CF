# AWS-Automating-a-Big_Data_Lake-with-CF

## These set of templates will intent to create and deploy secure Data Lake stackset using Cloudformation.  

*Usefull CLI Commands*:
aws --region <region-name> cloudformation validate-template --template-body file://<file-name.yaml>


aws --region <region-name> cloudformation create-stack --stack-name <name> --template-body file://<file-name.yaml>

aws --region <region-name> cloudformation describe-stacks --stack-name <name> --profile <profile-name>

aws --region <region-name> cloudformation update-stack --stack-name <name> --template-body file://<file-name.yaml>

aws --region <region-name> cloudformation delete-stack --stack-name <name> --profile <profile-name>

aws --region <region-name> cloudformation create-stack --stack-name <name> --template-body file://<file-name.yaml> --capabilities CAPABILITY_NAMED_IAM --profile <profile-name>



# install cfn-lint
pip3 install cfn-lint