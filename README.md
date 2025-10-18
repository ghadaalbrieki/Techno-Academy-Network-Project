Techno Academy Network Project

📘 Overview
This project is a simulation of a network for a technical education institute called Techno Academy.
It includes three branches: Muscat (main branch), Salalah, and Sohar. Each branch has multiple VLANs to separate users into IT, Staff, Teachers, Students, and Guests. The main branch hosts core servers for DHCP, DNS, Web, Email, NTP, and Syslog, while other branches have DHCP servers to manage IP addresses.

🖥️ Network Components

3 Branch Routers

Multiple Switches in each branch

DHCP Servers

DNS, Web, Email, NTP, Syslog Servers (Main branch)

Multiple PCs per VLAN

🗺️ VLAN Distribution

VLAN	Purpose	Branches
10	IT	All branches
15	Staff	All branches
20	Teacher	All branches
30	Student	All branches
40	Guest	All branches

⚙️ Configuration Highlights

VLANs created on all switches and assigned to access ports.

Trunk ports configured for inter-switch communication.

DHCP configured per VLAN to automatically assign IPs.

Core services (DNS, Web, Email, NTP, Syslog) configured at the main branch.

All branches are interconnected for communication and resource sharing.

✅ Testing & Results

VLAN separation works correctly for all user types.

DHCP assigns IP addresses in each VLAN correctly.

PCs can communicate within VLANs and between branches.

Core services are reachable from all branches.

📁 Included Files

File Name	Description
TechnoAcademy.pkt	Cisco Packet Tracer network file
screenshot.png	Image of the network design
README.md	Project documentation
