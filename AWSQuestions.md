## You have an application running on Amazon Elastic Compute Cloud (Amazon EC2) that needs read-only access to several AWS services. What is the best way to grant that application permissions only to a specific set of resources within your account?

- Use API credentials derived based on the AWS account.
- Launch the EC2 instance into an AWS Identity and Access Management (IAM) role and attach the ReadOnlyAccess IAM-managed policy.
- Declare the necessary permissions as statements in the AWS SDK configuration file on the EC2 instance.
- Launch the EC2 instance into an IAM role with custom IAM policies for the permissions.

## You have deployed a new application in the US West (Oregon) Region. However, you have accidentally deployed an Amazon Polly lexicon needed for your application in EU (London). How can you use your lexicon to synthesize speech while minimizing the changes to your application code and reducing cost?

- Point your SDK client to the EU (London) for all requests to Amazon Polly, but to US West (Oregon) for all other API calls.
- No action needed; the data is automatically available from all Regions.
- Upload a copy of the lexicon to US West (Oregon).
- Move the rest of the application resources to EU (London).

## When you’re placing subnets for a specific Amazon Virtual Private Cloud (Amazon VPC), you can place the subnets in which of the following?

- In any Availability Zone within the Region for the Amazon VPC
- In any Availability Zone in any Region
- In any AWS edge location
- In any specific AWS data center

## You have identified two Amazon Elastic Compute Cloud (Amazon EC2) instances in your account that appear to have the same private IP address. What could be the cause?

- These instances are in different Amazon Virtual Private Cloud (Amazon VPCs).
- The instances are in different subnets.
- The instances have different network ACLs.
- The instances have different security groups.

## You have a workload that requires 15,000 consistent IOPS for data that must be durable. What combination of the following do you need? (Select TWO.)

- Use an Amazon Elastic Block Store (Amazon EBS) optimized instance.
- Use an instance store.
- Use a Provisioned IOPS SSD volume.
- Use a previous-generation EBS volume.

## Your company stores critical documents in Amazon Simple Storage Service (Amazon S3), but it wants to minimize cost. Most documents are used actively for only about one month and then used much less frequently after that. However, all data needs to be available within minutes when requested. How can you meet these requirements?

- Migrate the data to Amazon S3 Reduced Redundancy Storage (RRS) after 30 days.
- Migrate the data to Amazon S3 Glacier after 30 days.
- Migrate the data to Amazon S3 Standard – Infrequent Access (IA) after 30 days.
- Turn on versioning and then migrate the older version to Amazon S3 Glacier.

## You are migrating your company’s applications and data from on-premises to the AWS Cloud. You have performed a data inventory and discovered that you will need to transfer about 2 PB of data to AWS. Which migration option will be the best choice for your company with minimal cost and shortest time?

- AWS Snowball
- AWS Snowmobile
- Upload files directly to AWS over the internet using Amazon Simple Storage Service (Amazon S3) Transfer Acceleration.
- Amazon Kinesis Data Firehose

## You are changing your application to take advantage of the elasticity and cost benefits provided by AWS Auto Scaling. To do this, you must move session state information from the individual Amazon Elastic Compute Cloud (Amazon EC2) instances. Which of the following AWS Cloud services is best suited as an alternative for storing session state information?

- Amazon DynamoDB
- Amazon Redshift
- AWS Storage Gateway
- Amazon Kinesis

## Your company’s senior management wants to query several data stores to obtain a “big picture” view of the business. The amount of data contained within the data stores is at least 2 TB in size. Which of the following is the best AWS service to deliver results to senior management?

- Amazon Elastic Block Store (Amazon EBS)
- Amazon Simple Storage Service (Amazon S3)
- Amazon Relational Database Service (Amazon RDS)
- Amazon Redshift

## Your ecommerce application provides daily and ad hoc reporting to various business units on customer purchases. These operations result in a high level of read traffic to your MySQL Amazon Relational Database Service (Amazon RDS) instance. What can you do to scale up read traffic without impacting your database’s performance?

- Increase the allocated storage for the Amazon RDS instance.
- Modify the Amazon RDS instance to be a Multi-AZ deployment.
- Create a read replica for an Amazon RDS instance.
- Change the Amazon RDS instance DB engine version.

## Your company has refactored their application to use NoSQL instead of SQL. They would like to use a managed service for running the new NoSQL database. Which AWS service should you recommend?

- Amazon Relational Database Service (Amazon RDS)
- Amazon Elastic Compute Cloud (Amazon EC2)
- Amazon DynamoDB
- Amazon Redshift

## A company is currently using Amazon Relational Database Service (Amazon RDS); however, they are retiring a database that is currently running. They have automatic backups enabled on the database. They want to make sure that they retain the last backup before deleting the Amazon RDS database. As the lead developer on the project, what should you do?

- Delete the database. Amazon RDS automatic backups are already enabled.
- Create a manual snapshot before deleting the database.
- Use the AWS Database Migration Service (AWS DMS) to back up the database.
- SSH into the Amazon RDS database and perform a SQL dump.

## When using Amazon Redshift, which node do you use to run your SQL queries?

- Compute node
- Cluster node
- Master node
- Leader node

## Your company is building a recommendation feature for their application. They would like to use an AWS managed graph database. Which service should you recommend?

- Amazon Relational Database Service (Amazon RDS)
- Amazon Neptune
- Amazon ElastiCache
- Amazon Redshift

## You have an Amazon DynamoDB table that has a partition key and a sort key. However, a business analyst on your team wants to be able to query the DynamoDB table with a different partition key. What should you do?

- Create a local secondary index.
- Create a global secondary index.
- Create a new DynamoDB table.
- Advise the business analyst that this is not possible.

## An application is using Amazon DynamoDB. Recently, a developer on your team has noticed that occasionally the application does not return the most up-to-date data after a read from the database. How can you solve this issue?

- Increase the number of read capacity units (RCUs) for the table.
- Increase the number of write capacity units (WCUs) for the table.
- Refactor the application to use a SQL database.
- Configure the application to perform a strongly consistent read.

## A developer on your team would like to test a new idea and requires a NoSQL database. Your current applications are using Amazon DynamoDB. What should you recommend?

- Create a new table inside DynamoDB.
- Use DynamoDB Local.
- Use another NoSQL database on-premises.
- Create an Amazon Elastic Compute Cloud (Amazon EC2) instance, and install a NoSQL database.

## The AWS Encryption SDK provides an encryption library that integrates with AWS Key Management Service (AWS KMS) as a master key provider. Which of the following operations does the AWS Encryption SDK perform to build on the AWS SDKs?

- Generates, encrypts, and decrypts data keys
- Uses the data keys to encrypt and decrypt your raw data
- Stores the encrypted data keys with the corresponding encrypted data in a single object
- All of the above

## Of all the cryptographic algorithms that the AWS Encryption SDK supports, which one is the default algorithm?

- AES-256
- AES-192
- AES-128
- SSH-256

## Amazon Elastic Block Store (Amazon EBS) volumes are encrypted by default.

- True
- False

## Which of the following cannot be retained when deleting an AWS Elastic Beanstalk environment?

- Source code from the Git repository
- Data from the automatic backups of an Amazon Relational Database Service (Amazon RDS) instance
- Packaged code from the source bundle stored in an Amazon Simple Storage Service (Amazon S3) bucket
- Data from the snapshot of an Amazon RDS instance

## Which of the following is not part of the AWS Elastic Beanstalk functionality?

- Notify the account user of language runtime platform changes
- Display events per environment
- Show instance statuses per environment
- Perform automatic changes to AWS Identity and Access Management (IAM) policies

## What happens to AWS CodePipeline revisions that, upon reaching a manual approval gate, are rejected?

- The pipeline continues.
- A notification is sent to the account administrator.
- The revision is treated as failed.
- The pipeline creates a revision clone and continues.

## Which of the following is an invalid strategy for migrating data to AWS CodeCommit?

- Incrementally committing files from a large repository
- Syncing the files from Amazon Simple Storage Service (Amazon S3) using the sync AWS CLI command
- Cloning an existing repository, updating the remote, and pushing
- Manually creating files in the AWS Management Console

## You have an AWS CodeBuild task in your pipeline that requires large binary files that do not frequently change. What would be the best way to include these files in your build?

- Store the files in your source code repository. They will be passed in as part of the revision.
- Store the files in an Amazon Simple Storage Service (Amazon S3) bucket and copy them during the build.
- Create a custom build container that includes the files.
- It is not possible to include files above a certain size.

## When you update an AWS::S3::Bucket resource, what is the expected behavior if the Name property is updated?

- The resource is updated with no interruption.
- The resource is updated with some interruption.
- The resource is replaced.
- The resource is deleted.

## What is the preferred method for updating resources created by AWS CloudFormation?

- Updating the resource directly in the AWS Management Console
- Submitting an updated template to AWS CloudFormation to modify the stack
- Updating the resource using the AWS Command Line Interface (AWS CLI)
- Updating the resource using an AWS Software Development Kit (AWS SDK)

## When does the AWS OpsWorks Stacks configure lifecycle event run?

- On individual instances immediately when they are first created
- On individual instances after a deploy lifecycle event
- On all instances in a stack when a single instance comes online or goes offline
- On all instances in a stack after a deploy lifecycle event

## Which non-Amazon Elastic Compute Cloud (Amazon EC2) AWS resources can AWS OpsWorks Stacks manage? (Select THREE.)

- Elastic IP addresses
- Amazon Elastic Block Store (Amazon EBS) volumes
- Amazon Relational Database Service (Amazon RDS) database instances
- Amazon ElastiCache clusters
- Amazon Redshift data warehouses

## Which AWS Cloud service can Simple Active Directory (Simple AD) use to authenticate users?

- Amazon WorkDocs
- Amazon Cognito
- Amazon Elastic Compute Cloud (Amazon EC2)
- Amazon Simple Storage Service (Amazon S3)

## What is the best application of Amazon Cognito?

- Use instead of Active Directory for AWS Identity and Access Management (IAM) users.
- Provide authentication to third-party web applications.
- Use as an Amazon Aurora database.
- Use to access objects in an Amazon Simple Storage Service (Amazon S3) bucket.

## You manage a sales tracking system in which point-of-sale devices send transactions of this form: {"date":"2017-01-30", "amount":100.20, "product_id": "1012", "region": "WA", "customer_id": "3382"}

- You need to generate two real-time reports. The first reports on the total sales per day for each customer. The second reports on the total sales per day for each product. Which AWS offerings and services can you use to generate these real-time reports?
- Ingest the data through Amazon Kinesis Data Streams. Use Amazon Kinesis Data Analytics to query for sales per day for each product and sales per day for each customer using SQL queries. Feed the result into two new streams in Amazon Kinesis Data Firehose.
- Ingest the data through Kinesis Data Streams. Use Kinesis Data Firehose to query for sales per day for each product and sales per day for each customer with SQL queries. Feed the result into two new streams in Kinesis Data Firehose.
- Ingest the data through Kinesis Data Analytics. Use Kinesis Data Streams to query for sales per day for each product and sales per day for each customer with SQL queries. Feed the result into two new streams in Kinesis Data Firehose.
- Ingest the data in Amazon Simple Queue Service (Amazon SQS). Use Kinesis Data Firehose to query for sales per day for each product and sales per day for each customer with SQL queries. Feed the result into two new streams in Kinesis Data Firehose.

## You design an application for selling toys online. Every time a customer orders a toy, you want to add an item into the orders table in Amazon DynamoDB and send an email to the customer acknowledging their order. The solution should be performant and cost-effective. How can you trigger this email?

- Use an Amazon Simple Queue Service (Amazon SQS) queue.
- Schedule an AWS Lambda function to check for changes to the orders table every minute.
- Schedule an Lambda function to check for changes to the orders table every second.
- Use Amazon DynamoDB Streams.

## A company would like to use Amazon DynamoDB. They want to set up a NoSQL-style trigger. Is this something that can be accomplished? If so, how?

- No. This cannot be done with DynamoDB and NoSQL.
- Yes, but not with AWS Lambda.
- No. DynamoDB is not a supported event source for Lambda.
- Yes. You can use Amazon DynamoDB Streams and poll them with Lambda.

## A company wants to access the infrastructure on which AWS Lambda runs. Is this possible?

- No. Lambda is a managed service and runs the necessary infrastructure on your behalf.
- Yes. They can access the infrastructure and make changes to the underlying OS.
- Yes. They need to open a support ticket.
- Yes, but they need to contact their Solutions Architect to provide access to the environment.

## Using the smallest amount of memory possible for an AWS Lambda function, currently 128 MB, will result in the lowest bill.

- True. Lambda bills based on the total memory allocated.
- False. Lambda has a flat rate—memory allocation is not important for billing, only performance.
- False. Lambda bills based on memory plus the number of times that you trigger the function.
- False. Lambda bills based on memory, the amount of compute time spent on a function in 100-ms increments, and the number of times that you execute or trigger a function.

## Which Amazon services can you use for caching? (Select TWO.)

- AWS CloudFormation
- Amazon Simple Storage Service (Amazon S3)
- Amazon CloudFront
- Amazon ElastiCache

## Which Amazon API Gateway feature enables you to create a separate path that can be helpful in creating a development endpoint and a production endpoint?

- Authorizers
- API keys
- Stages
- Cross-origin resource sharing (CORS)

## Which of the following methods does Amazon API Gateway support?

- GET
- POST
- OPTIONS
- All of the above

## Which authorization mechanisms does Amazon API Gateway support?

- AWS Identity and Access Management (IAM) policies
- AWS Lambda custom authorizers
- Amazon Cognito user pools
- All of the above

## Which tool can you use to develop and test AWS Lambda functions locally?

- AWS Serverless Application Model (AWS SAM)
- AWS SAM CLI
- AWS CloudFormation
- None of the above

## Which serverless AWS service can you use to store user session state?

- Amazon Elastic Compute Cloud (Amazon EC2)
- Amazon ElastiCache
- AWS Elastic Beanstalk
- Amazon DynamoDB

## Which AWS service can you use to store user profile information?

- Amazon CloudFront
- Amazon Cognito
- Amazon Kinesis
- AWS Lambda

## Which of the following objects are good candidates to store in a cache? (Select THREE.)

- Session state
- Shopping cart
- Product catalog
- Bank account balance

## Which of the following cache engines does Amazon ElastiCache support? (Select TWO.)

- Redis
- MySQL
- Couchbase
- Memcached

## How can you aggregate Amazon CloudWatch metrics across Regions?

- CloudWatch does not aggregate data across Regions.
- This is enabled by default.
- Send the metric data from other Regions to Amazon Simple Storage Service (Amazon S3) for retrieval by CloudWatch.
- Stream the metric data to Amazon Kinesis, and retrieve it using an AWS Lambda function.

## Why would an Amazon CloudWatch alarm report as INSUFFICIENT_DATA instead of OK or ALARM? (Select THREE.)

- The alarm was just created.
- The metric is not available.
- There is an AWS Identity and Access Management (IAM) permission preventing the metric from receiving data.
- Not enough data is available for the metric to determine the alarm state.
- The alarm period is missing.

## You were asked to develop an administrative web application that consumes low throughput and rarely receives high traffic. Which of the following instance type families will be the most optimized choice?

- Memory optimized
- Compute optimized
- General purpose
- Accelerated computing

## Which of the following AWS Cost Management Tools can you use to view your costs and find ways to take advantage of elasticity?

- AWS Cost Explorer
- AWS Trusted Advisor
- Amazon CloudWatch
- Amazon EC2 Auto Scaling

## Because cloud resources are easier to deploy and they incur usage-based costs, your organization is setting up good governance rules to manage costs. They are currently focusing on controlling and restricting Amazon Elastic Compute Cloud (Amazon EC2) instance deployments. Which of the following is an effective recommendation?

- Seek approval from Cost Engineering teams before deploying any EC2 instances.
- Use AWS Identity and Access Management (IAM) policies to enable engineers to deploy EC2 instances only when specific mandatory tags are used.
- Review Amazon CloudWatch metrics to optimize the resource utilization.
- Use AWS Cost Explorer usage and forecasting reports.

## Because your applications are showing a consistent steady-state compute usage, you have decided to purchase Amazon Elastic Compute Cloud (Amazon EC2) Reserved Instances to gain significant pricing discounts. Which of the following is not the best purchase option?

- All Upfront
- Partial Upfront
- No Upfront
- Pay-as-you-go

## Your application processes transaction-heavy and IOPS-intensive database workloads. You need to choose the right Amazon Elastic Block Store (Amazon EBS) volume so that application performance is not affected. Which of the following options would you suggest?

- HDD-backed storage (st1)
- SSD-backed storage (io1)
- Amazon Simple Storage Service (Amazon S3) Intelligent Tier class storage
- Cold HDD-backed storage (sc1)

## A legacy financial institution is planning for a huge technical upgrade and planning to go global. The architecture depends heavily on using caching solutions. Which one of the following services does not fit into the caching solutions?

- Amazon ElastiCache for Redis
- Amazon ElastiCache for Memcached
- Amazon DynamoDB Accelerator
- Amazon Elastic Compute Cloud (Amazon EC2) memory-optimized

## Which of the following characteristics separates Amazon DynamoDB from the Amazon Relational Database Service (Amazon RDS) design?

- Incurs the performance costs of an ACID-compliant transaction system
- Normalizes data and stores it on multiple tables
- Keeps related data together
- May require expensive joins

## Which of the following partition key choices is an inefficient design that leads to poor distribution of the data in an Amazon DynamoDB table?

- User ID, where the application has many users
- Device ID, where each device accesses data at relatively similar intervals
- Status code, where there are only a few possible status codes
- Session ID, where the user session remains distinct

## You are planning to build serverless backends by using AWS Lambda to handle web, mobile, Internet of Things (IoT), and third-party API requests. Which of the following are the main benefits in opting for a serverless architecture in this scenario? (Select THREE.)

- No need to manage servers
- No need to ensure application fault tolerance and fleet management
- No charge for idle capacity
- Flexible maintenance schedules
- Powered for high complex processing

## Your enterprise infrastructure has recently migrated to the AWS Cloud. You are now trying to optimize the storage solutions. Which of the following are the appropriate storage management tools that you can use to review and analyze the storage classes and access patterns usage to help reduce costs? (Select TWO.)

- Amazon Simple Storage Service (Amazon S3) analytics
- Cost allocation Amazon S3 bucket tags
- Amazon S3 Transfer Acceleration
- Amazon Route 53
- AWS Budgets
