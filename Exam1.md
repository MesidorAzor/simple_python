# Questions I did not get correct!
![](exam_1_practice.png)

51. Multi AZ (Availability Zone) deployment is an example of which of the following?

a. Vertical Scaling 

b. Performance Efficiency 

c. High Availability 

d. Horizontal Scaling

# ANSWER: C

High Availability – A system that is available is capable of delivering the designed functionality at a given point in time. Highly available systems are those that can withstand some measure of degradation while still remaining available. On AWS Cloud, you can run instances for an application across multi AZ to achieve High Availability.

Incorrect options:

Horizontal Scaling – A “horizontally scalable” system is one that can increase capacity by adding more computers to the system. This is in contrast to a “vertically scalable” system, which is constrained to running its processes on only one computer; in such systems, the only way to increase performance is to add more resources into one computer in the form of faster (or more) CPUs, memory or storage. Horizontally scalable systems are oftentimes able to outperform vertically scalable systems by enabling parallel execution of workloads and distributing those across many different computers. Auto Scaling Group is an example of Horizontal Scaling on AWS.

Vertical Scaling – Vertical Scaling is adding more resources (like CPU, RAM) to a single node or machine. Example- Resizing an instance of EC2.

Performance Efficiency – Is the ability to use computing resources efficiently to meet system requirements and to maintain that efficiency as demand changes and technologies evolve.

References:

https://wa.aws.amazon.com/wat.concept.availability.en.html

https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html

----------
54. A customer has created a VPC and a subnet within AWS Cloud. Which of the following statements is correct?

a. A VPC spans all of the Availability Zones in the Region whereas a subnet spans only one 
Availability Zone in the Region	

b.A subnet spans all of the Availability Zones in the Region whereas a VPC spans only 
one Availability Zone in the Region	

c.Both the VPC and the subnet span all of the Availability Zones in the Region

d.Both the VPC and the subnet span only one Availability Zone in the Region

# ANSWER: A

A VPC spans all of the Availability Zones in the Region whereas a subnet spans only one Availability Zone in the Region

Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways. A VPC spans all of the Availability Zones in the Region.

A subnet is a range of IP addresses within your VPC. A subnet spans only one Availability Zone in the Region.
VPC and Subnet Overview:  via – https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html

Incorrect options:

Both the VPC and the subnet span all of the Availability Zones in the Region
Both the VPC and the subnet span only one Availability Zone in the Region
A subnet spans all of the Availability Zones in the Region whereas a VPC spans only one Availability Zone in the Region
These three options contradict the details provided earlier in the explanation, so these options are incorrect.

Reference:

https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html

------------------
 65. What are the advantages that AWS Cloud offers over a traditional on-premises IT infrastructure? (Select two)

a. Provide lower latency to applications by maintaining servers on-premises

b. Increase speed and agility by keeping servers and other required resources ready before time in your data centers

c. Make a capacity decision before deploying an application, to reduce costs

d. Trade capital expense for variable expense

e. Eliminate guessing on your infrastructure capacity needs

# ANSWER: D,E

Trade capital expense for variable expense – In a traditional on-premises environment, you have to invest heavily in data centers and servers before you know how you’re going to use them. With Cloud Computing, you can pay only when you consume computing resources, and pay only for how much you consume.

Eliminate guessing on your infrastructure capacity needs – When you make a capacity decision before deploying an application, you often end up either sitting on expensive idle resources or dealing with limited capacity. With Cloud Computing, these problems go away. You can access as much or as little capacity as you need, and scale up and down as required with only a few minutes’ notice. You can Stop guessing capacity.

Incorrect options:

Make a capacity decision before deploying an application, to reduce costs – As explained above, when you make a capacity decision before deploying an application, you often end up either sitting on expensive idle resources or dealing with limited capacity.

Provide lower latency to applications by maintaining servers on-premises – Maintaining servers on-premises involves costly capital expenses and costly ongoing expenses to maintain, manage and upgrade them.

Increase speed and agility by keeping servers and other required resources ready before time in your data centers – This again is indicative of maintaining on-premises infrastructure which is neither a cost-effective or time effective way of managing the resources.

Reference:

https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html


66. Which of the following AWS Support plans provides access to 7 core checks from the AWS Trusted Advisor Best Practice Checks? (Select two)

a. Busniess

b.Enterpise

c. Corporate

d.Developer
	
e.Basic

# ANSWER: D,E

Basic – The basic plan only provides access to the following:
Customer Service & Communities – 24×7 access to customer service, documentation, whitepapers, and support forums. AWS Trusted Advisor – Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security. AWS Personal Health Dashboard – A personalized view of the health of AWS services, and alerts when your resources are impacted.

Developer – AWS recommends Developer Support if you are testing or doing early development on AWS and want the ability to get email-based technical support during business hours as well as general architectural guidance as you build and test. This plan provides access to just the 7 core Trusted Advisor checks.

Exam Alert:

Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:
via – https://aws.amazon.com/premiumsupport/plans/

Incorrect options:

Business – AWS recommends Business Support if you have production workloads on AWS and want 24×7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. You also get full access to AWS Trusted Advisor Best Practice Checks.

Enterprise – AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24×7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts. You also get full access to AWS Trusted Advisor Best Practice Checks.

Corporate – This is a made-up option and has been added as a distractor.

Reference:

https://aws.amazon.com/premiumsupport/plans/

-----------

 71. AWS Shield Advanced provides expanded DDoS attack protection for web applications running on which of the following resources? (Select two)

a. AWS Global Accelerator

b. AWS Elastic Beanstalk	

c. AWS CloudFormation
d. Amazon Route 53

e. Amazon API Gateway

# ANSWER: A,D

Amazon Route 53

AWS Global Accelerator
AWS Shield Standard is activated for all AWS customers, by default. For higher levels of protection against attacks, you can subscribe to AWS Shield Advanced. With Shield Advanced, you also have exclusive access to advanced, real-time metrics and reports for extensive visibility into attacks on your AWS resources. With the assistance of the DRT (DDoS response team), AWS Shield Advanced includes intelligent DDoS attack detection and mitigation for not only for network layer (layer 3) and transport layer (layer 4) attacks but also for application layer (layer 7) attacks.

AWS Shield Advanced provides expanded DDoS attack protection for web applications running on the following resources: Amazon Elastic Compute Cloud, Elastic Load Balancing (ELB), Amazon CloudFront, Amazon Route 53, AWS Global Accelerator.

Incorrect options:

Amazon API Gateway – Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the “front door” for applications to access data, business logic, or functionality from your backend services. Amazon Web Application Firewall is used to monitor the HTTP and HTTPS requests that are forwarded to an Amazon API Gateway API. It is not covered under AWS Shield Advanced.

AWS CloudFormation – AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. CloudFormation is not covered under AWS Shield Advanced.

AWS Elastic Beanstalk – AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with various programming languages. You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. Elastic Beanstalk is covered under AWS Shield Standard. Advanced coverage is not offered for this service.

Reference: https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html

--------------

72. Which AWS services can be used to facilitate organizational change management, part of the Reliability pillar of AWS Well-Architected Framework (Select 2)?

a. AWS CloudTrail	

b. Amazon Inspector

c. AWS Trusted Advisor

d. AWS Config
	
e. Amazon CloudWatch

# ANSWER: A,D

There are three best practice areas for Reliability in the cloud – Foundations, Change Management, Failure Management. Being aware of how change affects a system (change management) allows you to plan proactively, and monitoring allows you to quickly identify trends that could lead to capacity issues or SLA breaches.
AWS Config – AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.

How AWS Config Works:  via – https://aws.amazon.com/config/
AWS CloudTrail – AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services.
How CloudTrail Works:  via – https://aws.amazon.com/cloudtrail/

Incorrect options:
AWS Trusted Advisor – AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement.

Amazon Inspector – Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices.

Amazon CloudWatch – Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health.

References:

https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf

https://aws.amazon.com/config/

https://aws.amazon.com/cloudtrail/

-----------------
73. Which of the following AWS services support reservations to optimize costs? (Select three)

a.Lambda	
b.EC2 Instances	
c.S3
d.RDS
e.DynamoDB
f.DocumentDB

# ANSWER: B,D,E

EC2 Instances

DynamoDB

RDS
The following AWS services support reservations to optimize costs:

Amazon EC2 Reserved Instances: You can use Amazon EC2 Reserved Instances to reserve capacity and receive a 
discount on your instance usage compared to running On-Demand instances.

Amazon DynamoDB Reserved Capacity: If you can predict your need for Amazon DynamoDB read-and-write throughput, Reserved Capacity offers significant savings over the normal price of DynamoDB provisioned throughput capacity.

Amazon ElastiCache Reserved Nodes: Amazon ElastiCache Reserved Nodes give you the option to make a low, one-time payment for each cache node you want to reserve and, in turn, receive a significant discount on the hourly charge for that node.

Amazon RDS RIs: Like Amazon EC2 RIs, Amazon RDS RIs can be purchased using No Upfront, Partial Upfront, or All Upfront terms. All Reserved Instance types are available for Aurora, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server database engines.

Amazon Redshift Reserved Nodes: If you intend to keep an Amazon Redshift cluster running continuously for a prolonged period, you should consider purchasing reserved-node offerings. These offerings provide significant savings over on-demand pricing, but they require you to reserve compute nodes and commit to paying for those nodes for either a 1- or 3-year duration.

Incorrect options:

DocumentDB – Amazon DocumentDB (with MongoDB compatibility) is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads. As a document database, Amazon DocumentDB makes it easy to store, query, and index JSON data.

Lambda – AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume.

S3 – Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.
None of these AWS services support reservations to optimize costs.

Reference: https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf

-------------

74. An IT company is planning to migrate from an on-premises environment to AWS Cloud. Which of the following expense areas would result in cost savings when the company moves to AWS Cloud? (Select two)
a.Data center physical security expenditure	
d.Project manager salary
b.Computing hardware infrastructure expenditure	
e.SaaS application license fee
c.Developer salary

# ANSWER: A,B

Data center hardware infrastructure expenditure

Data center physical security expenditure

The company does not need to spend on the computing hardware infrastructure and data center physical security. So these expense areas would result in cost savings.

The expenditure on the SaaS application license fee, developer salary, and project manager salary would remain the same.

Exam Alert:
Please check out the following six advantages of Cloud Computing. You would certainly be asked questions on the advantages of Cloud Computing compared to a traditional on-premises setup:  via – https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html

Incorrect options:

SaaS application license fee

Developer salary

Project manager salary

As explained earlier, the expenditure on the SaaS application license fee, developer salary, and project manager salary would remain the same, so these options are incorrect.

Reference:https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html

-----------------

75. Which of the following AWS services support VPC Endpoint Gateway for a private connection from a VPC? (Select two)
a.s3
d.Amazon SQS
b.Amazon SNS	
e.Amazon EC2
c.DynamoDB

# ANSWER: A,C

S3

DynamoDB

A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. Traffic between your VPC and the other service does not leave the Amazon network.

There are two types of VPC endpoints: interface endpoints and gateway endpoints.
An interface endpoint is an elastic network interface with a private IP address from the IP address range of your subnet that serves as an entry point for traffic destined to a supported service. Interface endpoints are powered by AWS PrivateLink, a technology that enables you to privately access services by using private IP addresses.

A gateway endpoint is a gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service. The following AWS services are supported:

Amazon S3

DynamoDB

Exam Alert:

You may see a question around this concept in the exam. Just remember that only S3 and DynamoDB support VPC Endpoint Gateway. All other services that support VPC Endpoints use a VPC Endpoint Interface.

Incorrect options:

Amazon EC2

Amazon SQS

Amazon SNS

As explained earlier, these services support VPC Endpoint Interfaces.


Reference: https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html

---------------------

76. Which of the following statements are CORRECT regarding the AWS VPC service?
(Select two)
a.A NAT Instance is managed by AWS	
d.A Security Group can have both allow and deny rules
b.A NAT Gateway is managed by AWS	
e.A Security Group can have allow rules only
c.A NACL can have allow rules only

# ANSWER: B,E

A Security Group can have allow rules only
A NAT Gateway is managed by AWS
A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. Security groups act at the instance level, not at the subnet level. You can specify allow rules, but not deny rules. You can specify separate rules for inbound and outbound traffic.
Security Group Overview:  via – https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html
A Network Access Control List (NACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets (i.e. it works at subnet level). A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic.
Network Access Control List (NACL) Overview:  via – https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html
You can use a network address translation (NAT) gateway or a NAT Instance to enable instances in a private subnet to connect to the internet or other AWS services, but prevent the internet from initiating a connection with those instances. NAT Gateway is managed by AWS but NAT Instance is managed by you.
Please see this comparison table for differences between NAT Gateway and NAT Instance:  via – https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-comparison.html
Incorrect options:
A Security Group can have both allow and deny rules
A NAT Instance is managed by AWS
A NACL can have allow rules only
These three options contradict the details provided earlier in the explanation, so these options are incorrect.
References:
https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html
https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html

------------------

80. The engineering team at an IT company wants to monitor the CPU utilization for its fleet of EC2 instances and send an email to the administrator if the utilization exceeds 80%. As a Cloud Practitioner, which AWS services would you recommend to build this solution? (Select two)
a.CloudWatch	
d.SQS
b.Lambda	
e.CloudTrail
c.SNS

# ANSWER: A,C

CloudWatch – Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. You can create an CloudWatch alarm that sends an email message using Amazon SNS when the alarm changes state from OK to ALARM. The alarm changes to the ALARM state when the average CPU use of an EC2 instance exceeds a specified threshold for consecutive specified periods.
SNS – Amazon Simple Notification Service (SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.
How SNS Works:  via – https://aws.amazon.com/sns/
Incorrect options:
CloudTrail – AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Think account-specific activity and audit; think CloudTrail. CloudTrail cannot be used to monitor CPU utilization for EC2 instances or send emails.
Lambda – AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. Lambda cannot be used to monitor CPU utilization for EC2 instances or send emails.
SQS – Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS offers two types of message queues – Standard queues vs FIFO queues. SQS cannot be used to monitor CPU utilization for EC2 instances or send emails.
References:
https://aws.amazon.com/cloudwatch/
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/US_AlarmAtThresholdEC2.html
