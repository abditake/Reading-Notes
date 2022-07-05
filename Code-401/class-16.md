# [Class 16: AWS: Cloud Servers](/README.md)


## [AWS EC2](https://aws.amazon.com/ec2/)
## [EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)
## [Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

<hr>

## AWS EC2

- What is an EC2 Instance?
    - a virtual server that runs applications on AWS infrastructure.
- Name 2 use cases for EC2.
    - Train an deploy Machine learning projects
    - Run Cloud-native and enterprise applications.
- Provide 1 reason to use ECS instead of Heroku.
  - AWS can meet high/very high computational demands.


<hr>

## EC2 For Humans

- Where can we find EC2 on the AWS Console?
  - `https://aws.amazon.com/console/`
- Explain the general difference between T2 Micro and XL.
  - performance T2.micro just has 1 gb of alloted ssd memory and 1 cpu.
  - xl has 64 cpu capacity 488 gb of ssd space and a dedicated 8x1900 ssd storage for persisting data. this data doesn't get removed once the instance is shutdown.
- Explain a “Compute Cycle” to a non-technical friend.
  - reboot: data stays on where we first hosted
  - stop/start: move to a new host
  - hibernate: move to a new host 
  - terminate: completely shutdown
<hr>

## Elastic Beanstalk

- What is Elastic Beanstalk?
  - Service that deploys, manages, and scales web apps and services.
- Describe the relationship between EC2 and Elastic Beanstalk.
  - BeanStalk uses EC2 instances to deploy and scale web apps and services.
- Name some benefits of using Elastic Beanstalk.
  - auto-scaling
  - health-monitoring
  - load balancing
  - provisions
  - tweak any resources whenever you want.