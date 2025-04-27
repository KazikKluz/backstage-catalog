# Containerized WebApp on AWS Elastic Beanstalk

## Overview

The **WebApp** is a scalable, containerized website built with Node.js and React, deployed on AWS Elastic Beanstalk using Docker containers. It serves dynamic content for e-commerce platforms, supporting user authentication, product catalogs, and checkout workflows. Elastic Beanstalk simplifies deployment, scaling, and management, while Docker ensures consistent environments across development and production.

**Key Features**:

- Containerized with Docker for portability and consistency.
- Auto-scaling and load balancing via Elastic Beanstalk.
- Integration with AWS RDS for PostgreSQL database.
- Built-in monitoring with DataDog dashboards.
- CI/CD support with GitHub Actions or AWS CodePipeline.
- Secure HTTPS with AWS Certificate Manager.

**Version**: 1.4.2  
**License**: MIT  
**Repository**: [github.com/example/webapp-eb](https://github.com/example/webapp-eb)

---

## Installation

### Prerequisites

- AWS CLI >= 2.9.0
- Docker >= 20.10.0
- Node.js >= 18.0.0
- EB CLI >= 3.20.0
- AWS account with IAM permissions for Elastic Beanstalk, ECR, and RDS
