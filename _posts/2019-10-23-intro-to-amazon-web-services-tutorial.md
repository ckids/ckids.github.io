---
layout: post
title:  "Introduction to Amazon Web Services"
date:   2019-10-23 14:38:00 -0700
categories: [Cloud, AWS, EC2, S3, Elastic, Zixuan Zhang]
---

### Amazon Web Services (AWS)
###### Author: Zixuan Zhang
---------------------------------------------------
AWS is a great technology, and a buzzword that everyone is talking about. So, what is AWS and what are some applications of AWS?

### Scenario 1 EC2:  
John is the supervisor of USC XYZ Lab. He just got funded for his brilliant machine learning/big data proposal during a conference and is ready to do some deep learnings. As you know, deep learning projects are computationally expensive thus requires advanced hardware. However, XYZ lab hasn’t had a hardware upgrade for years, hence it is impossible for John to use the current hardware for such a large project. Traditionally, John would have to spend a good portion of his fund on new workstations that have larger RAM and advanced GPUs. That’s not the case anymore, John has a better option: cloud computing.
Amazon and other internet giants offer comprehensive cloud computing services. I’ll use Amazon’s AWS service as an example, but the idea generalizes to other brands as well. AWS’s Elastic Compute Cloud (EC2) service is a brilliant option for John because:

1. He can customize the hardware of the workstation (e.g. 60 cores and 500 GB RAM) in
minutes
2. The service is paid by seconds. In other words, if John is not using the cloud
computer, he doesn’t need to pay for it even though no one else has access to it. If John does not do deep learning often, he doesn’t need to spend thousands of dollars on hardware that is unlikely to be used in full extent in the future.
3. John can use easily upgrade/downgrade his computing instance (e.g. add more cores, RAM, and storage) according to his need with just a few mouse clicks.

* [For more information](https://aws.amazon.com/ec2/)

### Scenario 2 S3 Bucket:
Jane is among a group of CS students who are working on a Kaggle competition called Hemorrhage Image Classification sponsored by RSNA. The competition, unlike many other events, has huge amount of data (~400GB).  Store this amount of data on a personal laptop is unrealistic, not to mention future data processing and training tasks. The team needs a cloud storage that everyone has access to from their local computer (for experiment purpose) and from the powerful EC2 instance (actual training). Amazon offers a cloud storage service call Simple Storage Service (S3) is a good choice for them because:
1. Easy data access: data can be accessed in code as well as in command line. This is typically useful if they want to pull data for processing in real-time without downloading them locally.
2. Elastic storage: easily add new storage or shrink volume size. They only pay for what they need

* [For more information](https://aws.amazon.com/s3/features/?nc=sn&loc=2)

### Scenario 3 Elastic Beanstalk:
Li is a research assistant in USC ISI and is building a web application for his group. The web needs to be very high-performance as they are anticipating high volume traffic. One good way to host this web project is on AWS using Elastic Beanstalk. A typical web project needs a domain name (user friendly), reliable servers, and databases, which all takes some time to configure or register. Instead of doing all these things separately, Elastic Beanstalk handles everything in one stop. Li just need choose what type of network speed, decide the hardware configuration of the server and the size of the database, and Beanstalk will ration the all required resources for Li automatically. This is very convenient because Li can focus on software development without worrying the required resources.

* [For more information](https://aws.amazon.com/elasticbeanstalk/?nc2=type_a)

### Further Readings
* [Amazon Web Service Getting Started](https://aws.amazon.com/getting-started/)

* [10-minute Tutorials](https://aws.amazon.com/getting-started/tutorials/)

* [Create EC2 instance step by step](https://www.youtube.com/watch?v=PHOo3Ekb_Ys)

* [S3 Bucket for beginner](https://www.youtube.com/watch?v=XGcoeEyt2UM)
