# <center>IAM 

| Question | Answer | 
| --- | --- |
| What is a proper definition of an IAM Role |  |
| Which of the following is an IAM Security Tool? | |
| Which answer is INCORRECT regarding IAM Users ? | IAM User access AWS services using root account cred |
| What are IAM Policies? | |
| Which principle should you apply regarding IAM Permissions | |
| What should you do to increase your root account security? | |
| IAM User Groups can contain IAM Users and other User Groups | False -- User groups cant be nested |
| An IAM policy consists of one or more properties  | *Effect *Action *Resource *principal *version |
| An IAM policy consists of one or more statements. A statement in an IAM Policy consists of the following, EXCEPT: | version |

# <center>IAM 

| Question | Answer | 
| --- | --- |
| Which EC2 Purchasing Option can provide you the biggest discount, but it is not suitable for critical jobs or databases? | |
| What should you use to control traffic in and out of EC2 instances? | |
| How long can you reserve an EC2 Reserved Instance? | |
| You would like to deploy a High-Performance Computing (HPC) application on EC2 instances. Which EC2 instance type should you choose?| |
| Which EC2 Purchasing Option should you use for an application you plan to run on a server continuously for 1 year? | |
| You are preparing to launch an application that will be hosted on a set of EC2 instances. This application needs some software installation and some OS packages need to be updated during the first launch. What is the best way to achieve this when you launch the EC2 instances | |
| Which EC2 Instance Type should you choose for a critical application that uses an in-memory database| |
| You have an e-commerce application with an OLTP database hosted on-premises. This application has popularity which results in its database has thousands of requests per second. You want to migrate the database to an EC2 instance. Which EC2 Instance Type should you choose to handle this high-frequency OLTP database| |
| | |
| You're planning to migrate on-premises applications to AWS. Your company has strict compliance requirements that require your applications to run on dedicated servers. You also need to use your own server-bound software license to reduce costs. Which EC2 Purchasing Option is suitable for you | |
| You would like to deploy a database technology on an EC2 instance and the vendor license bills you based on the physical cores and underlying network socket visibility. Which EC2 Purchasing Option allows you to get visibility into them | |

# <center>EC2

| Question | Answer | 
| --- | --- |
| You have launched an EC2 instance that will host a NodeJS application. After installing all the required software and configured your application, you noted down the EC2 instance public IPv4 so you can access it. Then, you stopped and then started your EC2 instance to complete the application configuration. After restart, you can't access the EC2 instance, and you found that the EC2 instance public IPv4 has been changed. What should you do to assign a fixed public IPv4 to your EC2 instance | allocate elastic IP and assign it to your instance |
| Spot Fleet is a set of Spot Instances and optionally | ondemand instances |
| You have an application performing big data analysis hosted on a fleet of EC2 instances. You want to ensure your EC2 instances have the highest networking performance while communicating with each other. Which EC2 Placement Group should you choose | Cluster placement |
| You have a critical application hosted on a fleet of EC2 instances in which you want to achieve maximum availability when there's an AZ failure. Which EC2 Placement Group should you choose | |
| Elastic Network Interface (ENI) can be attached to EC2 instances in another AZ. | False |
| The following are true regarding EC2 Hibernate, EXCEPT | To enable EC2 Hibernate, the EC2 Instance Root Volume type must be an EBS volume and must be encrypted to ensure the protection of sensitive content. |