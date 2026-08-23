## Security Recommendations for NovaPay

Each recommendation follows a **Problem → Solution → Benefit** structure, tied back to the actual incidents NovaPay experienced.

---

### Multi-Factor Authentication (MFA)

**Problem:** Employee credentials were compromised (keylogging, dark web leak) and used for a suspicious late-night login.

**Solution:** Require a second verification step (authenticator app, SMS code, or hardware key) in addition to a password for all company logins.

**Benefit:** Even if a password is stolen, an attacker can't log in without the second factor — directly closing the gap that allowed the suspicious login.

---

### Endpoint Protection

**Problem:** A USB device introduced malware onto a company computer without detection.

**Solution:** Install endpoint detection and response (EDR) software on all company devices to monitor, detect, and block malicious activity in real time.

**Benefit:** Malware from infected USBs or other sources gets flagged and blocked before it can spread or install a keylogger.

---

### Password Manager

**Problem:** Reused or weak passwords make credential theft far more damaging, since one leaked password can unlock multiple accounts.

**Solution:** Provide employees with a company-approved password manager to generate and store strong, unique passwords for every account.

**Benefit:** Reduces password reuse, so a single leaked credential doesn't compromise multiple systems.

---

### Employee Cybersecurity Training

**Problem:** An employee plugged in an unknown USB device and others may not recognize phishing, fake news, or social engineering tactics (Event 1, 5).

**Solution:** Run regular, mandatory security awareness training covering USB risks, phishing, and disinformation.

**Benefit:** Employees become the first line of defense instead of the weakest link — much of NovaPay's incident could have been prevented by awareness alone.

---

### USB Device Restrictions

**Problem:** A rogue USB device was plugged directly into a company computer.

**Solution:** Disable USB ports by default, allow only approved devices, and require unknown USBs to be handed to IT.

**Benefit:** Removes the exact entry point that started NovaPay's entire incident chain.

---

### Firewall Protection

**Problem:** Without network-level filtering, malware can communicate freely with external attacker servers once it's inside the network.

**Solution:** Deploy and properly configure firewalls on the company network and individual devices.

**Benefit:** Blocks or limits malicious traffic in and out of the network, potentially stopping malware from "phoning home" or spreading further.

---

### Browser Privacy Policies

**Problem:** Company computers were found to have excessive third-party tracking cookies (Event 4), raising privacy concerns.

**Solution:** Set browser policies that limit or block third-party cookies and enforce privacy-focused browser settings company-wide.

**Benefit:** Reduces unnecessary tracking and data exposure, and limits the risk of session-cookie theft.

---

### Access Control

**Problem:** If every employee has broad access to systems and data, one compromised account can expose far more than necessary.

**Solution:** Apply the principle of least privilege — employees only get access to the systems and data required for their specific role.

**Benefit:** Limits how much damage a single compromised account can cause.

---

### Security Monitoring

**Problem:** The suspicious login was only noticed because an administrator happened to spot it — not through active monitoring.

**Solution:** Implement continuous security monitoring/logging tools that automatically flag unusual activity (odd login times, locations, failed attempts).

**Benefit:** Suspicious activity gets caught faster and more reliably, instead of depending on chance discovery.

---

### Virtual Payment Cards

**Problem:** NovaPay's real company card is exposed every time it's used for online software/service purchases.

**Solution:** Use virtual, merchant-locked, or single-use card numbers for online company purchases instead of the main card.

**Benefit:** If a virtual number is leaked, NovaPay's real payment card details remain safe and unaffected.


