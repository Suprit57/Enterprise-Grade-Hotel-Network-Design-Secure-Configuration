
## **📡 Project Title**

#**Enterprise-Grade Hotel Network Infrastructure Design & Implementation**


This project involved creating a **modern, secure, and reliable computer network** for a hotel that has multiple departments — **Reception**, **Guest Rooms**, **Restaurant**, **Administration**, and **Security**. The goal was to ensure that **all departments could communicate efficiently**, share resources when needed, and **stay protected from security threats**.

We started by **planning the entire network structure**. Each department was placed in its **own virtual network** (called a **VLAN** – Virtual Local Area Network). This ensures that, for example, the Security department’s systems are kept separate from the Guest Wi-Fi, so **private data stays safe** and network traffic doesn’t get congested.

To allow controlled communication **between these VLANs**, we used a method called **Inter-VLAN Routing** (Router-on-a-Stick). This setup lets different departments talk to each other **only when necessary**, while keeping other data isolated.

The **IP addressing scheme** was carefully designed so that every device — from hotel reception computers to restaurant billing systems — has its own **unique and logically assigned address**. This makes it **easier to manage**, locate, and troubleshoot devices on the network.

For ease of management, a **DHCP server** was set up to **automatically assign IP addresses** to devices when they connect, saving time and avoiding manual mistakes.

To ensure the network can be **managed securely from anywhere**, **SSH (Secure Shell)** was enabled for encrypted remote access. **Telnet** was used during the setup stage to verify device connectivity, although SSH is preferred for security in real-world operation.

We implemented **port security** on the switches so that only authorized devices can connect. This stops outsiders from plugging in their own devices to access the hotel’s network.

Finally, we set up **redundancy and failover routes**. This means if one link or path fails, the network will **automatically switch to a backup route** so that guests and staff experience **no downtime** — crucial for a 24/7 operation like a hotel.



## **💡 Why This Matters**

* **For Guests** → Smooth, fast, and secure internet access.
* **For Staff** → Reliable systems for booking, billing, and communication.
* **For Security Department** → Isolated and protected systems.
* **For Management** → Easier control, monitoring, and troubleshooting.



## **📌 Key Features Implemented**

* **VLAN Segmentation** for security and traffic control
* **Inter-VLAN Routing** (Router-on-a-Stick) for controlled communication
* **Structured IP Addressing** for easy management
* **DHCP Server** for automatic IP allocation
* **SSH Remote Access** for secure management
* **Telnet Testing** for connectivity verification
* **Port Security** to block unauthorized devices
* **Redundancy & Failover Routes** for uninterrupted service



## **📜Summary

Designed and deployed a **secure, scalable hotel network** connecting all departments with isolated VLANs and controlled routing. Automated IP allocation via DHCP and secured management through SSH. Applied port security to prevent unauthorized access. Ensured high availability with redundancy and failover routes for 24/7 service reliability.

