# CLOUD-MONITORING-AND-ALERTS
COMPANY: CODETECH IT SOLUTIONS

NAME: SANJANA MARIA P.S

INTERN ID: CT04DH2447

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# DESCRIPTION

Amazon CloudWatch is a powerful monitoring and observability service that collects data from various AWS resources like EC2, Lambda, RDS, and more. It provides insights through metrics, logs, dashboards, and alarms.

Steps to Set Up Monitoring Using AWS CloudWatch: Launch the Cloud Resource: I deployed an EC2 instance that hosted my web application. This acted as the primary compute resource for my cloud app.

Access CloudWatch Console: From the AWS Management Console, I navigated to the CloudWatch service. CloudWatch automatically provides basic monitoring for EC2 instances (e.g., CPU utilization, network traffic).

Enable Detailed Monitoring: For enhanced visibility, I enabled detailed monitoring on my EC2 instance, which provided 1-minute frequency metrics instead of the default 5-minute interval.

Install the CloudWatch Agent: To collect additional data like memory usage, disk space, and custom application logs, I installed the CloudWatch Agent on the EC2 instance and configured it using a JSON configuration file.

Visualize Metrics: In the CloudWatch dashboard, I added widgets for CPUUtilization, DiskReadOps, DiskWriteOps, NetworkIn, and NetworkOut. These graphs allowed me to monitor application health at a glance.

Set Alarms for Auto-Notifications: I created alarms on key metrics such as:

CPUUtilization > 80% for 5 minutes

MemoryUsedPercent > 85% When thresholds were breached, Amazon SNS (Simple Notification Service) was triggered to send an email alert to my registered email address.

Custom Dashboards: I created a CloudWatch Dashboard to visualize all key metrics in one view. This included line graphs and numeric displays for performance tracking

# OUTPUT
<img width="1366" height="636" alt="Image" src="https://github.com/user-attachments/assets/ffe631ee-9ebe-4058-9faa-f12887800859" />
<img width="1366" height="636" alt="Image" src="https://github.com/user-attachments/assets/fd89f302-3dfa-49d2-85c1-b4c6a5ea8951" />
