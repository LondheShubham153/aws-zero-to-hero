# 🌐 Day 5 – AWS VPC, Transit Gateway & CloudWatch

Welcome to **Day 5** of the **7 Days of AWS Challenge** 🚀  
Today, you’ll step into the role of a **Cloud Architect** and design secure, connected, and monitored AWS environments.  
You’ll learn about **VPCs, Peering, Transit Gateways**, and **CloudWatch monitoring**.

---

## 🧠 Concepts to Learn

### 🏗️ What is a VPC (Virtual Private Cloud)?
A **Virtual Private Cloud (VPC)** is a private, isolated section of the AWS Cloud where you can launch your resources securely.  
It gives you control over your network configurations — including subnets, routing, and gateways.

### 🔗 What is VPC Peering?
A **VPC Peering connection** is a **networking link between two VPCs** that allows traffic routing using **private IP addresses** (IPv4 or IPv6).  
This helps teams or departments communicate privately without going through the public internet.

### 🌍 What is AWS Transit Gateway?
**AWS Transit Gateway** acts as a **central hub** connecting multiple VPCs and on-premises networks.  
It simplifies complex peering relationships and scales easily, functioning like a **cloud router** that connects everything with a single link.

📘 [AWS Transit Gateway Documentation → Click Here](https://docs.aws.amazon.com/vpc/latest/userguide/extend-tgw.html)

---

## 🎯 Tasks for Day 5

### 🪜 Task 1: Learn & Share on LinkedIn
Learn about the following **core networking concepts**:
- Virtual Private Cloud (VPC)
- Subnets
- Internet Gateways
- Route Tables
- Peering Connections

Write a short LinkedIn post summarizing what you learned and how these pieces connect.  
Use hashtags **#7DaysOfAWS** and **#AWSwithTWS**, and tag [@TrainWithShubham](https://www.linkedin.com/in/shubhamlondhe1996/).

---

### 🪜 Task 2: Connect Departments Using Transit Gateway

**Scenario:**  
You’re the cloud architect for a company called **ByteConnect Inc.**  
Each department operates in a separate VPC, but now they need to **communicate securely** with each other.

**What to do:**
- Set up a **Transit Gateway** and attach multiple VPCs to it.  
- Configure route tables to enable seamless inter-VPC communication.  
- Test connectivity using EC2 instances in different VPCs.

📖 Reference → [AWS Transit Gateway Docs](https://docs.aws.amazon.com/vpc/latest/userguide/extend-tgw.html)

> 💡 This setup reflects how real-world enterprises connect multiple isolated workloads across departments.

---

### 🪜 Task 3: Implement CloudWatch for Monitoring

**Scenario:**  
You’re an AWS intern at **XYZ Company**, and your goal is to monitor your AWS resources using **CloudWatch**.

**Steps:**
1. Launch an **EC2 instance** and deploy an **Nginx web server**.  
2. Create a **CloudWatch log group** and connect it to your Nginx server to monitor access and error logs.  
3. Set up a **CloudWatch alarm** to get notified if the server goes down.

> 🧠 This task helps you understand how to track performance and logs for your AWS applications.

---

## 💬 Engagement Activity

✅ Share your **Day 5 learnings** on **LinkedIn** with  
> `#7DaysOfAWS` `#AWSwithTWS`

Mention:
> “Day 5 of my #7DaysOfAWS Challenge with @TrainWithShubham 🌐  
> Explored AWS VPCs, Transit Gateways & CloudWatch — feeling like a real cloud architect!”

You can also:
- Comment on or share two other learners’ posts.  
- Share a CloudWatch dashboard screenshot or VPC diagram.  
- Discuss your setup in our [Discord Community](https://discord.gg/7GjDgDHR49).

Let’s build visibility together 🌟

---

## 🧩 Finding It Difficult?

No worries — you can always reach out:  
- 💬 [LinkedIn](https://www.linkedin.com/in/shubhamlondhe1996/)  
- 💭 [Discord Community](https://discord.gg/7GjDgDHR49)  
- 🌐 [Official Website](https://trainwithshubham.com)

---

## 📚 References

- [AWS Transit Gateway Documentation](https://docs.aws.amazon.com/vpc/latest/userguide/extend-tgw.html)  
- [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)  
- [AWS CloudWatch Overview](https://docs.aws.amazon.com/cloudwatch/index.html)

---

## 🌟 Bonus Tip
> Networking is the backbone of the cloud — master it early.  
> Draw your architecture diagram for this setup and post it — it makes your learning visible and share-worthy!

Happy Learning ✨  
**– TrainWithShubham**
