<img width="2048" height="797" alt="wireshark-interface" src="https://github.com/user-attachments/assets/5983baac-c504-4e9f-809e-f0ae01d565c1" />
<img width="2048" height="1151" alt="tls-handshake" src="https://github.com/user-attachments/assets/083a7fbd-2559-411b-b67a-09b411f0ff7e" />
<img width="1717" height="1399" alt="tcp-stream-analysis" src="https://github.com/user-attachments/assets/111dda7c-d9f8-4c3c-81e0-4c960d492309" />
<img width="2047" height="1153" alt="tcp-handshake" src="https://github.com/user-attachments/assets/09cd9a62-0905-4ef1-9570-d845cc54a6b7" />
<img width="2048" height="1143" alt="dns-traffic-overview" src="https://github.com/user-attachments/assets/39d413e5-f979-4f06-945e-5976ead94381" />
<img width="2048" height="1232" alt="dns-terminal-validation" src="https://github.com/user-attachments/assets/f89def17-c3cb-4414-a901-d5434e2d20aa" />
<img width="2048" height="1135" alt="dns-packet-breakdown" src="https://github.com/user-attachments/assets/c8a721e1-b820-474c-8a61-12955b8c61c3" />
# 🌐 Wireshark Network Analysis Lab

> A simple breakdown of how a website request works behind the scenes

---

## 🔄 How It Works

DNS → TCP → TLS → Secure Data

---

## 🧭 DNS (Finding the Website)

This is the first step when visiting a website.

![DNS Query](dns-query.png)

The computer sends a request to find the IP address of a domain.

![DNS Response](dns-response.png)

The DNS server responds with the IP address.

---

## 🔌 TCP (Making the Connection)

This is how a connection is created between devices.

![TCP Handshake](tcp-handshake.png)

The connection is established using:

* SYN
* SYN-ACK
* ACK

---

## 🔒 TLS (Securing the Data)

This is what makes HTTPS secure.

![TLS](tls-handshake.png)

After the connection is made, encryption begins:

* Client Hello
* Server Hello
* Encrypted communication

---

## 🧠 Key Takeaways

* DNS finds the website's IP address
* TCP creates the connection
* TLS encrypts the data

---

## 🎯 Why This Matters

Every website you visit goes through these steps.
Understanding this is important for networking and cybersecurity roles.

---

## 🚀 Built By

Justin — aspiring network engineer
