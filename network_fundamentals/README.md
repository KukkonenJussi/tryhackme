<h2>Network Fundamentals</h2>

<h3>What is Networking?</h3>

The Internet's initial version, ARPANET, emerged in the late 1960s under US Defense Department funding. However, it wasn't until Tim Berners-Lee invented the World Wide Web in 1989 that the Internet began to function as a platform for storing and sharing information, similar to its modern usage.

An **_I_**nternet **_P_**rotol address (or IP address) can be used as a way of identifying a host on a network for a period of time. An IP address is a set of numbers divided into four octects. For example a private IP address is 192.168.1.1 and a public IP address is 86.157.52.21. A **_public IP address_** is used to identify a device on the Internet, while a **_private IP address_** is utilized for communication within a local network.

**_IPv4_** has 2^32 IP addresses (4,29 billion) while **_IPv6_** supports up to 2^128 of IP addresses (340 trillion-plus).

The MAC (**_M_**edia **_A_**ccess **_C_**ontrol) address is a unique identifier assigned to network interfaces for communication on a physical network. It's used to distinguish devices on a network and is typically hardcoded into the hardware, providing a permanent and unique identity for each device.
A MAC address is a twelve-character hexadecimal number separated by colons, with the first six characters indicating the manufacturer of the network interface and the last six serving as a unique identifier for the device.

MAC addresses can be spoofed, meaning a device can pretend to be another by using its MAC address. This can disrupt security measures, like firewalls configured to trust specific MAC addresses. Public Wi-Fi hotspots often utilize MAC address control for better service, such as offering faster connections for a fee per device.

![](image.png)

**_Ping_** is a fundamental network tool that measures connection performance using **_ICMP_** packets. It determines if a connection exists and its reliability. Pings measure the time ICMP packets take to travel between devices using echo and echo reply packets. This tool is commonly used to test devices on a network or websites and is pre-installed on operating systems like Linux and Windows. An example of ping would be `ping 192.168.1.254`.

![](image-1.png)

<h3>Intro to LAN</h3>
