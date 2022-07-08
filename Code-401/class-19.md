
# [Class 19: AWS: Cloud Servers](/README.md)


## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

<hr>


# AWS SQS vs SNS

- What is the difference betweeen SQS and SNS?
  - Amazon SNS is a fully managed push notification service that lest you send messages
to large numbers of people; whereas, SQS is a distributed queuing system messages are not
pushed to receivers. SQS also doesn't push messages to multiple receivers like SNS does.
- What are some use cases for both SNS and SQS?
    - SNS
      - you would like to able to publish or consume batches of messages
      - allow same message to be processed multiple ways
      - multiple recipients 
    - SQS
      - simple queue with not requirements 
      - only one subscriber needed
      - allowing parallel asynchronous processing decoupling two applications 


# AWS SNS and SQS

- Describe how to use SQS and SNS in a “fanout” pattern.
  - 
  
- Explain how “push notifications” work, using SNS.

# SQS and SNS Basics

- How might a large scale, distributed application make use of a Queue system like SQS?


