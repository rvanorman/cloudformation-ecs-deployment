# cloudformation-ecs-deployment
This is a proof of concept for a deployment of a functional test environment into AWS using Elastic Container Service (ECS) via CloudFormation in YAML

## Preperation to Use
1) Make sure to copy the modules folder and its entire contents into an s3 bucket of your choosing for the main file to call the nested templates from. The structure should looks something like the following:

s3 bucket root directory
└── modules
    ├── alb.yaml
    ├── ec2.yaml
    └── vpc.yaml