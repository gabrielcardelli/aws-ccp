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
