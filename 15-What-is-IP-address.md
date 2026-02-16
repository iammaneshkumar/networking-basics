# IP Address – Complete Detailed Notes

## 1. Introduction

An IP (Internet Protocol) Address is a unique numerical identifier assigned to every device connected to a network that uses the Internet Protocol for communication.

It performs two main functions:

- Identification of a device (Host Identification)
- Location addressing for routing packets

Without IP addressing, devices cannot communicate over the internet or private networks.

---

## 2. Versions of IP Address

### 2.1 IPv4 (Internet Protocol Version 4)

- 32-bit address
- Written in dotted decimal format
- Example: 192.168.1.1
- Total possible addresses: 2^32 (≈ 4.3 billion)

#### Structure of IPv4

IPv4 consists of 4 octets.  
Each octet = 8 bits  
Range of each octet = 0 to 255  

Example:

192.168.1.1

Binary Representation:

192 = 11000000  
168 = 10101000  
1   = 00000001  
1   = 00000001  

Total bits = 32

---

### 2.2 IPv6 (Internet Protocol Version 6)

- 128-bit address
- Written in hexadecimal format
- Example: 2001:0db8:85a3:0000:0000:8a2e:0370:7334
- Total addresses: 2^128

#### Advantages of IPv6

- Very large address space
- Built-in IPsec support
- Improved routing efficiency
- No need for NAT
- Better header design

---

## 3. Types of IP Address

### 3.1 Public IP Address

- Assigned by ISP
- Globally unique
- Used for communication over the internet

### 3.2 Private IP Address

Used inside local networks.  
Not directly accessible from the internet.

#### Private IPv4 Ranges (RFC 1918)

- 10.0.0.0 – 10.255.255.255
- 172.16.0.0 – 172.31.255.255
- 192.168.0.0 – 192.168.255.255

---

## 4. Static vs Dynamic IP

### Static IP

- Manually configured
- Does not change
- Used for servers, routers, CCTV, etc.

### Dynamic IP

- Automatically assigned by DHCP
- Changes periodically
- Common for home users

---

## 5. IPv4 Address Classes

### Class A
Range: 1.0.0.0 – 126.255.255.255  
Default Subnet Mask: 255.0.0.0  

### Class B
Range: 128.0.0.0 – 191.255.255.255  
Default Subnet Mask: 255.255.0.0  

### Class C
Range: 192.0.0.0 – 223.255.255.255  
Default Subnet Mask: 255.255.255.0  

### Class D
Range: 224.0.0.0 – 239.255.255.255  
Used for Multicast  

### Class E
Range: 240.0.0.0 – 255.255.255.255  
Reserved for experimental use  

---

## 6. Subnet Mask and CIDR

A subnet mask divides an IP address into:

- Network Portion
- Host Portion

Example:

IP Address: 192.168.1.10  
Subnet Mask: 255.255.255.0  

Network ID: 192.168.1.0  
Host ID: 10  

### CIDR Notation

192.168.1.0/24  

Meaning: First 24 bits are used for network portion.

---

## 7. Important Networking Concepts

### NAT (Network Address Translation)

Allows multiple private IP addresses to use a single public IP address.

### DHCP (Dynamic Host Configuration Protocol)

Automatically assigns IP addresses to devices.

### DNS (Domain Name System)

Converts domain names into IP addresses.

Example:
google.com → 142.250.183.206

---

## 8. Role of IP Address in Cybersecurity

IP addressing is very important in cybersecurity because:

- Used in network scanning (Nmap)
- Packet analysis (Wireshark)
- Firewall configuration
- Intrusion detection
- Log tracing of attackers

Understanding IP addressing is fundamental for ethical hacking and penetration testing.

---

## 9. Practical Commands

### Windows

```
ipconfig
```

### Linux

```
ifconfig or ip a
```

or

```
ip addr
```

---

## 10. Conclusion

IP Addressing is the foundation of networking.

It enables:

- Device identification
- Communication between networks
- Routing of data packets

Mastering IP concepts is essential for networking, cybersecurity, and penetration testing professionals.
