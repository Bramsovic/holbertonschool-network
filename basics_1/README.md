# 🌐 Networking Basics #1

> Master essential networking skills with simple yet powerful Bash scripts for IP management and port listening.

---

## 📚 Project Overview

This project covers fundamental networking concepts, including IP address management, hosts file configuration, and port listening on **Ubuntu 22.04**. You'll write Bash scripts to manipulate network settings, display active IP addresses, and set up basic socket communication.

---

## 🎯 Learning Objectives

By the end of this project, you should be able to explain:

- **localhost / 127.0.0.1**  
- **0.0.0.0** and its significance  
- The **/etc/hosts** file and its role  
- How to display your machine’s active network interfaces  

---

## 🛠️ Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- Tested on **Ubuntu 22.04**
- All scripts must:
  - Be executable
  - Pass **Shellcheck** (version **0.7.0**)
  - Start with `#!/usr/bin/env bash`
  - Include a comment on the second line explaining the script's purpose
- All files should end with a **new line**

---

## 📁 Project Structure

```
basics_1/
├── 0-change_your_home_IP         # Configure localhost and facebook.com IPs
├── 1-show_attached_IPs           # Display all active IPv4 addresses
├── 2-port_listening_on_localhost # Set up a port listener on localhost
└── README.md                     # Project documentation
```

### 📄 File Descriptions

- **0-change_your_home_IP**  
  - Configures the `/etc/hosts` file to:
    - Resolve **localhost** to `127.0.0.2`
    - Resolve **facebook.com** to `8.8.8.8`

- **1-show_attached_IPs**  
  - Displays all active **IPv4** addresses on the machine.

- **2-port_listening_on_localhost**  
  - Sets up a **TCP** listener on port **98** of **localhost**.

- **README.md**  
  - Main project documentation, including learning objectives, requirements, and task descriptions.

---

## 📎 Resources

Make sure to review:

- [What is localhost](https://en.wikipedia.org/wiki/Localhost)  
- [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)  
- [What is the hosts file](https://en.wikipedia.org/wiki/Hosts_(file))  
- [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)  
- `ifconfig`, `telnet`, `nc`, `cut` (use `man` or `help` for more info)

---

## 🧑‍💻 Author

**Holberton School**  
Networking Basics Project

---
