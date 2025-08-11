# Wireshark Network Capture Task

## 📅 Date of Capture
August 11, 2025

## 🎯 Purpose
To capture and analyze network traffic using Wireshark, and identify different network protocols in action.

## ✅ Steps Performed
- Installed Wireshark on Windows
- Captured network traffic using an active interface (Wi-Fi)
- Visited a website (`example.com`) and used `ping google.com` to generate traffic
- Stopped the capture after 1 minute
- Filtered packets by protocol:
  - `tcp` for transport layer inspection
  - `http` for web traffic
  - `dns` for domain resolution
- Exported filtered packets as separate `.pcap` files

## 📦 Files Included
- `my_capture_tcp.pcap` – Captured TCP traffic
- `my_capture_http.pcap` – Captured HTTP traffic (web browsing)
- `my_capture_dns.pcap` – Captured DNS queries (name resolution)
- `README.md` – This summary of the task

## 🔍 Protocols Observed
- **TCP** – Used for reliable communication and seen in most traffic
- **HTTP** – Unencrypted web traffic (GET requests and responses)
- **DNS** – Requests for IP addresses corresponding to domain names

## 📝 Summary of Findings
- Observed a DNS query sent to resolve `example.com`
- Captured an HTTP GET request and response from `example.com`
- Saw TCP handshakes and data exchange between client and server
- Each protocol was saved into its own `.pcap` file for clarity
