# Firewall

## What is a Firewall?

A **firewall** is a network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules. It acts as a barrier between a trusted internal network (like your home or corporate network) and untrusted external networks (like the Internet), protecting your systems from unauthorized access, malware, and cyber attacks.

---

## Key Functions of a Firewall

1. **Packet Filtering:**  
   Examines data packets entering or leaving the network and allows or blocks them based on source/destination IP address, port number, or protocol.

2. **Stateful Inspection:**  
   Keeps track of the state of active connections and makes decisions based on the context of the traffic, not just individual packets.

3. **Proxy Service:**  
   Acts as an intermediary between users and the services they access, hiding the true network addresses.

4. **Network Address Translation (NAT):**  
   Hides internal IP addresses by translating them to a single public IP, enhancing security.

5. **Monitoring & Logging:**  
   Records traffic data for analysis, helping detect suspicious activity.

---

## Types of Firewalls

1. **Packet-Filtering Firewall:**  
   Works at the network layer and examines packets individually. Simple and fast but limited in advanced security.

2. **Stateful Firewall:**  
   Tracks active connections and ensures packets are part of valid sessions. More secure than packet-filtering firewalls.

3. **Proxy Firewall:**  
   Operates at the application layer, intercepting requests between clients and servers. Provides strong security but may reduce speed.

4. **Next-Generation Firewall (NGFW):**  
   Combines traditional firewall functions with features like intrusion prevention, application awareness, and malware detection.

---

## Use Cases

- Protecting corporate networks from external attacks  
- Securing personal devices from malware and unauthorized access  
- Controlling employee access to the internet in enterprises  
- Logging and monitoring traffic for compliance and forensic purposes

---

## Advantages

- Blocks unauthorized access to networks  
- Monitors and logs network activity  
- Protects against viruses, worms, and other cyber threats  
- Can enforce corporate security policies  

---

## Limitations

- Cannot protect against threats inside the network (insider threats)  
- Misconfigured firewalls can block legitimate traffic  
- Some advanced attacks can bypass firewalls
