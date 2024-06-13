﻿<a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title"><img src="images/Solodev_Lite_Header.jpg"/></a>

# Solodev CMS Lite Edition
The perfect launch pad for small development projects, Solodev CMS Lite Edition gives you optimal control in a streamlined package. Pack your ship with the best-of-breed CMS features, access to PHP, Apache, MySQL, and Mongo all on a single web server - and available on-demand in the <a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title">AWS Marketplace</a>.

## Overview
Solodev CMS Lite Edition on AWS uses a set of YAML templates including [Amazon Virtual Private Cloud (VPC)](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html), [Amazon Elastic Compute Cloud (EC2)](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html), [Amazon Simple Storage Service (S3)](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html), and [Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html).

![AWS Diagram](https://raw.githubusercontent.com/solodev/aws/master/pages/images/solodev-cms-lite-edition-diagram.jpg)

## How to Launch Solodev CMS
Getting to the Solodev Launchpad is easy. In just a few short steps, you'll be lifting off on AWS.


## Step 1: Subscribe on the AWS Marketplace

Solodev is a professionally managed, enterprise-class Digital Customer Experience Platform and content management system (CMS). Before launching one of our products, you'll first need to subscribe to Solodev on the <a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title">AWS Marketplace.</a> Click the button below to get started: 
<table>
	<tr>
		<td width="60%"><a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title"><img src="images/AWS_Marketplace_Logo.jpg" /></a></td>
		<td><a href="https://aws.amazon.com/marketplace/pp/B01LXZKO21?qid=1534773581495&sr=0-1&ref_=srh_res_product_title"><img src="images/Subscribe_Large.jpg" /></a></td>
	</tr>
</table>


Already have a Solodev license? Call <a href="tel:1.800.859.7656">1-800-859-7656</a> and we’ll activate your subscription for you.<br /><br />

## Step 2: Return to this Solodev Product Page
Once you complete your subscription the AWS Marketplace, simply return to this Solodev CMS Lite Edition product page.<br/><br />

## Step 3: Configure Your VPC and EC2 Key Pair
Please note that both a <a href="http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html">VPC</a> and <a href="http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html">EC2 Key Pair</a> must be configured within the region you intend to launch your stack. If the following items are already created, you can skip directly to launch.<br/><br />

## Step 4: Launch your CloudFormation Stack
Once you’ve configured your <a href="http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html">VPC</a> and <a href="http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html">EC2 Key Pair</a>, you can launch your CloudFormation stack. Select the AWS region of your choice below:<br/><br/>

<table>
	<tr>
		<th width="299">AWS Region Code</td>
		<th width="299">Name</td>
		<th width="299" align="center">Launch</td>
	</tr>
	<tr>
		<td>us-east-1</td>
		<td>US East (N. Virginia)</td>
		<td align="center"><a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=solodev-lite&templateURL=https://s3.amazonaws.com/solodev-cms/cloudformation/solodev-lite-linux.yaml"><img src="images/Solodev_LaunchStack.png" width="200" /></td>
	</tr>
	<tr>
		<td>us-east-2</td>
		<td>US East (Ohio)</td>
		<td align="center"><!-- <a href="#"><img src="images/Solodev_LaunchStack.png" width="200" />--></td>
	</tr>
	<tr>
		<td>us-west-1</td>
		<td>US West (N. California)</td>
		<td align="center"><a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/new?stackName=solodev-lite&templateURL=https://s3.amazonaws.com/solodev-cms/cloudformation/solodev-lite-linux.yaml"><img src="images/Solodev_LaunchStack.png" width="200" /></td>
	</tr>
	<tr>
		<td>us-west-2</td>
		<td>US West (Oregon)</td>
		<td align="center"><a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=solodev-lite&templateURL=https://s3.amazonaws.com/solodev-cms/cloudformation/solodev-lite-linux.yaml"><img src="images/Solodev_LaunchStack.png" width="200" /></td>
	</tr>
	<tr>
		<td>eu-west-1</td>
		<td>EU (Ireland)</td>
		<td align="center"><!-- <a href="#"><img src="images/Solodev_LaunchStack.png" width="200" />--></td>
	</tr>
	<tr>
		<td>eu-west-2</td>
		<td>EU (London)</td>
		<td align="center"><!-- <a href="#"><img src="images/Solodev_LaunchStack.png" width="200" />--></td>
	</tr>
	<tr>
		<td>eu-central-1</td>
		<td>EU (Frankfurt)</td>
		<td align="center"><!-- <a href="#"><img src="images/Solodev_LaunchStack.png" width="200" />--></td>
	</tr>
	<tr>
		<td>eu-central-2</td>
		<td>Canada (Central)</td>
		<td align="center"><!-- <a href="#"><img src="images/Solodev_LaunchStack.png" width="200" />--></td>
	</tr>
</table>
The above links will launch the "Select Template" wizard, with the master template preselected. Click the "Next" button to customize the launch parameters.

## Parameters
The following parameters must be configured to launch your Solodev CMS CloudFormation stack:

![Parameters](https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/parameters-solodev-cms-lite.jpg)

<table>
	<tr>
		<th width="33%">Parameter</th>
		<th width="600px">Description</th>
	</tr>
	<tr>
		<td>Stack name</td>
		<td>The name of your stack (set to "solodev-cms-lite" by default). Please note, the name must be all lowercase.</td>
	</tr>
</table>

<table>
	<tr>
		<td colspan="2"><strong>Network Setup</strong></td>
	</tr>
	<tr>
		<td width="33%">VPCID</td>
		<td width="600px">Choose which VPC the Application should be deployed to</td>
	</tr>
	<tr>
		<td>Subnets</td>
		<td>Choose at least two public subnets for this application</td>
	</tr>
	<tr>
		<td>InstanceType</td>
		<td>EC2 instance type</td>
	</tr>
	<tr>
		<td>KeyName </td>
		<td>Name of an existing EC2 KeyPair to enable SSH access to the instances</td>
	</tr>
</table>

<table>
	<tr>
		<td colspan="2"><strong>Optional: Advanced</strong></td>
	</tr>
	<tr>
		<td width="33%">HostVolumeSize</td>
		<td width="600px">Size in GB of root volume</td>
	</tr>
	<tr>
		<td>Deletion Policy</td>
		<td>Experimental: Deletion Policy (Retain, Delete, Snapshot)</td>
	</tr>
</table>

## Step 5: View CloudFormation Stack Outputs

If your stack builds successfully, you will see the green "CREATE_COMPLETE" message. Click on the primary stack and view the "Outputs" tab. You will find the IP address associated with the Solodev backend.

<img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/outputs-solodev-cms-lite.jpg" />

## Step 6: Login to Solodev

Navigate to the EC2 dashboard within AWS. View the details associated with the recently created EC2 server and take note of the "Instance ID" as this will be the default password for the admin account. 

<img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/instance-id-solodev-cms-lite.jpg" />

Visit the IP address acquired in Step 7. Log-in to Solodev using the username "Solodev". The password will be the "Instance ID" that corresponds to the recently launched EC2 Server.

<img src="https://raw.githubusercontent.com/solodev/AWS-Launch-Pad/master/pages/images/install/login-solodev-cms-pro.jpg" />

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


## Need Help?

Solodev is a professionally managed, enterprise-class solution, and our team of certified engineers are here to support your success. While our self-serve options are easy to launch, you’ve always got a co-pilot at the helm. If you have any questions – or if you already have a Solodev license and need support with your AWS subscription – call <a href="tel:1.800.859.7656">1-800-859-7656</a> and we’ll help you get to the launchpad.


© 2019 Solodev. All rights reserved worldwide. And off planet. 

Errors or corrections? Email us at help@solodev.com.

---
Visit [solodev.com](https://www.solodev.com/) to learn more. <img src="https://www.google-analytics.com/collect?v=1&tid=UA-3849724-1&cid=1&t=event&ec=github_aws&ea=main&cs=github&cm=github&cn=github_aws" />
