# SOC Analyst Home Lab – Linux Log Analysis

## Objective
The goal of this lab was to practice basic SOC analyst tasks by analyzing Linux
authentication logs. I focused on identifying successful and failed login attempts
to better understand how analysts monitor systems for potential security issues.

## Tools Used
- Ubuntu Linux
- Bash (Linux command line)
- Native Linux authentication logs

## Lab Steps
1. Accessed Linux authentication logs located at `/var/log/auth.log`
2. Used command-line tools to identify failed login attempts
3. Reviewed successful login attempts to understand normal activity
4. Captured screenshots as evidence of findings
5. Documented commands and observations for reporting purposes
   
## Skills Demonstrated
- Linux command-line usage
- Log analysis
- Security monitoring fundamentals
- Documentation and reporting

## What I Learned
- Where Linux stores authentication activity and how to navigate `/var/log/auth.log`
- How SOC analysts use simple filtering tools like `grep` to quickly find security-relevant events
- Why documenting commands and saving evidence is important during investigations
- How patterns such as failed versus successful logins can help determine whether an issue needs further attention

## Why This Matters for SOC Work
This lab reflects a basic SOC monitoring task where authentication logs are reviewed to look
for potential unauthorized access. Working through this process helped me better understand
how SOC teams rely on log visibility, documentation, and verification when monitoring systems
and making escalation decisions.
