## Log Analysis: SSH Brute Force Attempt

### Objective
To analyze system logs and detect brute-force login attempts.

### Log Source
- Linux authentication logs

### Observations
- Multiple failed login attempts from the same IP.
- Attempts occurred within a short time interval.

### Analysis
- Pattern indicates automated attack.
- No successful login was detected.

### Mitigation Suggestions
- Block IP using firewall.
- Enable intrusion detection.
- Monitor logs continuously.

### What I Learned
- How log patterns reveal attack behavior.
- Importance of log analysis in SOC environments.
