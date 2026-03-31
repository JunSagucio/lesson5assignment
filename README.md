# Home Network Documentation  
Name: Jun Santos III Sagucio  

---

## 1. Physical Topology

My home network consists of a modem connected to a router, which provides internet access to wireless devices.

Structure:
Internet → Modem → Router → Devices (WiFi)

Connected Devices:
- Laptop (WiFi)
- Smartphone (WiFi)
<img width="1536" height="1024" alt="Jun&#39;s Home Network Physical Topology" src="https://github.com/user-attachments/assets/068c87dc-ead5-4498-a357-36ff5ff2da3c" />


---

## 2. Logical Topology

The network uses a topology, where all devices connect to a central router.

- The router manages communication between devices  
- All traffic passes through the router before reaching the internet  
- Devices communicate through the router  
<img width="1536" height="1024" alt="Jun&#39;s Home Network Logical Topology" src="https://github.com/user-attachments/assets/0f94a116-6e97-48d7-9ff6-e0da12e3ad68" />



---

## 3. Addressing Documentation

*(Note: IP addresses are modified for privacy.)*

| Device       | IP Address    | MAC Address        | Connection |
|--------------|--------------|--------------------|------------|
| Router       | 192.168.0.1  | AA:BB:CC:DD:EE:01  | Ethernet   |
| Laptop       | 192.168.0.2  | AA:BB:CC:DD:EE:02  | WiFi       |
| Smartphone   | 192.168.0.3  | AA:BB:CC:DD:EE:03  | WiFi       |

- Subnet Mask: 255.255.255.0  
- Default Gateway: 192.168.0.1  
- IP Assignment: DHCP (Automatic)

---

## 4. Network Devices and Services

### Devices:
- Modem – Connects to the Internet Service Provider (ISP)  
- Router – Manages and distributes the network  
- Laptop – Personal device connected via WiFi  
- Smartphone – Mobile device connected via WiFi  

### Services:
- DHCP  – Assigns IP addresses automatically  
- DNS  – Resolves website names to IP addresses  
- WiFi – Wireless connectivity  

---

## 5. Device Configurations

### Router Configuration:
- SSID: HomeNetwork
- Security Type: WPA2-PSK
- DHCP: Enabled  
- Firewall: Enabled  

### Laptop Configuration:
- Connection: WiFi  
- IP Address: Automatic (DHCP)  
- Firewall: Enabled  

### Smartphone Configuration:
- Connection: WiFi  
- IP Address: Automatic (DHCP)  

---

## 6. Credential Security Method 

To securely store login credentials:

- Passwords are stored using a password manager (Google Password Manager)  
- Strong passwords are used (mix of uppercase, lowercase, numbers, and symbols)  
- Default router username and password are changed  
- Credentials are not shared with others  
- Two-Factor Authentication (2FA) is enabled when available  

---

## 7. Network Topology Diagram
Internet
        
Modem
        
Router

Laptop and Smartphone

---

##  Summary

This home network uses a simple topology with a router as the central device. It provides secure and efficient internet access to connected devices using DHCP and WiFi, while maintaining security through strong credentials and firewall protection.

