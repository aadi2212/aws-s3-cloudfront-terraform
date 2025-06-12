# Static Website Hosting using AWS S3 and CloudFront with Terraform

This project demonstrates how to host a static website on AWS using S3 and serve it globally via CloudFront, all managed through Terraform.

## Features

- S3 bucket with static website hosting enabled
- CloudFront distribution for global delivery
- Simple HTML landing page (index.html)
- Public access configuration via bucket policy
- Infrastructure managed with Terraform

## Prerequisites

- AWS CLI configured
- Terraform installed
- Basic HTML page (index.html)

## Usage

1. Clone the repo
2. Place your `index.html` in the `/website` folder
3. Run Terraform commands:
   - `terraform init`
   - `terraform apply`
4. Visit the CloudFront domain to view your website

## Author

Aadi – AWS Certified Solutions Architect Associate

