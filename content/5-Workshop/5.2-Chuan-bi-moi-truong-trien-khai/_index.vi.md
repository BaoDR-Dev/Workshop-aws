---
title: "Chuẩn bị môi trường triển khai"
date: 2026-07-10
weight: 2
chapter: false
pre: " <b> 5.2. </b> "
---

Trước khi bắt đầu triển khai hệ thống lên AWS, cần chuẩn bị đầy đủ các thành phần sau:

- **[5.2.1 – Chuẩn bị source code Spring Boot](5.2.1-Chuan-bi-source-code-Spring-Boot/):** Clone repository RecruitPro, kiểm tra cấu hình `application.properties` và đảm bảo build thành công với Maven.
- **[5.2.2 – Chuẩn bị database MySQL](5.2.2-Chuan-bi-database-MySQL/):** Chuẩn bị file SQL schema và dữ liệu khởi tạo để import vào Amazon RDS sau khi tạo instance.
- **[5.2.3 – Chuẩn bị tài khoản AWS và region triển khai](5.2.3-Chuan-bi-tai-khoan-AWS-va-region-trien-khai/):** Đăng nhập AWS Console, chọn region **Asia Pacific (Singapore) – ap-southeast-1**, kiểm tra quyền IAM và đảm bảo tài khoản chưa vượt Free Tier limit.

{{% notice info %}}
Toàn bộ tài nguyên trong workshop này được triển khai tại region **ap-southeast-1 (Singapore)**. Đảm bảo chọn đúng region trước khi thực hiện bất kỳ bước nào.
{{% /notice %}}
