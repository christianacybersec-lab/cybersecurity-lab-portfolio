# Lab 002: Wireshark Network Traffic Analysis

**Date:** October 22, 2026  
**Difficulty:** Beginner  
**Lab Type:** Guided Hands-On Exercise  
**Tools:** Wireshark 4.6.9, Npcap 1.88  
**Operating System:** Windows 11

## 1. Objective

The objective of this lab was to gain introductory experience with Wireshark by capturing and examining network traffic.

I wanted to understand how network protocols operate in real-world communication rather than relying solely on textbook definitions.

## 2. Lab Environment

- Personal Windows 11 laptop
- Wireshark 4.6.9
- Npcap 1.88
- Wi-Fi network interface
- Live network packet capture

## 3. Activities Performed

### Part 1: Wireshark Installation and Configuration

Installed Wireshark and Npcap on my Windows 11 laptop.

Identified available network interfaces and selected the active Wi-Fi interface for packet capture.

### Part 2: Capturing Network Traffic

Captured live network traffic and identified several protocols, including:

- TCP (Transmission Control Protocol)
- TLS (Transport Layer Security) 1.3
- ARP (Address Resolution Protocol)
- SSDP (Simple Service Discovery Protocol)

Practiced using Wireshark display filters to isolate specific network protocols.

### Part 3: ARP Analysis

Examined ARP requests and responses to understand how devices identify MAC addresses associated with IPv4 addresses on a local network.

Observed the difference between an ARP request asking for a device's MAC address and an ARP message providing an IP-to-MAC address association.

### Part 4: TCP Three-Way Handshake

Identified and traced a TCP three-way handshake:

1. **SYN** — Connection request
2. **SYN-ACK** — Server acknowledgment
3. **ACK** — Connection established

Examined source and destination IP addresses, TCP ports, and packet direction.

### Part 5: TLS 1.3 Analysis

Located a TLS 1.3 Client Hello message after the TCP connection was established.

Expanded the TLS packet details and identified the cipher suites section.

Learned that the Client Hello advertises cryptographic options supported by the client and that further negotiation is required to establish a secure TLS session.

## 4. Key Findings

- Network communication can be investigated through individual packets.
- ARP helps resolve IPv4 addresses to MAC addresses on a local network.
- TCP uses a three-way handshake to establish a connection.
- TCP source and destination ports help identify communication endpoints.
- TLS negotiates security parameters to protect network communication.
- Wireshark display filters make it easier to investigate specific protocols and packets.

## 5. Challenges Encountered

As a beginner, I initially found the Wireshark interface and packet filtering unfamiliar.

I experienced difficulty locating related packets and interpreting certain display filter results.

With step-by-step guidance, I learned to distinguish between invalid display filters and valid filters that returned no matching packets.

I also practiced tracing a TCP connection by examining packet direction, ports, and TCP flags.

## 6. Skills Practiced

- Network packet capture
- Network interface identification
- Basic Wireshark navigation
- Display filtering
- ARP analysis
- TCP handshake identification
- Introductory TLS analysis
- Network traffic interpretation

## 7. Reflection

This lab helped me connect networking theory to actual network communication.

One of the most interesting parts was observing devices exchange ARP messages and tracing the TCP three-way handshake.

Although navigating Wireshark required guidance, I was able to identify real network protocols and better understand how devices communicate.

This exercise reinforced my interest in technical cybersecurity work, particularly network traffic analysis and Security Operations Center (SOC) investigations.

## 8. Next Steps

- Continue practicing Wireshark display filters
- Examine additional TLS handshake messages
- Practice identifying DNS queries and responses
- Learn to recognize normal versus potentially suspicious network traffic
- Continue developing practical network analysis skills

---

**Portfolio Note:** This was a guided introductory lab conducted for educational purposes using authorized network traffic. Raw packet captures were not included to avoid exposing potentially sensitive network information.
