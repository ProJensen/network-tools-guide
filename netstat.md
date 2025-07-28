# Tool: `netstat`

## 🔧 Purpose
The netstat (network statistics) command is used to display active network connections, listening ports, routing tables, interface statistics, and more. It helps diagnose network problems or monitor ongoing connections.

---

## 📘 Common Syntax

```bash
netstat [options]
```

## 🔍 Commonly Used netstat Commands

### 1️⃣ netstat -a

Displays all active connections and listening ports.

```bash
netstat -a
```

![netstat -a](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-1.png)

This shows every connection and port your system is using or waiting on. Great for checking if a service is listening on a certain port.

### 2️⃣ netstat -n

Displays numerical IP addresses and port numbers (instead of resolving to host/domain names).

```bash
netstat -n
```

![netstat -n](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-2.png)

Useful when DNS resolution is slow or you want to avoid it for privacy or speed. Shows raw IPs and ports.

###
