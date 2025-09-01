# 🚨 Real-Time Threat Detection & Automated Response on AWS

This project implements an **AI-powered security pipeline** on AWS that detects suspicious activities in real-time using **Amazon GuardDuty**, and automatically triggers alerts and responses with **Lambda, EventBridge, and SNS**.


## 🚀 Features
- ✅ Real-time threat detection using **Amazon GuardDuty**
- ✅ Automated response with **AWS Lambda**
- ✅ Real-time alerts via **Amazon SNS (Email/SMS)**
- ✅ Event-driven integration with **Amazon EventBridge**
- ✅ Tested with simulated attacks (Trojan, Port Scan, Unauthorized Access)

## 🛠 Tech Stack
- **Amazon CloudTrail** → Collects API activity logs  
- **Amazon GuardDuty** → AI-based anomaly & threat detection  
- **Amazon EventBridge** → Triggers automated responses  
- **AWS Lambda (Python)** → Parses findings, generates alerts  
- **Amazon SNS** → Sends security alerts in real-time    

## 📂 Project Structure
.
- ├── GuardDuty-Automated-Response.py # Lambda function
- └── screenshots/ # proof 
- ├── README.md # Documentation

## 🧪 Testing
- Generate a sample GuardDuty finding:

aws guardduty create-sample-findings \
--detector-id YOUR_DETECTOR_ID \
--finding-types "Trojan:EC2/BlackholeTraffic"

## 🎯 Learning Outcomes
- Hands-on experience with AWS security services (GuardDuty, CloudTrail, EventBridge, SNS, Lambda).
- Designed and deployed an event-driven architecture for real-time threat detection.
- Built serverless automation with AWS Lambda and Python.
- Strengthened understanding of cloud security automation & AI-powered anomaly detection.
- Practiced incident response workflows with automated alerting and remediation.
- Gained experience integrating multiple AWS services into a cohesive solution.
- Enhanced troubleshooting by simulating attacks and validating responses.

## 📸 Project Screenshots

### 1. CloudTrail Logs
![CloudTrail](screenshots/Cloud%20trail.png)
### 2. GuardDuty Dashboard
![GuardDuty Dashboard](screenshots/GuardDuty%20Dashboard.png)
### 3. GuardDuty Findings
![GuardDuty Findings](screenshots/GuardDuty%20Findings.png)
### 4. EventBridge Rule
![EventBridge](screenshots/Amazon%20EventBridge.png)
### 5. Lambda Function
![Lambda](screenshots/Lambda%20Function.png)
### 6. SNS Topic
![SNS](screenshots/SNS%20Topic.png)
### 7. IAM Role for GuardDuty
![IAM Role](screenshots/IAM-Role%20For%20GuardDuty.png)
### 8. Lambda Automated Response
![Lambda Auto Response](screenshots/GuardDuty%20Automated%20Response.png)




