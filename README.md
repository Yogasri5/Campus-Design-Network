# Campus-Design-Network
This project presents a comprehensive network topology design for Albion University, a large university with two campuses located 20 miles apart. The network infrastructure has been designed using Cisco Packet Tracer, following best practices in hierarchical network architecture and ensuring scalability, security, and efficient communication across departments and faculties.
🏫 Project Overview
The university comprises two campuses:
🔹 Main Campus:
Building A:

Administrative Departments: Management, HR, Finance

Faculty of Business

Use of VLANs for departmental segregation

Router-based DHCP server for dynamic IP assignment

Building B:

Faculty of Engineering and Computing

Faculty of Art and Design

Building C:

Student Labs

IT Department (hosts internal university servers including the Web Server)

External Cloud-based Email Server connectivity

🔹 Smaller Campus:
Faculty of Health and Sciences

Staff and student labs located on separate floors

Separate IP networks

⚙️ Technologies Implemented
 Cisco Packet Tracer Simulation

 Hierarchical Network Design

 Proper Device Cabling (Straight-through, Crossover, Console)

 VLAN Configuration & Port Assignment

 Inter-VLAN Routing (Router-on-a-Stick)

 Subnetting & IP Addressing (Each Faculty/Dept on Separate Subnets)

 DHCP Configuration (Router as DHCP Server)

 SSH Configuration for Secure Remote Access

 RIPv2 Routing for Internal Network

 Static Routing for Cloud-based Email Server

 Switch Port Security (MAC Binding, Port Shutdown on Violation)

 Host Device Configuration and Testing

 End-to-End Connectivity Verification (Ping, SSH, Web Server)

🧪 Testing and Verification
🧪 All VLANs tested for intra-VLAN and inter-VLAN connectivity

🧪 DHCP working in Building A

🧪 Successful SSH connections to network devices

🧪 Web server reachable from any faculty

🧪 Port-security in place to mitigate unauthorized access

🧪 Cloud email server reachable via static route

🗂️ Files Included
.pkt file (Cisco Packet Tracer project file)

Configuration notes or device CLI outputs (optional)

Subnetting and IP allocation documentation

🔐 Security Measures
Inter-VLAN routing with access controls

SSH-enabled remote access

Port-security to prevent MAC flooding or rogue devices

Router passwords and console protections

🏁 How to Use
Open the .pkt file in Cisco Packet Tracer 8.x

Start the simulation or real-time mode

Use console access or CLI to review configuration

Test connectivity (ping, web browser, SSH)

Modify or expand based on new requirements
