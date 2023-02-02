I need to study

AWS Trust Advisor
AWS Inspector
VPC
AWS CLOUD TRAIL
Write ML resumo here.
EFS x EBS x Local Storage x S3 x Redshift

## Resume


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
