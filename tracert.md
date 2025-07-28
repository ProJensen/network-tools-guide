# Tool: `tracert`

## 🔧 Purpose
The tracert command is used to identify the route and measure the delay of packets across a network. It helps you determine where a connection fails or slows down when communicating with another device or website.

## ✅ Use Cases:
- Identify slow or unreachable network segments

- Locate where a network connection is dropping

- Understand the path between your device and an external server

## 1️⃣ Tracing your Destination

```bash
tracert google.com
```

This command traces the path from your computer to your destination, showing all routers (hops) along the way. If a specific hop takes too long or times out, it may indicate a network issue.

![tracert google.com](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/tracert-example-1.png)

## 2️⃣ Tracing DNS

```bash
tracert 8.8.8.8
```

This is useful to see how your network reaches DNS server. Useful if DNS lookup is slow or failing.

![tracert 8.8.8.8](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/tracert-example-2.png)
