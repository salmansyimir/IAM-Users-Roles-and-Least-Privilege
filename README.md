# Project 4: AWS IAM - Role-Based Access Control

## Project Overview
This project demonstrates how to manage access to AWS resources using Identity and Access Management (IAM). The goal is to implement least-privilege access by assigning different permissions to users based on their responsibilities.

## Project Objectives
- Create and manage IAM users and groups.
- Configure IAM policies to control access to AWS resources.
- Apply the principle of least privilege.
- Test allowed and denied actions using different user accounts.
- Understand the difference between IAM users, groups, roles, and policies.

## AWS Services & Technologies
- AWS Identity and Access Management (IAM)
- IAM Users and Groups
- IAM Policies
- Amazon S3
- AWS Management Console

## Project Scenario
A company has employees with different responsibilities. As a cloud administrator, I must ensure that each employee can access only the AWS resources required for their job.

Example access requirements:
- salman1: Have administration access and read only access.
- Finance (salman1,salman2): Have read only access.
- HR (salman3,salman4: Have all EC2 access.

## Implementation Steps
1. Created IAM users and groups for different job responsibilities.
2. Configured policies based on each user's required permissions.
3. Assigned policies to the appropriate groups.
4. Tested access using separate user sessions.
5. Verified that unauthorized actions were denied.
6. Reviewed permissions to ensure least-privilege access.

## Key Learnings
- Understanding IAM users, groups, roles, and policies.
- Applying least-privilege access control.
- Understanding AWS identity-based policies.
- Testing permissions and troubleshooting access-denied errors.
- Improving AWS account security through access management.

## Security Best Practices
- Avoided using the AWS root account for routine tasks.
- Followed the principle of least privilege.
- Never shared passwords, access keys, or other credentials.
- Avoided granting unnecessary administrative permissions.
- Used temporary credentials where appropriate.

## Project Status
Complete

## Disclaimer
This project is for educational purposes and demonstrates fundamental AWS identity and access management concepts.
