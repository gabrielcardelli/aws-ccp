I need to study

AWS Trust Advisor
AWS Inspector
VPC
AWS CLOUD TRAIL
Write ML resumo here.
EFS x EBS x Local Storage x S3 x Redshift

## Account Management , Billing & Support

**AWS Organizations**\
It's a global service\
Multiple Organization = One Bill and Discount because use more resources.

Multi Account Strategies
- Create account per departament or per environment (dev, test, prod)

Service Control Policies
- Applied at the OU or Account
- SCP is applied to all User and roles
- Use to restrict access to certain services
- If one in the hierarchy deny nothing under can allow.

**AWS Control Tower**
- Set up and govern a secure and compliant
- Detect policy violations
- Monitor compliance
- Run on top of AWS Organizations

**Princing Models in AWS
- Pay as you go
- Save when you reserve
- Pay less by using more 
- Pay less as AWS grows

**Free services&&
- IAM, VPNC, Billing, Elastic Beanstalk, CloudFormation , Auto Scaling Groups

**Compute Pricing - EC2**
- On-demand: Minimum 60s, pay per second
- Reserved Instances: Up to 75% discord , 1 - 3 years commitment
- - Payment types: All upfront, partial upfront, no upfront
- Spot Instances: Upp to 90% discount compared to on demand
- Dedicated Host
- Savings Plans

**Lambda & ECS Pricing**
- Lambda: Pay per call, pay per duration
- ECS: EC2 Lauch Type Model -> No additional fees, you pay for AWS resources.
- Fargate: Pay for CPU and Memory allocated to your apps on containers

**S3 Pricing **
- More objects more disconts
- Pay for request
- Lifecycle transitions you need to pay

**EBS Pricing**
- Volume type
- Storage volume in GB

**RDS Pricing**
- Per hour
- Engine, size, memory
- Purchase Type: On demand or Reserved
- Additional Storage, number input and output

**CloudFront Pricing**
-- Pay per request based on region (regions has different prices)

**Networking Costs**
- Prefer user private IP instead of Public IP.
- You pay when connect and az to another ($0.01 per gb)  or  one region to other ($0.02 per gb)

**Saving plans**
- EC2: 72% discount usage indifidual instance families in regin C5 or M5
- Compute: 66% discount compared to on demand.

**Compute Optimizer**
- Helps us to choose optimal configurations
- Uses machine learning to know

**AWS Pricing Calculator**


**Cost Allocation Tags*
- Track in detailed level

**Trust Advisor**
- Analyze account and provides recommendations on: Cost optimization, Performance, Security, Fault tolerance, Service limits
- Default 7 core checks on Basic & Developer Suupport plan: S3 Bucket Permission, Security Groups, IAM USE, MFA on Root Account, EBS Public Snapshots, RDS Public Snapshots and Service Limits
- Full Checks Businnes & Enterprise Support Plan:  Full checks available on the 5 categories, Set CloudWatchAlarms, Programmatic Access using AWS Support API

**Support Plan**
- Basic
- Developer
- Business 
- - Trust Advisor Full Checks
- - Phone and chat Support
- Enterprise On-Ramp
- - Access to a pool technical account manager
- - Concierge Support Team
- Enterprise
- - Access to a designated technical account manager
- Concierge Support Team

**Best Practices**
- Operate multiple accounts using organizations
- Use cost allocation tags

## Machine Learning

**Rkognition**
- face detection

**Transcribe**
- audio to text

**Polly**
- text to audio

**Translate**
- translations

**Lex**
- chatbots

**Connection**
- cloud contact center

**Comprehend**
- NPL
- Servless
- Extraction
- Understand if the text is positive or negative
- Used to analyze emails

**SageMaker**
- Build machine learning models.

**Forecast**
- Predict the future

**Kendra**
- Document Search Service
- Extract answers from documents, for example 'Where is the IT support Desk?'

**Personalize**
- Product Recommendations

**Textract**
- extract text handwrited to json



## Others



**AWS Trust Advisor**
- Aconselhará sobre Well Archtecture.

**AWS Inspector**
- Focus on security

**AWS Cloud Trail**

**AWS Glue**



**AWS IAM**
- Identity Access Management

**AWS STS** (Security Token Service)
- Temporary, limited-privileges to access AWS resouces

**AWS Cognito**
- Create database for users accessed by mobile and web application

**AWS Directory Services**
- Managed microsoft active directory

**AWS IAM Identity Center**
- SSO for all organizations.

**Amazon Workspaces**
-- Virtual Desktops

**Amazon AppStream 2.0**
- Desktop Application Streaming Service
- Application Heavy running at browser by Stream

**Amazon Sumerian**
- Create and run Virtual Reality, Create 3D Models

**AWS IOT Core**
- Easy connect IOT devices to the AWS Cloud
- Servless, secure & sacalable

**Amazon Elastic Transcorder**
- Convert s3 files to fortmat required by consumer
- S3 Input -> Transcoding Pipeline -> S3 OutputBucket <- Smartphones, Tablets, PCs

**AWS AppSync**
- Use GraphQL
- Store and sync data across mobile and web apps
- Real-time subscriptions
- Offline data sync

**AWS Amplify**
- Tools and services to help develop deploy scalable fullstack web and mobile apps

**AWS Device Farm**
- Service that tests web and mobile apps 
- Run tests concurrently on mutiple devices

**AWS DataSync**
- Move large amount of data from o premises to AWS.
- Incremental

**AWS Backup**
- Centrally manage and automate backups
- Has a backup plan (frequency, retention and policy)


**AWS Application Discovery Service**
- Plan Migration
- - Agentless Discorvery
- - Agent based Discorvery

**AWS Application Migration Service**
- Simplify migrating applications to AWS

**AWS Fault Injection Simulator**
- Based on Chaos Engeneering - stressing an application by creating disruptive events
- AWS Fault -> Create Experiment Template -> Start Resources (EC2,ECS) <- Monitoring With CloudWatch and EventBridge -> View Results

**AWS Step Functions**
- Build servless visual workflow to orchestrate your lambda functions

**AWS Ground Station**
- Control sattelite
- Allows you to download satellite data to S3 or EC2

**Amazon Pinpoint**
- Marketing communications service
- Support email,SMS, push, voice and in-app messaging.

**AWS Whitepapers Well-Architected Framework**
_1st pillar: Operational Excelence_
- Ability to run and monitor systems
- Design Principles: 
  - Perform operations as code
  - Annotate documentation
  - Make frequent small reversible chances
  - Refine operations procedures frequently
  - Anticipate failure
  -Learn from all operational failures
- Prepare Stage: Cloud Formation, AWS  Config
- Operate Stage: CloudFormation, AWS Config, AWS CloudTrail, CloudWatch, X-Ray
- Evolve Stage: CloudFormation, CodeBuild, CodeCommit, CodeDeploy, CodePipeline

_2nd pillar: Security_
- Design Principles
  - Implement a strong identity foundation: Centralize Previlege Management (IAM,STS,MFA token , Organizatios)
  - Enable traceability: Integrate logs and metrics
  - Apply Security at all layers (VPC, SHIELD, WAF, Inspector)
  - Automate security best practices
  - Protect data in transit and at rest (KMS, S3)
  - Keep people away from data
  - Prepare for security events

_3rd pillar: Reliability_
- Ability of a system to recover from infra or service disruptions.
- Design Principles:
  - Test recovery procedures
  - Automatically recover from failure
  - Scale horizontally to increse aggregate availability
  - Stop guessing capacity
  - Manage chance in automation

_4th pillar: Performance Efficiency_
- Design Principles:
  - Democratize advanced tech
  - Go global in minutes
  - Use servless architectures
  - Experiment more often
  - Mechanical Sympathy: Be aware of all AWS Services
_5th pillar: Cost Optimization:
- Design Principles:
  - Adopt a consumption mode
  - Measure overall efficiency: Use cloud watch
  - Stop spending money on data center operations
  - Analyze and attribute expenditure: Accurate identification of system usage
  - Use managed and application level services to reduce cost of ownership

_6th pillar: Sustainability_
- Design Principles: 
  - Understand your impact 
  - Establish sustainability goals
  - Maximize utilization: Minimize idle resources
  - Anticipate and adopt new, more efficient hardware and software offerings: Adopt new technologies over time
  - Use managed services: Shared services reduce the amount of infra.
  - Reduce the downstream impact of your cloud workloads

**AWS Well-Architected Tool**

**AWS Right Sizing**
- Matching instance type and sizes to workload performance at lowest possible cost
- Important on: before a Cloud Migration, continously after the cloud onboarding process

**AWS Ecosystem**
- AWS Blogs, AWS Forums, AWS Whitepapers & Guides, AWS QuickStarts (Ex: Wordpress, build env quickly), AWS Solutions

**AWS Support**
- Developer:
  - Business Hour by Email
  - General guidance: < 24 businnes hour
  - System impaired: < 12 business hour
- Business
  - 24h phone, email, chat access to Cloud Support Engineers
  - Production system impaired: < 4h
  - Production system down: < 1h
- Enterprise
  - Access to a Technical Account Manager (TAM)
  - Concierge Support Team (for billing and account best practices)
  - Business-critical system down: < 15m

**AWS Marketplace**
- Digital catalog listing independent software vendors: Custom AMI, CloudFormation templates, SaaS, Containers.

**AWS Training**
- Online and Classroom Training
- Private Training for Organization
- Training and Cert for the U.S Government
- Training and Cert for the Enterprise

**AWS Professional Services & Partnet Network**
- Global team of experts to help us.

**AWS Knowledge Center**
- Contains the most frequently and common questions

**AWS IQ**
- Quickly find profissional help for AWS projects.

**AWS re:Post**
- Like stackoverflow
