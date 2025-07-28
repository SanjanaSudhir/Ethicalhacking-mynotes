Sure! Here's a set of clean, formatted notes for **Day04** and **Day05** topics that you can directly upload to GitHub in a `README.md` or `.md` file format.

---

## 📘 Day04 & Day05 Networking Notes

---

### 🗓️ **DAY04 NOTES**

#### 📌 IP Address

* An **IP Address** (Internet Protocol Address) is a unique identifier assigned to each device connected to a network.
* It allows devices to locate and communicate with each other.
* Format: `192.168.1.1` (for IPv4)

---

#### 🌐 IPv4 vs IPv6

| Feature           | IPv4                      | IPv6                             |
| ----------------- | ------------------------- | -------------------------------- |
| Address Size      | 32-bit                    | 128-bit                          |
| Format            | Decimal (e.g., 192.0.2.1) | Hexadecimal (e.g., 2001\:db8::1) |
| Total Addresses   | \~4.3 billion             | \~340 undecillion                |
| Header Complexity | Less                      | More                             |
| Introduced        | 1983                      | 1998                             |

---

#### 🔁 UDP vs TCP

| Feature     | TCP (Transmission Control Protocol) | UDP (User Datagram Protocol) |
| ----------- | ----------------------------------- | ---------------------------- |
| Connection  | Connection-oriented                 | Connectionless               |
| Reliability | Reliable, guarantees delivery       | Unreliable, no guarantee     |
| Speed       | Slower due to overhead              | Faster, lightweight          |
| Use Cases   | Web (HTTP/HTTPS), FTP, Email        | Video streaming, DNS, VoIP   |

---

#### 🔐 UAC - User Access Control

* UAC is a security feature in Windows that prevents unauthorized changes to the system.
* Prompts the user for administrative permission when software or settings are changed.
* Helps prevent malware or untrusted apps from gaining full access.

---

### 🗓️ **DAY05 NOTES**

#### 🌐 What is a Network?

* A **network** is a collection of interconnected devices that can communicate and share resources (data, printers, internet).
* Types: LAN, WAN, MAN, PAN

---

#### 🛠️ NAT (Network Address Translation)

* NAT translates **private IP addresses** to a **public IP address** before packets are forwarded to the internet.
* Allows multiple devices on a local network to share one public IP.

**Example:**
Private IP (192.168.1.5) → NAT → Public IP (102.45.33.7)

---

#### 🌉 Bridge Network

* A **Bridge Network** connects multiple network segments and makes them function as a single network.
* Used in virtual machines and containers to simulate physical networks.

---

#### 🌐 Subnet

* A **subnet** is a logically visible subdivision of an IP network.
* Helps in efficient IP address allocation and improved security.

**Example:**
Network: `192.168.1.0/24`
Subnets: `192.168.1.0/26`, `192.168.1.64/26`, etc.

---

#### 🌐 TCP, UDP, HTTP, HTTPS

| Protocol | Full Form                     | Description                       |
| -------- | ----------------------------- | --------------------------------- |
| TCP      | Transmission Control Protocol | Reliable, ordered communication   |
| UDP      | User Datagram Protocol        | Fast, connectionless transmission |
| HTTP     | HyperText Transfer Protocol   | Web protocol, no encryption       |
| HTTPS    | HTTP Secure                   | HTTP over SSL/TLS (encrypted)     |

---

#### 📢 What is Broadcasting?

* **Broadcasting** sends a message from one device to all devices in a network.
* Useful for discovery protocols (like ARP).

**Example:**
Sending ARP request to all devices in the subnet.

---

#### 🆔 MAC ID (MAC Address)

* **MAC (Media Access Control) Address** is a unique identifier assigned to a network interface.
* Format: `00:1A:2B:3C:4D:5E`
* Used in LAN communication and hardware-level addressing.

---

## ✅ Summary

This document covers:

* IP fundamentals
* Networking protocols (TCP, UDP, HTTP, etc.)
* Network types and components (Bridge, Subnet, NAT)
* Security and addressing (UAC, MAC ID)


