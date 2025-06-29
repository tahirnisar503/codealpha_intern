# 🛰️ Internship Task - Basic Network Sniffer (Python + Scapy)

## 👨‍💻 Created By:
**Tahir Nisar**  
Bachelor of Cyber Security, 6th Semester  


---

## 📌 Task Objective:

Build a **basic network packet sniffer** using Python that:
- Captures real-time network traffic (TCP/HTTP)
- Displays source/destination IPs and ports
- Shows protocol type and raw payload
- Helps understand how data flows in a network

---

## 🧰 Tools & Technologies:
- **Language**: Python 3.x
- **Library**: [Scapy](https://scapy.readthedocs.io/)
- **Platform**: Windows (Tested on CMD with admin rights)

---

## 🚀 How to Run

### 🔧 Step 1: Install Required Library

  
  ### step 2
pip install scapy

cd C:\Users\tahir\Desktop
python first.py

 ### Step 3: Generate Traffic
Open browser or use:

bash
Copy
Edit
ping google.com

 Sample Output
yaml
Copy
Edit
============================================================
[+] TCP Packet Captured - 2025-06-29 21:48:12
    Source IP     : 192.168.100.10
    Dest IP       : 172.64.155.209
    Source Port   : 53215
    Dest Port     : 80
    Flags         : S
    Payload       : GET / HTTP/1.1...


