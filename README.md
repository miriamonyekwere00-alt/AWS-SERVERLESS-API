# AWS Serverless REST API

## Overview
A fully functional serverless REST API built on AWS with 
zero server management.

## Architecture
User → API Gateway → Lambda → DynamoDB
## What I Built
- REST API endpoint using API Gateway
- Lambda function written in Python to process requests
- DynamoDB table to store user data
- IAM Role with least privilege permissions
- Tested live API with Postman

## How It Works
1. User sends POST request to API Gateway endpoint
2. API Gateway triggers Lambda function
3. Lambda generates unique UserID and saves to DynamoDB
4. Returns success response with UserID

## Tech Stack
- AWS API Gateway (REST API)
- AWS Lambda (Python 3.12)
- Amazon DynamoDB
- AWS IAM
- Postman (API testing)

## Key Concepts Demonstrated
- Serverless architecture — zero EC2 needed
- Event driven computing
- IAM least privilege — Lambda only has DynamoDB access
- REST API design (POST method)
- NoSQL database usage

## Live Test Evidence
- API returned 200 OK status
- Multiple users saved successfully
- Each user assigned unique UUID automatically

## Author
Built by Miriam | Fribourg, Switzerland | April 2026
