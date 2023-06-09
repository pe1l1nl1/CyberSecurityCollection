## Data Communication eli Tietoliikenne 2023-4-28


## Data transmission ##

Data communication or digital communications, including data transmission and data reception, is the transfer and reception of data in the form of a digital bitstream or a digitized analog signal (A.P.Clark 1983) transmitted over a point-to-point or point-to-multipoint communication channel.

## Topology ##

- Ring 
- Mesh 
- Star
- Fully Connected 
- Line
- Tree
- Bus

## Transmission methods ##

- Anycast
- Broadcast 
- Multicast 
- Unicast
- Geocast

- Simplex
- Half Duplex
- Full Duplex (now also wire network/langalliset verkot)

## Network appliances ##

- Repeater (Toistimet)
- Keskittimet, HUB, moniporttitoistimet 
- Bridge (Sillat)
- Switch (Kytkimet)
- Router (Reitittimet) 
- Firewall (Palomuuri)
- NGFW (DPI & IPS) = next generation firewall with deep packet inspection and intrution prevention system 

## Protocols p1 ##

![image](https://user-images.githubusercontent.com/19546253/235070494-ec4b011c-0498-48d2-9611-4e9426478142.png)

Data transmission deal with the following OSI model protocol layers and topics: 

![image](https://user-images.githubusercontent.com/19546253/235070692-3b62633e-dc55-43ea-80fc-d2b20940d33b.png)

*Source: https://en.wikipedia.org/wiki/Data_communication*

- Protocol = connection policy = traffic procedure 
- A protocol is a set of rules that two or more devices must follow in order to allow communication between them.
- The role of protocols is to work together to provide a data transfer protocol service to application processes.

## Protocols p2 ##

- TCP/IP
*The most used and common
- NetBEUI
*IBM & Microsfot (1985)
- IPX/SPX
*Novell Netware (1983)
- Appletalk 
*Apple appliances (1984-2009)
- DECnet
*Digitalin VAX-machines (1975; 1983-2010)

## TCP/IP p1 ##

- Data transfer is a family of protocols that includes several different types of protocols/ Tiedonsiirto on protokollaperhe, johon kuuluu useita erilaisia protokollia
- TCP = Transmission Control Protocol
- IP = Internet Protocol
- UDP = User DatagramProtocol
- ICMP = Internet Control Message Protocol
- ARP = AddressResolutionProtocol
- IGMP = Internet Group Management Protocol

## TCP/IP p2 ##

- Vendor- and hardware-independent
- Most commonly used protocol
- Must be Windows 98 by default
- Compatible with high-speed backbone connections (ATM, FrameRelay)
- Bidirectional (fullduplex)
- IPv
*4192.168.0.1*
- IPv6 
*2001:0DB8:3FA9:0000:0000:0000:0000:00D3:9C5A*

![image](https://user-images.githubusercontent.com/19546253/235074166-d882a21c-0d0d-41a0-9eaa-fb948c124447.png)

*In Windows 95, TCP/IP has to be separately set up with network protocol*

## Connection models/Viitemallit - OSI-malli ja TCP/IP- malli ##

![image](https://user-images.githubusercontent.com/19546253/235073054-6dec91e0-ee02-4ccc-9afa-c717d8714a5f.png)

![image](https://user-images.githubusercontent.com/19546253/235073113-8ac01eff-9f67-4b55-9e4b-7072cfcf94ea.png)

![image](https://user-images.githubusercontent.com/19546253/235075020-5f8000bb-b7b2-4fcf-a7f9-64bc28610cc9.png)
*[Source](https://media.fs.com/images/community/upload/kindEditor/202107/29/original-seven-layers-of-osi-model-1627523878-JYjV8oybcC.png)*

![image](https://user-images.githubusercontent.com/19546253/235074638-d34a0a36-4126-410f-87ea-9791299e995f.png)
*[Source](https://www.researchgate.net/publication/327483011/figure/fig2/AS:668030367436802@1536282259885/The-logical-mapping-between-OSI-basic-reference-model-and-the-TCP-IP-stack.jpg)*

![image](https://user-images.githubusercontent.com/19546253/235074791-59bf213f-0090-4f1c-b31e-a3fd0660beb0.png)

*[Source](https://www.researchgate.net/figure/A-Summary-of-DER-Communication-Level-Attacks-and-Existing-Solutions-Layers-1-4_tbl2_327483011)**

## Transferring data through the TCP/IP model ##

![image](https://user-images.githubusercontent.com/19546253/235075506-68978f37-91f5-428b-908c-23fe29d39e93.png)


## IP-packet ##

## Paircable ##

## What transmits in the cable ##


[FS Cables](https://www.fs.com/de-en/c/fiber-testers-18?page=2)

## Physical address - MAC (Media Access Control) ##

Check your own mac address from cmd:`ipconfig/all`

![image](https://user-images.githubusercontent.com/19546253/235086456-a6cd7a2a-2f25-43b0-b614-3caf749e81f8.png)

![image](https://user-images.githubusercontent.com/19546253/235086544-1d44da22-599c-473c-a6bb-5ba67fb106f0.png)

![image](https://user-images.githubusercontent.com/19546253/235086874-05fba1c4-c285-4815-ac57-7dc479091b9a.png)

MAC addresses act as the physical addresses for local communications. They show up in most IEEE 802 networks including: 802.3 (as well as Ethernet II), 802.5, 802.11 (Wi-Fi), 802.15 (Bluetooth), and the ITU-T G.hn standards.

The IEEE now manages MAC addresses. Their current projection is that the amount of addresses available with 48 bits (over 281 Trillion) will last until 2100. They have already planned to extend the MAC address space to 64 bits and will call it EUI-64.

*[Resource](https://www.globalknowledge.com/us-en/resources/resource-library/articles/does-a-mac-address-mean-apple-invented-it/)*
*[macvendors](https://macvendors.com/)*

![image](https://user-images.githubusercontent.com/19546253/235086782-45b74510-28ad-46a6-a469-b6c2fef7df42.png)

![image](https://user-images.githubusercontent.com/19546253/235086829-7d8d2771-bc7f-4ea7-9f45-7578a471098d.png)

## Network Devices ##

![image](https://user-images.githubusercontent.com/19546253/235089996-d54d97a5-53a7-4671-8dbd-0fbc3b2120ce.png)
![image](https://user-images.githubusercontent.com/19546253/235090115-0e31ab41-f366-4259-b910-6fe05610fdee.png)


**Switch/Kytkin**
**Virtual LAN (VLAN)**
**ARP**

![image](https://user-images.githubusercontent.com/19546253/235092941-f1c46a21-754a-4e9b-ace8-f525bb5af7df.png)

cmd: `arp -a`

**ICMP, IGMP**

cmd: `ping 8.8.8.8`

![image](https://user-images.githubusercontent.com/19546253/235104976-45d7a3d5-52eb-4c63-b90c-db2b07ae64f6.png)


## IPv4 ##

## IP - Internet Protocol ##
- Takes care of routing between networks
- Includes sender and recipient addresses
- IP address
![image](https://user-images.githubusercontent.com/19546253/235106858-5f5b7912-b442-40f3-bbf6-15634b161322.png)
![image](https://user-images.githubusercontent.com/19546253/235106902-abd5c2f6-be96-4429-bd6a-129d832f27ab.png)

## IPv4-addressing/osoitteistus ##

- Each computer must have a unique IP address in order for the information to be
goes to the right place
- A 32-bit number that identifies a device on the network
- Decimal numbers in four octets separated by a dot
- The subnet mask defines the network part (NetworkID) and the device part (HostID)
- Devices on the same logical network must have the same network part

![image](https://user-images.githubusercontent.com/19546253/235107691-b7e9b1ab-26ac-454d-a2f4-758934e10e23.png)

## IP-address and binary numbers ##

- 8 bits = 1 byte = 256 different numbers between 0 and 255. This is why an IP address cannot
for example 192.429.13.7 The maximum possible value of one octet is 255.

![image](https://user-images.githubusercontent.com/19546253/235107987-d3a78af7-0098-4d96-8e38-0d75d4add218.png)


192.168.1.10 

![image](https://user-images.githubusercontent.com/19546253/235109675-cc472e54-d95f-4699-a0a1-5593198cd622.png)

255.255.255.0 = /24 

![image](https://user-images.githubusercontent.com/19546253/235109823-5a6873dd-3e2c-42f9-a53c-9ccd7abc1db4.png)

**Verkko-osoitetta ei konfiguroida **
- 192.168.1.10
- 1100 0000 . 1010 1000 . 0000 0001 . 0000 1010 
- 1100 0000 . 1010 1000 . 0000 0001 . 0000 0000 = verkko osoite 
- 192.168.1.0

- 192.168.1.1
- 192.168.1.2
- 192.168.1.3

## Network Mask ##

When specifying the network, you must also mention the network mask, i.e. directly
in other words, the size of the network. You can specify the mask in different ways, but the idea is the same:
How big is the network part?
- In decimal form, a 32-bit binary number with so many 1's is drawn.
consecutively as the length of the network part and the rest 0. For example, given a network
10.10.10.1 and the network part is 10.10.10, then the length of the network part is 24 bits
(8x3), so the mask in binary is: 1111111111 1111111111 1111111111 00000000.
In decimal form it would be: 255.255.255.0
- The current way of representing the mask is the CIDR format, using
slash character and the length of the network segment. In the previous example, it would be /24
This is now the preferred method, as it is much easier to understand and
to write.

Although in principle any length between 0 and 32 mm can be used as a mask.
range, it is common to use masks that are easier for people to use, i.e.
/8, /16 and /24 when they follow octet boundaries. Historically, for those of size
Class A, B and C, but nowadays their use is not more common than in the past.

![image](https://user-images.githubusercontent.com/19546253/235111261-e4cd9301-6ecf-4061-9bb0-ea39cdc600b9.png)

- Network coverage directly affects the number of addresses (and therefore devices)
can fit on a given network.
- The number of addresses then comes directly from the number of bits in the device portion.
Mathematically, 2n
(n is the number of bits in the device partition):
- 1 bit → 2 addresses
- 2 bits → 4 addresses
- 3 bits → 8 addresses
- 4 bits → 16 addresses
- 5 bits → 32 addresses
- 6 bits → 64 addresses
- 7 bits → 128 addresses
- 8 bits → 256 addresses

**Examples of the different masks**

![image](https://user-images.githubusercontent.com/19546253/235111504-f985d056-c900-47fb-bc77-4d58508f66cc.png)


## IP ¨rules¨  ##

**Two reserved addresses on each network:**
**1. Network address:** an address where the bits of the device part are 0. The address is the address where the part of the device is set to 0.
**2. Broadcast address:** An address where the bits of the device part are 1.
(remember the octet has a maxima value of 255).
- These addresses must not be assigned to devices
**- Example:** a network using the IP address 192.168.41.17/24
The mask /24 means that the network part of the address is 192.168.41 (24 bits from the left), so
the device part is .17
It is calculated that the network address is: 192.168.41.0/24 and the broadcast address is 192.168.41.255/24
**No two addresses on the same network**
- Typical student error in the lab: the default gateway is 192.168.1.1.
Assigns the same address 192.168.1.1 to their own workstation
- A conflict arises, potentially causing the entire lab's internal network to be disconnected from the Internet.

**Exercise**

-What are the network addresses of 172.20.16.50/16?
verkon osoite/network address and yleislähetys osoite/broadcast address?
-And the address 10.20.30.40/20?

