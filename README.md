# Purpose
To verify and document the scanning of the local network to identify active hosts and open ports using Zenmap.

#Tool Used
 Zenmap (Graphical front-end for Nmap)

# Network Scanned
 IP Range: 10.168.255.0/24

# Profile/Command Used in Zenmap
 Profile: Intense Scan
-Command Shown in Zenmap: nmap -T4 -A -v 10.168.255.0/24

# Steps Followed
1. Open Zenmap as Administrator.
2. Enter target: 10.168.255.0/24
3. Select Profile: Intense Scan
4. Click on Scan
5. Observe the output and view in Ports/Hosts, Topology, Host Details, and Scanstabs.


# Expected Output
 List of devices connected to the network
 Open ports for each IP
 Services running on those ports
 OS and version detection 

# Test Result
Hosts detected: ✅ Yes
Open ports identified: ✅ Yes
Visualization available: ✅ Topology, Services, Ports, OS info
