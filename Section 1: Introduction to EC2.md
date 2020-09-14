# Section 1: EC2

## What is EC2

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity.
Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic.

## Setup

These are some useful links:

- [Introduction to EC2](https://viblo.asia/p/tim-hieu-ve-amazon-ec2-maGK7jRe5j2)

## How to use

Steps to connect with EC2 instance:

- Download private key file `.pem`
- Allow execute for key file: `chmod 400 xxx.pem`
- Access to instance with this command: `ssh -i .ssh/xxx.pem ec2-user@XX.XX.XX.XX`

Some useful note:

- Default username in EC2 is `ec2-user`
