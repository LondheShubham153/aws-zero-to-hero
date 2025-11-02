# 🗄️ Day 4 – Databases, Lambda & Automation

Welcome to **Day 4** of the **7 Days of AWS Challenge** 🚀  
Today, you’ll move beyond basic compute and storage into **databases**, **serverless**, and **automation**.  
You’ll learn how to migrate, scale, and optimize applications the AWS way!

---

## 🧠 Concepts to Learn

### 💾 Amazon RDS
Amazon Relational Database Service (RDS) lets you easily set up, operate, and scale a relational database in the cloud.  
You can choose engines such as **MySQL, PostgreSQL, MariaDB, Oracle, or SQL Server**, and AWS handles backups, patching, and monitoring for you.

### ⚡ DynamoDB
A fully managed **NoSQL** database service that provides **millisecond performance** at any scale.  
Perfect for applications that need high availability and flexible schema.

📘 [Getting Started with DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html)

### 🌀 AWS Lambda
Lambda lets you **run code without provisioning servers.**  
You just upload your function, and AWS runs it automatically in response to triggers such as S3 events or CloudWatch schedules.

📘 [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/?icmpid=docs_homepage_featuredsvcs)

---

## 🎯 Tasks for Day 4

### 🪜 Task 1: Learn & Share
- Read about **AWS RDS**, **DynamoDB**, and **AWS Lambda**.  
- Write a LinkedIn post in your own words with a short example for each.  
- Use hashtags **#7DaysOfAWS** and **#AWSwithTWS**, and tag [@TrainWithShubham](https://www.linkedin.com/in/shubhamlondhe1996/).

---

### 🪜 Task 2: Database Migration to RDS
**Scenario:**  
You’re part of a team migrating an e-commerce platform’s self-managed MySQL database to Amazon RDS to improve scalability and manageability.

**What to do:**  
- Set up and configure a **MySQL RDS instance** with optimal performance.  
- Establish a secure connection between the **RDS** instance and your **EC2** application environment.  
- Test the migration by connecting and performing CRUD operations.

---

### 🪜 Task 3: Deploy a Scalable Web Application
Build a **two-tier Flask application** with:
- A **MySQL database** managed by Amazon RDS.  
- A **Flask-based web app** deployed on EC2 inside an **Auto Scaling Group** behind an **Elastic Load Balancer**.  

Use this repo to get started:  
👉 [Two-Tier Flask App on AWS](https://github.com/LondheShubham153/two-tier-flask-app)

> 💡 This exercise demonstrates how real-world web apps scale seamlessly on AWS.

---

### 🪜 Task 4: Automate EC2 Start/Stop Using Lambda
**Scenario:**  
You’re managing a budget-friendly project and want to save costs by automatically starting/stopping EC2 instances during non-business hours.

**What to do:**  
- Create an **AWS Lambda function** that starts or stops EC2 instances based on instance tags.  
- Use **Python Boto3** and **EventBridge** (CloudWatch Events) to schedule the function.  

📖 Reference → [Start/Stop Instances with Lambda + EventBridge](https://repost.aws/knowledge-center/start-stop-lambda-eventbridge)

---

## 💬 Engagement Activity

✅ Post your **Day 4** learnings on **LinkedIn** using  
> `#7DaysOfAWS`  `#AWSwithTWS`

Mention:
> “Day 4 of my 7 Days of AWS Challenge with @TrainWithShubham 🚀  
> Today I worked with RDS, DynamoDB, Lambda & automation — making AWS do the heavy lifting!”

You can also:
- Comment on or share 2 other learners’ posts.  
- Ask a question in our [Discord Community](https://discord.gg/7GjDgDHR49).  
- Share your Lambda automation snippet!

The more you share, the stronger your AWS visibility becomes 🌟

---

## 🧩 Finding It Difficult?

Reach out for help on:  
- 💬 [LinkedIn](https://www.linkedin.com/in/shubhamlondhe1996/)  
- 💭 [Discord Community](https://discord.gg/7GjDgDHR49)  
- 🌐 [Official Website](https://trainwithshubham.com)

---

## 📚 References
- [AWS RDS & DynamoDB Docs](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html)  
- [AWS Lambda Docs](https://docs.aws.amazon.com/lambda/?icmpid=docs_homepage_featuredsvcs)  
- [Python Boto3 Docs](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)

---

## 🌟 Bonus Tip
> Automate everything you can — databases, apps, and even servers.  
> The more you automate, the more time you save for innovation!

Happy Learning ✨  
**– TrainWithShubham**
