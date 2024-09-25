**Static Website Deployment on AWS**

This repository contains the source code and configuration details for deploying a static website using Amazon S3 and CloudFront for global content distribution, security, and performance.

🚀 **Project Overview**

The goal of this project was to build and deploy a static web application leveraging AWS services to provide a scalable, secure, and high-performance website.

Key AWS Services Used:

Amazon S3: For storing and serving static content (HTML, CSS,  images).
AWS CloudFront: Content Delivery Network (CDN) to ensure low-latency access to the site globally.
IAM (Identity and Access Management): Secure access and control over resources.
Amazon Route 53: DNS routing for directing traffic to the application.
SSL/TLS Encryption: Implemented for secure communication over HTTP.
AWS CloudWatch: Monitoring the performance and health of the website.

🛠️ **Features**

High Availability: Deployed on S3 with replication across multiple availability zones.
Scalable Content Delivery: Powered by CloudFront’s CDN to deliver content globally with reduced latency.
Secure: HTTPS enforced with SSL certificates and IAM for access control.
Monitoring: Enabled CloudWatch for real-time performance tracking and alerts.

📁 **Project Structure**


├── index.html         
├── error.html         
└── README.md          

📚 **Resources**
AWS S3 Documentation
AWS CloudFront Documentation
SSL/TLS Setup on AWS

🤝 **Contributing**
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.
