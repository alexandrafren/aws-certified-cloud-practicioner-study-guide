# Introduction to the Cloud

**Section Goal**: Define what the cloud is and the basic global infrastructure

### Introduction to the AWS Cloud

Before cloud computing, we had to build servers and estimate what our maximum usage for applications might be. If we didn't plan enough, our customers would suffer, it we planned too much, we pay for servers we don't need. AWS allows us to access servers, databases, storage, and higher-level application components in seconds, and allows us to scale up and down our usage of these items as we go.

**“Cloud Computing”**: the on-demand delivery of IT resources and applications via the internet. 

Being able to provision resources quickly with AWS allows us to **reduce risk, scale with use, ensure reliable coverage (in case of a natural disaster or system failure), and secure data.**

1. **Reduction of risk** refers to reduction of security risks and cost risks, both of which are possibility due to AWS's agility. Agility means we can **quickly** adjust our resource use up and down. Cloud services help reduce cost risks because we can pull funds from services as soon as they are not being profitable, protecting risk on investment. We can also quickly respond to an increased need for resources, ensuring we don't lose out on customer revenue. 

Security risks are reduced because we can test often, patch quickly, and respond to incidents fast as part of new security models.

The key with risk reduction is that AWS is **agile** because it allows you to make changes to your environment quickly. Agility allows for increased speed, ease of experimentation, and innovation. 

2. **Scalability** is the ability to resize your resources as necessary, without impacting *performance*. If you know you’ll have more web traffic around the holidays because you’re a retailer, you can scale up your resources here, and then scale back down after the holiday season. AWS is designed for high availability and dependability. With AWS you can spin up new servers in minutes, and shut them down when you don’t need them or switch them to another purpose.


> #### What's the difference between elasticity and scalability?
>Elasticity is the power to scale computing resources up or down easily, q.>quickly deploy new applications, scale up as your workload grows, shut >down when you don’t need them, autonomically. The differences between >scalability and elasticity is that the scalability focuses on making sure >your resources are availble so there is no impact on performance. >Elasticity is the the abilitiy to provision and de-provision autonomically >so that available resources match demand as close as possible. 

3. **Reliability** is the abilitiy of a system to recover from infrastructure or system failues. This is broken in to two components: Fault Tolerance and High Availability. 

Fault Tolerance means a system can remain operational even if some components are failing. 

AWS ensures fault tolerance by havihng data centers that are hosted all over the world in AWS regions. Each region is a seperate geographic area that has multiple isolated locations known as Availability Zones, which consist of one or more discrete data centers, customers can place resources in multiple locations, which protects you from failure. If one fails, you can access in another. 

High availability ensures that systems are always functioning and accessible, and downtime is minimized.

AWS helps with this because you can acquire computing resources to meet demand so you don’t have failures, such as auto scaling and elastic load balancing which can scale up or down based on demand *automatically* for you.

You can also deploy to multi regions around the world, making data highly available. AWS facilities are spread out all over the world, so you can spread out your data to where your customers are, allowing them to access your services quicker.

4. **Security** refers to the protection around your data and who can access it, both electronically and physcally. With AWS you retain control & ownership over your data including where it is stored, how to handle encryptions and who holds those keys, and who can access your data through roles, IAMs and Security Groups. 

Physically, data centers have electronic surveillance, multi factor access control systems, 24/7 staffed by guards, and access is strictly regulated.


