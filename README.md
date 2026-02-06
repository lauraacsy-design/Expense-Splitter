# Expense Splitter – Cloud Application

This project is a simple cloud-based expense splitter application. It was developed as part of a Cloud Computing coursework. The main goal is to show how a web application can be deployed and run fully in the cloud using AWS services.

## What the application does

The application allows users to:
- Create expense groups
- Add shared expenses
- Edit or delete existing expenses
- Calculate how much each person owes
- See who should pay and who should receive money

The system is designed for small groups, for example friends sharing dinner or travel costs.

## Technologies used

The project uses the following technologies:
- HTML, CSS and JavaScript for the frontend
- AWS Lambda for backend logic
- Amazon API Gateway for HTTP requests
- Amazon DynamoDB for data storage
- Amazon S3 for hosting static files
- Amazon CloudFront for HTTPS and content delivery

## Project structure

frontend/ - Web interface files
backend/ - AWS Lambda function
diagrams/ - Architecture diagram


## System architecture

The application follows a serverless cloud architecture. The frontend is hosted on Amazon S3 and delivered through CloudFront. User actions are sent to API Gateway, which triggers AWS Lambda functions. These functions store and read data from DynamoDB.

An architecture diagram is included in the diagrams folder.

## Deployment

The application is fully deployed in AWS and can be accessed online using a CloudFront URL. No local server is required once deployment is complete.

## Author

This project was created for academic purposes as part of a cloud computing module.
