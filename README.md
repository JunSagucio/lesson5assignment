# 🏠 Home Network Documentation  
**Name:** Jun Santos III Sagucio  

---

## 1. Physical Topology

My home network consists of a modem connected to a router, which provides internet access to wireless devices.

**Structure:**
Internet → Modem → Router → Devices (WiFi)

**Connected Devices:**
- Laptop (WiFi)
- Smartphone (WiFi)

---

## 2. Logical Topology

The network uses a **star topology**, where all devices connect to a central router.

- The router manages communication between devices  
- All traffic passes through the router before reaching the internet  
- Devices communicate through the router  

---

## 3. Addressing Documentation

*(Note: IP addresses are modified for privacy.)*

| Device       | IP Address    | MAC Address        | Connection |
|--------------|--------------|--------------------|------------|
| Router       | 192.168.1.1  | AA:BB:CC:DD:EE:01  | Ethernet   |
| Laptop       | 192.168.1.10 | AA:BB:CC:DD:EE:02  | WiFi       |
| Smartphone   | 192.168.1.11 | AA:BB:CC:DD:EE:03  | WiFi       |

- Subnet Mask: 255.255.255.0  
- Default Gateway: 192.168.1.1  
- IP Assignment: DHCP (Automatic)

---

## 4. Network Devices and Services

### Devices:
- **Modem** – Connects to the Internet Service Provider (ISP)  
- **Router** – Manages and distributes the network  
- **Laptop** – Personal device connected via WiFi  
- **Smartphone** – Mobile device connected via WiFi  

### Services:
- **DHCP (Dynamic Host Configuration Protocol)** – Assigns IP addresses automatically  
- **DNS (Domain Name System)** – Resolves website names to IP addresses  
- **WiFi** – Wireless connectivity  

---

## 5. Device Configurations

### Router Configuration:
- SSID: HomeWiFi  
- Security Type: WPA2/WPA3  
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

## 6. Credential Security Method 🔐

To securely store login credentials:

- Passwords are stored using a password manager (Google Password Manager)  
- Strong passwords are used (mix of uppercase, lowercase, numbers, and symbols)  
- Default router username and password are changed  
- Credentials are not shared with others  
- Two-Factor Authentication (2FA) is enabled when available  

---

## 7. Network Topology Diagram

    Internet
        │
      Modem
        │
      Router
      /    \
 Laptop   Smartphone

---

##  Summary

This home network uses a simple star topology with a router as the central device. It provides secure and efficient internet access to connected devices using DHCP and WiFi, while maintaining security through strong credentials and firewall protection.

