# wireshark-network-traffic-analysis
Project overview 
-This project documents a beginner-level network traffic analysis lab using wireshark. The goal was to observe network packets and identifying networking protocols. 

Objectives
-Capturing network traffic generated during normal device use.
-identifing DNS, TCP and TLS traffic.
-understanding basic packet information and protocol behaviors
-Document observations accurately and identifying limitations 

Tools Used 
-Wireshark
-Personal computer and network connection
-GitHub for project documentation 

Methodology
-Opened Wireshark and reviewed the available network interfaces
-Captured networrk traffic from my own network activity 
-Inspected captured packets and their protocol labels
-Recovered the observed DNS, TCP, and TLS traffic
-Documented finding without assuming that unobserved packets were presented

Observde Results 
-DNS
DNS packets were identified in the capture. The specific query details have not been documented in this report
-TCP
TCP packets with (ACK) flags were identified. These packets demonstrated TCP acknowledgment activity.
-TLS
TLS pakcets labeled Application Data were identified. This is consistent with traffic carried over a TLS-protected connection; the encrypted application contents were not interpreted

Skills practiced 
-Basic packet inspection
-DNS, TCP, and TLS identification
-Networkk traffic analysis
-Technical documentation 
-Responsible handling of network data

This lab provided hands-on experience inspecting network traffic with Wireshark and documenting protocol observations. Future work can include capturing a fresh connection from its beginning and comparing the observed DNS, TCP handshake, and TLS handshake traffic.
