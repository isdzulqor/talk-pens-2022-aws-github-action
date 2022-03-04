# Talk PENS 2022 - Automated Deployment to AWS with Github Action

This repo contains of my talk materials. It includes Slides, and Demo Materials. You can fork this repo and try the demo by yourself.

## Cloudformation Template
- [Demo EC2](cloudformation/demo-ec2.yml)
  
  Deployment Demo by provisioning Server Instance with EC2 from Cloudformation

## Github Action
- [Release](.github/workflows/release.yml)
  
  Github Action Demo by triggering from TAG Push Event to trigger deployment with Cloudformation 

## Prerequisites
- AWS Account
  - Make sure you have sign up for creating an AWS Account
  - `ap-southeast-1` or Singapore region is enabled
- Add Repository Secrets for
  - `AWS_ACCESS_KEY_ID`

    Credential key for your AWS_ACCESS_KEY_ID
  - `AWS_SECRET_ACCESS_KEY`
    
    Credential key for your AWS_SECRET_ACCESS_KEY
  - `VPCID`

    What VPC ID this template is deployed in
    