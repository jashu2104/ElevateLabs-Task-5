# Wireshark Traffic Analysis - Cyber Security Internship Task

## 📌 Objective
Capture and analyze live network traffic using Wireshark. Identify different protocols and summarize packet details.

---

## 🔧 Tools Used
- **Wireshark** (network protocol analyzer)
- **Windows/Linux/Mac** (supported OS)

---

## 📡 Steps Performed
1. Installed Wireshark on the system.
2. Started capture on the active network interface (Wi-Fi).
3. Generated traffic:
   - Browsed websites in a browser.
   - Used `ping` to reach external servers.
4. Stopped the capture after ~1 minute.
5. Applied filters (`dns`, `tcp`, `udp`, `http`) to identify protocols.
6. Exported capture as `Wireshark-captures.pcapng`.

---

## 📊 Protocols Identified
1. **DNS (Domain Name System)**  
   - Used to resolve domain names into IP addresses.  
   - Example: Query for `google.com` → response with IP address.  

2. **TCP (Transmission Control Protocol)**  
   - Provides reliable, connection-oriented communication.  
   - Example: Observed TCP 3-way handshake (SYN → SYN/ACK → ACK).  

3. **UDP (User Datagram Protocol)**  
   - Lightweight, connectionless communication.  
   - Example: DNS queries/responses over UDP port 53.  

4. **HTTP/HTTPS (Hypertext Transfer Protocol)**  
   - Used for web traffic.  
   - Example: HTTP GET requests visible; HTTPS encrypted traffic also observed.  

---

## 📂 Sample Packet Details
- **DNS Query:**  
  `Standard query A google.com → 8.8.8.8`  

- **TCP Handshake:**  
  `Client SYN → Server SYN/ACK → Client ACK`  

- **HTTP Request:**  
  `GET /index.html HTTP/1.1`  

---

## 🎯 Outcome
- Learned how to capture, filter, and analyze network traffic.  
- Identified common internet protocols (DNS, TCP, UDP, HTTP/HTTPS).  
- Gained practical understanding of packet-level communication.

---

## 📤 Deliverables
- `Wireshark-captures.pcapng` (packet capture file)  
- `README.md` (this report)  
- Screenshots of packet filters (optional)  

---

## 🔗 Submission
Upload this repository to GitHub and share the repo link in the provided Google Form.
