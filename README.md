# AWS


## Five Pillars of the AWS Well-Architected Framework:

1. Operational Excellence 
2. Security
3. Reliability
4. Performance Efficiency 
5. Cost Optimization


### Performance Efficiency:
- The ability to use available computing resources to meet the systems requirement and maintain their efficiency as demand changes and technology evolves

5 Design Principles:


•	Democratize advanced technologies: Instead of bringing inhouse infrastructure and training talents to learn how to use them, delegate them to cloud vendors. The tech they use will be a service and more time will be spent on product development.
o	Use the OPEX model to leverage the available high performing resources on the cloud. It will allow us to delegate the operational management and focus on the actual doing


•	Go global in minutes: Deploy to multiple AWS Regions around the world to achieve lower latency and better experience for customer for minimal costs
o	Using the capability to deploy anywhere of AWS’ regions allows us to seamlessly scale globally, allowing us to be more efficient, have better customer experience, and make more money


•	Use Serverless Architecture: remove the need for running and maintaining physical servers for traditional compute activities. Removes operational burden of managing physical servers, which can lower transactional costs as they’re managed on cloud scale
o	Take advantage of the serverless services offered, which can be faster, cheaper, and easier to use than having to build from bottom.


•	Experiment more often: Access to number of virtual and automatable resources on the cloud, we can quickly carry out comparative testing using different types of instance, storage, or configurations
o	The excess and cheap number of resources available for stimulations are great for testing the possibilities and scenarios of potential environments


•	Consider mechanical sympathy: Understand how cloud services are consumed and always use the technology approach that aligns best with your workload.
o	Know how cloud works and their limits to what we can do with them

4 Best Practice Ares for Performance Efficiency in the cloud:

Selection
Review
Monitoring
Tradeoffs

Selection: The optimal solution for a particular workload varies, and solutions often combine multiple approaches. AWS provides many resources that are available in different types and configurations, which makes it important to choose the workload that best works for you


o	Use a data driven approach to select the patterns and implementations for your architecture and achieve a cost-effective solution
o	Your architecture will likely combine a number of different approaches 
o	Four main resource types to consider: compute, storage, database, and network
•	Compute: selecting compute resources that meet your requirements and provice great efficiency of cost and effort will enable you to accomplish more with the same number of resources
o	Instances:
o	Containers
o	Functions
•	Storage: hold information used by your workload
o	Object: S3 Bucket, to store files
o	Block Storage: EBS, network blocks used for storage
o	File Storage: shared file system across multiple systems
•	Database: cloud offers multiple types of database for your project’s needs. AWS does the maintenance and monitoring for us.
	workload database can significantly impact the performance and is often chosen by organization defaults
•	Network: workloads can be heavily dependent on the network (High Performance Computing)
o	MUST determine the workload requirements for bandwidth, latency, jitter, and throughput
	Must consider location when deploying your network
	


















