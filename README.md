# 🧠 Task 5 - Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
To capture and analyze live network traffic using **Wireshark**, identify different protocols, and understand how data moves between devices on a network.

---

## 🧰 Tool Used
- **Wireshark** (Free network packet analyzer)
- **Windows 10** with active Wi-Fi connection

---

## ⚙️ Steps Performed
1. Downloaded and installed Wireshark from the official website.  
2. Opened Wireshark as Administrator.  
3. Selected the active **Wi-Fi interface** and started capturing packets.  
4. Opened a few websites like `google.com`, `youtube.com`, and `github.com` to generate network traffic.  
5. Used the `ping google.com` command in Command Prompt to capture ICMP packets.  
6. Stopped the capture after around one minute.  
7. Applied filters like `dns`, `http`, and `tcp` to analyze specific types of packets.  
8. Saved the capture file as **task5_capture.pcap** for submission.

---

## 📊 Protocols Identified
| Protocol | Description |
|-----------|--------------|
| **DNS** | Used to convert domain names into IP addresses |
| **TCP** | Connection-based protocol ensuring reliable data transfer |
| **HTTP** | Used for web communication (GET and POST requests) |
| **ARP** | Resolves IP addresses to MAC addresses on local network |
| **ICMP** | Used for ping and network diagnostics |

---

## 🧠 Key Learnings
- Understood how **packets** are captured and analyzed.  
- Learned to filter packets using protocol names in Wireshark.  
- Observed the **3-way TCP handshake** and **DNS query process**.  
- Gained practical experience in **network traffic analysis** and **protocol identification**.

---

## 📁 Files Included
- `task5_capture.pcap` — captured packets file  
- `README.md` — this report  
> 🧩 *Simple observation can reveal complex network behavior — Wireshark makes it visible.*
