# AWS Serverless API using Lambda and API Gateway

This project demonstrates a step-by-step implementation of a **Serverless HTTP API**
using **AWS Lambda** and **Amazon API Gateway**.
Each step includes clear explanations and screenshots for better understanding.

---

## Step 1: Login to AWS Console

- Logged into the **AWS Management Console** using an **IAM user** account.
- After successful login, the **AWS Console Home** page is displayed.
- The region is set to **US East (N. Virginia)**, which will be used for creating AWS resources in this project.
- From the Console Home, AWS services such as **EC2, S3, RDS, and Lambda** can be accessed using the search bar or service links.

![AWS Console Home](screenshots/01-login-aws-console.png)

---

## Step 2: Search for AWS Lambda Service

- Used the **search bar** at the top of the AWS Management Console.
- Typed **“Lambda”** to find the AWS Lambda service.
- AWS displays Lambda under the **Services** section with the description *“Run code without thinking about servers”*.
- This step is required to navigate to the Lambda service, where serverless functions will be created.

![Search for AWS Lambda](screenshots/02-search-for-lambda.png)

---

## Step 3: Open AWS Lambda Console

- After selecting **AWS Lambda** from the search results, the Lambda service console is opened.
- The Lambda console provides an overview of how AWS Lambda works and supported runtimes such as **Node.js, Python, Java**, etc.
- From this page, users can create and manage serverless functions.
- Click the **Create a function** button to start building a new Lambda function.

![AWS Lambda Console](screenshots/03-open-lambda-console.png)

---

## Step 4: Create a New Lambda Function

- Clicked on **Create a function** in the AWS Lambda console.
- Selected **Author from scratch** to create a custom Lambda function.
- Entered a meaningful **Function name** to identify the Lambda function.
- Chose **Node.js** as the runtime for implementing the serverless logic.
- Selected the default **x86_64 architecture**.
- Allowed AWS to create a default **execution role** with permissions to write logs to CloudWatch.

![Create Lambda Function](screenshots/04-create-lambda-function.png)

