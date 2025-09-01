

DNS Resolution – Iterative and Recursive Lookup

This repository contains my implementation of a DNS resolution system as part of the CS425: Computer Networks course. The project explores how human-readable domain names are translated into IP addresses using both iterative and recursive resolution mechanisms.

The objective of this project was to gain hands-on experience with DNS querying, protocol understanding, and network programming by building a resolver in Python with the dnspython library.

Project Objectives

* Implement an iterative resolver that queries root, TLD, and authoritative servers step by step until an IP address is resolved.
* Implement a recursive resolver that delegates the full resolution process to an external resolver and directly returns the final result.
* Handle common error scenarios such as timeouts, unreachable servers, and non-existent domains.
* Provide a command-line interface to choose the resolution mode and input the domain name.

Key Learnings

* Practical understanding of the Domain Name System hierarchy and resolution process.
* Differences between iterative and recursive lookup strategies.
* Error handling and debugging in real network environments.
* Strengthened Python programming skills with dnspython and socket-based querying.

Repository Contents

* dns\_resolver.py – Implementation of both iterative and recursive DNS lookup.
* README.md – Documentation and instructions for running the resolver.

How to Run

1. Install dependencies: pip install dnspython
2. Run iterative lookup: python3 dns\_resolver.py iterative example.com
3. Run recursive lookup: python3 dns\_resolver.py recursive example.com

Example Output
Iterative DNS Lookup: google.com -> 142.250.194.78
Recursive DNS Lookup: google.com -> 172.217.167.206

This project provided valuable insights into one of the most fundamental components of the internet infrastructure and strengthened my understanding of protocol-level operations in computer networks.



Would you like me to also **combine both assignments (A2: DNS + A3: TCP Handshake)** into a single GitHub repo with a **top-level README** describing both projects together as your networking portfolio?
