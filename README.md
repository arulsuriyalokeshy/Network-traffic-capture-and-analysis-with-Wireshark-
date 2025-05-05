# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network packets using Wireshark, in order to inspect data flows, identify protocols, and detect any suspicious or unusual network behavior.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.


## PROCEDURE:
1. Open Wireshark and Select a Network Interface
• Launch Wireshark.
• Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.

2. Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.

3. Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter
bar to narrow down results.

4. Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,
IP, TCP/UDP layers, and data payload.

5. Export or Save the Capture
• Go to File > Save As to store the capture in .pcap format for future analysis.

## OUTPUT:
**Open Wireshark and Select a Network Interface**
![image](https://github.com/user-attachments/assets/bd32d5ca-13e1-4923-8590-207e32e12ced)


**Start Capturing Packets**
![image](https://github.com/user-attachments/assets/d315e201-72d2-4b8a-9e81-2b02e203ed56)


**Apply Filters to Focus on Specific Traffic**

![image](https://github.com/user-attachments/assets/f275c6be-ffb4-435f-b774-98b558ef18dc)


**Analyze Packet Details**
![image](https://github.com/user-attachments/assets/66b400b9-45cb-4fe3-a482-605e5caf80a5)




**Export or Save the Capture**
![image](https://github.com/user-attachments/assets/582f1b2c-bdcc-48a9-90e5-1659f17f48be)


## RESULT:
Wireshark was used to successfully capture and analyze real-time network traffic.

