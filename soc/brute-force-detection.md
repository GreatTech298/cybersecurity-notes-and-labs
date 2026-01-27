# SOC Lab 2: Brute Force Detection

## Objective
To understand how SOC analysts detect and respond to brute force attacks.

## What is a Brute Force Attack?
A brute force attack is when an attacker tries many passwords rapidly to gain unauthorized access to accounts.

Indicators include:
- Multiple failed login attempts from a single IP  
- Multiple accounts targeted from one IP  
- Unusual login patterns or times  

---

## Example Log Pattern
- 3 failed attempts within 4 seconds → suspicious  
- May indicate automated attack  

---

## Steps to Investigate
1. Identify the source IP(s) generating multiple failures  
2. Check which accounts are being targeted  
3. Determine if any login was eventually successful  
4. Check IP reputation (internal logs, threat intel)  
5. Decide response:
   - Block the IP temporarily or permanently  
   - Reset targeted accounts’ passwords  
   - Notify management/security team  
6. Document findings and actions  

---

## Tools SOC Analysts Use
- SIEM platforms (Splunk, ELK, Graylog)  
- Linux logs (`/var/log/auth.log`)  
- Firewall logs  
- IDS/IPS alerts  

---

## Key Learnings
- Repeated failed logins = primary indicator  
- Correlating logs across systems improves detection  
- Fast response is critical to prevent compromise  

---

## Next Labs
- Creating alert rules in SIEM  
- Investigating suspicious IPs using threat intelligence  
- Real-time monitoring
