# REAN Assessment
#DevOps Assignment 1
 
#Objective:
#Use CM tools such as Puppet, Ansible, or Chef to automate the installation of basic Drupal or WordPress. Setup a sample site. Automate the solution using #Cloudformation template.
 
#Deliverable:
#A cloudformation template that accepts user inputs as parameters where applicable ( for example, Admin password). This template should setup VPC, create #subnets, launch a CM instance, pull the necessary code (modules, classes, recipes etc) from a GIT repo (or S3), and configure the web instance for basic Drupal #or Wordpress setup.

#Approach to this assessment
# 1 - Research CM tools listed above
# 2 - Research Cloudformation on AWS
# 3 - Use sample tamplates as a starting point then add other parameters in the assessment
# 4 - Referencing STACK_ID: arn:aws:cloudformation:us-east-1:400006646297:stack/WordPress/c2f72550-caf3-11e7-b121-500c219a1afd
# 5 - Design a new template by adding resources pane









#Links:
#http://docs.aws.amazon.com/quickstart/latest/sharepoint/app-b.html - password paremter for template
#https://github.com/awslabs/aws-cfn-windows-hpc-template/blob/master/cfn-init/change-administrator-password.ps1 
#https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stack/detail?stackId=arn:aws:cloudformation:us-east-1:400006646297:stack%2FWordPress%2Fc2f72550-caf3-11e7-b121-500c219a1afd - using this sample template as a platform
#https://console.aws.amazon.com/cloudformation/designer/home?templateURL=https://s3.amazonaws.com/bonusbits-public/cloudformation-templates/github/bastion.yml&region=us-east-1

