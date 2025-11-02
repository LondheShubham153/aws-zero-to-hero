# 🐳 Day 6 – AWS ECS, ECR, Route 53 & CloudFront

Welcome to **Day 6** of the **7 Days of AWS Challenge** 🚀  
Today, you’ll explore **containerization and networking** in AWS — learning how to deploy scalable applications using **ECS, ECR, Route 53**, and **CloudFront**.

---

## 🧠 Concepts to Learn

### 🧩 Amazon ECS (Elastic Container Service)
Amazon **Elastic Container Service (ECS)** is a **fully managed container orchestration** service that helps you deploy, manage, and scale Docker containers with ease.  
It supports both EC2 and Fargate launch types, letting you choose between managing servers yourself or letting AWS handle the infrastructure.

📘 [Learn More About ECS](https://aws.amazon.com/ecs/features/)

---

### 📦 Amazon ECR (Elastic Container Registry)
**Amazon ECR** is a **fully managed Docker container registry** that allows you to store, manage, and deploy container images securely.  
You can easily push your local Docker images to ECR and use them in ECS for production-grade workloads.

📘 [Learn More About ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)

---

### 🌍 Amazon Route 53
**Amazon Route 53** is AWS’s scalable **Domain Name System (DNS)** web service that provides reliable domain registration, routing, and health checks.

#### How DNS Works
1. A user opens a browser and requests `www.example.com`.
2. The request goes to a **DNS resolver** managed by their Internet Service Provider (ISP).
3. The resolver queries the **root name servers**, then the **TLD servers** (like `.com`).
4. The request reaches **Amazon Route 53**, which finds the correct IP address for `example.com`.
5. The browser connects to your server (EC2, S3, or CloudFront) and loads the web page.

📘 [Route 53 Documentation](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)

---

### ⚡ Amazon CloudFront
**CloudFront** is a **Content Delivery Network (CDN)** that speeds up distribution of your web content (images, videos, APIs, etc.) using edge locations around the world.

**Caching** in CloudFront helps deliver frequently accessed content faster to users and reduces the load on your origin servers.

📘 [CloudFront Overview – LinkedIn Example](https://www.linkedin.com/posts/madhup-pandey-0311821b3_awscloud-aws-cloud-activity-7133303181345718272-cToL)

---

## 🎯 Tasks for Day 6

### 🪜 Task 1: Deploy a Two-Tier Application with ECS & ECR
- Deploy the **Two-Tier Flask App** using **Amazon ECS**.  
- Push your **Docker image** to **ECR**.  
- Configure ECS to pull the image from ECR for deployment.

> 💡 *Hint:* You can reuse the [Two-Tier Flask App Repository](https://github.com/LondheShubham153/two-tier-flask-app) from Day 4.

---

### 🪜 Task 2: Understand and Implement CloudFront
1. Learn about **caching in CloudFront** and how it improves latency.  
2. Create an **EC2 instance** with an **Apache webserver**.  
3. Create a **CloudFront distribution** and connect it to your EC2 instance to serve the webpage globally.

---

### 🪜 Task 3: Learn Route 53 and Write a Blog
- Explore how **Route 53** manages DNS and connects domain names to AWS resources.  
- Write a **detailed LinkedIn blog** explaining Route 53 with a diagram or real-world example.  
- Use hashtags **#7DaysOfAWS** and **#AWSwithTWS**, and tag [@TrainWithShubham](https://www.linkedin.com/in/shubhamlondhe1996/).

---

## 💬 Engagement Activity

✅ Share your **Day 6 learnings** on LinkedIn using  
> `#7DaysOfAWS`  `#AWSwithTWS`

Mention:
> “Day 6 of my #7DaysOfAWS Challenge with @TrainWithShubham 🐳  
> Deployed containers with ECS & ECR, explored Route 53 and CloudFront — learning how AWS connects the world!”

You can also:
- Comment on 2–3 other learners’ posts.  
- Share your ECS dashboard screenshot or CloudFront setup diagram.  
- Ask questions in our [Discord Community](https://discord.gg/7GjDgDHR49).

Keep learning, keep sharing 🌟

---

## 🧩 Finding It Difficult?

Don’t worry — ask questions or get help via:  
- 💬 [LinkedIn](https://www.linkedin.com/in/shubhamlondhe1996/)  
- 💭 [Discord Community](https://discord.gg/7GjDgDHR49)  
- 🌐 [Official Website](https://trainwithshubham.com)

---

## 📚 References
- [AWS ECS Documentation](https://aws.amazon.com/ecs/features/)  
- [AWS ECR Documentation](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)  
- [AWS Route 53 Documentation](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)  
- [AWS CloudFront Overview](https://aws.amazon.com/cloudfront/)  

---

## 🌟 Bonus Tip
> Containers make apps portable. DNS makes them reachable. CDNs make them fast.  
> Today you learned how AWS combines all three to power the internet 🌍  

Happy Learning ✨  
**– TrainWithShubham**
