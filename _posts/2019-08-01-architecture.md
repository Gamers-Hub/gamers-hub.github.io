---
layout: post
title: Deployment Logs - Devops
author: Admin
date: '2019-08-01 10:35:23 +0530'
category: personal
summary: Tech Stack or Architectural Changes 
thumbnail: hello.jpg
---

### Architectural or Tech Stack Logs :

##### v1. 01.08.2019

Our App is built on MERN Stack. We use Linode Server running on Ubuntu 16.04 LTS with 2GB RAM and Gitlab CI/CD for all our Code Management and Pipelines.

We use Letsencrypt for SSL Certificates , for all sub-domains/domain being at Godaddy

Currently we use apache2 as reverse proxy in our Linode VPS to help us run our Node Apps using PM2.

###### Plans:

- To shift to NGINX from Apache 
- Docker Containerization of Node App for faster builds
- Automated Testing using Jenkins.


