# Task for Day6

### What is Elastic Container Service?
  - Amazon Elastic Container Services (Amazon ECS) is a fully managed container orchestration service that helps organizations easily deploy, manage, and scale containerized applications.
  - <a href="https://aws.amazon.com/ecs/features/"> Learn more about ECS </a>

### What is Elastic Container Registry?
  - Amazon Elastic Container Registry (ECR) is a fully managed Docker container registry service provided by Amazon Web Services (AWS). In simple terms, it's a place where you can store, manage, and deploy Docker container images, making it easier for you to run applications in the cloud using containers.
  - <a href="https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html"> Learn more about ECR </a>

### What is Route53?
  - Amazon Route 53 is a scalable and highly available Domain Name System (DNS) web service provided by Amazon Web Services (AWS). It is named after the TCP/IP port 53, which is used for DNS services. Route 53 is designed to provide reliable and cost-effective domain registration, DNS routing, and health checking of resources within your AWS infrastructure.
  - How Does DNS Route Traffic To Your Web Application? see the below diagram:
![image](https://github.com/LondheShubham153/aws-zero-to-hero/assets/121779953/aac36a26-e48e-4444-bff5-27a15568040a)

<details>
  <summary>Explaination of Above Diagram</summary><br>
  1) A user opens a web browser, enters www.example.com in the address bar, and presses Enter.<br><br>
  2) The request for www.example.com is routed to a DNS resolver, which is typically managed by the user's Internet service provider (ISP), such as a cable Internet provider, a DSL broadband provider, or a corporate network.<br><br>
  3) The DNS resolver for the ISP forwards the request for www.example.com to a DNS root name server.<br><br>
  4) The DNS resolver for the ISP forwards the request for www.example.com again, this time to one of the TLD name servers for .com domains. The name server for .com domains responds to the request with the names of the four Amazon Route 53 name servers that are associated with the example.com domain.<br><br>
  5) The DNS resolver for the ISP chooses an Amazon Route 53 name server and forwards the request for www.example.com to that name server.<br><br>
  6) The Amazon Route 53 name server looks in the example.com hosted zone for the www.example.com record, gets the associated value, such as the IP address for a web server, 192.0.2.44, and returns the IP address to the DNS resolver.<br><br>
  7) The DNS resolver for the ISP finally has the IP address that the user needs. The resolver returns that value to the web browser. The DNS resolver also caches (stores) the IP address for example.com for an amount of time that you specify so that it can respond more quickly the next time someone browses to example.com. For more information, see time to live (TTL).<br><br>
  8) The web browser sends a request for www.example.com to the IP address that it got from the DNS resolver. This is where your content is, for example, a web server running on an Amazon EC2 instance or an Amazon S3 bucket that's configured as a website endpoint.<br><br>
  9) The web server or other resource at 192.0.2.44 returns the web page for www.example.com to the web browser, and the web browser displays the page.<br>
</details>
   

## Tasks:
#### 1) Deploy two-tier application on Elastic Container Service (ECS) and configure Elastic Container Registry (ECR) to push docker images.
> `Note:` The Docker image must be fetched from ECR.

#### 2) Understand the concept of CloudFront and try to perform below sub-tasks:
    - What is caching in cloudfront?
    - Create an EC2 instance with apache webserver
    - Create a CloudFront distribution and attach to EC2 instance to access the apache webpage.

#### 3) Learn about AWS fully managed DNS Service (Route53) and write a detailed blog and post it on linkedin. 

#### Finding it difficult?
- let me know on linkein

- Happy Learning :)

## Reference:
 - <a href="https://www.linkedin.com/posts/madhup-pandey-0311821b3_awscloud-aws-cloud-activity-7133303181345718272-cToL?utm_source=share&utm_medium=member_desktop"> CloudFront </a> 
