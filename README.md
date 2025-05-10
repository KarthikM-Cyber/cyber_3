# Threat Hunting Project: Ransomware Detection in Retail Network

## Overview

This repository showcases my involvement in a **hypothesis-driven threat hunting** project as part of the **SOC Essentials: Introduction to Threat Hunting** course offered by Splunk Training and Certification. The project aimed at detecting **ransomware** activity targeting a retail network environment using the **PEAK Threat Hunting Framework**. 

In this project, I contributed to **research**, **data analysis preparation**, **scope definition**, and **documentation** in collaboration with a team of cybersecurity professionals. The project focused on identifying potential **Windows Defender evasion** tactics using the **T1059.003 Windows Command Shell** technique from **MITRE ATT&CK**.

---

## My Role

As a team member in this project, my contributions included:

- **Research & Hypothesis Refinement:**  
  - Investigated relevant **MITRE ATT&CK techniques**, specifically **T1059.003 Windows Command Shell**, commonly used by threat actors in ransomware attacks.
  - Helped define and refine the hypothesis:  
    > "Threat actors are attempting to disable Windows Defender to evade detection."

- **Data Validation & Analysis Preparation:**  
  - Ensured that critical data sources (e.g., **Windows Event Logs**, **Sysmon Logs**) were available and correctly formatted for analysis.
  - Verified **CIM compliance** for Splunk, ensuring data compatibility with detection rules.

- **Scope Definition:**  
  - Focused the hunt on **high-risk user machines** within a **1-week timeframe** to balance data relevance and volume.
  
- **Collaborative Decision Making:**  
  - Assisted the team in narrowing the scope based on real-time findings, ensuring the analysis remained focused and efficient.

- **Documentation & Reporting:**  
  - Contributed to documenting the entire process of hypothesis formulation, data collection, analysis, and findings.
  - Helped compile the **final report**, summarizing the analysis, recommendations, and next steps.

---

## Tools and Techniques

- **Splunk Enterprise Security**: Used for collecting, analyzing, and correlating security data across the network.
- **MITRE ATT&CK**: A knowledge base of adversary tactics and techniques used for building our hypothesis and focusing the hunt.
- **Windows Event Logs & Sysmon**: Data sources for detecting anomalous activities indicative of ransomware behavior.
- **PEAK Threat Hunting Framework**: The framework used to guide our threat hunting methodology through the **Prepare**, **Execute**, and **Act** phases.

---

## Key Skills Demonstrated

- **Threat Hunting**: Hands-on experience with a hypothesis-driven threat hunting approach.
- **MITRE ATT&CK Framework**: Applied techniques and sub-techniques to identify attack vectors, specifically **T1059.003 Windows Command Shell**.
- **Data Analysis & SIEM**: Validated and analyzed data within **Splunk**, ensuring accurate data collection and actionable findings.
- **Collaboration**: Worked effectively as part of a team, refining hypotheses and sharing responsibilities in the hunting process.
- **Documentation**: Documented the entire threat hunting process and compiled a final report, ready for incident escalation and future reference.

---

## Project Outcome

While the hunt did not uncover active ransomware in the environment, the process helped refine the network's detection capabilities, particularly in detecting **Windows Defender evasion** tactics. The insights gathered during this hunt will be used for **future detection improvements**.

---

## Conclusion

This project provided me with hands-on experience in **cyber threat hunting** and allowed me to apply key methodologies like the **PEAK Threat Hunting Framework**. I gained valuable skills in **data analysis**, **hypothesis formulation**, and **collaborative work in a team** environment, which are essential in a **Security Operations Center (SOC)**.

---

## How to Run

This project is a case study that involves **Splunk** for threat hunting activities. It does not have specific code or tools for running the hunt directly but illustrates the process used in a **SOC environment**. However, to replicate this type of threat hunting:

1. Set up **Splunk** with data sources such as **Windows Event Logs** and **Sysmon**.
2. Implement **MITRE ATT&CK** techniques for identifying threats and anomalies.
3. Use the **PEAK Threat Hunting Framework** to structure the hunt:  
   - **Prepare**: Define scope, identify relevant techniques, and refine the hypothesis.
   - **Execute**: Collect and analyze data based on refined hypothesis.
   - **Act**: Document findings and escalate to Incident Response if necessary.

---

## License

This project is for educational purposes and follows the guidelines of the **SOC Essentials** course. No proprietary code is included.

