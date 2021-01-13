# terraform-aws-vpc
[TEST] terraform common vpc module for test. @moomoo 


# Resources
* VPC
* private subnet, public subnet
* private route table, public route table
* internet gateway
* nat gateway
* nat eip
* flow log

# Variables
* name
* environment
* cidr
* public_subnets
* private_subnets
* availability_zones

# Outputs
* id
* public_subnets
* private_subnets

# 추후 구현 기능
* 특정 리소스 제외
* 게이트웨이 리소스 모듈 분리 고려
