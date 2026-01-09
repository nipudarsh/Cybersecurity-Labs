## Windows Networking Commands

**Check IP Configuration**
```powershell
ipconfig
```
*Why:* Shows Windows network adapter settings, IP addresses, DNS servers, and gateway.

**Trace Route**
```powershell
tracert google.com
```
*Why:* Shows the path network packets take to reach a destination, with hop-by-hop timing.

---

## Linux vs Windows Comparison

| Task | Linux Command | Windows Command |
|------|--------------|-----------------|
| Check IP Address | `ip a` or `ifconfig` | `ipconfig` |
| Check Routing Table | `ip route` | `route print` |
| Test Connectivity | `ping google.com` | `ping google.com` |
| DNS Lookup | `nslookup google.com` | `nslookup google.com` |
| Trace Route | `traceroute google.com` | `tracert google.com` |
| Check Connections | `ss -tuln` or `netstat -tuln` | `netstat -an` |

**Key Differences:**
- Linux uses `ip` commands, Windows uses `ipconfig`
- Linux: `traceroute`, Windows: `tracert`
- Both share `ping` and `nslookup`
- Linux's `ss` is more modern than `netstat`
