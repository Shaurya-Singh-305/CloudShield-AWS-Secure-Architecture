# CloudShield — AWS Cloud Security Architecture

A security-focused, three-tier AWS architecture demonstrating network segmentation, identity and access management, infrastructure security, monitoring, and secure cloud operations.

## Project Overview

**CloudShield** is a hands-on AWS infrastructure project focused on designing and implementing a secure, manageable, and resilient cloud environment.

The project demonstrates how AWS services can work together to separate application tiers, control access to resources, distribute incoming traffic, monitor infrastructure, and support secure operations.

The primary focus is **cloud infrastructure architecture and security**, rather than application development.

## Architecture

![CloudShield AWS Infrastructure Architecture](FINAL-INFRA.jpg)

The architecture incorporates the following components:

- **Networking:** Amazon VPC, public and private subnets, Internet Gateway, and NAT Gateway.
- **Traffic Management:** Application Load Balancer and Auto Scaling Group across multiple Availability Zones.
- **Compute:** EC2 instances for the web and backend tiers.
- **Database:** Amazon RDS with private network placement.
- **Storage:** Amazon S3 with security-focused access controls.
- **Identity and Access Management:** IAM roles and policies following least-privilege principles.
- **Monitoring and Auditing:** Amazon CloudWatch and AWS CloudTrail.
- **Security Operations:** AWS Systems Manager, patch management, EventBridge, and alerting integrations.

## Security Objectives

- Separate public-facing resources from private backend infrastructure.
- Restrict communication between tiers using security groups.
- Use IAM roles to manage access to AWS resources.
- Keep database infrastructure private.
- Apply security controls to S3 resources.
- Monitor infrastructure health and security-relevant activity.
- Configure alerts for selected infrastructure events and metrics.
- Support operational management through AWS Systems Manager.

## AWS Services Used

Amazon VPC · Amazon EC2 · IAM · Application Load Balancer · Auto Scaling · Amazon RDS · Amazon S3 · Amazon CloudWatch · AWS CloudTrail · AWS Systems Manager · Amazon SNS · Amazon EventBridge

## Documentation

The complete project documentation is divided into phases and problem-solving sections for easier navigation.

| Document | Description |
|---|---|
| [Phase 1](phase-1-documentation.pdf) | Phase 1 documentation |
| [Phase 2](phase-2-documentation.pdf) | Phase 2 documentation |
| [Phase 3](phase-3-documentation.pdf) | Phase 3 documentation |
| [Phase 4](phase-4-documentation.pdf) | Phase 4 documentation |
| [Phase 5](phase-5-documentation.pdf) | Phase 5 documentation |
| [Phase 6](phase-6-documentation.pdf) | Phase 6 documentation |
| [Phase 7](phase-7-documentation.pdf) | Phase 7 documentation |
| [Problem 1](problem-1-documentation.pdf) | Problem-solving documentation |
| [Problem 2](problem-2-documentation.pdf) | Problem-solving documentation |
| [Policies and Outcomes](policy-used-explination-and-outcome-documentation.pdf) | Policies used, explanations, and outcomes |

Open any document above to explore the corresponding section in detail.

## Project Demonstration

The project demonstration video is available via the following link--

https://bit.ly/CloudShield-Full-Walkthrough

## Key Takeaway

CloudShield demonstrates my practical understanding of AWS infrastructure design, cloud security fundamentals, access control, network isolation, monitoring, and secure cloud operations.

For detailed documentation, architecture decisions, and implementation details, please refer to this repository.



