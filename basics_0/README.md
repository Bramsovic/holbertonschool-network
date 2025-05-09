# Basics of Computer Networking

> A foundational project to understand networking concepts including the OSI model, IP addresses, TCP/UDP protocols, and basic Bash networking scripts.  
> **By Holberton School**

---

## 📚 Description

This project covers the fundamental concepts of computer networking, including:

- The OSI model and its 7 layers
- Different types of networks (LAN, WAN, Internet)
- MAC and IP addresses
- TCP and UDP protocols
- Network ports
- Basic Bash networking tools and scripts

---

## 🎯 Learning Objectives

By the end of this project, you should be able to explain:

### OSI Model
- What the OSI model is
- The 7 layers of the OSI model
- How the OSI model is organized

### Network Types
- What is a **LAN**
- What is a **WAN**
- What is the **Internet**

### IP Addresses
- What is an IP address
- The difference between public and private IP addresses
- What is **localhost**
- What is a **subnet**
- Why **IPv6** was created

### TCP/UDP
- The two main data transfer protocols for IP
- The difference between TCP and UDP
- Common port numbers (SSH, HTTP, HTTPS)
- How to check if a device is connected to a network

---

## 🛠️ Requirements

- Bash script files
- Allowed editors: `vi`, `vim`, `emacs`
- Files must:
  - Be executable
  - Pass `shellcheck` without errors
  - Start with `#!/usr/bin/env bash`
  - Include a comment explaining the script on the second line
- All scripts should work on **Ubuntu 22.04**

---

## 📁 Project Structure
```
basics_0/
├── 0-OSI_model                     # OSI model basics (text answer)
├── 1-types_of_network             # Network types: LAN, WAN, Internet (text answer)
├── 2-MAC_and_IP_address           # MAC and IP address basics (text answer)
├── 3-UDP_and_TCP                  # Understanding TCP and UDP protocols (text answer)
├── 4-TCP_and_UDP_ports            # Bash script to list active network ports
├── 5-is_the_host_on_the_network   # Bash script to check if a host is online
└── README.md                      # Project documentation
```

---

## 📦 Task Descriptions

### 0. OSI Model
Understand the OSI model's purpose and structure.

### 1. Types of Network
Identify the differences between LAN, WAN, and Internet.

### 2. MAC and IP Address
Learn the differences between MAC and IP addresses.

### 3. UDP and TCP
Understand how TCP and UDP protocols differ in terms of speed and reliability.

### 4. TCP and UDP Ports
Identify and display active ports and their corresponding processes.

### 5. Is the Host on the Network
Check if a device is reachable over the network using `ping`.

---

## 🧪 Example Outputs

### OSI Model (File: `0-OSI_model`)
```
2
```

### Types of Network (File: `1-types_of_network`)
```
3
2
1
```

### MAC and IP Address (File: `2-MAC_and_IP_address`)
```
2
1
```

### UDP and TCP (File: `3-UDP_and_TCP`)
```
1
2
1
```

### TCP and UDP Ports (File: `4-TCP_and_UDP_ports`)
```bash
sudo ./4-TCP_and_UDP_ports
```
Example output:
```
tcp        0      0 *:ssh                   *:*                     LISTEN      1240/sshd
udp        0      0 *:bootpc                *:*                                 562/dhclient
```

### Is the Host on the Network (File: `5-is_the_host_on_the_network`)
```bash
./5-is_the_host_on_the_network 8.8.8.8
```
Example output:
```
PING 8.8.8.8 (8.8.8.8) 56(84) bytes of data.
64 bytes from 8.8.8.8: icmp_seq=1 ttl=63 time=12.9 ms
64 bytes from 8.8.8.8: icmp_seq=2 ttl=63 time=13.6 ms
...
```

---

## 📎 Resources

Make sure to review:

- [OSI Model](https://en.wikipedia.org/wiki/OSI_model)
- [TCP/UDP Ports List](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [MAC address](https://en.wikipedia.org/wiki/MAC_address)
- [IP address](https://en.wikipedia.org/wiki/IP_address)
- [What is ping /ICMP](https://en.wikipedia.org/wiki/Ping_(networking_utility))

---

## 🧑‍💻 Author

**Holberton School**  
Networking Fundamentals

---
