#   General cloud interview questions
# What is cloud computing?

    Cloud computing can be defined as teh on-demand delivery of compute power, database, storage, applications, and other IT resources via the internet with pay-as-you-go pricing.

# What is teh difference between black-box testing and white-box testing?

    Black-box testing refers to a testing scenario where the internal structure, design, and implementation are unknown to the tester.  White-box testing refers to a testing scenererio where the internal structure, design, and implementation are known to the tester.

# What is teh difference between static analysis and dynamic analysis?

    static analysis is when you go through the code looking for errors.

    Dynamic analysis when the code is in an operational or a runtime state.  Memory usage is monitored, along with functional behavior, response time, and other performance benchmarks.

# Can you explain the purpose of a function?

    Reusability is the primary purpose of a function.

# How do you troubleshoot a technical problem?

    In order to troubleshoot a problem is first you must understand what the problem is.  Second, can you replicate the problem to see what is the cause of the problem.  Once the problem is understood and can be replicated, the solution to it will be within the replication.

# Academy Cloud Operations—Module 1, section 1
1. What are the three models of cloud computing? Can you provide me with examples of each model?
    1. What are the three models of cloud computing? Can you provide me with examples of each model?

The three models are infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS).

IaaS (or infrastructure as a service) – Typically provides access to networking features and computers (virtual or on dedicated hardware). An example that uses AWS could be Amazon Elastic Compute Cloud (Amazon EC2.

PaaS (or platforms as a service) – Reduces the need for companies to manage the underlying infrastructure (usually, hardware and operating systems). An example that uses AWS could be AWS Elastic Beanstalk.
SaaS (software as a service) – Provides your customer with a completed product that is run and managed by the service provider. An example could be AWS.

2. At our company, we mainly employ an [all-in-cloud, hybrid, or private cloud] cloud deployment model. Can you describe the benefits of using this cloud deployment model?

All-in-cloud – The benefit of all-in-cloud is that it’s a cloud-based application that is fully deployed in the cloud, and all parts of the application run in the cloud. An example of all-in-cloud is an application that was either created in the cloud or was migrated from an existing infrastructure.

# Or
Hybrid – Hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud. An example of a hybrid deployment model is when an organization extends its infrastructure into the cloud while connecting cloud resources to an internal system. An advantage of this would be a data center extension. A company could run on-premises networking, security, storage, and access control infrastructure along with AWS to create a data center extension, and run backups and disaster recovery to the cloud

# Or

Private cloud – With private cloud, you deploy resources on-premises. You then use virtualization and resource-management tools. It sometimes called on-premises deployment. An advantage of this model would be for use with mission-critical workloads, or highly regulated workloads.

# Academy Cloud Operations—Module 1, section 2 
3. What is a web service?
A web service is any piece of software that makes itself available over the internet or on private (intranet) networks. A web service uses a standardized format—such as Extensible Markup Language (XML) or JavaScript Object Notation (JSON)—for the request and the response of an application programming interface (API) interaction.

# Module 1: Section 3 
4. How should we ensure the availability of mission-critical system resources on AWS?

A way to ensure that mission-critical resources are available is by creating backups across multiple isolated locations or Availability Zones. Availability Zones comprise one or more discrete data centers that are designed for fault isolation.

5. What is the difference between Amazon CloudFront and Amazon Route 53?

Amazon CloudFront is a content delivery network (CDN) service. Amazon Route 53 is a Domain Name System (DNS) service. CDNs are used to distribute content to users to reduce latency. A DNS service is a globally distributed service that translates human-readable names like www.example.com into their numeric IP addresses.

6. What service provides resizable compute capacity in the cloud?

Amazon EC2 can provide resizable compute capacity in the cloud. EC2 instances are configurable virtual compute capacity. You can select from a variety of operating systems and resource configurations (such as memory, CPU, storage, etc.).

7. How do you launch an EC2 instance?

From the AWS Management Console, go to the Compute category, select Amazon EC2, and choose Launch Instance. Then, choose the instance type that you need, and configure it to meet the needs of your customer. Finally, launch the instance.

8. When should I use AWS Lambda?

AWS Lambda makes it easy to execute serverless code in response to events, such as changes to Amazon Simple Storage Service (Amazon S3) buckets, updates to an Amazon DynamoDB table, or custom events that are generated by your applications or devices.

9. What is automatic scaling? What is the purpose of automatic scaling?

Automatic scaling (or dynamic scaling) enables organizations to scale Amazon EC2 (or other service resource) capacity up or down automatically according to conditions that are defined for a particular workload. It’s used to help maintain application availability and ensures that the desired number of service resources are running. It also enables resources to scale in and scale out to match workload demand.

10. What happens to a customer’s data when an Amazon EC2 instance is terminated?

The data that is stored on the EC2 instance store will persist only as long as that instance is running.

 Is it possible to keep the data?

 The data can be stored on an Amazon Elastic Block Store (Amazon EBS) volume. The data will persist independently of the life of the instance. Another way to keep the data is to back up the data to Amazon S3.

 11. When you choose an Amazon Machine Image (AMI), what should you consider? 
 
 Here’s a chance for you to critically think about customer needs.

An example of considerations could include: 
- Core count 
- Memory size 
- Storage size and type 
- Network performance 
- CPU technologies

12. What is the best way to explain Amazon Virtual Private Cloud (Amazon VPC) to a potential customer?

Amazon VPC is your network environment in the cloud. It enables you to create a private network within the AWS Cloud that uses many of the same concepts and constructs as an on-premises network. Customers can define normal networking configuration items, such as IP address ranges, subnet creation, route table creation, network gateways, and security settings.

13. What are two ways to ensure security within a virtual private cloud (VPC)?

AWS provides two features that you can use to increase security in your VPC: security groups and network access control lists (network ACLs).

14. What is the difference between security groups and network ACLs?

Security groups control inbound and outbound traffic for your instances, and network ACLs control inbound and outbound traffic for your subnets.

15. How do you allow access to your Amazon VPC resources without sharing your security credentials?

You must create and attach an AWS Identity and Access Management (IAM) policy to the IAM user or to the group that the IAM user belongs to. The IAM user must be given permission to use the specific Amazon VPC resources and Amazon EC2 API actions that they need.

16. How do you monitor traffic to a VPC?

VPC Flow Logs is a feature that enables you to capture information about the IP traffic that goes to and from network interfaces in your VPC.

17. When you establish a VPC, how do you determine where customer network traffic is directed?

A route table contains a set of rules, called routes, that are used to determine where network traffic is directed. Each subnet in an Amazon VPC must be associated with a route table. The table controls the routing for the subnet.

18. What is VPC peering?

An Amazon VPC peering connection is a networking connection between two VPCs that enables instances in either VPC to communicate with each other as if they are in the same network.

# Academy Cloud Operations—Module 2, section 5

19. What is the purpose of load balancing?

20. What are the types of load balancers that AWS offers?

Elastic Load Balancing offers three types of load balancers: The Application Load Balancer, the Network Load Balancer, and the Classic Load Balancer.

First, an Application Load Balancer functions at the application level. It supports content-based routing and applications that run-in containers.

Next, the Network Load Balancer handles requests while maintaining high throughput at ultra-low latency.

Finally, the Classic Load Balancer provides basic load balancing across multiple Amazon EC2 instances. It operates at both the request level and the connection level.

21. How do you monitor the performance of your customer’s workload? You can monitor the performance of your customer’s workload by using Amazon CloudWatch.

Module 3 
22. IAM is used to manage users and groups. What else can IAM do? IAM enables you to:
Manage IAM users and their access. You can create users in IAM and assign individual security credentials to these users. Or
Manage IAM roles and their permissions. You can create roles in IAM and manage permissions to control which operations can be performed by the entity, or the AWS service that assumes the role.
Or
Manage federated users and their permissions. You can enable identity federation to allow existing identities (users, groups, and roles) from your corporate directory to access the AWS Cloud.
And




