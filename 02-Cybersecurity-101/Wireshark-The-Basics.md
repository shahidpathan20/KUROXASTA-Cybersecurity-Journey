# Wireshark: The Basics

> Personal study notes from TryHackMe / Cybersecurity 101.

## Tool Overview

## **Use Cases**

Wireshark is one of the most potent traffic analyser tools available in the wild. There are multiple purposes for its use:

- Detecting and troubleshooting network problems, such as network load failure points and congestion.
- Detecting security anomalies, such as rogue hosts, abnormal port usage, and suspicious traffic.
- Investigating and learning protocol details, such as response codes and payload data.

PCAP = packet capture

> *Image from the original Notion note was not copied into this Markdown file.*

## **Packet Dissection**

**The Frame (Layer 1):**This will show you what frame/packet you are looking at and details specific to the Physical layer of the OSI model.

> *Image from the original Notion note was not copied into this Markdown file.*

**Source [MAC] (Layer 2):**This will show you the source and destination MAC Addresses; from the Data Link layer of the OSI model.

> *Image from the original Notion note was not copied into this Markdown file.*

**Source [IP] (Layer 3):**This will show you the source and destination IPv4 Addresses; from the Network layer of the OSI model.

> *Image from the original Notion note was not copied into this Markdown file.*

**Protocol (Layer 4):**This will show you details of the protocol used (UDP/TCP) and source and destination ports; from the Transport layer of the OSI model.

> *Image from the original Notion note was not copied into this Markdown file.*

**Protocol Errors:**This continuation of the 4th layer shows specific segments from TCP that needed to be reassembled.

> *Image from the original Notion note was not copied into this Markdown file.*

**Application Protocol (Layer 5):**This will show details specific to the protocol used, such as HTTP, FTP,  and SMB. From the Application layer of the OSI model.

> *Image from the original Notion note was not copied into this Markdown file.*

**Application Data:** This extension of the 5th layer can show the application-specific data.

> *Image from the original Notion note was not copied into this Markdown file.*

## PACKET NAVIGATION

### **Packet Numbers**

shows the number of packets

### **Go to Packet**

Navigate to the specific packets. it will show in the GO option in toolbar

### **Find Packets**

find the packet .it will show in edit option in tollbar

### **Mark Packets**

mark the selected packets. it will show in edit option in toolbar

### **Packet Comments**

we can write comments in any packets. have to right clit on the specific packet

### **Export Packets**

we can export the packet to the other file, by selecting the packets and then use the file option in toolbar

### Expert Info

> *Image from the original Notion note was not copied into this Markdown file.*
