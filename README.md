# Cisco-Packet-Tracer-Projects
Welcome to my repository of network designs and simulations! This collection documents my journey through networking fundamentals, from basic LAN setups to complex enterprise architectures involving OSPF, VLANs, and VPNs.

🚀 Overview</br>
Each project in this repository is a .pkt file designed to demonstrate a specific networking concept or solve a particular business requirement.

🛠️ Key Concepts & Protocols</br>
Below are the core technologies implemented across these projects:

Switching: VLANs, VTP, STP (Spanning Tree Protocol), EtherChannel (LACP/PAgP).

Routing: Static Routing, RIPv2, OSPF (Single & Multi-area), EIGRP, BGP.

Security: Standard & Extended ACLs, Port Security, DHCP Snooping.

Services: DHCP, DNS, NAT (Static, Dynamic, PAT), HTTP/FTP.

Advanced: Frame Relay, VPN (IPsec), IPv6 Transitioning.

📚 Educational Context: Jeremy’s IT Lab</br>
  
  <ul>
    <li><b>CLI Proficiency</b>: Advanced configuration of Cisco IOS devices.</li>
    <li><b>Troubleshooting</b>: Identifying and fixing misconfigured trunks, incorrect subnets, and routing loops.</li>
    <li><b>Infrastructure Management</b>: Implementing HSRP for gateway redundancy and LLDP/CDP for neighbor discovery.</li>
    <li><b>Security Fundamentals</b>: Configuring SSH, Port Security, and AAA.</li>
  </ul>

📂 Project Highlights</br>
<ol>
  <li>Enterprise Multi-Floor Office Network</li>
  <ul>
  <li>Description: A 3-floor office design utilizing a collapsed core architecture.</li>
  
  <li>Key Features: Inter-VLAN routing via Router-on-a-Stick.</li>
  
  <li>DHCP server for automated IP assignment.</li>
  
  <li>Redundant links between switches using EtherChannel.</li>
  
  <li>File: Enterprise_Office_v1.pkt</li>
  </ul>

<li>Secure Branch-to-Branch VPN</li>
<ul>
  <li>Description: Connecting two remote offices over a simulated ISP cloud.</li>
  
  <li>Key Features: Site-to-Site IPsec VPN tunnel configuration.</li>
  
  <li>NAT Overload (PAT) for internet access.</li>
  
  <li>Edge router security using Extended ACLs.</li>
  
  <li>File: VPN_Site_to_Site.pkt</li>
</ul>

<li>OSPF Dynamic Routing Architecture</li>
<ul>
  <li>Description: A large-scale network divided into OSPF Area 0 and Area 1.</li>
  
  <li>Key Features: Multi-area OSPF configuration.</li>
  
  <li>Route redistribution.</li>
  
  <li>Passive interfaces for security and bandwidth optimization.</li>
  
  <li>File: OSPF_MultiArea.pkt</li>
</ul>
</ol>

📖 How to Use These Files</br>
Software: You will need Cisco Packet Tracer (v8.0 or higher recommended) to open these files.

Exploration: Open any .pkt file to view the topology.

CLI Access: You can click on any device (Router/Switch) and go to the CLI tab to inspect the running configuration using commands like:

Bash</br>
<code>show run
show ip route
show ip int brief
</code>

👤 Author</br>
Milan Thapa

LinkedIn: [https://www.linkedin.com/in/thapamilan/](https://www.linkedin.com/in/thapamilan/)
