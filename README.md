# Wireshark Packet Capture and Analysis on Kali Linux

## Overview
This repository demonstrates the process of capturing and analyzing live network traffic using wireshark in a Kali Linux environment. The purpose of this project is to understand network protocols, packet structure, and traffic flow.


## Methodology

The following methodology was followed for capturing and analyzing network traffic:

### 1. Packet Capture and Analysis using Wireshark

Steps Performed:

1. Installed Wireshark on Kali Linux.  
2. Started packet capture on the active network interface.  
3. Browsed multiple websites to generate network traffic.  
4. Stopped the capture after one minute.  
5. Filtered captured packets by protocol (e.g., HTTP, DNS, TCP).  
6. Identified at least three different protocols in the capture.  
7. Exported the captured packets as a `.pcap` file for further analysis.  


### 2. TCP Packet Analysis

Captured TCP packets were analyzed to identify:

- Source IP and Destination IP
- Protocol Type
- Sequence Number and other TCP header details  

This provides insights into network communication and connection establishment between hosts.


## Files Included

- `capture.pcap` : Sample captured packets in `.pcap` format  
- `Wireshark_screenshots/` : Screenshots showing packet capture and protocol filtering  
  

## Tools Used

- Wireshark : Network protocol analyzer  
- Kali Linux : Operating system for cybersecurity and penetration testing  


## Observations

- Multiple protocols including HTTP, DNS, and TCP were identified.  
- The packet capture revealed source and destination IPs, ports, and sequence numbers.  
- Exporting to `.pcap` allows further detailed analysis using Wireshark or other tools.  
