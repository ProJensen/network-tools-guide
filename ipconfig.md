# Tool: `ipconfig`

## 🔧 Purpose
The `ipconfig` command displays and manages the IP configuration of a computer running Windows. It’s commonly used for network troubleshooting and to refresh DHCP settings.

---

## 1️⃣ View IP Configuration
```bash
ipconfig
```
This command provides a summary of your current IP address, subnet mask, and default gateway. It’s useful to quickly check if you have a valid IP.

![ipconfig](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-1.png)

## 2️⃣ View Detailed Network Info
```bash
ipconfig /all
```
This version gives detailed information for all network adapters, including MAC address, DNS servers, DHCP status, and lease information. Use it for deep diagnostics.

![ipconfig /all](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-2.png)

