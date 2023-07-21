<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Download Wireshark
- Create Virtual machines
- User commands in command prompt and PowerShell to monitor traffic
- Filter out specific pathways in Wireshark to view specific traffic

<h2>Actions and Observations</h2>

<h3>Monitor traffic with Wireshark and Powershell</h3>
<p>
<img src="https://i.imgur.com/HGgWRAt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can use Wireshark as well as Powershell to monitor traffic between the two virtual machines you created. Using the filters in wireshark allows you to monitor specific traffic from your pings in powershell. 
</p>
<br />
