---
title: "Workshop"
date: 2026-07-10
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

## Workshop Outcomes

Learners deploy the Spring Boot RecruitBox application end-to-end on AWS following the CloudFront → ALB → EC2 → RDS model, storing CVs/artifacts on S3 and monitoring with CloudWatch/SNS.

**Web Application:** [RecruitBox](https://d32lxiso1iao8j.cloudfront.net/)<br>
**Source Code:** [View here](https://github.com/Tiennnn1107/RecruitPro-Springboot)<br>
**Web Feature Demo Video:** [View here](https://youtu.be/KYXhFO2_IjI?si=dSwqP4bfRtKRo2tI)

## How to Follow

Follow sequentially from 5.1 to 5.12. Each section includes objectives, prerequisites, steps on the AWS Console/CLI, expected results, testing, and clean-up.

## Completion Criteria

- Architecture and request flow are explained; each service has a reason for selection.
- EC2/RDS runs in a private subnet; users only access via CloudFront/ALB.
- Application logs are centralized; key metrics and alarms send email notifications via SNS.
- Functional, error, and basic security test scenarios are tested.
- Cost estimates, least privilege principles, and a resource deletion process are provided.

{{% notice warning %}}
NAT Gateway, ALB, RDS, EC2, and CloudFront may incur costs. Complete section 5.12 immediately after finishing the hands-on practice.
{{% /notice %}}
