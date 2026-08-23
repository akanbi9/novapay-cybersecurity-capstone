## Geolocation Security

### What is geolocation?
Geolocation is the process of figuring out where a device — and likely its user — is physically located in the real world. Your phone, laptop, or browser can estimate this and share it with websites or apps, which is how a weather app knows your city without you typing it in.

### How Websites and Apps Determine Your Location

**GPS (Global Positioning System)**
Uses satellites orbiting Earth to calculate your exact position. The most accurate method, used by phones for maps and navigation, but it needs a clear view of the sky, so it works best outdoors.

**IP-based location**
Every device connecting to the internet has an IP address, which is loosely tied to a geographic region assigned by the internet provider. It's like knowing which city or neighborhood someone's mail gets delivered to — not precise, but a useful estimate. This is the method most commonly used to flag "login from an unusual location."

**Wi-Fi positioning**
Your device detects nearby Wi-Fi networks and compares them to a database of known router locations. Works well indoors, where GPS struggles, and is more accurate than IP-based location.

**Mobile networks**
Phones can be located based on which cell towers they're connecting to — the closer you are to a tower, the stronger the signal, letting providers estimate your position even without GPS turned on.

**Browser location permissions**
When a website asks "Allow this site to know your location?" it's the browser requesting permission to share GPS/Wi-Fi/IP data with that specific site. You can always deny it, and the site falls back to less accurate IP-based guessing.

### Privacy and Cybersecurity Risks

- **Stalking/physical safety risk** — leaked or misused location data could let someone track a person's real-world movements
- **Profiling** — companies can build a picture of daily habits (home, work, gym) from location patterns over time
- **Data breaches** — stored location history becomes a valuable target if a company's database is hacked
- **Social engineering** — attackers can use known location patterns to make phishing attempts more convincing
- **Third-party sharing** — some apps sell location data to advertisers without users fully realizing it

### How Geolocation Helps NovaPay Investigate Suspicious Logins

This connects directly to **Suspicious Account Login** — the login from an unfamiliar location, late at night.

Geolocation (usually IP-based, since it works automatically without needing user permission at login) lets NovaPay's security team:

- **Compare login location to the employee's normal pattern** — a sudden login from an unfamiliar country is a red flag
- **Flag logins from high-risk regions** — some locations are known sources of frequent cyberattacks
- **Trigger automatic security responses** — systems can auto-require MFA or temporarily block a login that looks abnormal
- **Support the investigation timeline** — knowing exactly where a suspicious login came from helps determine if it was the real employee traveling, or an attacker using stolen credentials


