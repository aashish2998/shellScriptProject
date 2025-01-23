# shellScriptProject
Develop a streamlined approach for storing Jenkins build logs by leveraging AWS S3, ensuring cost-effective and scalable long-term storage.

# Prerequisites 
- Set up EC2 instance with Amazon Linux/Ubuntu as base operating system
- Install Jenkins on EC2 instance using official Jenkins installation guide
- Configure AWS CLI on EC2 by creating IAM user with S3 and EC2 access permissions
- Install and configure shell scripting environment with necessary permissions

# Key Features
- Objective: Automate the storage of Jenkins build logs through a script.
- Daily Automation: Script to read and archive the current day's Jenkins build logs.
- AWS Integration: Seamless upload of logs to an S3 bucket using AWS CLI.
-  Cost Efficiency: Utilize AWS S3 over the ELK stack for reduced long-term storage costs.
