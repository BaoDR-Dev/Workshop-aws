---
title: "Prepare the Deployment Environment"
date: 2026-07-10
weight: 2
chapter: false
pre: " <b> 5.2. </b> "
---

Before starting the deployment on AWS, make sure the following components are ready:

- **[5.2.1 – Prepare Spring Boot Source Code](5.2.1-Chuan-bi-source-code-Spring-Boot/):** Clone the RecruitPro repository, review the `application.properties` configuration, and confirm a successful build with Maven.
- **[5.2.2 – Prepare MySQL Database](5.2.2-Chuan-bi-database-MySQL/):** Prepare the SQL schema file and seed data to import into Amazon RDS after the instance is created.
- **[5.2.3 – Prepare AWS Account and Deployment Region](5.2.3-Chuan-bi-tai-khoan-AWS-va-region-trien-khai/):** Log in to the AWS Console, select region **Asia Pacific (Singapore) – ap-southeast-1**, verify IAM permissions, and ensure the account has not exceeded Free Tier limits.

{{% notice info %}}
All resources in this workshop are deployed in region **ap-southeast-1 (Singapore)**. Make sure the correct region is selected before performing any step.
{{% /notice %}}
