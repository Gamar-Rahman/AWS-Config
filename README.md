# AWS-Config
Check the Compliance status of Security group using AWS Config
---------------------------------------------------------------------------------------------------------------
# AWS Config – Complete Guide

## Introduction

AWS Config is a service provided by Amazon Web Services under the **Management & Governance** category.  
It is designed to help you **audit, assess, and evaluate** the configurations of AWS resources in your account.

AWS describes Config as:

> A service that enables you to assess, audit, and evaluate the configurations of your AWS resources.

AWS Config continuously monitors and records resource configurations, enabling compliance tracking, security analysis, and operational troubleshooting.

---

## What is AWS Config?

AWS Config keeps track of:
- **What resources exist**
- **How they are configured**
- **How their configurations change over time**

It acts as a configuration history and compliance monitoring service for your AWS environment.

## What AWS Config Does

AWS Config provides the following capabilities:

### 1. Configuration Recording
- Retrieves **current and historical configurations** of AWS resources.
- Stores configuration snapshots for auditing and review.

### 2. Configuration Evaluation
- Evaluates AWS resources against **desired configurations** using:
  - AWS managed rules
  - Custom rules (Lambda-based)

### 3. Change Notifications
- Sends notifications whenever a resource is:
  - Created
  - Modified
  - Deleted

### 4. Resource Relationship Tracking
- Displays relationships between AWS resources  
  (EC2 instances → Security Groups → VPCs)


## Why Use AWS Config?

- Security compliance
- Governance and auditing
- Troubleshooting configuration drift
- Change management
- Regulatory compliance (HIPAA, PCI-DSS, SOC.)
  
# How AWS Config Works

1. AWS Config discovers supported resources
2. Records configuration changes
3. Stores configuration history in Amazon S3
4. Evaluates resources using rules
5. Sends notifications via Amazon SNS


-------------------------------------------------------------------------------------------------------------
📁 Repository Structure

aws-config-guide/
│
├── README.md
├── docs/
│   ├── introduction.md
│   ├── how-aws-config-works.md
│   ├── aws-config-components.md
│   └── use-cases.md
│
├── examples/
│   ├── enable-aws-config.md
│   └── sample-rules.md
│
├── diagrams/
│   └── aws-config-architecture.jpg
----------------------------------------------------------------------------------------------------------------

📄 Gamar-Rahman
Cybersecurity Analyst | cloud security | AI - ML | I build hands-on labs, automate security workflows.



