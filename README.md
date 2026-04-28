
<img width="1774" height="887" alt="0a9f17f3-8d4e-4dee-8c23-1c3c3ef10409" src="https://github.com/user-attachments/assets/be45dc88-577c-4f43-bdf2-471d9a85776a" />

#  Wireshark Network Analysis Lab


This project demonstrates how I used Wireshark to analyze real network traffic and understand how DNS, TCP, and HTTPS work together.

---

## What I Did

- Captured live network traffic using Wireshark
- Filtered DNS traffic to observe domain lookups
- Analyzed TCP 3-way handshake (SYN, SYN-ACK, ACK)
- Followed TCP streams to inspect HTTPS traffic
- Used terminal commands (nslookup, curl) to generate traffic

---

## Skills Demonstrated
- Packet capture and filtering
- DNS traffic analysis
- TCP three-way handshake analysis
- HTTPS/TLS traffic inspection
- Terminal-based traffic generation
- Basic network troubleshooting

---

##  Screenshots

### 1. Wireshark Capture Interface
This shows the main Wireshark interface where network traffic is captured and analyzed in real time.

<img width="2048" height="797" alt="wireshark-interface" src="https://github.com/user-attachments/assets/5983baac-c504-4e9f-809e-f0ae01d565c1" />

---

### 2. DNS Traffic Analysis
This shows DNS queries being sent to resolve domain names into IP addresses before connecting to a website.

![dns](https://github.com/user-attachments/assets/39d413e5-f979-4f06-945e-5976ead94381)

---

### 3. DNS Query Analysis
This shows the details of a DNS packet, including the requested domain and the response from the DNS server.

![dns-details](https://github.com/user-attachments/assets/c8a721e1-b820-474c-8a61-12955b8c61c3)

---

### 4. TCP 3-Way Handshake
This shows the TCP three-way handshake (SYN, SYN-ACK, ACK) used to establish a connection between devices.

![tcp](https://github.com/user-attachments/assets/09cd9a62-0905-4ef1-9570-d845cc54a6b7)

---

### 5. HTTPS / TLS Traffic Analysis
This shows the TLS handshake process where encryption is established for secure HTTPS communication.

![tls](https://github.com/user-attachments/assets/083a7fbd-2559-411b-b67a-09b411f0ff7e)

---

### 6. Follow TCP Stream (encrypted data)
This shows a TCP stream where data between the client and server can be followed, including encrypted traffic.

![stream](https://github.com/user-attachments/assets/111dda7c-d9f8-4c3c-81e0-4c960d492309)

---

### 7. Terminal Validation (nslookup + curl)
This shows terminal commands used to generate and verify network traffic, including DNS lookups and HTTP requests.

![terminal](https://github.com/user-attachments/assets/f89def17-c3cb-4414-a901-d5434e2d20aa)

---

### 8. Follow TCP Stream (HTTP Conversation)
Captured and followed a TCP stream to analyze the full HTTP conversation between client and server.



##  Tools Used

- Wireshark
- macOS Terminal
- nslookup
- curl

---

##  Summary

This lab helped me understand how real network communication works behind the scenes. I gained hands-on experience analyzing packets and identifying key protocols used in everyday internet activity.
