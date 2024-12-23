# pfSense Firewall Labs

## Objective
This section showcases hands-on experience with pfSense, an open-source firewall platform. Tasks include configuring VLANs, NAT, VPNs, and managing network traffic with advanced monitoring and troubleshooting techniques.

## Skills Learned
- Configuring VLANs and DHCP services.
- Setting up and managing NAT and port forwarding.
- Implementing VPN tunneling and PKI for secure communication.
- Monitoring and analyzing system logs and network interfaces.
- Troubleshooting connectivity and configuration issues.

## Tools Used
- pfSense WebGUI and CLI
- OpenVPN for VPN tunneling
- Wireshark for network analysis
- Syslog Servers for logging
- Virtualized network environments

## Tasks
Below are the key tasks performed:

### 1. VLAN and Interface Configuration
![Picture5](https://github.com/user-attachments/assets/edb78dfa-aa65-4083-9b81-c1052fe911d0)
![Screenshot 2024-12-21 143800](https://github.com/user-attachments/assets/a3ee9468-b87a-4e42-be20-a2db8299024b)
![Screenshot 2024-12-21 170613](https://github.com/user-attachments/assets/a800b75c-c995-46c2-9a27-f7ddc4792deb)
- Configured VLANs for network segmentation and better traffic management.
- Assigned and edited interfaces for specific VLANs.
- Displays real-time status of WAN, LAN, and VLAN interfaces, including traffic details, packet loss, and DNS configurations

### 7. DHCP Lease Management
![Screenshot 2024-12-21 170752](https://github.com/user-attachments/assets/c9a148df-322e-47ad-9163-40b41ebba3c7)
- Reviewed active DHCP leases, including IP assignments, MAC addresses, and lease duration.
- Verified accurate IP allocation within the LAN network using DHCP lease logs.
- Cross-checked device connectivity with real-time lease status for troubleshooting.

### 3. Traffic Monitoring and Logs
![Screenshot 2024-12-21 170507](https://github.com/user-attachments/assets/34252233-9803-48b4-bada-9204387ae4b6)
- Monitored real-time traffic on WAN and LAN interfaces.
- Analyzed system and DHCP logs for troubleshooting and optimization.

### 4. DHCP and NAT Setup
- Enabled and verified DHCP services for automatic IP assignment.
- Configured Source NAT (SNAT) and Port Forwarding to manage external connections.

### 5. VPN and PKI Implementation
- Set up site-to-site and remote-access VPN tunnels using OpenVPN.
- Configured Public Key Infrastructure (PKI) for secure authentication.

### 6. Firewall Rules Management
- Created and managed firewall rules to control traffic flow between VLANs and networks.
- Fine-tuned rules to enhance network security.

### 7. Advanced Troubleshooting
- Diagnosed configuration errors affecting NAT and VPN connectivity.
- Performed packet capture using Wireshark for deep analysis.

---

Return to the [Main Repository](https://github.com/darpanne/Firewall-Management) for other firewall and network monitoring configurations.
