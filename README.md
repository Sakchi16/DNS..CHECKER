# DNS..CHECKER
This project is a graphical tool for analyzing and verifying DNS records using Python. It combines the power of Scapy, a packet manipulation library, to send and analyze DNS queries, with Tkinter, a user-friendly GUI library, to create an intuitive interface for users. 

Overview of the Tool:
Python-based tool with Scapy for network sniffing and Tkinter for user interaction.

Core Workflow:
Interface Selection: User chooses a network adapter for monitoring.
Packet Sniffing: Real-time analysis of DNS packets (UDP port 53).
DNS Query Validation: Compares IP addresses in packets with
responses from Google’s DNS server (8.8.8.8).

Detection and Alerts: Notifies the user via a GUI if spoofing is detected.

Logging: Records all detected queries and spoofing attempts for analysis.

Key Features:

Lightweight, real-time operation.
GUI-based user interaction for accessibility.
Comprehensive logging for security audits.
Technologies Used: Python libraries (Scapy, Tkinter), and logging modules.
Significance: Enhances security for small networks without advanced
hardware.
![image](https://github.com/user-attachments/assets/8babe6bb-49cf-49a6-9144-f161cc9c241a)

