# Building Continuously Available and Highly Performant Critical Systems

Aman Sardana &mdash; _Discover Financial Services, Senior Principal Application Architect_

- [LinkedIn](https://www.linkedin.com/in/amansardana22/)
- [Website](https://asardana.com/)

Bhargav Krishna Nachegari &mdash; _Discover, Principal Application Engineer_

- [LinkedIn](https://www.linkedin.com/in/bhargav-nachegari-422a1233/)

## Bio &mdash; Aman

I am a technology professional working in the financial services and payments domain. I’m a hands-on technology leader, enabling business capabilities by implementing cutting-edge, modernized technology solutions. I am skilled in designing, developing, and implementing innovative financial technology solutions that drive business results and establish best-in-class operations.

I did my Masters in Information Technology from Northwestern University which is a unique program that straddles the business and technical side of information technology focusing on data mining, information security, enterprise architecture, statistics, innovation, marketing and finance to name a few.

## Bio &mdash; Bhargav

As a Full Stack Engineer with over nine years of experience, I have honed my skills in designing solutions, architecting high-availability payment platforms, and leading teams to build resilient systems and APIs. My foundation in data structures, algorithms, and core programming principles forms the backbone of my technical expertise, enabling me to adapt and thrive in various programming languages and frameworks

I am excited on sharing my insights and experiences in building continuously available critical systems. I have served in key advisory roles for senior leadership on Enterprise System Management, contributed to the design and architecture of high-availability, resilient, and distributed systems, and overseen projects to ensure the timely delivery of key objectives. My strong technical background, exceptional analytical ability, effective communication skills, and team-oriented mindset equip me to make a valuable contribution to the discourse on critical system availability.

## Abstract

Have you ever wondered what it takes to build a highly resilient distributed caching platform for critical real-time payment systems? Join us as we share our journey of building a highly available and fault-tolerant caching solution while leveraging automation to achieve a faster MTTR.

Payment systems that support real-time transaction processing are expected to be available and highly responsive 24/7/365. These systems must be fault-tolerant and highly resilient to any failures that might happen during payment transaction processing.
Building a low-latency payment system that spans multiple geographic locations requires a distributed caching solution for low latency and high-throughput data access. While building a real-time transaction processing system at Discover - one that is continuously available and can process thousands of transactions per second with a sub-second response time - we decided to introduce distributed caching technology into our architecture to minimize the latency and to replicate the data across multiple data centers. This presented numerous challenges:
• How to run Active-Active cache clusters in multiple deployment regions with high-availability
• How to auto-heal cache cluster failures due to network partitioning or disaster
• How to automatically failover client applications in response to failures
• How to automatically recover failed clusters to reduce MTTR
• How to ensure data consistency after the cluster is recovered
• How to implement a real-time monitoring and alerting solution for client and cluster connectivity

In this talk, we will take you through our journey of how we built a distributed caching solution to solve the challenges we faced.
• Configuration-driven and thread-safe smart client solution that can intelligently detect failures
• Ability for the client application to failover if the error rate is above a certain threshold
• Automation to recover failed cluster and failback client connections after the cluster is recovered
• Workflow automation for data consistency after the cluster is recovered
• Real-time streaming of client connectivity metrics
• Observability solution to simplify operational support

- **Level**: Intermediate
- **Tags**: DevOps, Patterns & Practices, Back-End, Other
