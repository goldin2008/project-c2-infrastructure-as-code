create-network-stack:
	aws cloudformation create-stack --stack-name udagram-network --template-body file://network.yml --parameters file://network-params.json --region=eu-west-2 --capabilities CAPABILITY_NAMED_IAM

update-network-stack:
	aws cloudformation update-stack --stack-name udagram-network --template-body file://network.yml --parameters file://network-params.json --region=eu-west-2 --capabilities CAPABILITY_NAMED_IAM

create-server-stack:
	aws cloudformation create-stack --stack-name udagram-servers --template-body file://servers.yml --parameters file://server-params.json --region=eu-west-2 --capabilities CAPABILITY_NAMED_IAM

update-server-stack:
	aws cloudformation update-stack --stack-name udagram-servers --template-body file://servers.yml --parameters file://server-params.json --region=eu-west-2 --capabilities CAPABILITY_NAMED_IAM

delete-network-stack:
	aws cloudformation delete-stack --stack-name udagram-network

delete-server-stack:
	aws cloudformation delete-stack --stack-name udagram-servers