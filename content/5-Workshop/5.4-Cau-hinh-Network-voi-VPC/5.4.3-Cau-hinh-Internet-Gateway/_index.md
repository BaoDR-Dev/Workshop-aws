---
title: "Configure the Internet Gateway"
date: 2026-07-10
weight: 3
chapter: false
pre: " <b> 5.4.3. </b> "
---

### 5.4.3. Configure the Internet Gateway

1. Open **VPC → Internet gateways → Create internet gateway**.
2. Enter `Recruit-igw` and create the gateway.
3. Select it, choose **Actions → Attach to a VPC**, and select `RecruitVPC`.

Confirm that the gateway state is `Attached` and its VPC ID points to `RecruitVPC`.

![Tạo Internet Gateway](</Workshop-aws/images/5-Workshop/5.4-Cau-hinh-Network-voi-VPC/5.4.3-Cau-hinh-Internet-Gateway/internet%20gateway.png>)
![Chọn thao tác attach](</Workshop-aws/images/5-Workshop/5.4-Cau-hinh-Network-voi-VPC/5.4.3-Cau-hinh-Internet-Gateway/igw%20attach%20vpc.png>)
![Attach vào RecruitVPC](</Workshop-aws/images/5-Workshop/5.4-Cau-hinh-Network-voi-VPC/5.4.3-Cau-hinh-Internet-Gateway/igw%20attach%20vpc%202.png>)
