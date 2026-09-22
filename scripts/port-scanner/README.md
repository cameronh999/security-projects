# Port Scanner

A Python script that scans a given IP range for open TCP ports using sockets and multithreading.

## How to run
python scanner.py --target 192.168.1.1 --ports 1-1024

## What I learned
Building the multithreading logic taught me how socket timeouts behave 
under concurrent connections, and why raw sockets need root privileges on Linux.
