## RAW-OSINT & WAF Detector


### Installation FOR KALI

-(open your terminal)-


git clone https://github.com/sami-chawalwala/OSINT-with-WAF-Detector.git raw-osint

cd raw-osint

pip3 install requests beautifulsoup4 aiohttp wafw00f --break-system-packages

chmod +x RAW-OSINT

 **Installation Done**
 
  ### RUN IT 
1. OSINT Mode - Domain Reconnaissance:
 
 bash
 
      ./RAW-OSINT -d example.com




   
2. WAF Detection Mode - Firewall Detection:
   
 bash
 
     ./RAW-OSINT -waf https://example.com






## What is RAW-OSINT?

RAW-OSINT is a powerful OSINT (Open Source Intelligence) Harvester with built-in WAF Detection. It collects emails, subdomains, IPs, social media accounts, GitHub repos, and more — all from publicly available sources.

**NO API KEYS REQUIRED**

---

## Features

### OSINT Mode
- Email Harvesting - Google, Bing, DuckDuckGo, GitHub, Pastebin
- Subdomain Discovery - Passive DNS, CRT.sh, Common Crawl, URLScan
- IP Discovery - IPv4, IPv6, historical IPs, ASN information
- GitHub Repos - Find relevant repositories
- Social Media - Instagram, Twitter/X, LinkedIn
- Wayback Machine - Historical URLs
- Reddit & Pastebin - Mentions and pastes

### WAF Detection Mode
- wafw00f integration - Full WAF fingerprinting
- Confidence scoring - HIGH/MEDIUM/LOW
- Detailed evidence - Request statuses, fingerprints
- Notes & issues - Timeouts, configuration notes

---
Developed by: **SAMI CHAWALWALA**
---
