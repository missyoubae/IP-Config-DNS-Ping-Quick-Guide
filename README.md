# ipconfig-dns-ping-quick-guide

A beginner-friendly cheat sheet explaining:
- `ipconfig`
- `ipconfig /all`
- DNS flushing (`ipconfig /flushdns`)
- DNS display cache (`ipconfig /displaydns`)
- DNS spoofing (concept, defensive view)
- Continuous ping (`ping <gateway> -t`)

> 🎯 Goal: Easy visuals + simple explanations so anyone can understand quickly.

---

## 📌 Commands Overview

| Command | What it does |
|--------|----------------|
| `ipconfig` | Shows basic IP info (IP, subnet mask, gateway) |
| `ipconfig /all` | Shows full adapter details (MAC, DHCP, DNS, etc.) |
| `ipconfig /flushdns` | Clears DNS cache on your PC |
| `ipconfig /displaydns` | Shows DNS cache stored on your PC |
| `ping <ip> -t` | Continuous ping to check connection stability |

---

## 🖼️ Diagrams with Icons

### 1) `ipconfig` (Basic Network Info)
**Command:**
```bat
ipconfig
