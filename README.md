# Network Packet Sniffer
The Network Packet Sniffer is a Python-based tool that captures and analyzes network packets in real-time. This tool uses the scapy library to sniff packets and extract information about the source and destination IP addresses, protocol, and payload.

# Features:

Packet Capture: The tool captures network packets in real-time, allowing for instant analysis.
IP Address Extraction: The tool extracts the source and destination IP addresses from each packet.
Protocol Identification: The tool identifies the protocol used in each packet (e.g., TCP, UDP, ICMP).
Payload Analysis: The tool attempts to decode and display the payload of TCP and UDP packets.
Real-time Output: The tool prints the extracted information to the console in real-time.

# How to Use:

Run the Script: Run the Python script to start the packet sniffer.
Packet Capture: The tool will start capturing and analyzing network packets in real-time.
View Output: The tool will print the extracted information to the console, including source and destination IP addresses, protocol, and payload (if decodable).
Note: This tool is for educational purposes only and should not be used to intercept or analyze network traffic without permission.

# System Requirements:

Operating System: The tool can run on Windows, macOS, and Linux operating systems.
Python: The tool requires Python to be installed on the system.
Scapy Library: The tool requires the scapy library to be installed.

# How To Install

git clone https://github.com/hac6326/Prasunet_SC_05.git

cd Prasunet_SC_05

python3 Network_Packet_Analyzer.py
