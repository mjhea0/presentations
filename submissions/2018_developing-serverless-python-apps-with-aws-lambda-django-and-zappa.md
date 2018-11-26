# Developing Serverless Python Apps with AWS Lambda, Django, and Zappa

## Submitted by

Michael Herman

## Description

Zappa is a powerful open source tool that allows you to quickly deploy a Django project on AWS Lambda and AWS API Gateway.

In this tutorial, you'll learn how to migrate an existing Django project to run on AWS Lambda via Zappa. We'll also look at how to work with other AWS services for managing static assets, sending transactional emails, handling data persistence, and processing batch jobs.

## Audience

This is an intermediate-level tutorial geared toward those that have experience with Django and AWS in general.

## Objectives

By the end of this tutorial, you will be able to...

1. Explain what serverless architecture is and why it may be a good option for you
2. Discuss the pros and cons of using Zappa for serverless apps over other serverless options like AWS Chalice
3. Migrate an existing Django project over to AWS Lambda and AWS API Gateway using Zappa
4. Utilize Amazon Relational Database Service (RDS) for data persistence
5. Configure an Amazon S3 bucket to load and serve up static files
6. Send transactional emails with Amazon Simple Email Service (SES)
7. Run long-running batch processes in the background with Amazon Simple Queue Service (SQS)

## Outline

Introduction (20 minutes - (100% lecture))

1. About Me
2. Objectives
3. Architecture
4. Serverless 101

AWS Setup and Zappa Deployment (1 hour (100% hands-on))

1. Project Setup
2. AWS Setup
3. Zappa Config
4. Local test
5. Deployment

Additional AWS Services (1.5 hours (100% hands-on))

1. RDS for data persistence
2. S3 for static assets
3. SES for transactional emails
4. SQS for batch processing

What's next? (10 minutes)

1. Next Steps
2. Questions

## Additional notes

A few things...

1. This tutorial comes from a modified version of the course at http://testdriven.io/
2. You can see my past speaking history at http://mherman.org/talks (I spoke at PyTennessee, PyCon, and DockerCon in 2018)
3. I run the NodeJS Meetup in the Denver + Boulder area - https://www.meetup.com/Node-js-Denver-Boulder/
4. I am a former lead web development instructor for Galvanize, where I taught full-stack JavaScript
