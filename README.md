# aws-security-monitoring
AWS security monitoring implementation using VPC Flow Logs, CloudWatch, CloudTrail, Amazon Inspector, and Security Hub.


## EC2 Instance Configuration
![Architecture Diagram](screenshots/ec2-architecture.png)

This project demonstrates an AWS security monitoring architecture using native AWS services to monitor network traffic, audit account activity, and detect vulnerabilities.

Security monitoring stack:

Internet → Bastion Host → Private EC2 Instance  
                 ↓  
            VPC Flow Logs  
                 ↓  
         Amazon CloudWatch Logs  
                 ↓  
           AWS Security Hub  

Additional services used:

- AWS CloudTrail for API auditing
- Amazon Inspector for vulnerability scanning
- AWS Security Hub for centralized security findings





## Implementation Screenshots

### EC2 Architecture
![EC2 Architecture](screenshots/ec2-architecture.png)

### EBS Volume Mounted
![EBS Volume](screenshots/ebs-volume-mounted.png)

### VPC Flow Log Active
![VPC Flow Log Active](screenshots/vpc-flow-log-active.png)

### VPC Flow Log Creation
![VPC Flow Log Creation](screenshots/vpc-flow-log-creation.png)

### VPC Flow Log Entries
![VPC Flow Log Entries](screenshots/vpc-flow-log-entries.png)

### CloudWatch Log Group
![CloudWatch Logs](screenshots/cloudwatch-log-group.png)

### CloudTrail Logs
![CloudTrail Logs](screenshots/cloudtrail-logs.png)

### CloudTrail Event History
![CloudTrail Event History](screenshots/cloudtrail-event-history.png)

### Security Hub Dashboard
![Security Hub](screenshots/security-hub-dashboard.png)

### Security Hub Findings
![Security Hub Findings](screenshots/security-hub-findings.png)

### Spot Instance
![Spot Instance](screenshots/spot-instance.png)

































