# My Portfolio Website Hosted on AWS EC2

## Project Overview
This is a simple **static portfolio website** hosted on **AWS EC2** and connected to a **custom domain** using **Route 53**. The project demonstrates deploying a website end-to-end on the cloud.

## Tech Stack / Tools Used
- AWS EC2
- AWS Route 53
- Apache HTTP Server (httpd)
- HTML & CSS
- Elastic IP (for static IP address)

## Features
- Custom HTML and CSS design
- Hosted on AWS EC2 instance
- Custom domain linked via Route 53
- Accessible via public URL
- Scalable and cloud-ready setup

## Architecture / Workflow
1. EC2 instance created and Apache installed.
2. HTML and CSS files (`index.html` and `style.css`) deployed in `/var/www/html`.
3. Elastic IP assigned to EC2 instance to ensure persistent access.
4. Route 53 Hosted Zone created and DNS records updated to point custom domain to EC2.

## Setup / Installation Instructions
1. Launch an EC2 instance (Amazon Linux / Ubuntu).  
2. Install Apache HTTP Server:  
   ```bash
   sudo yum install httpd -y   # For Amazon Linux
   sudo systemctl start httpd
   sudo systemctl enable httpd ```
   Linkedin Link: 
