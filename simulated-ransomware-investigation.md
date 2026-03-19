# Simulated Ransomware Investigation

## Objective

Investigate potential ransomware-related activity identified within a simulated environment by analyzing suspicious behavior, validating indicators of compromise, documenting findings, and recommending containment actions.

---

## Environment

- Simulated SOC / cybersecurity lab environment
- Windows-based endpoint activity
- Log analysis using SIEM tools (Splunk / Microsoft Sentinel)
- Endpoint behavior and file activity review

---

## Detection Summary

Suspicious activity was identified based on behavior consistent with possible ransomware execution, including abnormal file modification patterns and indications of unauthorized encryption activity on a host system.

---

## Investigation Steps

1. Reviewed alerts and indicators associated with the affected endpoint.
2. Analyzed available logs for abnormal process execution and file activity.
3. Identified high-frequency file modifications within a short time frame.
4. Evaluated whether activity aligned with legitimate system behavior or potential malicious execution.
5. Documented findings and assessed potential scope and impact.

---

## Key Findings

- The affected host exhibited behavior consistent with ransomware-like activity.
- Multiple files appeared to be modified or encrypted in rapid succession.
- The pattern of activity deviated from normal system operations.
- Indicators suggested a potential compromise requiring immediate attention.

---

## Containment Recommendations

- Immediately isolate the affected host from the network.
- Disable or restrict any accounts potentially associated with the activity.
- Preserve logs and endpoint data for further forensic investigation.
- Initiate malware scanning and incident response procedures.
- Review additional systems for related indicators of compromise.

---

## Analyst Assessment

Based on the observed behavior, this activity should be treated as a high-priority security incident due to the potential for data encryption, operational disruption, and possible lateral movement.

---

## Outcome

This investigation demonstrates a structured approach to security analysis:

- Identification of suspicious activity
- Investigation using available data sources
- Clear documentation of findings
- Recommendation of containment and response actions

---

## Skills Demonstrated

- Incident triage and analysis
- Log review and pattern recognition
- Threat investigation
- Security documentation
- Escalation readiness
- Analytical thinking and communication
