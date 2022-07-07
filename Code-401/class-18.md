
# [Class 16: AWS: Cloud Servers](/README.md)


## [AWS API Gateway Overview](https://www.serverless.com/guides/amazon-api-gateway)
## [AWS API Gateway](https://aws.amazon.com/api-gateway/)
## [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)
## [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
## [Dynamoose](https://dynamoosejs.com/getting_started/Introduction/)

<hr>








# AWS API Gateway Overview

- What is Amazon API Gateway?
  - a service that allows you to define HTTP endpoints of a rest API.
- Why is Amazon API Gateway an important part of the Serverless ecosystem?
  - it's the piece that ties together serverless functions and API definitions; being able to trigger a serverless function directly in a response to an HTTP request.
- How does API Gateway integrate with other AWS services?
  - AWS Lamda is an example which lets you run functions to generate HTTP API responses; invoking lambda function 


# AWS API Gateway

- What are the some benefits of using Amazon API Gateway?
    - efficient api development
    - cost savings at scale
- What two API types might you choose from?
  - RESTful API's and WEBSOCKET API's


# AWS DynamoDB Guide

- What is DynamoDB?
  - a database that is hosted by AWS, specifically a noSql database
- Under what circumstances would you recommend DynamoDB over MongoDB?
  - if i'm worried about the scalability of my  database i will lean more towards dynamoDB since their upscale is much easier. 
  - if i'm just working on a small project and want a more flexible query from a database then i will go with mongoDB


# AWS DynamoDB

- Explain to a non-technical friend how DynamoDB works.
  - DynamoDB is a place where data is stored. AWS provides a good service that allows me to upscale efficiently as my company grows.


# Dynamoose

- What is Dynamoose?
  - modelling tool
- What are some key features of Dynamoose?
  - type safety
  - ability to transform data before saving or retrieving data
  - Easy to use syntax