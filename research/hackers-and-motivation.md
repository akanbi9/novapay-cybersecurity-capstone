## Why Do Hackers Hack?

Cyberattacks aren't random, attackers are usually driven by specific goals. Below 
are five common motivations, along with how each one could apply to the NovaPay 
incidents.

### 1. Financial Gain
The most common motivation: attackers steal money, card details, or credentials 
they can sell or use directly.
- **Relevant to NovaPay:** (keylogging) and (account login) both 
  point toward stolen credentials being used or sold for profit. Event 7 (payment 
  security) also relates directly to protecting against financial theft.

### 2. Revenge
A disgruntled employee, ex-employee, or customer may attack a company they feel 
wronged them.
- **Relevant to NovaPay:** Event 5 (fake news attack) could fit this — someone with 
  a personal grudge spreading false claims to damage the company out of spite.

### 3. Political Motivation
Some attackers target organizations to make a political statement or protest 
company/government actions.
- **Less likely here**, since NovaPay is a payment company, not a political target — 
  but not impossible if NovaPay had taken a controversial public stance.

### 4. Espionage
Attackers (sometimes backed by competitors or even nation-states) steal confidential 
data for strategic advantage.
- **Relevant to NovaPay:** Event 1 (USB baiting) could be used for espionage — 
  planting malware to quietly monitor internal operations rather than just steal 
  passwords.

### 5. Curiosity
Some attackers (often less experienced, sometimes called "script kiddies") hack 
simply to see if they *can*, without a deeper goal.
- **Relevant to NovaPay:** Possible but less likely, since the attack shows a clear 
  chain (USB → keylogger → account access) suggesting intent, not random poking 
  around.

### 6. Reputation
Some attackers hack to build street cred in hacker communities, or to prove skill.
- **Less central here**, though publicly bragging about breaching NovaPay would fit 
  this motive if the attacker wanted recognition.

### 7. Ideology
Attacks driven by strong beliefs — e.g., hacktivists opposing a company's practices.
- **Possibly relevant to Event 5** if the fake news post was motivated by opposition 
  to NovaPay's business model (e.g., anti-fintech sentiment) rather than personal 
  revenge.

### 8. Data Theft
Stealing personal or financial data — either to sell it or use it directly.
- **Relevant to NovaPay:** Event 6 (dark web report) is a direct example — stolen 
  credentials ending up in a leaked database is a classic outcome of data theft.

### 9. Competition
A rival company may sponsor or conduct attacks to damage a competitor's standing or 
steal trade secrets.
- **Relevant to NovaPay:** Event 5 (fake news attack) fits well — a competitor 
  spreading false collapse rumors could drive NovaPay's customers toward a rival 
  service.

### 10. Disruption
Some attacks aim purely to cause chaos or take services offline, without necessarily 
stealing anything.
- **Less central to NovaPay's case**, since the attacker seems focused on 
  credentials/data rather than shutting systems down — though disruption is a side 
  effect of Event 5's reputational damage.

---

## Most Likely Motivation Behind the NovaPay Incident

Looking at the full chain of events — USB malware (Event 1) → keylogger (Event 2) → 
account compromise (Event 3) → leaked credentials on the dark web (Event 6) — the 
pattern points strongly toward **financial gain** as the primary motivation.

The attacker's actions consistently target **credentials and account access**, 
which are the building blocks needed to commit fraud, drain funds, or sell stolen 
data for profit — not to make a political statement or prove a point.

Event 5 (the fake news attack) may represent a **secondary motivation** — possibly 
**competition** or **revenge** — run either by the same attacker to cause confusion 
and cover their tracks, or by an entirely separate actor. This shows that a single 
incident can involve more than one motivation working together.

