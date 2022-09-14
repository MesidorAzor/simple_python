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