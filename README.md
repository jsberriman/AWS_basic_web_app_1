# AWS_basic_web_app_1
 * AWS walkthrough to build and deploy a basic web application and add interactivity with an API and a database
 * https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/?trk=gs_card

# Modules: 
 * This tutorial was divided into five short modules, with each module reliant on the preceding module.
 * Building this web application using the AWS Web Console accessible directly from your browser.

 1. Create Web App (5 minutes): Deploy static resources for your web application using the AWS Amplify Console.
  * Services Used: AWS Amplify
  * Create index.html file with example front end content; e.g. 'Hello world'; send to zip file
  * Deploy on AWS Amplify; test by clicking on Domain; yields live web app users can interact with
 2. Build Serverless Function (5 minutes): Build a serverless function using AWS Lambda.
  * Services Used: AWS Lambda
  * Create example lambda function (e.g. Hello from Lambda, Name), using boilerplate function code to use lambda_handler for extracting from and returning JSON objects
  * Configure test event (e.g. firstName lastName, with key:value pairs) to test lambda function, and test
 3. Link Serverless Function to Web App (5 minutes): Deploy your serverless function with API Gateway.
  * Services Used: AWS API Gateway
  * Create a new edge-optimized REST API,  
 4. Create Data Table (10 minutes): Persist data in an Amazon DynamoDB table.
 5. Add Interactivity to Web App (5 minutes): Modify your web app to invoke your API.

 # Contents:
 * index.html: example html file establishing front end/static website
 * index.zip: zipped index.html for hosting on AWS Amplify