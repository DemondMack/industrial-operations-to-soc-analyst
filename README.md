# Industrial Operations to SOC Analyst Mindset

![Workflow Diagram](images/workflow-diagram.png)

## Project Overview

This project demonstrates how my current role as a Tank Farm Technician in an oil processing plant directly translates to the responsibilities and mindset of a SOC Analyst Level 1.

Although my professional experience is not in cybersecurity, my daily responsibilities require continuous monitoring, anomaly detection, structured investigation, real-time decision-making, escalation, and detailed documentation.

The purpose of this project is to show how my operational experience has prepared me for SOC analyst work by mapping my current responsibilities to equivalent security operations workflows.

## Industrial Operations vs SOC Analyst Mapping

### Monitoring

- **Industrial:** Continuously monitor tank levels, temperature gauges, vacuum levels, flow rates, and system behavior in real time  
- **SOC Equivalent:** Monitor SIEM dashboards, endpoint activity, and network traffic for anomalies  

---

### Detection

- **Industrial:** Identify abnormal conditions such as rapid temperature spikes, foaming, flow stoppage, or contamination indicators  
- **SOC Equivalent:** Detect alerts, suspicious activity, or deviations from normal system behavior  

---

### Investigation

- **Industrial:**  
  - Trace valve configurations  
  - Check system dependencies (pump, vacuum, heat)  
  - Pull samples and validate with lab software  
- **SOC Equivalent:**  
  - Analyze logs and alerts  
  - Correlate activity across systems  
  - Validate findings using security tools  

---

### Response

- **Industrial:**  
  - Adjust valves, vacuum, or heat  
  - Control chemical processes  
  - Prevent overflow, combustion, or system failure  
- **SOC Equivalent:**  
  - Contain threats  
  - Block malicious activity  
  - Apply remediation actions  

---

### Validation

- **Industrial:**  
  - Re-test samples  
  - Visually confirm oil quality  
  - Ensure contamination and chemicals are removed  
- **SOC Equivalent:**  
  - Confirm threat is removed  
  - Verify system integrity  
  - Ensure no residual impact  

---

### Escalation

- **Industrial:** Escalate unfamiliar issues, dangerous conditions, or system failures to the tank farm manager or maintenance  
- **SOC Equivalent:** Escalate complex incidents to Tier 2 analysts or incident response teams  

---

### Documentation

- **Industrial:** Log tank levels, transfers, chemical usage, timing, and all process steps  
- **SOC Equivalent:** Document alerts, investigation steps, findings, and resolution in ticketing systems

 ## Real-World Scenario Comparisons

### Scenario 1: Hidden Contamination vs Hidden Threat

**Industrial Situation:**
A batch of oil appears visually clean, but testing reveals contamination (PCB levels or moisture still present).

**My Actions:**
- Pulled and analyzed samples using lab software  
- Identified contamination not visible to the eye  
- Determined correct processing path (drying, chemical treatment)  
- Re-tested after each stage to confirm safe levels  

**SOC Equivalent:**
A system appears normal, but an alert indicates suspicious activity.

**SOC Actions:**
- Analyze alert in SIEM  
- Investigate logs and system behavior  
- Identify root cause  
- Remediate and validate the system is clean  

---

### Scenario 2: High-Risk Chemical Reaction vs High-Impact Threat

**Industrial Situation:**
During water washing, improper water flow can cause sodium to react rapidly, leading to explosion risk.

**My Actions:**
- Controlled water flow rate precisely  
- Monitored gauges and system behavior continuously  
- Prevented rapid reaction conditions  
- Maintained safe operating thresholds  

**SOC Equivalent:**
Improper handling of a security incident can escalate impact across systems.

**SOC Actions:**
- Carefully control response actions  
- Avoid overcorrection that disrupts operations  
- Balance containment with system stability  

---

### Scenario 3: System Imbalance vs Active Threat Behavior

**Industrial Situation:**
High vacuum combined with high moisture causes foaming and overflow risk.

**My Actions:**
- Detected abnormal system behavior early  
- Adjusted vacuum levels in real time  
- Prevented overflow and equipment failure  

**SOC Equivalent:**
A spike in activity indicates possible attack or misconfiguration.

**SOC Actions:**
- Detect abnormal behavior patterns  
- Adjust monitoring or response strategy  
- Prevent escalation or system disruption

  ## Conclusion

This project demonstrates that while my professional background is in industrial operations, my daily responsibilities already reflect the core mindset and workflow of a SOC Analyst.

I continuously monitor live systems, detect anomalies, perform structured investigations, make real-time decisions under pressure, and validate outcomes before completion. I also document all actions and escalate when necessary—core responsibilities in any security operations environment.

Through this experience, combined with my hands-on cybersecurity training (SIEM, ELK stack, alert triage, and threat analysis), I have developed the ability to think analytically, respond methodically, and operate with discipline in high-stakes environments.

I am confident in my ability to transition into a SOC Analyst Level 1 role and contribute effectively from day one.    
