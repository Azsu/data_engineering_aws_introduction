# Basic Data Engineering using AWS SageMaker

## Outline

1. [Pre-requisites](#pre-requisites)
1. [AWS CloudFormation](#aws-cloudformation)
1. [AWS SageMaker](#aws-sagemaker)


### Pre-requisites

1. Create an AWS Account
   1. Navigate to https://aws.amazon.com/ and select a button to create a new account. ![https://aws.amazon.com/](https://github.com/Azsu/data_engineering_aws_introduction/blob/master/images/aws_create_account.jpg)
   1. Add a "+designation" to the end of your sign up email so that you can keep track of your AWS accounts. Expect to create more than one, expect to have to track and coordinate between the accounts. By adding a "+" and a following label after your email you can still receive notifications for all acounts from a single email address while allowing seperate AWS accounts. ![User Details](https://github.com/Azsu/data_engineering_aws_introduction/blob/master/images/aws_user_details.jpg)
   1. Continue the sign-up workflow until the end and login to the console: https://aws.amazon.com/cloudformation/resources/
   
1. Secure your account: For the latest best practices on securing your AWS account see: https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html 
   1. Note: It is highly recommended you purchase a Gemalto Token, they are relatively inexpensive especially compared to the cost and effort of dealing with a hacker getting access to your AWS account and racking up a giant bill. For more information see: https://aws.amazon.com/iam/features/mfa/
   1. Best Practices: When securing your system there should be no root access and all activity and permissions should be designed around role permissions. This allows scalability and risk mitigation by allowing multiple accounts to interact with each other via the AssumeRole functionality. For more information see: https://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRole.html
1. Note: Using API keys and environmental variables https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-envvars.html
1. Set a budget alert on the new account: https://console.aws.amazon.com/billing/home?#/budgets
  
1. Create GitHub account
   1. Create GitHub repository


### AWS-CloudFormation

1. Introduction: From the AWS Site: "AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts." https://aws.amazon.com/cloudformation/
1. Purpose: It's important to create your cloud resources from code for many reasons, and although it adds some complexity for beginers here, it also adds a level of financial protection to your account by providing you the ability to scale down all your resources from a single location while also keeping track of all systems you have created.
   1. Alternative: https://www.terraform.io/
   1. Comparison: https://www.missioncloud.com/blog/aws-cloudformation-vs-terraform-which-one-should-you-choose
   1. Note: I recommend students review Terraform as an alternative to CloudFormation as it is an important knowledge domain when applying for work positions.
1. Documentation: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-sagemaker-model.html
1. Pricing: This should be free, if you find yourself exceeding the free tier consider creating a new account and splitting resources logically.
1. Resources: https://aws.amazon.com/cloudformation/resources/

### AWS-SageMaker

1. Introduction:
1. Purpose:
1. Documentation: 
1. Pricing: https://aws.amazon.com/sagemaker/pricing/
1. Code:
