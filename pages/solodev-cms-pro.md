<a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title"><img src="images/Solodev_Lite_Header.jpg"/></a>

# Solodev CMS Professional Edition
Take command of your digital universe! Get the full power of the galaxy's most advanced CMS and take your design and development to the stars and beyond. Professional Edition includes Solodev CMS, PHP, Apache, and Mongo on a single web server with an external RDS MySQL database – and available on-demand in the <a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title">AWS Marketplace</a>.

## Overview
Solodev CMS Professional Edition on AWS uses a set of YAML templates including [Amazon Virtual Private Cloud (VPC)](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html), [Amazon Elastic Compute Cloud (EC2)](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html), [Amazon Relational Database Service (RDS)](http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html), [Amazon Simple Storage Service (S3)](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html), [Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html), [Amazon CloudFront](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html), [Amazon Route 53](http://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html), [Amazon Web Application Firewall (WAF)](https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html) and deployed by [AWS CloudFormation](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html).

![AWS Diagram](images/Solodev_Pro_Architecture.jpg)

Getting to the Solodev Launchpad is easy. In just a few short steps, you'll be lifting off on AWS.

## Step 1: Subscribe on the AWS Marketplace

Solodev is a professionally managed, enterprise-class Content Management System (CMS). Before launching one of our products, you'll first need to subscribe to Solodev on the <a href="https://aws.amazon.com/marketplace/pp/B07KMFPW3X/ref=_ptnr_solodev_github_B07KMFPW3X">AWS Marketplace.</a> Click the button below to get started: 
<table>
	<tr>
		<td width="60%"><a href="https://aws.amazon.com/marketplace/pp/B07KMFPW3X/ref=_ptnr_solodev_github_B07KMFPW3X"><img src="images/AWS_Marketplace_Logo.jpg" /></a></td>
		<td><a href="https://aws.amazon.com/marketplace/pp/B07KMFPW3X/ref=_ptnr_solodev_github_B07KMFPW3X"><img src="images/Subscribe_Large.jpg" /></a></td>
	</tr>
</table>


Already have a Solodev license? Call <a href="tel:1.800.859.7656">1-800-859-7656</a> and we’ll activate your subscription for you.<br /><br />

## Step 2: Configure Your VPC and EC2 Key Pair
Please note that both a <a href="http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html">VPC</a> and <a href="http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html">EC2 Key Pair</a> must be configured within the region you intend to launch your stack. If the following items are already created, you can skip directly to launch.<br/><br />

## Step 3: Launch your CloudFormation Stack
<strong>Confirm Subscription</strong><br />
Click on the "Continue to Subscribe" link within the AWS Marketplace listing. Once your subscription is processed, you will see confirmation and the "Continue to Configuration" button.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/subscription-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<strong>Configure Solodev CMS</strong><br />
Specify the basic configurables such as the software version and the region you wish to launch the stack. Click on the "Continue to Launch" button to proceed.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/configuration-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<strong>Launch Solodev CMS</strong><br />
Confirm your configurations and choose "Launch CloudFormation" within the "Choose Action" field. Click on the "Launch" button to continue to CloudFormation.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/launch-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

## Step 4: Fill Out the CloudFormation Stack Wizard
<strong>Continue with the preselected CloudFormation Template</strong><br />
The Amazon S3 template URL (used for the CloudFormation configuration) should be preselected. Click "Next" to continue.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/template-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<strong>Specify Details</strong><br />
The following parameters must be configured to launch your Solodev CMS CloudFormation stack:

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/parameters-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<table>
	<tr>
		<th width="33%"><strong>Parameter</strong></th>
		<th width="600px"><strong>Description</strong></th>
	</tr>
	<tr>
		<td>Stack name</td>
		<td>The name of your stack (set to "solodev-cms-pro" by default). Please note, the name must be all lowercase.</td>
	</tr>
</table>

<table>
	<tr>
		<td colspan="2"><strong>Network Setup</strong></td>
	</tr>
	<tr>
		<td width="33%">VPCID</td>
		<td width="600px">Choose which VPC the application should be deployed to</td>
	</tr>
	<tr>
		<td>Subnets</td>
		<td>Choose at least two public subnets for this application</td>
	</tr>
	<tr>
		<td>InstanceType</td>
		<td>The EC2 instance type you wish to launch</td>
	</tr>
	<tr>
		<td>KeyName</td>
		<td>Name of an existing EC2 KeyPair to enable SSH access to the instances</td>
	</tr>
</table>

<table>
	<tr>
		<td colspan="2"><strong>CMS Settings</strong></td>
	<tr>
		<td width="33%">AdminUser</td>
		<td width="600px">The solodev admin username</td>
	</tr>
	<tr>
		<td>AdminPassword</td>
		<td>The solodev admin password</td>
	</tr>
	<tr>
		<td>DatabasePassword</td>
		<td>The database root password</td>
	</tr>
	<tr>
		<td>StorageEncrypted</td>
		<td>Enable encryption for both Database (RDS) and Filesystem (EFS). True or False.</td>
	</tr>
</table>

<table>
	<tr>
		<td colspan="2"><strong>Optional: Advanced</strong></td>
	</tr>
	<tr>
		<td width="33%">RestoreBucketName</td>
		<td width="600px">Name of S3 bucket containing files for restore</td>
	</tr>	
	<tr>
		<td>CookbookURL</td>
		<td>https://s3.amazonaws.com/solodev-aws-ha/cookbooks.tar.gz | Download and host on your own S3 bucket or copy this URL.</td>
	</tr>
	<tr>
		<td>DeletionPolicy</td>
		<td>Experimental: Deletion Policy (Retain, Delete, Snapshot)</td>
	</tr>
</table>

<strong>Specify Options</strong><br />
Generally speaking, no additional options need to be configured. If you are experiencing continued problems installing the software, disable "Rollback on failure" under the "Advanced" options. This will allow for further troubleshooting if necessary. Click on the "Next" button to continue.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/options-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<strong>Review</strong><br />
Review all CloudFront details and options. Ensure that the "I acknowledge that AWS CloudFormation might create IAM resources with custom names" checkbox is selected as well as the "I acknowledge that AWS CloudFormation might require the following capability: CAPABILITY_AUTO_EXPAND" checkbox. Click on the "Create" button to launch your stack.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/review-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

## Step 5: Monitor the CloudFormation Stack Creation Process
Upon launching your CloudFormation stack, you will be able to monitor the installation logs under the "Events" tab. The CloudFormation template will launch several stacks related to your Solodev instance including EFS, EDS, and EC2. If you encounter any failures during this time, please visit the <a href="https://github.com/solodev/AWS-Launch-Pad/wiki/Common-Issues">Common Issues</a> page to begin troubleshooting.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/monitor-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

## Step 6: View CloudFormation Stack Outputs

If your stack builds successfully, you will see the green "CREATE_COMPLETE" message. Click on the primary stack and view the "Outputs" tab. You will find the IP address associated with the Solodev backend. Point both your primary domain (mydomain.com) and a dedicated backend domain/subdomain (solodev.mydomain.com) to this URL.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/outputs-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/dns-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

## Step 7: Login to Solodev

Visit either the IP address or the backend domain you configured in Step 6. Login to CMS using the username "solodev" and the password you configured in Step 5.

<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/login-solodev-cms-pro.jpg" /></td>
	</tr>
</table>

## Support
Houston, we have no problems… because Solodev Customer Care has your back at every step! From our world-class HelpDesk to our focused training sessions, you’ve got the best team on the ground to get you to the stars. 

Solodev Customer Care Includes
* 24x7x365 U.S. based human support
* Online HelpDesk ticketing
* Phone and email support
* Live training courses
* Over 300 pages of searchable documentation and tutorials

To learn more about our add-on support options, call 1-800-859-7656 to speak with one of our Solodev Customer Care Specialists.

<a href="https://www.solodev.com/product/support.stml"><img src="images/Solodev_Git_Support.jpg"/></a>

## Developers
Are you a Solodev Developer? Launch a development stack in your AWS account using the below links. Please note, the builds will only be successfull for authorized Solodev Developers.
* <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=solodev-pro-dev&templateURL=https://s3.amazonaws.com/solodev-aws-ha/aws/solodev-pro-opsworks.yaml">Launch Solodev Pro</a>
* <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=solodev-pro-byol-dev&templateURL=https://s3.amazonaws.com/solodev-aws-ha/aws/solodev-pro-opsworks-byol.yaml">Launch Solodev Pro BYOL</a>

## Need Help?

Solodev is a professionally managed, enterprise-class solution, and our team of certified engineers are here to support your success. While our self-serve options are easy to launch, you’ve always got a co-pilot at the helm. If you have any questions – or if you already have a Solodev license and need support with your AWS subscription – call <a href="tel:1.800.859.7656">1-800-859-7656</a> and we’ll help you get to the launchpad.


© 2018 Solodev. All rights reserved worldwide. And off planet. 

Errors or corrections? Email us at help@solodev.com.

---
Visit [solodev.com](https://www.solodev.com/) to learn more. <img src="https://www.google-analytics.com/collect?v=1&tid=UA-3849724-1&cid=1&t=event&ec=github_aws&ea=main&cs=github&cm=github&cn=github_aws" />
