# 🔒 Day 2 – AWS WAF (Web Application Firewall)

Welcome to **Day 2** of the **7 Days of AWS Challenge** 🚀  
Today, you’ll learn how AWS helps you **secure your web applications** from attacks using **AWS WAF (Web Application Firewall).**

---

## 🧠 What Is AWS WAF?

**AWS WAF** is a managed service that protects your web apps from common exploits such as  
**SQL Injection**, **Cross-Site Scripting (XSS)**, and **malicious IP requests**.  
It monitors incoming HTTP(S) traffic and allows you to define rules to **block, allow, or count** requests based on patterns you choose.

**Example:**  
If you host a website on AWS EC2 or through CloudFront, you can use AWS WAF to block traffic from a specific country, IP range, or suspicious query patterns.

📖 [Official AWS Docs → Getting Started with WAF](https://docs.aws.amazon.com/waf/latest/developerguide/getting-started.html)

---

## 🎯 Tasks for Day 2

1. **Learn & Share**
   - Understand how AWS WAF works and how it protects your apps.  
   - Write a short LinkedIn post summarizing what you learned.  
   - Use hashtags **#7DaysOfAWS** and **#AWSwithTWS**, and tag [@TrainWithShubham](https://www.linkedin.com/in/shubhamlondhe1996/).

2. **Hands-On Project — Implement AWS WAF for Web App Protection**

   **Scenario:**  
   You need to secure a web application hosted on AWS against common vulnerabilities.

   **Steps:**
   - **Set Up a Web Application:**  
     Deploy a sample web app on an **EC2 instance** in your AWS account.
   - **Configure AWS WAF:**  
     Create a **Web ACL** and define rules to block malicious requests (e.g., SQL injection patterns, blocked IPs).
   - **Attach WAF:**  
     Associate the Web ACL with your **CloudFront distribution**, **ALB**, or directly with **API Gateway**.
   - **Test WAF:**  
     Send test requests that trigger your rules and confirm WAF is blocking them.

3. **Document & Engage**
   - Share screenshots or a short demo video of your WAF setup.  
   - Write a LinkedIn post or short blog:  
     *“How I Secured My Web App on AWS Using WAF — Day 2 of #7DaysOfAWS”*

---

## 💬 Engagement Activity

✅ Post your **Day 2** learnings on **LinkedIn** using  
> `#7DaysOfAWS` `#AWSwithTWS`

Mention:
> “Today I secured a web application on AWS using WAF — my Day 2 challenge in #7DaysOfAWS with @TrainWithShubham 🔒🚀”

You can also:
- Like or comment on 2 other participants’ posts.  
- Ask a question in our [Discord Community](https://discord.gg/7GjDgDHR49).  
- Share your blog link on the server to inspire others.

The more you engage, the more you grow 🌟

---

## 🧩 Finding It Challenging?

Don’t worry — reach out for help on:  
- 💬 [LinkedIn](https://www.linkedin.com/in/shubhamlondhe1996/)  
- 💭 [Discord Community](https://discord.gg/7GjDgDHR49)  
- 💬 [Official Website](https://trainwithshubham.com)

---

## 📚 References

- [Getting Started with AWS WAF](https://docs.aws.amazon.com/waf/latest/developerguide/getting-started.html)  
- [How AWS WAF Works](https://docs.aws.amazon.com/waf/latest/developerguide/how-aws-waf-works.html)

---

## 🌟 Bonus Tip
> Security is not a one-time setup — it’s a habit.  
> Keep testing and updating your WAF rules as your application grows.  
> Share what you secured today and encourage others to protect their apps too!  

Happy Learning ✨  
**– TrainWithShubham**
