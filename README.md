# 🚀 CI/CD Pipeline for .NET Core Applications on AWS Elastic Beanstalk

## 📘 Introduction
This repository contains the `ci-cd-dotnet-aws-beanstalk` project, which is designed to test and demonstrate a deployment pipeline for a .NET Core application using AWS Elastic Beanstalk. The main objective is to automate the deployment process using GitHub Actions, specifically leveraging the `Beanstalk Deploy` GitHub action.

## 📦 Deployment Pipeline: Beanstalk Deploy

`Beanstalk Deploy` is a GitHub Action and command line script designed to simplify deployments to AWS Elastic Beanstalk. It automates several tasks including:

- Uploading the application zip file to an AWS S3 bucket.
- Creating a new application version in Elastic Beanstalk.
- Deploying the application version to a specified environment.
- Monitoring the deployment process and logging status messages.
- Exiting with a non-zero status code if the deployment fails.

This tool does not manage rollbacks if the deployment process encounters errors.

## 📚 Additional Resources
For more detailed information and advanced configuration options, visit the [Beanstalk Deploy GitHub repository](https://github.com/einaregilsson/beanstalk-deploy).

## 📞 Contact
If you have any questions or need further assistance, you can contact the project maintainer:

- **Name:** Matias Vallejos
- 🌐 [matiasvallejos.com](http://matiasvallejos.com)

Feel free to reach out if you have any inquiries or need any additional information about the project.
