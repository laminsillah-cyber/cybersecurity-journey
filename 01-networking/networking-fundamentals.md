# Networking Fundamentals

## IP Addresses

An IP address is a unique address used to identify a device on a network and allow devices to communicate with each other.

### Example

A small network might contain:

- Laptop: 192.168.1.10
- Phone: 192.168.1.11
- Server: 192.168.1.20

### Private IP Addresses

Private IP addresses are used inside local networks.

Examples:
- 192.168.1.10
- 10.0.0.5
- 172.16.0.10

### Cybersecurity Importance

IP addresses are important in cybersecurity because analysts use them to investigate network activity, identify the source and destination of connections, and investigate suspicious traffic.

## What I Learned

- An IP address identifies a device on a network.
- Different devices can have different IP addresses.
- Private IP addresses are commonly used inside local networks.
- IP addresses are important when investigating network activity.


## Subnet Masks

A subnet mask determines which portion of an IP address represents the network and which portion represents the host.

For example:

- IP address: 192.168.1.10
- Subnet mask: 255.255.255.0
- CIDR notation: 192.168.1.10/24

A /24 network commonly uses the first three octets to identify the network, while the final octet identifies individual hosts.

### Example

The following devices are on the same /24 network:

- PC1: 192.168.1.10/24
- PC2: 192.168.1.20/24

The following device is on a different network:

- PC3: 192.168.2.10/24

### Cybersecurity Importance

Subnetting helps security professionals understand network boundaries and identify how systems are organized. Network segmentation can also be used to restrict communication between systems and limit an attacker's ability to move through a network.

## What I Learned

- A subnet mask separates the network portion from the host portion of an IP address.
- /24 corresponds to 255.255.255.0.
- Devices with the same network portion belong to the same subnet.
- Understanding subnets is important for network monitoring, security analysis, and network segmentation.
