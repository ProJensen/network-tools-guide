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

![netstat -a](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-1-2.png)

This shows every connection and port your system is using or waiting on. Great for checking if a service is listening on a certain port.

### 2️⃣ netstat -n

Displays numerical IP addresses and port numbers (instead of resolving to host/domain names).

```bash
netstat -n
```

![netstat -n](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-2.png)

Useful when DNS resolution is slow or you want to avoid it for privacy or speed. Shows raw IPs and ports.

### 3️⃣ netstat -o

Shows connections with associated Process IDs (PIDs).

![netstat -o](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-3.png)

This is helpful when you want to know which program or process is using a specific port.

You can match the PID with Task Manager to identify the program.

### 4️⃣ netstat -an

Combines -a and -n: shows all connections with raw IP and port numbers.

![netstat -an](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-4.png)

Efficient for scanning open ports without hostname resolution.

### 5️⃣ netstat -b (Needs Admin)

Displays which executable (program) created each connection or listening port.

```bash
netstat -b
```

![netstat](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/netstat-example-5.png)

Shows you what software is actively listening or connecting. Very useful for detecting malware or unauthorized software.

⚠️ You need to run Command Prompt as Administrator to use -b.
