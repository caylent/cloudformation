# Caylent Templates for AWS CloudFormation

A repository for Caylent AWS CloudFormation templates

## Launch a VPC
Launch a VPC with 2 private and 2 public subnets in 2 availability zones for High Availability Stacks

[![Launch a VPC](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=Caylent-HA-VPC-2azs&templateURL=https://s3.amazonaws.com/cf-templates-xn0xe15cpz0d-us-east-1/ha-vpc-2azs.template.yaml)

## Launch an Alert
Creates an SNS topic that alerts you if there is an event in your Stack(s)

[![Launch an Alert](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=Caylent-Alert&templateURL=https://s3.amazonaws.com/cf-templates-xn0xe15cpz0d-us-east-1/alert.yaml)

## Launch a high-availability Docker Swarm
Creates the infrastructure so you can run Docker Swarm in HA; includes two auto-scaling groups containing EC2 instances and a master load balancer

[![Launch a Docker Swarm](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=Caylent-Docker-Swarm&templateURL=https://s3.amazonaws.com/cf-templates-xn0xe15cpz0d-us-east-1/ha-docker-stack.template.yaml)
