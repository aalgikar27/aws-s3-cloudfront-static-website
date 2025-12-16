# Static Website Deployment using AWS S3 & CloudFront

## 📌 Project Overview
This project demonstrates how to deploy a static website using **Amazon S3** and enhance performance and security using **Amazon CloudFront** within AWS Free Tier limits.

## 🏗 Architecture
User → CloudFront → Amazon S3 (Static Website Hosting)

## 🛠 AWS Services Used
- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (CDN)
- AWS IAM (Bucket Policy)

## 🚀 Deployment Steps (High Level)
1. Created an S3 bucket and enabled static website hosting
2. Uploaded static website files (HTML/CSS)
3. Configured bucket policy for public read access
4. Created CloudFront distribution using S3 website endpoint
5. Enabled HTTPS and caching via CloudFront

## 🔒 Security & Cost Considerations
- Used AWS Free Tier eligible services
- No sensitive credentials stored in repository
- CloudFront distribution disabled after testing to avoid charges

## 📸 Screenshots
Screenshots available upon request.

## 👤 Author
Anurag Algikar
