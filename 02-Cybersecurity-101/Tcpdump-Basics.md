# TCP Dump Basics

> Personal study notes from TryHackMe / Cybersecurity 101.

## Basic packet capture

| tcpdump -i INTERFACE | Captures packets on a specific network interface |
| --- | --- |
| tcpdump -ip a s | list the available ip interface |
| tcpdump -w file | Writes captured packets to a file and the file extension is mostly use is .pcap |
| tcpdump -r file | to reads packets from a file |
| tcpdump -c count | Limit the Number of Captured Packets |
| tcpdump -n | don’t resolve IP addresses |
| tcpdump -nn | Don’t resolve IP addresses and don’t resolve protocol numbers |
| tcpdump -v | Verbose display; verbosity can be increased with vv and vvv |

## filtering Expressions

| tcpdump host IP or tcpdump host HOSTNAME | Filters packets by IP address or hostname |
| --- | --- |
| tcpdump src host IP | Filters packets by a specific source host |
| tcpdump dst host IP | Filters packets by a specific destination host |
| tcpdump port PORT_NUMBER | Filters packets by port number |
| tcpdump src port PORT_NUMBER | Filters packets by the specified source port number |
| tcpdump dst port PORT_NUMBER | Filters packets by the specified destination port number |
| tcpdump protocols | Filters packets by protocol; examples include ip, ip6, and icmp |
