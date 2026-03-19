# Phishing Email Investigation

## Objective

Investigate a suspicious email was reported by a user after noticing unusual urgency and a request to verify account information.

---

## Environment

- Simulated SOC / cybersecurity lab environment
- Email security review and analyst triage workflow
- Examination of sender details, embedded links, and message content
- Analysis supported by phishing investigation methodology

---

## Tools Used

- Splunk
- Microsoft Sentinel
- Windows Event Logs

## Detection Summary

A suspicious email was reported for review after the recipient noticed unusual language, a sense of urgency, and a request to click a link to verify account information.

Initial indicators suggested possible phishing activity based on the sender domain, social engineering language, and embedded hyperlink behavior.

---

## Investigation Steps

1. Reviewed the sender address and compared the domain to the legitimate organization it claimed to represent.
2. Examined the subject line and body content for urgency, fear-based language, and social engineering tactics.
3. Inspected embedded links to determine whether the displayed URL matched the actual destination.
4. Evaluated the message for signs of spoofing, impersonation, or suspicious formatting.
5. Assessed the overall risk and documented findings for escalation or user guidance.

---

## Key Findings

- The sender address did not match the legitimate domain of the organization being impersonated.
- The email used urgency-based language designed to pressure the user into immediate action.
- The embedded link destination differed from the visible text presented in the message.
- The message requested account verification in a manner consistent with credential harvesting attempts.
- Multiple indicators supported classifying the message as a phishing email.

---

## Analyst Assessment

Based on the sender inconsistency, social engineering language, and misleading link behavior, this email should be classified as a phishing attempt and handled as a malicious message.

---

## Recommended Actions

- Do not click any links or download any attachments contained in the email.
- Block or quarantine the message within the email environment.
- Report the sender and associated domain for further review.
- Advise affected users to delete the message immediately.
- If a user interacted with the email, initiate credential reset and review for suspicious account activity.

---

## Outcome

This investigation demonstrates a structured phishing analysis workflow:

- review suspicious email characteristics
- identify social engineering indicators
- inspect sender and link mismatches
- classify the message based on evidence
- recommend containment and user protection steps

---

## Skills Demonstrated

- Email threat analysis
- Phishing identification
- Risk assessment
- Security documentation
- Analytical thinking
- Escalation readiness
