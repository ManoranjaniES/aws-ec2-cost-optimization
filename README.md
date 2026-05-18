AWS EC2 Automated Cost Optimization System
Project Overview
This project automates AWS EC2 cost optimization using AWS Lambda, CloudWatch, SNS, and Cost Explorer API.
The system monitors EC2 CPU utilization and:
Sends alerts for high CPU usage
Detects idle EC2 instances
Automatically stops unused instances
Tracks estimated AWS cost
Reduces unnecessary cloud expenses
AWS Services Used
Amazon EC2
AWS Lambda
Amazon CloudWatch
Amazon SNS
AWS Cost Explorer API
IAM
Features
High CPU Alert (>70%)
Idle CPU Detection (<5%)
Automatic EC2 Shutdown
Email Notifications
Cost Monitoring
Serverless Automation
Workflow
CloudWatch monitors EC2 CPU metrics
SNS triggers Lambda functions
Lambda checks instance utilization
Idle instances are automatically stopped
Cost Explorer API retrieves estimated costs
implemented real-time estimated cost calculation logic inside Lambda function to quickly analyze instance running cost
Email notifications are sent to users
Project Outcome
Reduced unnecessary EC2 runtime costs
Improved cloud resource efficiency
Automated infrastructure monitoring
Serverless cost optimization solution

Author

Manoranjani ES
