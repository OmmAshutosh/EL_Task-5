# 🌐 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective  
Capture live network packets using Wireshark and analyze basic protocols and traffic types to develop packet analysis skills.

---

## 🧰 Tools Used

- 🧪 [Wireshark](https://www.wireshark.org/) – Free network packet analyzer

---

## 📝 Task Steps

---

### ✅ Step 1: Install Wireshark

- Download and install Wireshark:  
  [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)

---

### ✅ Step 2: Start Capture on Active Network Interface

1. Launch Wireshark
2. Select your **active network interface** (e.g., Ethernet, Wi-Fi)
3. Click **"Start Capturing Packets"**

---

### ✅ Step 3: Generate Network Traffic

- While capture is running, perform these actions in a browser or terminal:
  - Visit `https://www.google.com`
  - Run: `ping google.com` from terminal/command prompt

---

### ✅ Step 4: Stop the Capture

- Wait for about 1 minute of traffic
- Click the **red square (■)** in Wireshark to stop capture

---

### ✅ Step 5: Apply Protocol Filters

Use the filter bar to view specific traffic:

| Protocol | Filter Expression |
|----------|-------------------|
| HTTP     | `http`            |
| DNS      | `dns`             |
| TCP      | `tcp`             |
| ICMP     | `icmp`            |

---

### ✅ Step 6: Identify 3 Protocols & Analyze Packets

Identify and document at least **3 protocols** you observed:

| Protocol | Description                  | Usage Example                  |
|----------|------------------------------|--------------------------------|
| DNS      | Domain Name Resolution       | Resolves `google.com` to IP    |
| HTTP     | Web Communication            | Loading websites               |
| ICMP     | Network Diagnostics          | Seen during `ping` test        |

---

### ✅ Step 7: Export the Capture File

1. Go to **File → Export Packet Dissections → As .pcap**
2. Save as `network_capture.pcap`

---

### ✅ Step 8: Summarize Your Findings

Create a short report (`capture_summary.md`) including:

## 🔐 Reminder

> Only capture traffic on networks you own or have permission to analyze.  
> Do **not** capture sensitive or private information.

---

## 📚 References

- [Wireshark Filters Guide](https://wiki.wireshark.org/DisplayFilters)
- [Wireshark Tutorial for Beginners](https://www.geeksforgeeks.org/wireshark/)
