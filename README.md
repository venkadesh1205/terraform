# Terraform Notes

# What is Infrastructure as Code (IAC)?
 
 Let's say, We used to log in to the management console on AWS or Azure or GCP and provision the resource. It is good for limited number of resources. For the organization with huge infrastructure it is not a good practice. For that we came up with the solution called IAC. We will write a simple code with easy and in human readable declarative code format to provision the resource.
  
# Types of IAC tools
 * Configuration Management Tool - Ansible
 * Server Templating Tool - Docker
 * Provisioning Tool - Terraform
 
 The above types severs different use cases. 
 
# What is Terraform? 
 Terraform is an IAC tool that allow us to build, change, destroy, version control on cloud and on-prem resources in a matter of minutes. 
 
# Why Terraform?
 The biggest advantages of terraform is we can deploy resouces in a multiple platforms.
  # EXAMPLE
    We want to create a 100 EC2 in AWS for our company. We want to automate the process. 
    So we decided to use AWS CLI and AWS Cloud formation Template. Then we wrote a script for AWS and we created a resource. 
    At some point we are unhappy with AWS and want to move to Azure. So the script we wrote is of no use.
    Then we moved to Azure and wrote a script and create a resource. And same happended with Azure. So the script is of no use. 
    And then we also want to work with both AWS and Azure in a hybrid model. 
    
    So to overcome this issue we came up with the terraform. 
    
Terraform have a terraform provider(will learn later) which talk to the target API's and create a resource.

Terraform also use HashiCorp Configuration Language(HCL) which is simple and in declarative way.
