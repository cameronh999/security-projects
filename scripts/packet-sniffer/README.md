# Packet Sniffer

A Python script using raw sockets (or Scapy) to capture and inspect network 
traffic in real time, displaying source/destination IPs, protocols, and payload 
summaries for each packet.

## How to run
sudo python sniffer.py --interface eth0

## What I learned
Capturing raw packets required running with elevated privileges and taught me 
how the OSI model actually looks in practice — parsing the Ethernet, IP, and 
TCP/UDP headers byte by byte instead of just reading about them.
