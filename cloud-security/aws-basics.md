# AWS Basics for Cloud Security

## Why Cloud Security Matters
Many organizations run their systems in the cloud. Securing cloud resources is critical to prevent data breaches, misconfigurations, and unauthorized access.

AWS is one of the most widely used cloud platforms.

## Core AWS Concepts

### EC2 (Elastic Compute Cloud)
Virtual servers in the cloud used to run applications.

### S3 (Simple Storage Service)
Object storage for files and backups.
Security risks:
- Publicly accessible buckets
- Data exposure

### IAM (Identity and Access Management)
Controls who can access AWS resources and what they can do.

Best practices:
- Use least privilege
- Avoid using root account
- Enable MFA

### Security Groups
Virtual firewalls that control inbound and outbound traffic.

## Cloud Security Risks
- Misconfigured storage
- Weak access controls
- Exposed services
- Lack of monitoring

## SOC Perspective
SOC analysts may monitor:
- Cloud logs (CloudTrail)
- Unauthorized login attempts
- Suspicious API activity

## Next Topics
- CloudTrail
- GuardDuty
- IAM policies
