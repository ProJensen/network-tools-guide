# Tool: `nslookup`

## 🔧 Purpose
nslookup (Name Server Lookup) is a command-line tool used to query Domain Name System (DNS) records. It helps resolve domain names to IP addresses and vice versa, useful for troubleshooting DNS-related issues.

## 1️⃣ nslookup google.com

Ask your computer’s default DNS server what IP address belongs to google.com.

```bash
nslookup google.com
```

![nslookup google.com](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/nslookup-example-1.png)


✅ Result shows:

- Your current DNS server

- The IP address(es) of google.com

---


## 2️⃣ nslookup google.com 8.8.8.8

Same query, but use Google's public DNS (8.8.8.8) instead of your default DNS.

```bash
nslookup google.com 8.8.8.8
```

![nslookup google.com 8.8.8.8](https://raw.githubusercontent.com/ProJensen/network-tools-guide/refs/heads/main/screenshots/nslookup-example-2.png)

✅ Useful for:

- Verifying if your DNS server gives different results than others

- Checking DNS issues on your network
