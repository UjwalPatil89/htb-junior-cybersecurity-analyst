\# Day 4 – DNS, Routing, and IP Concepts



\## Overview

This day focused on understanding how network traffic is resolved and routed across networks, with emphasis on DNS, IP addressing, gateways, and routing behavior.



---



\## 1. Domain Name System (DNS)



DNS translates human-readable domain names into IP addresses that computers can understand.



\### Example

\- google.com → 142.250.x.x



\### DNS Resolution Process

1\. Browser cache

2\. Operating System cache

3\. Router cache

4\. ISP DNS resolver

5\. Root DNS server

6\. TLD DNS server

7\. Authoritative DNS server



\### Common DNS Record Types

\- \*\*A\*\* – Maps domain to IPv4 address  

\- \*\*AAAA\*\* – Maps domain to IPv6 address  

\- \*\*CNAME\*\* – Alias record  

\- \*\*MX\*\* – Mail server record  

\- \*\*NS\*\* – Name server record  



---



\## 2. IP Addressing



\### IPv4

\- 32-bit address

\- Written in dotted decimal format



\### Public vs Private IP

\- \*\*Public IP\*\*: Routable on the internet

\- \*\*Private IP\*\*: Used inside internal networks



\#### Private IP Ranges

\- 10.0.0.0 – 10.255.255.255

\- 172.16.0.0 – 172.31.255.255

\- 192.168.0.0 – 192.168.255.255



---



\## 3. Default Gateway



\- The gateway is the exit point of a local network

\- Usually the router

\- All traffic destined outside the local network is forwarded to the gateway



---



\## 4. Routing



\- Routing determines the path a packet takes to reach its destination

\- Decisions are based on the routing table

\- Default route handles unknown destinations



---



\## Commands Practiced



```bash

ipconfig

ip route

ping google.com

nslookup google.com

tracert google.com



