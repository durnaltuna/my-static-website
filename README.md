# My Static Website

This repository contains the source code for a simple static website hosted on a robust, scalable, and fully automated cloud infrastructure.

## Project Overview

This project was built to demonstrate a complete CI/CD (Continuous Integration/Continuous Delivery) pipeline for deploying a static website using a modern DevOps toolchain.

### Key Features:

- **Static Hosting:** The website is hosted in an **AWS S3 bucket**, providing high availability and durability.
- **Global CDN:** **AWS CloudFront** is used as a Content Delivery Network (CDN) to cache the website content at edge locations worldwide, ensuring low latency and fast page load times for users.
- **Custom Domain & HTTPS:** The domain `tunadurnalcloud.com` is managed through **AWS Route 53**, with traffic routed to the CloudFront distribution. The site is secured with **HTTPS**, using a free SSL certificate from **AWS Certificate Manager (ACM)**.
- **Automated Deployment:** The entire deployment process is automated using **GitHub Actions**. Any changes pushed to the `main` branch of this repository automatically trigger a workflow that syncs the files to the S3 bucket and invalidates the CloudFront cache.

## Technologies Used

- **Cloud Infrastructure:**
  - AWS S3
  - AWS CloudFront
  - AWS Route 53
  - AWS Certificate Manager (ACM)
- **CI/CD & Version Control:**
  - Git
  - GitHub Actions

## How to View the Project

1.  Clone this repository to your local machine.
2.  Open the `index.html` file in your browser.
3.  To see the live, deployed version, visit the live demo link above.
