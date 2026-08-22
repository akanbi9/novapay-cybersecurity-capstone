# novapay-cybersecurity-capstone

# NURAIN ABDULLAH

# SCIENERIOS

**Event 1 — Suspicious USB Device**  
An employee found an unmarked USB flash drive outside the company's office and 
plugged it into a company computer in an attempt to identify its owner. Shortly 
afterward, the computer began behaving abnormally, suggesting the device may have 
delivered malicious software (a technique known as USB baiting).

**Event 2 — Possible Keylogging**  
An employee reported that several passwords had been compromised, despite never 
having shared them. The cybersecurity team suspects a keylogger — malicious software 
that records keystrokes — may have been installed, potentially as a result of the 
infected USB device from Event 1.

**Event 3 — Suspicious Account Login**  
The company administrator identified a login to an employee account from an 
unfamiliar location, occurring late at night — well outside the employee's normal 
access pattern. This is consistent with the use of credentials stolen via the 
suspected keylogger in Event 2.

**Event 4 — Browser Tracking**  
Employees discovered that several company computers contained large numbers of 
third-party browser cookies. Management wants the security team to clarify what 
these cookies are, what information they may collect, their privacy implications, 
and whether cookies themselves constitute malware.

**Event 5 — Fake News Attack**  
A fake social media post falsely claimed that NovaPay had suffered a major financial 
collapse and urged customers to withdraw their money immediately. The false 
information began spreading online, and management suspects a deliberate attempt to 
damage the company's reputation.

**Event 6 — Dark Web Report**  
The company received information suggesting that usernames and passwords belonging 
to some employees may have appeared in a leaked credential database circulating on 
the dark web.

**Event 7 — Payment Security Concern**  
NovaPay employees regularly purchase software and online services on behalf of the 
company. Management has asked the security team to investigate whether Virtual Card 
Numbers (VCNs) could reduce the risk of exposing the company's main payment card 
information during these transactions.


## Incident Analysis Table

| # | Event | What Happened | Possible Threat | Possible Vulnerability | Info/System at Risk | Possible Attacker | Why They Might Attack | Recommended Response |
|---|---|---|---|---|---|---|---|---|
| 1 | Suspicious USB Device | Employee plugged an unknown USB drive into a company PC; PC began acting strangely | Malware infection (USB baiting) | No policy against plugging in unknown devices; no auto-scan on USB insertion | Company computer, potentially the wider network | External opportunistic attacker | To gain network access, install further malware, or steal data | Disconnect PC from network, run malware scan, report to IT, train staff on USB policy |
| 2 | Possible Keylogging | Employee's passwords were compromised despite not sharing them | Keylogger capturing keystrokes | Infected endpoint (likely from Event 1); no antivirus/endpoint monitoring | Login credentials, personal/company accounts | Same attacker from Event 1, or a separate credential thief | To steal login details for financial gain or further access | Scan/clean the device, reset all affected passwords, enable MFA |
| 3 | Suspicious Account Login | Login to an employee account from an unusual location, late at night | Account compromise | Stolen credentials; no login anomaly detection or MFA | Employee account, any systems it can access | Attacker using stolen credentials from Event 2 | To access company systems/data using a valid login | Lock the account, investigate login logs, reset password, enable MFA |
| 4 | Browser Tracking | Many third-party cookies found on company computers | Privacy/data-tracking risk (not malware) | No browser security policy; cookies not regularly cleared or blocked | Employee browsing data, potentially sensitive activity patterns | Advertisers/data brokers (not a traditional "attacker") | To collect user data for tracking, profiling, or targeted ads | Clear cookies regularly, use tracker-blocking tools, set browser privacy policies, educate staff |
| 5 | Fake News Attack | False social media post claimed NovaPay had collapsed financially | Disinformation/reputation attack | Public social media presence with no rapid-response monitoring | Company reputation, customer trust, stock/financial standing | Competitor, disgruntled individual, or malicious actor | To damage the company's reputation or cause panic/financial harm | Issue an official public statement, report the fake post to the platform, monitor social media, involve PR/legal team |
| 6 | Dark Web Report | Employee usernames/passwords found in a leaked credential database | Credential exposure/leak | Reused passwords; credentials leaked from a prior breach (possibly unrelated to NovaPay) | All accounts using the leaked credentials | Cybercriminals trading leaked data | To sell or use credentials for unauthorized access | Force password resets for affected accounts, enable MFA, monitor for suspicious activity, discourage password reuse |
| 7 | Payment Security Concern | Employees use the main company card for online purchases | Payment card exposure | Main card number reused across many vendors, increasing exposure risk | Company's primary payment card and linked funds | Any party who intercepts or misuses exposed card details | To commit financial fraud using exposed card data | Implement Virtual Card Numbers (VCNs) for online purchases to limit exposure of the main card |




