# OSINT-with-WAF-Detector
Open Source Intelligence with WAF Detector 
Developed by: **SAMI CHAWALWALA**

---

##  What is RAW-OSINT?

RAW-OSINT is a powerful **OSINT (Open Source Intelligence) Harvester** with built-in **WAF Detection**. It collects emails, subdomains, IPs, social media accounts, GitHub repos, and more — all from publicly available sources.

**NO API KEYS REQUIRED**

---

##  Features

###  OSINT Mode
-  **Email Harvesting** - Google, Bing, DuckDuckGo, GitHub, Pastebin
-  **Subdomain Discovery** - Passive DNS, CRT.sh, Common Crawl, URLScan
-  **IP Discovery** - IPv4, IPv6, historical IPs, ASN information
-  **GitHub Repos** - Find relevant repositories
-  **Social Media** - Instagram, Twitter/X, LinkedIn
-  **Wayback Machine** - Historical URLs
-  **Reddit & Pastebin** - Mentions and pastes

##  WAF Detection Mode
-  **wafw00f integration** - Full WAF fingerprinting
-  **Confidence scoring** - HIGH/MEDIUM/LOW
-  **Detailed evidence** - Request statuses, fingerprints
-  **Notes & issues** - Timeouts, configuration notes

---

##  Installation

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/RAW-OSINT.git
cd RAW-OSINT

# Install dependencies
pip install -r requirements.txt

# Make it executable (Linux/Mac)
chmod +x RAW-OSINT.py
