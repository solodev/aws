# Solodev on a Single Server
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Overview
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

*AWS Reference Architectures*
![AWS Diagram](http://via.placeholder.com/898x450)

## Prerequisites
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Steps to Run
To launch the entire stack and deploy on AWS, click on one of the ***Launch Stack*** links below.

You can launch this CloudFormation stack, using your account, in the following AWS Regions:

AWS Region Code             | Name                       | Launch 
----------------------------|----------------------------|:-------------------------:
us-east-1                   | US East (N. Virginia)      | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=solodev-aws&templateURL=https://s3.amazonaws.com/solodev-aws-ha/aws/solodev-lite-single.yaml)
us-east-2                   | US East (Ohio)             | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
us-west-1                   | US West (N. California)    | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
us-west-2                   | US West (Oregon)           | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
eu-west-1                   | EU (Ireland)               | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
eu-west-2                   | EU (London)                | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
eu-central-1                | EU (Frankfurt)             | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)
ca-central-1                | Canada (Central)           | [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](#)

The above links will launch the "Select Template" wizard with the master template preselected. Click "Next" to customize the launch parameters.

## Parameters
![Parameters](images/parameters-single.jpg)

Parameter                             | Description
------------------------------------- | ---------------------
Stack name     				          | The name of your stack
**Network Configuration**     		  | 
Which VPC should this be deployed to? | Choose which VPC the Application should be deployed to
Subnets     						  | Choose at least two public subnets for this application
**Server Configuration**              | 
InstanceType                          | EC2 instance type
KeyName                               | Name of an existing EC2 KeyPair to enable SSH access to the instances
HostVolumeSize                        | Size in GB of root volume
SSHFrom                               | Lockdown SSH access to the bastion host
**Solodev Configuration**             | 
InstanceType                          | Build AMI - Please leave this blank unless told otherwise

## FAQs
1. Lorem ipsum dolor sit amet?
> Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

2. Lorem ipsum dolor sit amet?
> Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

3. Lorem ipsum dolor sit amet?
> Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
