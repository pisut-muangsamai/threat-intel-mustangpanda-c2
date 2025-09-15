# Unmasking Mustang Panda’s Hidden C2 Network

**Revealing stealth infrastructure fueling future cyberespionage campaigns**

This repository shares **100+ suspected C2 IP addresses** linked to the  
**Frankenstein variant of the ToneShell backdoor** operated by the  
**China-nexus Mustang Panda (TA416) APT group**.

These indicators were identified through **pivot-based infrastructure analysis** leveraging Censys, FOFA, WHOIS, and Shodan, focusing on:

- Non-standard RDP services (TCP 26263)
- Exposed WinRM (TCP 5985)
- Shared TLS certificate attributes
- Temporal co-observation and overlapping hosting on M247 (AS9009)

---

## 📂 Indicators

- `indicators/suspected_c2_ipv4.csv` — Clean CSV list (IP, ASN, Notes)
- `indicators/suspected_c2_ipv4.txt` — Plain text list

---

## ⚠️ Usage Notice

- Classification: **TLP:CLEAR**
- Use only for **defensive cybersecurity research and threat detection**.
- These IPs are **suspected** infrastructure — validate before enforcement.

---

## 📎 Reference

- Fishbein, N. (2025, Sep 10). [Frankenstein variant of the ToneShell backdoor targeting Myanmar](https://intezer.com/blog/frankenstein-variant-of-the-toneshell-backdoor-targeting-myanmar/). Intezer
