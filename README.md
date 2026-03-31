🏠 Home Network Documentation

Name: Jun Santos III Sagucio

1. Physical Topology

My home network consists of a modem connected to a router, which provides internet access to wireless devices.

Structure:

Internet → Modem → Router → Devices (WiFi)

Connected Devices:

Laptop (WiFi)
Smartphone (WiFi)
2. Logical Topology

The network uses a star topology, where all devices connect to a central router.

The router manages communication between devices
All traffic passes through the router before reaching the internet
Devices do not directly communicate with each other without passing through the router
3. Addressing Documentation

(Note: IP addresses are modified for privacy.)

Device	IP Address	MAC Address	Connection
Router	192.168.1.1	AA:BB:CC:DD:EE:01	Ethernet
Laptop	192.168.1.10	AA:BB:CC:DD:EE:02	WiFi
Smartphone	192.168.1.11	AA:BB:CC:DD:EE:03	WiFi
IP addresses are assigned dynamically using DHCP
Subnet: 255.255.255.0
4. Network Devices and Services
Devices:
Modem – Connects the home network to the Internet Service Provider (ISP)
Router – Distributes internet and manages the network
Laptop – Personal computing device
Smartphone – Mobile device connected via WiFi
Services:
DHCP (Dynamic Host Configuration Protocol) – Automatically assigns IP addresses
DNS (Domain Name System) – Translates domain names into IP addresses
WiFi – Provides wireless network access
5. Device Configurations
Router Configuration:
SSID: HomeWiFi
Wireless Security: WPA2/WPA3
DHCP: Enabled
Firewall: Enabled
Laptop Configuration:
Connection: WiFi
IP Assignment: Automatic (DHCP)
Firewall: Enabled
Smartphone Configuration:
Connection: WiFi
IP Assignment: Automatic (DHCP)
6. Credential Security Method 🔐

To securely store login credentials:

I use a password manager called Bitwarden
Strong passwords are used (combination of uppercase, lowercase, numbers, and symbols)
Default router credentials were changed
Passwords are not written down or shared
Two-Factor Authentication (2FA) is enabled where available
7. Network Topology Diagram (Optional)

You can create a diagram using:

draw.io

Basic diagram layout:

Internet
   │
 Modem
   │
 Router
  /   \
Laptop Phone
