# What is Server?

# Server – Complete Detailed Guide

## 1. Introduction

A Server is a computer or system that provides resources, data, services, or programs to other computers (called clients) over a network.

In simple words:

Client → Request send 
Server → Response

Example:
When you open a website, your browser (client) sends a request to a web server. The server sends back the webpage.

---

## 2. How Server Works

Basic Working Process:

1. Client sends request (HTTP, FTP, etc.)
2. Server receives request
3. Server processes request
4. Server sends response

This model is called:

Client-Server Architecture

---

## 3. Types of Servers

### 3.1 Web Server

- Hosts websites
- Handles HTTP/HTTPS requests
- Example software:
  - Apache
  - Nginx
  - Microsoft IIS

Used for:
- Websites
- Web applications

---

### 3.2 File Server

- Stores and manages files
- Allows multiple users to access shared files
- Used in offices and organizations

---

### 3.3 Database Server

- Stores and manages databases
- Handles queries from applications
- Examples:
  - MySQL
  - PostgreSQL
  - Oracle Database

---

### 3.4 Mail Server

- Sends and receives emails
- Uses:
  - SMTP (Sending)
  - POP3 / IMAP (Receiving)

---

### 3.5 DNS Server

- Converts domain names to IP addresses
Example:
google.com → 142.250.x.x

---

### 3.6 Application Server

- Runs backend applications
- Handles business logic
- Used in enterprise systems

---

## 4. Server Hardware Components

A physical server typically includes:

- High-performance CPU
- Large RAM
- RAID Storage (for data safety)
- Redundant Power Supply
- Network Interface Cards (NIC)

Servers are built for:

- 24/7 operation
- High reliability
- High performance

---

## 5. Types of Server Based on Structure

### 5.1 Physical Server

- Dedicated hardware machine
- Installed in data center

### 5.2 Virtual Server

- Created using virtualization software
- Multiple virtual servers run on one physical machine
- Uses Hypervisor

Examples:
- VMware
- VirtualBox
- Hyper-V

### 5.3 Cloud Server

- Hosted on cloud platform
- Scalable
- Pay-as-you-use model

Examples:
- AWS
- Google Cloud
- Microsoft Azure

---

## 6. Important Server Concepts

### 6.1 Client-Server Model

Client sends request  
Server responds  

Example:
Browser → Web Server → HTML Page

---

### 6.2 Port Numbers

Servers listen on specific ports:

- HTTP → 80
- HTTPS → 443
- FTP → 21
- SSH → 22
- MySQL → 3306

---

### 6.3 Server Operating Systems

Common Server OS:

- Linux (Ubuntu Server, CentOS)
- Windows Server

Linux is widely used in web hosting and cybersecurity.

---

## 7. Server in Cybersecurity

Servers are very important in cybersecurity because:

- Target of attacks (DDoS, SQL Injection)
- Must be hardened
- Requires firewall configuration
- Log monitoring is essential

Common attacks on servers:

- Brute Force
- DDoS
- Malware
- Exploits

Security Practices:

- Keep software updated
- Disable unused ports
- Use strong authentication
- Configure firewall
- Use IDS/IPS

---

## 8. Basic Practical Commands

### Check Open Ports (Linux)

~~~
netstat -tulnp
~~~

### Start Apache Server (Linux)

~~~
sudo systemctl start apache2
~~~

### Check Server IP

~~~
ip addr
~~~

---

## 9. Difference Between Server and Client

| Feature | Server | Client |
|----------|--------|--------|
| Role | Provides services | Requests services |
| Power | High performance | Normal device |
| Availability | 24/7 | As needed |
| Example | Web Server | Browser |

---

## 10. Real World Example

When you open YouTube:

1. Browser sends request
2. YouTube server processes it
3. Server sends video data
4. Browser displays video

Without servers, internet cannot function.

---

## 11. Conclusion

A server is the backbone of networking and the internet.

It:

- Provides services
- Stores data
- Handles client requests
- Enables communication

Understanding servers is essential for:

- Networking
- Cybersecurity
- Ethical hacking
- Web development
