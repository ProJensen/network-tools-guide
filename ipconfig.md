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
This command gives detailed information for all network adapters, including MAC address, DNS servers, DHCP status, and lease information. Use it for deep diagnostics.

![ipconfig /all](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-2.png)

## 3️⃣ Release the IP Address
```bash
ipconfig /release
```
This command disconnects your system from the network by releasing the current IP address. It's often used before manually renewing the IP or troubleshooting DHCP issues.

![ipconfig /release](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-3.png)

## 4️⃣ Renew the IP Address
```bash
ipconfig /renew
```
After using /release, this command requests a new IP address from the DHCP server. It’s helpful if the original IP was invalid or expired.

![ipconfig /renew](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-4.png)

## 5️⃣ Flush the DNS Cache
```bash
ipconfig /flushdns
```
This clears the DNS resolver cache on your system. Use it when a website’s IP has changed but your system is still using the old DNS entry.

![ipconfig /flushdns](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/ipconfig-example-5.png)
