# cloud

1.	A bank needs to store recordings of calls made to its contact center for 6 years. The recordings must be accessible within 48 hours from the time they are requested. Which AWS service will provide a secure and cost-effective solution for retaining these files?
A)	Amazon DynamoDB
B)	Amazon S3 Glacier
C)	Amazon Connect
D)	Amazon ElastiCache
ANSWER: C
2.	A batch workload takes 5 hours to finish on an Amazon EC2 instance. The amount of data to be processed doubles monthly and the processing time is proportional. What is the best cloud architecture to address this consistently growing demand?
A)	Run the application on a bigger EC2 instance size.
B)	Switch to an EC2 instance family that better matches batch requirements.
C)	Distribute the application across multiple EC2 instances and run the workload in parallel.
D)	Run the application on a bare metal EC2 instance.
ANSWER: C
3.	A characteristic of edge locations is that they:
A)	host Amazon EC2 instances closer to users.
B)	help lower latency and improve performance for users.
C)	cache frequently changing data without reaching the origin server.
D)	refresh data changes daily.
ANSWER: C
4.	A cloud practitioner has a data analysis workload that is infrequently executed and can be interrupted without harm. To optimize for cost, which Amazon EC2 purchasing option should be used?
A)	On-Demand Instances
B)	Reserved Instances
C)	Spot Instances
D)	Dedicated Hosts
ANSWER: C
5.	A Cloud Practitioner identifies a billing issue after examining the AWS Cost and Usage report in the AWS Management Console. Which action can be taken to resolve this?
A)	Open a detailed case related to billing and submit it to AWS Support for help.
B)	Upload data describing the issue to a new object in a private Amazon S3 bucket.
C)	Create a pricing application and deploy it to a right-sized Amazon EC2 instance for more information.
D)	Proceed with creating a new dashboard in Amazon QuickSight.
ANSWER: A
6.	A Cloud Practitioner is asked how to estimate the cost of using a new application on AWS. What is the MOST appropriate response?
A)	Inform the user that AWS pricing allows for on-demand pricing.
B)	Direct the user to the AWS Simple Monthly Calculator for an estimate.
C)	Use Amazon QuickSight to analyze current spending on-premises.
D)	Use Amazon AppStream 2.0 for real-time pricing analytics.
ANSWER: B
7.	A Cloud Practitioner is developing a disaster recovery plan and intends to replicate data between multiple geographic areas. Which of the following meets these requirements?
A)	AWS Accounts
B)	AWS Regions
C)	Availability Zones
D)	Edge locations
ANSWER: B
8.	A Cloud Practitioner must determine if any security groups in an AWS account have been provisioned to allow unrestricted access for specific ports. What is the SIMPLEST way to do this?
A)	Review the inbound rules for each security group in the Amazon EC2 management console to check for port 0.0.0.0/0.
B)	Run AWS Trusted Advisor and review the findings.
C)	Open the AWS IAM console and check the inbound rule filters for open access.
D)	In AWS Config, create a custom rule that invokes an AWS Lambda function to review rules for inbound access.
ANSWER: B
9.	A Cloud Practitioner needs a consistent and dedicated connection between AWS resources and an on-premises system. Which AWS service can fulfill this requirement?
A)	AWS Direct Connect
B)	AWS VPN
C)	Amazon Connect
D)	AWS Data Pipeline
ANSWER: A
10.	A cloud practitioner needs an Amazon EC2 instance to launch and run for 7 hours without interruptions. What is the most suitable and cost-effective option for this task?
A)	On-Demand Instance
B)	Reserved Instance
C)	Dedicated Host
D)	Spot Instance
ANSWER: D
11.	A cloud practitioner needs to obtain AWS compliance reports before migrating an environment to the AWS Cloud. How can these reports be generated?
A)	Contact the AWS Compliance team
B)	Download the reports from AWS Artifact
C)	Open a case with AWS Support
D)	Generate the reports with Amazon Macie
ANSWER: A
12.	A Cloud Practitioner needs to store data for 7 years to meet regulatory requirements. Which AWS service will meet this requirement at the LOWEST cost?
A)	Amazon S3
B)	AWS Snowball
C)	Amazon Redshift
D)	Amazon S3 Glacier
ANSWER: D
13.	A company believes an unauthorized user copied data from an Amazon S3 bucket to their own account. Which AWS service will record the actions taken by the user?
A)	Amazon CloudWatch
B)	AWS CloudTrail
C)	AWS Infrastructure Event Management
D)	AWS Systems Manager
ANSWER: B
14.	A company has a 500 TB image repository that needs to be transported to AWS for processing. Which AWS service can import this data MOST cost-effectively?
A)	AWS Snowball
B)	AWS Direct Connect
C)	AWS VPN
D)	Amazon S3
ANSWER: D
15.	A company has a business-critical Amazon RDS for MySQL DB instance that resides in a single Availability Zone. Which solution will improve the availability of the DB instance?
A)	Convert the DB instance into a multi-Region deployment.
B)	Create an Amazon Simple Queue Service (Amazon SQS) queue in the same AWS Region to manage writes to the DB instance.
C)	Convert the DB instance into a Multi-AZ deployment.
D)	Create an Amazon Simple Queue Service (Amazon SQS) queue in a different AWS Region to manage writes to the DB instance.
ANSWER: C
16.	A company has a centralized group of users with large file storage requirements that have exceeded the space available on premises. The company wants to extend its file storage capabilities for this group while retaining the performance benefit of sharing content locally. What is the MOST operationally efficient AWS solution for this scenario?
A)	Create an Amazon S3 bucket for each users. Mount each bucket by using an S3 file system mounting utility.
B)	Configure and deploy an AWS Storage Gateway file gateway. Connect each user’s workstation to the file gateway.
C)	Move each user’s working environment to Amazon WorkSpaces. Set up an Amazon WorkDocs account for each user.
D)	Deploy an Amazon EC2 instance and attach an Amazon Elastic Block Store (Amazon EBS) Provisioned IOPS volume.Share the EBS volume directly with the users.
ANSWER: B
17.	A company has a compliance requirement to record and evaluate configuration changes, as well as perform remediation actions on AWS resources. Which AWS service should the company use?
A)	AWS Config
B)	AWS Secrets Manager
C)	AWS CloudTrail
D)	AWS Trusted Advisor
ANSWER: A
18.	A company has a globally distributed user base. The company needs its application to be highly available and have low latency for end users. Which AWS architectural approach will MOST effectively support these requirements?
A)	Single-Region, Multi-AZ architecture
B)	Multi-Region, active-active architecture
C)	Multi-Region, active-passive architecture
D)	Single-Region, Single-AZ architecture
ANSWER: B
19.	A company has a Java web application. The company wants to use auto deployment to create the AWS environment and deploy new versions of its application. Which AWS service will meet these requirements?
A)	AWS Auto Scaling
B)	AWS Elastic Beanstalk
C)	AWS Control Tower
D)	Amazon EC2
ANSWER: B
20.	A company has a managed IAM policy that does not grant the necessary permissions for users to accomplish required tasks. How can this be resolved?
A)	Enable AWS Shield Advanced
B)	Create a custom IAM policy
C)	Use a third-party web application firewall (WAF) managed rule from the AWS Marketplace
D)	Use AWS Key Management Service (AWS KMS) to create a customer-managed key
ANSWER: B
21.	A company has a MySQL database running on a single Amazon EC2 instance. The company now requires higher availability in the event of an outage. Which set of tasks would meet this requirement?
A)	Add an Application Load Balancer in front of the EC2 instance
B)	Configure EC2 Auto Recovery to move the instance to another Availability Zone
C)	Migrate to Amazon RDS and enable Multi-AZ
D)	Enable termination protection for the EC2 instance to avoid outages
ANSWER: C
22.	A company has all of its servers in the us-east-1 Region. The company is considering the deployment of additional servers in a different Region. Which AWS tool should the company use to find pricing information for other Regions?
A)	Cost Explorer
B)	AWS Budgets
C)	AWS Purchase Order Management
D)	AWS Pricing Calculator
ANSWER: C
23.	A company has an application with users in both Australia and Brazil. All the company infrastructure is currently provisioned in the Asia Pacific (Sydney) Region in Australia, and Brazilian users are experiencing high latency. What should the company do to reduce latency?
A)	Implement AWS Direct Connect for users in Brazil
B)	Provision resources in the South America (São Paulo) Region in Brazil
C)	Use AWS Transit Gateway to quickly route users from Brazil to the application
D)	Launch additional Amazon EC2 instances in Sydney to handle the demand
ANSWER: B
24.	A company has an application workload that is stateless be design and can sustain occasional downtime. The application performs massively parallel computations. Which Amazon EC2 pricing model should the company choose for its application to reduce cost?
A)	On-Demand Instances
B)	Spot Instances
C)	Reserved Instances
D)	Dedicated Instances
ANSWER: B
25.	A company has an AWS environment that consists of a VPC, multiple subnets, and many Amazon EC2 instances in the subnets. An engineer wants to restrict inbound traffic to one particular EC2 instance without affecting the other EC2 instances. Which AWS service or feature should the engineer use to meet this requirement?
A)	Network ACLs
B)	Security groups
C)	Amazon GuardDuty
D)	AWS Shield
ANSWER: A
26.	A company has an AWS-hosted website located behind an Application Load Balancer. The company wants to safeguard the website from SQL injection or cross-site scripting. Which AWS service should the company use?
A)	Amazon GuardDuty
B)	AWS WAF
C)	AWS Trusted Advisor
D)	Amazon Inspector
ANSWER: B
27.	A company has defined the AWS resources that it needs for a new application. The company needs to estimate the costs of running the application on AWS. What should the company do to meet this requirement?
A)	Take advantage of AWS on-demand pricing.
B)	Use the AWS Pricing Calculator to generate an approximate dollar amount.
C)	Use Amazon QuickSight to analyze current on-premises spending.
D)	Use Amazon AppStream 2.0 for real-time pricing analytics.
ANSWER: B
28.	A company has deployed several relational databases on Amazon EC2 instances. Every month, the database software vendor releases new security patches that need to be applied to the databases. What is the MOST efficient way to apply the security patches?
A)	Connect to each database instance on a monthly basis, and download and apply the necessary security patches from the vendor.
B)	Enable automatic patching for the instances using the Amazon RDS console.
C)	In AWS Config, configure a rule for the instances and the required patch level.
D)	Use AWS Systems Manager to automate database patching according to a schedule.
ANSWER: D
29.	A company has distributed its workload on both the AWS Cloud and some on-premises servers. What type of architecture is this?
A)	Virtual private network
B)	Virtual private cloud
C)	Hybrid cloud
D)	Private cloud
ANSWER: C
30.	A company has enabled billing alerts in its AWS account and wants to receive a notification through Amazon Simple Notification Service (Amazon SNS) whenever its monthly bill exceeds a set amount. Which AWS service or tool should the company use to achieve this?
A)	Amazon CloudWatch
B)	Cost Explorer
C)	AWS Cost and Usage Report
D)	AWS Pricing Calculator
ANSWER: A
31.	A company has existing software licenses that it wants to bring to AWS, but the licensing model requires licensing physical cores. How can the company meet this requirement in the AWS Cloud?
A)	Launch an Amazon EC2 instance with default tenancy.
B)	Launch an Amazon EC2 instance on a Dedicated Host.
C)	Create an On-Demand Capacity Reservation.
D)	Purchase Dedicated Reserved Instances.
ANSWER: A
32.	A company has infrastructure in one AWS Region and is expanding operations to a second AWS Region. The company is using the same AWS CloudFormation template in the second Region that the company uses in the original Region. The company attempts to launch Amazon EC2 On-Demand Instances in the second Region and receives error messages. What could cause these error messages?
A)	A new EC2 key pair has not been created for the EC2 instances.
B)	The requested EC2 instance types are not available in the second Region.
C)	The company cannot operate in a second Region until it updates its AWS contract.
D)	The company has not configured AWS Budgets to monitor the budget for the EC2 instances.
ANSWER: A
33.	A company has multiple AWS accounts and wants to simplify and consolidate its billing process. Which AWS service will achieve this?
A)	AWS Cost and Usage Reports
B)	AWS Organizations
C)	AWS Cost Explorer
D)	AWS Budgets
ANSWER: B
34.	A company has multiple AWS accounts within AWS Organizations and wants to apply the Amazon EC2 Reserved Instances benefit to a single account only. Which action should be taken?
A)	Purchase the Reserved Instances from master payer account and turn off Reserved Instance sharing.
B)	Enable billing alerts in the AWS Billing and Cost Management console.
C)	Purchase the Reserved Instances in individual linked accounts and turn off Reserved Instance sharing from the payer level.
D)	Enable Reserved Instance sharing in the AWS Billing and Cost Management console.
ANSWER: A
35.	A company has multiple data sources across the organization and wants to consolidate data into one data warehouse. Which AWS service can be used to meet this requirement?
A)	Amazon DynamoDB
B)	Amazon Redshift
C)	Amazon Athena
D)	Amazon QuickSight
ANSWER: B
36.	A company has multiple departments. Each department uses its own AWS account. Which AWS service or tool can the company use to combine the billing for all accounts into one bill?
A)	Amazon Forecast
B)	AWS Budgets
C)	AWS Organizations
D)	AWS Marketplace
ANSWER: C
37.	A company has refined its workload to use specific AWS services to improve efficiency and reduce cost. Which best practice for cost governance does this example show?
A)	Resource controls
B)	Cost allocation
C)	Architecture optimization
D)	Tagging enforcement
ANSWER: B
38.	A company hosts an application on an Amazon EC2 instance. The EC2 instance needs to access several AWS resources, including Amazon S3 and Amazon DynamoDB. What is the MOST operationally efficient solution to delegate permissions?
A)	Create an IAM role with the required permissions. Attach the role to the EC2 instance.
B)	Create an IAM user and use its access key and secret access key in the application.
C)	Create an IAM user and use its access key and secret access key to create a CLI profile in the EC2 instance
D)	Create an IAM role with the required permissions. Attach the role to the administrative IAM user.
ANSWER: A
39.	A company hosts an application on multiple Amazon EC2 instances. The application uses Amazon Simple Notification Service (Amazon SNS) to send messages. Which AWS service or feature will give the application permission to access required AWS services?
A)	AWS Certificate Manager (ACM)
B)	IAM roles
C)	AWS Security Hub
D)	Amazon GuardDuty
ANSWER: B
40.	A company hosts images in an Amazon S3 bucket for a public-facing website that is viewed by millions of users around the globe. Which AWS service will deliver this content with reduced latency?
A)	AWS WAF
B)	Amazon CloudWatch
C)	Amazon Cloud Front
D)	AWS CloudFormation
ANSWER: C
41.	A company hosts its website on Amazon EC2 instances. The company needs to ensure that the website reaches a global audience and provides minimum latency to users. Which AWS service should the company use to meet these requirements?
A)	Amazon Route 53
B)	Amazon CloudFront
C)	Elastic Load Balancing
D)	AWS Lambda
ANSWER: A
42.	A company implements an Amazon EC2 Auto Scaling policy along with an Application Load Balancer to automatically recover unhealthy applications that run on Amazon EC2 instances. Which pillar of the AWS Well-Architected Framework does this action cover?
A)	Security
B)	Performance efficiency
C)	Operational excellence
D)	Reliability
ANSWER: D
43.	A company is based in the us-east-1 Region and has a satellite office in the eu-west-2 Region. The company wants to use Amazon WorkSpaces to host its internal web portal and virtual desktops for employees. What should the company do to minimize latency and ensure the best possible performance for employees?
A)	Deploy the internal web portal and virtual desktops to us-east-1 only. Use an Amazon CloudFront distribution for the users in eu-west-2.
B)	Deploy the internal web portal to us-east-1 only. Deploy the virtual desktops to us-east-1 and eu-west-2.
C)	Deploy the internal web portal to us-east-1 and eu-west-2. Deploy the virtual desktops on network optimized Amazon EC2 instances to us-east-1 only.
D)	Deploy the internal web portal and virtual desktops to us-east-1 and eu-west-2.
ANSWER: B
44.	A company is building a business intelligence solution and wants to use dashboards for reporting purposes. Which AWS service can be used?
A)	Amazon Redshift
B)	Amazon Elasticsearch Service (Amazon ES)
C)	Amazon QuickSight
D)	Amazon Athena
ANSWER: C
45.	A company is building a mobile app to provide shopping recommendations to its customers. The company wants to use a graph database as part of the shopping recommendation engine. Which AWS database service should the company choose?
A)	Amazon DynamoDB
B)	Amazon Aurora
C)	Amazon Neptune
D)	Amazon DocumentDB (with MongoDB compatibility)
ANSWER: C
46.	A company is building a new archiving system on AWS that will store terabytes of data. The company will NOT retrieve the data often. Which Amazon S3 storage class will MINIMIZE the cost of the system?
A)	S3 Standard-Infrequent Access (S3 Standard-IA)
B)	S3 Glacier
C)	S3 Intelligent-Tiering
D)	S3 One Zone-Infrequent Access (S3 One Zone-IA)
ANSWER: A
47.	A company is building an application that needs to deliver images and videos globally with minimal latency. Which approach can the company use to accomplish this in a cost effective manner?
A)	Deliver the content through Amazon CloudFront.
B)	Store the content on Amazon S3 and enable S3 cross-region replication.
C)	Implement a VPN across multiple AWS Regions.
D)	Deliver the content through AWS PrivateLink.
ANSWER: A
48.	A company is building an application that requires the ability to send, store, and receive messages between application components. The company has another requirement to process messages in first-in, first-out (FIFO) order. Which AWS service should the company use?
A)	AWS Step Functions
B)	Amazon Simple Notification Service (Amazon SNS)
C)	Amazon Kinesis Data Streams
D)	Amazon Simple Queue Service (Amazon SQS)
ANSWER: D
49.	A company is considering a move to the AWS Cloud. The company wants to be able to scale its compute resources as needed to accommodate changing loads. Which benefit of the AWS Cloud does this scenario describe?
A)	Global deployments in minutes
B)	Cost savings
C)	Agility
D)	Elasticity
ANSWER: D
50.	A company is considering migrating its applications to AWS. The company wants to compare the cost of running the workload on-premises to running the equivalent workload on the AWS platform. Which tool can be used to perform this comparison?
A)	AWS Simple Monthly Calculator
B)	AWS Total Cost of Ownership (TCO) Calculator
C)	AWS Billing and Cost Management console
D)	Cost Explorer
ANSWER: B
51.	A company is considering using AWS for a self-hosted database that requires a nightly shutdown for maintenance and costsaving purposes. Which service should the company use?
A) Amazon Redshift
B) Amazon DynamoDB
C) Amazon Elastic Compute Cloud (Amazon EC2) with Amazon EC2 instance store
D) Amazon EC2 with Amazon Elastic Block Store (Amazon EBS)
ANSWER: D
52.	A company is designing a new application that will store and retrieve millions of photos and videos. Which AWS service or feature can provide the underlying storage at the LOWEST cost?
A) Amazon EC2 instance store
B) Amazon Elastic Block Store (Amazon EBS)
C) Amazon S3
D) Amazon Simple Queue Service (Amazon SQS)
ANSWER: A
53.	A company is designing an application hosted in a single AWS Region serving end-users spread across the world. The company wants to provide the end-users low latency access to the application data. Which of the following services will help fulfill this requirement?
A) Amazon CloudFront
B) AWS Direct Connect
C) Amazon Route 53 global DNS
D) Amazon Simple Storage Service (Amazon S3) transfer acceleration
ANSWER: A
54.	A company is expecting a short-term spike in internet traffic for its application. During the traffic increase, the application cannot be interrupted. The company also needs to minimize cost and maximize flexibility. Which Amazon EC2 instance type should the company use to meet these requirements?
A) On-Demand Instances
B) Spot Instances
C) Reserved Instances
D) Dedicated Hosts
ANSWER: B
55.	A company is hosting a web application in a Docker container on Amazon EC2. AWS is responsible for which of the following tasks?
A) Scaling the web application and services developed with Docker
B) Provisioning or scheduling containers to run on clusters and maintain their availability
C) Performing hardware maintenance in the AWS facilities that run the AWS Cloud
D) Managing the guest operating system, including updates and security patches
ANSWER: C
56.	A company is launching a new application in the AWS Cloud. The application will run on an Amazon EC2 instance. More EC2 instances will be needed when the workload increases. Which AWS service or tool can the company use to launch the number of EC2 instances that will be needed to handle the workload?
A) Elastic Load Balancing
B) Amazon EC2 Auto Scaling
C) AWS App2Container (A2C)
D) AWS Systems Manager
ANSWER: A
57.	A company is launching an e-commerce site that will store and process credit card data. The company requires information about AWS compliance reports and AWS agreements. Which AWS service provides on-demand access to these items?
A) AWS Certificate Manager
B) AWS Config
C) AWS Artifact
D) AWS CloudTrail
ANSWER: C
58.	A company is looking for a scalable data warehouse solution. Which of the following AWS solutions would meet the company’s needs?
A) Amazon Simple Storage Service (Amazon S3)
B) Amazon DynamoDB
C) Amazon Kinesis
D) Amazon Redshift
ANSWER: D
59.	A company is looking for a way to encrypt data stored on Amazon S3. Which AWS managed service can be used to help to accomplish this?
A) AWS Certificate Manager (ACM)
B) AWS Secrets Manager
C) AWS Resource Access Manager
D) AWS Key Management Service (AWS KMS)
ANSWER: D
60.	A company is migrating an application that is running non-interruptible workloads for a three-year time frame. Which pricing construct would provide the MOST cost-effective solution?
A) Amazon EC2 Spot Instances
B) Amazon EC2 Dedicated Instances
C) Amazon EC2 On-Demand Instances
D) Amazon EC2 Reserved Instances
ANSWER: D
61.	A company is migrating its on-premises data center to AWS and wants to provide NFS access to its Linux clients. Which AWS service should the company use?
A) Amazon S3
B) Amazon Elastic File System (Amazon EFS)
C) Amazon Elastic Block Store (Amazon EBS)
D) Amazon S3 Glacier
ANSWER: B
62.	A company is moving its development and test environments to AWS to increase agility and reduce cost. Because these are not production workloads and the servers are not fully utilized, occasional unavailability is acceptable. What is the MOST cost-effective Amazon EC2 pricing model that will meet these requirements?
A) Reserved Instances
B) On-Demand Instances
C) Spot Instances
D) Dedicated Instances
ANSWER: C
63.	A company is moving its office and must establish an encrypted connection to AWS. Which AWS service will help meet this requirement?
A) AWS VPN
B) Amazon Route 53
C) Amazon API Gateway
D) Amazon Connect
ANSWER: A
64.	A company is moving its on-premises key-value database to the AWS Cloud. Which AWS service will support this use case?
A) Amazon RDS
B) Amazon ElastiCache
C) Amazon DynamoDB
D) Amazon Redshift
ANSWER: C
65.	A company is moving multiple applications to a single AWS account. The company wants to monitor the AWS Cloud costs incurred by each application. What can the company do to meet this requirement?
A) Set up invoiced billing.
B) Use AWS Artifact.
C) Set the budgets in Cost Explorer.
D) Create cost allocation tags.
ANSWER: D
66.	A company is piloting a new customer-facing application on Amazon Elastic Compute Cloud (Amazon EC2) for one month. What pricing model is appropriate?
A) Reserved Instances
B) Spot Instances
C) On-Demand Instances
D) Dedicated Hosts
ANSWER: C
67.	A company is planning to create a new application that will run on Amazon EC2 instances and back up data on Amazon Elastic Block Store (EBS) volumes to Amazon S3. The company wants to estimate the monthly costs of running the application before making a deployment decision. Which AWS service or feature can be used to estimate these costs?
A) Cost Explorer
B) AWS Pricing Calculator
C) AWS Cost and Usage Report
D) AWS Budgets
ANSWER: B
68.	A company is planning to migrate from on-premises to the AWS Cloud. Which AWS tool or service provides detailed reports on estimated cost savings after migration?
A) AWS Total Cost of Ownership (TCO) Calculator
B) Cost Explorer
C) AWS Budgets
D) AWS Migration Hub
ANSWER: A
69.	A company is required to store its data close to its primary users. Which benefit of the AWS Cloud supports this requirement?
A) Security
B) High availability
C) Elasticity
D) Global footprint
ANSWER: D
70.	A company is running a Microsoft SQL Server instance on premises and is migrating its application to AWS. The company lacks the resources need to refactor the application, but management wants to reduce operational overhead as part of the migration.Which database service would MOST effectively support these requirements?
A) Amazon DynamoDB
B) Amazon Redshift
C) Microsoft SQL Server on Amazon EC2
D) Amazon RDS for SQL Server
ANSWER: D
71.	A company is running a self-managed Oracle database directly on Amazon EC2 for its steady-state database. The company wants to reduce compute costs. Which option should the company use to maximize savings over a 3-year term?
A) EC2 Dedicated Instances
B) EC2 Spot Instances
C) EC2 Reserved Instances
D) EC2 On-Demand Instances
ANSWER: C
72.	A company is running an ecommerce application hosted in Europe. To decrease latency for users who access the website from other parts of the world, the company would like to cache frequently accessed static content closer to the users. Which AWS service will support these requirements?
A) Amazon ElastiCache
B) Amazon CloudFront
C) Amazon Elastic File System (Amazon EFS)
D) Amazon Elastic Block Store (Amazon EBS)
ANSWER: B
73.	A company is running and managing its own Docker environment on Amazon EC2 instances. The company wants to alternate to help manage cluster size, scheduling, and environment maintenance. Which AWS service meets these requirements?
A) AWS Lambda
B) Amazon RDS
C) AWS Fargate
D) Amazon Athena
ANSWER: C
74.	A company is undergoing a security audit. The audit includes security validation and compliance validation of the AWS infrastructure and services that the company uses. The auditor needs to locate compliance-related information and must download AWS security and compliance documents. These documents include the System and Organization Control (SOC) reports. Which AWS service or group can provide these documents?
A) AWS Abuse team
B) AWS Artifact
C) AWS Support
D) AWS Config
ANSWER: B
75.	A company is using Amazon EC2 Auto Scaling to scale its Amazon EC2 instances. Which benefit of the AWS Cloud does this example illustrate?
A) High availability
B) Elasticity
C) Reliability
D) Global reach
ANSWER: B
76.	A company must ensure that its endpoint for a database instance remains the same after a single Availability Zone service interruption. The application needs to resume database operations without the need for manual administrative intervention. How can these requirements be met?
A) Use multiple Amazon Route 53 routes to the standby database instance endpoint hosted on AWS Storage Gateway.
B) Configure Amazon RDS Multi-Availability Zone deployments with automatic failover to the standby.
C) Add multiple Application Load Balancers and deploy the database instance with AWS Elastic Beanstalk.
D) Deploy a single Network Load Balancer to distribute incoming traffic across multiple Amazon CloudFront origins.
ANSWER: B
77.	A company must keep records of all resource changes that are made through the AWS Management Console and AWS APIs. Which AWS service should the company use to meet this requirement?
A) Amazon CloudWatch
B) AWS CloudTrail
C) AWS X-Ray
D) Amazon Inspector
ANSWER: B
78.	A company must process a large amount of data from social media accounts by making graphical queries with high throughput. Which AWS service will help the company design a cloud architecture that will meet these requirements?
A) Amazon RDS
B) Amazon DynamoDB
C) Amazon Neptune
D) Amazon Redshift
ANSWER: C
79.	A company must store critical business data in Amazon S3 with a backup to another AWS Region. How can this be achieved?
A) Use an Amazon CloudFront Content Delivery Network (CDN) to cache data globally
B) Set up Amazon S3 cross-region replication to another AWS Region
C) Configure the AWS Backup service to back up to the data to another AWS Region
D) Take Amazon S3 bucket snapshots and copy that data to another AWS Region
ANSWER: B
80.	A company needs 24/7 phone, email, and chat access, with a response time of less than 1 hour if a production system has a service interruption. Which AWS Support plan meets these requirements at the LOWEST cost?
A) Basic
B) Developer
C) Business
D) Enterprise
ANSWER: C
81.	A company needs a content delivery network that provides secure delivery of data, videos, applications, and APIs to users globally with low latency and high transfer speed. Which AWS service meets these requirements?
A) Amazon CloudFront
B) Elastic Load Balancing
C) Amazon S3
D) Amazon Elastic Transcoder
ANSWER: A
82.	A company needs a firewall that will control network connections to and from a single Amazon EC2 instance. This firewall will not control network connections to and from other instances that are in the same subnet. Which AWS service or feature can the company use to meet these requirements?
A) Network ACL
B) AWS WAF
C) Route table
D) Security group
ANSWER: D
83.	A company needs an Amazon S3 bucket that cannot have any public objects due to compliance requirements. How can this be accomplished?
A) Enable S3 Block Public Access from the AWS Management Console.
B) Hold a team meeting to discuss the importance if only uploading private S3 objects.
C) Require all S3 objects to be manually approved before uploading.
D) Create a service to monitor all S3 uploads and remove any public uploads.
ANSWER: A
84.	A company needs protection from expanded distributed denial of service (DDoS) attacks on its website and assistance from AWS experts during such events. Which AWS managed service will meet these requirements?
A) AWS Shield Advanced
B) AWS Firewall Manager
C) AWS WAF
D) Amazon GuardDuty
ANSWER: A
85.	A company needs software solutions that are hosted on the AWS platform or that are integrated with the AWS platform. The company needs solutions from independent software vendors as well as management and security vendors. Which group or team can provide these solutions?
A) AWS technical account managers (TAMs)
B) AWS Partner Network (APN) Consulting Partners
C) AWS Concierge Support
D) AWS Partner Network (APN) Technology Partners
ANSWER: B
86.	A company needs to improve the response rate of high-volume queries to its relational database. Which AWS service should the company use to offload requests to the database and improve overall response times?
A) Amazon DynamoDB Accelerator (DAX)
B) Amazon ElastiCache
C) Elastic Load Balancing
D) AWS Global Accelerator
ANSWER: A
87.	A company needs to migrate its on-premises data to the AWS Cloud. The company requires elastic, highly optimized connectivity. Which AWS service meets these requirements?
A) Amazon S3 Glacier
B) AWS Storage Gateway
C) AWS Backup
D) Amazon Elastic File System (Amazon EFS)
ANSWER: B
88.	A company needs to monitor and forecast AWS costs and usage. The company also must set event-driven alert notifications that occur if spending limits are exceeded. Which AWS service or tool should the company use to meet these requirements?
A) AWS Budgets
B) Amazon CloudWatch
C) AWS Config
D) AWS Service Catalog
ANSWER: A
89.	A company needs to perform a one-time migration of 40TB of data from its on-premises storage servers to Amazon S3. The transfer must happen as quickly as possible while keeping costs to a minimum. The company has 100 Mbps internet connectivity. Which AWS service will meet these requirements?
A) AWS Snowball
B) AWS Direct Connect
C) AWS Storage Gateway
D) Amazon S3 Transfer Acceleration
ANSWER: A
90.	A company needs to plan, schedule, and run hundreds of thousands of computing jobs on AWS. Which AWS service can the company use to meet this requirement?
A) AWS Step Functions
B) AWS Service Catalog
C) Amazon Simple Queue Service (Amazon SQS)
D) AWS Batch
ANSWER: D
91.	A company needs to securely store important credentials that an application uses to connect users to a database. Which AWS service can meet this requirement with the MINIMAL amount of operational overhead?
A) AWS Key Management Service (AWS KMS)
B) AWS Config
C) AWS Secrets Manager
D) Amazon GuardDuty
ANSWER: C
92.	A company needs to send time-critical messages to multiple subscribers through a push mechanism. Which AWS service should the company use?
A) Amazon Kinesis
B) Amazon MQ
C) Amazon Simple Queue Service (Amazon SQS)
D) Amazon Simple Notification Service (Amazon SNS)
ANSWER: D
93.	A company needs to track the activity in its AWS accounts, and needs to know when an API call is made against its AWS resources. Which AWS tool or service can be used to meet these requirements?
A) Amazon CloudWatch
B) Amazon Inspector
C) AWS Cloud TrailD. AWS IAM
ANSWER: C
94.	A company needs to transfer a large volume of data from an on-premises data center to the AWS Cloud. The company’s internet connectivity is slow and unreliable. Which AWS service can facilitate this data transfer?
A) Amazon S3 Glacier
B) AWS Snowball
C) AWS Storage Gateway
D) Amazon Elastic File System (Amazon EFS)
ANSWER: B
95.	A company needs to use AWS Identity and Access Management (IAM) to attach an IAM policy to all IAM users in an AWS account. Which solution meets this requirement?
A) Attach the IAM policy to each IAM user.
B) Attach the IAM policy to the IAM group containing all the IAM users.
C) Attach the IAM policy to the IAM role containing all the IAM users.
D) Apply the IAM policy to the entire AWS account.
ANSWER: C
96.	A company operating in the AWS Cloud requires separate invoices for specific environments, such as development, testing, and production. How can this be achieved?
A) Use multiple AWS accounts
B) Use resource tagging
C) Use multiple VPCs
D) Use Cost Explorer
ANSWER: B
97.	A company plans to store sensitive data in an Amazon S3 bucket. Which task is the responsibility of AWS?
A) Activate encryption at rest for the data.
B) Provide security for the physical infrastructure.
C) Train the company's employees about cloud security.
D) Remove personally identifiable information (PII) from the data.
ANSWER: A
98.	A company previously lost data that was stored in an on-premises data center. To protect against future loss of data, the company wants to use AWS to automatically launch thousands of its machines in a fully provisioned state in minutes, in a format that supports data restoration. Which AWS service should the company use to meet these requirements?
A) AWS Direct Connect
B) AWS Storage Gateway
C) CloudEndure Disaster Recovery
D) AWS Backup
ANSWER: C
99.	A company recently migrated to AWS and wants to enable intelligent threat protection and continuous monitoring across all of its AWS accounts. Which AWS service should the company use to achieve this goal?
A) Amazon Macie
B) Amazon GuardDuty
C) AWS Shield
D) Amazon Detective
ANSWER: B
100.	A company requires a dedicated network connection between its on-premises servers and the AWS Cloud. Which AWS service should be used?
A) AWS VPN
B) AWS Direct Connect
C) Amazon API Gateway
D) Amazon Connect
ANSWER: B

