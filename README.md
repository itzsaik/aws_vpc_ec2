# Ansible-aws-vpc-ec2
Create AWS Virtual Private Cloud, Subnets, Internet Gateway, Route tables, Security group and EC2 instances

vars/main.yml

aws_access_key: ""
aws_secret_key: ""
region: ""
 
# VPC
vpc_cidr: 10.10.0.0/24
vpc_name: "Ansible VPC"
 
# Subnet
subnet_name: "Ansible Subnet"
subnet_cidr: 10.10.0.0/25
 
# Internet Gateway Name
igw_name: "Traffic IGW"

# Route table Name
route_name: "Route table" 

securitygroup_name: "Ansible Security Group"
 
ec2_tag: "WebServer"
 
#The local path to which we would save our EC2 Private Key
ec2_key_directory: "/home/ansible/roles/aws-vpc/"
keypair_name: "xxx"
