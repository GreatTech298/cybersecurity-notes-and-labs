# Project 1: CBT Exam System Threat Modeling

## Objective
To identify potential security threats in an online Computer-Based Testing (CBT) platform and propose mitigations.

## Background
As an IT Systems Engineer and ICT Instructor, I have experience supporting large-scale exam registration and testing platforms. This project applies cybersecurity principles to those systems.

## Assets to Protect
- Student data (PII)  
- Exam content (questions, answers)  
- Authentication system (login credentials)  
- Test environment integrity  

## Threat Scenarios

### 1. Unauthorized Access
- Attackers try to gain admin or student accounts  
- Risk: Data leaks, exam tampering  
- Mitigation:
  - Strong password policies  
  - Multi-factor authentication  
  - Rate limiting login attempts  

### 2. Data Exposure
- Exam questions accidentally accessible online  
- Risk: Compromised test integrity  
- Mitigation:
  - Encrypt sensitive files  
  - Secure storage permissions  
  - Monitor public-facing servers  

### 3. Session Hijacking
- Attackers steal session cookies to impersonate students  
- Risk: Answer manipulation, exam cheating  
- Mitigation:
  - Use HTTPS only  
  - Set secure cookie flags  
  - Implement session timeout  

### 4. Denial of Service (DoS)
- High traffic overwhelms the exam server  
- Risk: Exam disruption  
- Mitigation:
  - Load balancers  
  - Traffic monitoring and alerts  
  - Rate limiting  

## Tools and Methods
- OWASP Top 10 checklist  
- Log review and analysis  
- Threat modeling frameworks (STRIDE / DREAD)  
- AWS CloudWatch (if hosted in cloud)  

## Deliverables
- Threat model document (this file)  
- Suggested mitigation plan  
- Lessons learned  

## Next Steps
- Map each threat to specific logs and alerts  
- Implement monitoring alerts for suspicious activity  
- Extend threat model to IAM misconfigurations and cloud deployment
