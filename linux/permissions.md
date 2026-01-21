# Linux Permissions and Security Basics

## Why Linux Matters in Cybersecurity
Most servers and cloud platforms run on Linux. Understanding permissions helps prevent unauthorized access and privilege escalation.

## Permission Types
Linux permissions apply to:
- Owner
- Group
- Others

Each can have:
- Read (r)
- Write (w)
- Execute (x)

Example:

## Numeric Permissions
| Value | Meaning |
|------|--------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |

Example:

## Security Relevance
Incorrect permissions can allow attackers to:
- Modify sensitive files
- Execute malicious scripts
- Escalate privileges

## Common Commands
- ls -l
- chmod
- chown
- sudo
- whoami

## SOC Perspective
SOC analysts may investigate:
- Unexpected permission changes
- Abnormal sudo usage
- Compromised Linux accounts
