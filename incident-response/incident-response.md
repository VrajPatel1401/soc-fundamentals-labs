## Incident: Suspicious Login Attempts (Brute Force)

### Objective
To identify and analyze repeated failed login attempts and understand basic incident response steps.

### Tools Used
- Linux system logs
- Wireshark (basic understanding)

### Incident Description
Multiple failed SSH login attempts were observed from a single external IP address within a short time frame.

### Steps Performed
1. Checked authentication logs to identify failed login attempts.
2. Noted repeated failures from the same source IP.
3. Correlated login attempts with timestamps.
4. Classified the activity as a possible brute-force attack.

### Response Actions
- Suggested blocking the source IP using firewall rules.
- Recommended strong password policy.
- Advised enabling account lockout and monitoring alerts.

### What I Learned
- How brute-force attacks are detected.
- Importance of log monitoring in SOC operations.
- Basic incident response workflow.

