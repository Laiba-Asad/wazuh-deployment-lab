# Wazuh SIEM Lab – Log Monitoring & SOC Fundamentals

This project demonstrates the setup and configuration of a **Wazuh SIEM environment** for centralized log monitoring and basic Security Operations Center (SOC) workflows.

---

## Overview

The objective of this lab was to gain hands-on experience with:

- SIEM deployment (Wazuh)
- Log collection and forwarding
- Monitoring security events
- Understanding SOC fundamentals

The lab simulates how security teams collect and analyze logs to detect suspicious activity.

---

## Lab Environment

- **Platform:** Wazuh SIEM  
- **Endpoint:** Windows Virtual Machine  
- **Log Source:** Windows Security Logs  

---

## Implementation Steps

### 1. Wazuh Installation
- Installed Wazuh manager and agent
- Verified dashboard accessibility
- Ensured all services were running correctly

### 2. Log Collection Configuration
- Installed Wazuh agent on Windows endpoint
- Configured agent to communicate with manager
- Enabled collection of:
  - Windows Security logs

### 3. Log Generation
Simulated real-world activity to validate logging:
- User login/logout events  
- Multiple failed login attempts  

### 4. Verification
- Confirmed logs were successfully ingested
- Observed events in Wazuh dashboard visualizations

---

## Sample Output

The SIEM dashboard successfully displayed:
- Authentication events  
- Failed login attempts  
- Real-time log ingestion  

---

## Key Learnings

- How SIEM systems collect and centralize logs  
- Importance of endpoint visibility  
- Basics of log-based threat detection  
- Role of SIEM in SOC environments  

---

## Future Improvements

- Create custom alert rules  
- Detect brute-force attacks  
- Monitor PowerShell activity  
- Perform incident analysis  

---

## 📎 Repository Structure
