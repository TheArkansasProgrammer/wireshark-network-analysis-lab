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
