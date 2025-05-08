# 🛡️ Wireshark Analysis – Day 1

**Date:** May 8, 2025  
**Distro:** Kali Linux  
**Interface Used:** wlan0  
**Target Site:** http://stackoverflow.com, http://netacad.com

---

## 🔍 Observed Protocols:
- **DNS:** Queries to resolve domain names  
- **HTTP:** Unencrypted web traffic (viewable)  
- **TCP:** Transport control packets  
- **ICMP:** (if you used ping)  

---

## 🧪 Filters Used:
```http
http
dns
tcp
icmp
