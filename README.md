# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## Objective
To capture live network packets using Wireshark, identify different network protocols, and analyze basic traffic types for understanding network communication.

## Tools Used

- Wireshark – Open-source network protocol analyzer.
- Operating System – Windows/Linux.
- Internet Connection – For generating network traffic.

## Steps Performed

# Step 1 - Install Wireshark:
Download Wireshark from https://www.wireshark.org.
Install with default settings and ensure “WinPcap” or “Npcap” is selected for packet capture.

# Step 2 – Start Packet Capture
Open Wireshark.
Select the active network interface (e.g., Wi-Fi, Ethernet).
Click on the blue shark fin icon to start capturing.

# Step 3 – Generate Network Traffic
Open a web browser and visit multiple websites (e.g., google.com, wikipedia.org).
Ping a public server
**ping 8.8.8.8**

# Step 4 – Stop Capture

Let the capture run for ~1 minute.
Click the red square icon to stop.

# Step 5 – Apply Filters

Examples:
http → Show HTTP packets.
dns → Show DNS query packets.
tcp → Show TCP packets.

# Step 6 – Identify Protocols
At least 3 observed protocols:

HTTP – Web traffic protocol.
DNS – Domain name resolution protocol.
TCP – Reliable transport protocol.

# Step 7 – Export Capture File

File → Save As → Select .pcapng format

## Results:
Packet capture file: network_capture.pcapng
Report: Wireshark_Analysis_Report.pdf

