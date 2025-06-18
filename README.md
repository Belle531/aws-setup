# AWS Setup Guide

This repository documents how to set up an AWS account on a $1.00 monthly budget and introduces DynamoDB with ideas for integrating it into a capstone web project.

---

## 🔐 Creating an AWS Account

1. Visit [aws.amazon.com](https://aws.amazon.com/) and sign up using your email and payment method.
2. Log in to the AWS Console and enable billing access (if using IAM users).
3. Navigate to **Billing Dashboard → Budgets → Create Budget**:
   - Select **Cost Budget**
   - Set monthly limit: `$1.00`
   - Enable **email or SNS alerts** to track usage

---

## 🧠 AWS DynamoDB Overview

- **Fully Managed NoSQL Database** – Zero server maintenance
- **Scales Automatically** – Handles read/write demand with low latency
- **Key-Value & Document Storage** – Flexible data modeling
- **Secure by Design** – Encryption at rest and in transit; role-based access
- **Integrated with AWS Ecosystem** – Streams, Lambda, IAM, and more

---

## ⚡️ Why Use AWS & DynamoDB?

| Feature         | AWS                                 | DynamoDB                              |
|----------------|--------------------------------------|----------------------------------------|
| **Scalability** | Global infrastructure + Auto Scaling | Read/Write Auto Scaling                |
| **Cost Control**| Free Tier + Budget Alarms           | Pay-per-request pricing                |
| **Performance** | Low-latency global delivery         | Millisecond response time              |
| **Security**    | IAM roles, encryption, audit logs   | Built-in encryption & fine-grained ACL |
| **Tooling**     | AWS CLI, SDKs, CloudFormation       | SDKs, Streams, Global Tables           |

---

## 💡 Capstone Project Ideas Using DynamoDB

Here are practical uses for DynamoDB in your website:

- **🔐 User Profiles** – Store names, preferences, and login activity
- **🏆 Leaderboards** – Display real-time scores or activity rankings
- **📝 Feedback & Comments** – Capture and display user-generated feedback
- **📊 Content Tracking** – Monitor the most viewed lessons or pages
- **📂 Resource Management** – List and track downloadable tools or files

---

## 📦 Next Steps

- Set up DynamoDB from the AWS Console
- Design your table schema based on project needs
- Use AWS SDK for JavaScript to connect your frontend/backend
- Monitor usage to stay within budget

---

> ⚠️ This setup is optimized for development and testing under the AWS Free Tier with a $1/month budget cap.

![alt text](<AWS  2025-06-16 195944.jpg>)

