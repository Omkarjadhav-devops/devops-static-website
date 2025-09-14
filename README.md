# devops-static-website

## Overview
Static Website hosted on AWS S3 using GitHub Actions CI/CD.

## Technologies Used
- GitHub
- GitHub Actions
- AWS S3
- (Optional: AWS CloudFront for CDN)

## Steps to Deploy
1. Create & enable S3 bucket for static hosting.
2. Make IAM user with AmazonS3FullAccess policy.
3. Add AWS credentials in GitHub Secrets.
4. Add workflow file at .github/workflows/deploy-to-s3.yml
5. Every push/commit on main triggers auto deployment to S3.

## Features
- Fast automated deployment (CI/CD).
- Easy updates with every code push.
- Static website visible at: [S3 Endpoint URL](http://your-bucket-name.s3-website.ap-south-1.amazonaws.com)

## Screenshots
- ![Workflow Success](IMAGE_URL)
- ![Live Website](IMAGE_URL)

## Contact
Any queries: jomkar1311@gmail.com / 7385193166
