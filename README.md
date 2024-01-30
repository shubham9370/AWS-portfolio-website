# Portfolio Website with AWS

This repository contains resources and instructions to create and host a portfolio website using AWS (Amazon Web Services).

## Overview

In this project, we will leverage various AWS services to build and deploy a professional portfolio website. The website will showcase your projects, skills, and contact information.

## Technologies Used

- **AWS S3 (Simple Storage Service)**: Used to host the static files of the website.
- **AWS CloudFront**: Content Delivery Network (CDN) service to distribute the website content globally with low latency.
- **AWS Route 53**: Domain Name System (DNS) service to manage domain registration and routing.
- **AWS Certificate Manager**: To provision and manage SSL/TLS certificates for HTTPS encryption.
- **HTML, CSS, JavaScript**: Used for creating the website structure, styling, and interactivity.

## Setup Instructions

Follow these steps to set up your portfolio website on AWS:

1. **Create an S3 Bucket**: Create an S3 bucket to store your website files. Enable static website hosting and configure permissions.

2. **Upload Website Files**: Upload your HTML, CSS, JavaScript, and asset files to the S3 bucket.

3. **Configure CloudFront**: Create a CloudFront distribution with the S3 bucket as the origin. Configure caching behavior and distribution settings.

4. **Obtain a Domain**: Register a domain name through Route 53 or use an existing one.

5. **Set Up SSL Certificate**: Use AWS Certificate Manager to request an SSL certificate for your domain.

6. **Configure DNS**: Set up DNS records in Route 53 to point your domain to the CloudFront distribution.

7. **Test and Validate**: Test your website by accessing it via the domain name. Ensure that HTTPS is working correctly.

## Resources

- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)
- [AWS CloudFront Documentation](https://docs.aws.amazon.com/cloudfront/index.html)
- [AWS Route 53 Documentation](https://docs.aws.amazon.com/route53/index.html)
- [AWS Certificate Manager Documentation](https://docs.aws.amazon.com/acm/index.html)

## Contributors

- [Shubham Muge]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
