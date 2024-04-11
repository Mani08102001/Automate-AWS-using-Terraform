# Automate-AWS-using-Terraform
Setting up infrastructure on AWS using Terraform

## Resources I'm going to create on AWS using Terrform:
1. VPC
2. Public Subnets
3. Instances(virtual servers)
4. Security groups
5. Route tables
6. Internet gateway
7. Load balancer(type: Application)

## Step1:
- First create a Vpc with two availability zones(subnets).
- Then, deploy a instance(server) in each of these subnets.

## Step2:
-Create a Security group to access the server from outside which allows both HTTP and SSH traffic.
- Next, create a route table which routes incoming traffic to the instance.
- Create a internet gateway within a vpc to allow internet access to the instance.

## Step3:
-Finally, create a Application load balancer to maintain the traffic passing to the instance.
-Create a target group which has instances.
-Associate that target group with the Application load balancer.
-Make a listener port as 80 to allow HTTP traffic to the Load balancer.
-Yeah!!! Now the project is ready....
