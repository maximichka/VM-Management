Questions:
Exercise 1 Questions
Question 1.1
What protocol does Kali use when you run traceroute against your Metasploitable host? (TIP: Try using tcpdump to investigate.) UDP

Question 1.2
What port does ping use? Ping does not use ports, instead it uses ICMP's

Question 1.3
How can you send a UDP packet to port 69 (of the Metasploitable box) using hping3? What is returned from Metasploitable as a result of this packet? Why is this the response? 
1 pack transmitted; 0 packets received, 100% packet loss - meaning i received no response in hping3  


Question 1.4
When using traceroute targeting your home router, what is the TTL of the first packet sent by traceroute? What is returned in response to this packet and from what device? –
The TTL is one, what is returned is an ICMP time exceeded message, which simply means that the packet has expired. And when doing this, it came from the
from the VMware NAT gateway at Ip address 192.168.25.2
Question 1.5
By default what ports does Nmap scan? How can you configure Nmap to scan all ports? –
By default my Kali system scans 1000 ports, 977 being closed and 23 open. To configure the nmap to scan all tcp ports, use -p- or -p0-65535.
