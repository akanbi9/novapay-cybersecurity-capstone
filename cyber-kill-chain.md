# Cyber Kill Chain

## Cyber Kill Chain Analysis

The Cyber Kill Chain breaks an attack into 7 stages, showing how a small mistake 
(like plugging in a USB drive) can escalate into a full company-wide breach.

### Stage 1 — Reconnaissance
**What the attacker could learn about NovaPay:**
- Employee names and roles (from LinkedIn, company website, social media)
- Email formats (e.g., firstname.lastname@novapay.com)
- Office location (useful for dropping a "lost" USB drive nearby)
- What software NovaPay uses (from job postings)

### Stage 2 — Weaponization
**What malicious tool the attacker could prepare:**
- A USB drive pre-loaded with malware that runs automatically when plugged in
- Malware bundled with a keylogger, designed to silently capture keystrokes 
  (usernames, passwords, ID card numbers)

### Stage 3 — Delivery
**How the attack reaches an employee:**
- **Malicious USB** — left outside the office, relying on curiosity.
- Other common delivery methods: phishing emails, malicious attachment whereby the user will click on it.

### Stage 4 — Exploitation
**What human mistake:**
- The employee plugs the unknown USB into a company computer without checking with 
  IT first — this is a **human error**, not a technical flaw. Most successful 
  attacks rely on this kind of trust or curiosity rather than breaking through 
  technical defenses.

### Stage 5 — Installation
**What gets installed on the device:**
- Malware, specifically a **keylogger**, gets silently installed and starts running 
  in the background, recording everything typed

### Stage 6 — Command and Control (C2)
**How the compromised device talks back to the attacker:**
- The infected computer secretly connects to a server controlled by the attacker 
  over the internet, sending back captured data (like passwords) — this 
  communication is designed to look like normal internet traffic so it isn't 
  noticed

### Stage 7 — Actions on Objectives
**What the attacker ultimately wants:**
- Steal employee passwords
- Log into employee accounts using the stolen credentials
- Access sensitive data or financial information
- Damage NovaPay's reputation (by creating fake news)









