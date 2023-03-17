## IPV4 addresses are 32 bits numbers; i.e 4 octets with each octet having 8 bits.
Each IP address is divided between network ID and host ID how we divide it is derived from network classes.

|Class|   Range      |  Length of N/W    |  # of N/W   | # of hosts| Reserved bits                 |
|A    |1-126.a.b.c   |   8               | 126         | 16 million|  first bit reserved is 0      |
|B    |128-191.a.b.c |  16               | 16,384      | 65,534    | first 2 bits reserved are 10  |
|C    |192-223.a.b.c  | 24               |  2 Million  |  254      | first 2 bits reserved are 110 |

### There are two mores classes D- Multicast and E - Experimental R&D

|CIDR | IPV4 subnet Masks|
|/32 Mask = 2^0 IPs =1|
|/31 Mask = 2^1 IPs =2|
/30 Mask = 2^2 IPs =4
/29 Mask = 2^3 IPs =8
/28 Mask = 2^4 IPs =16
/27 Mask = 2^5 IPs =32
/26 Mask = 2^6 IPs =64
/25 Mask = 2^7 IPs =128
/24 Mask = 2^8 IPs =256
/23 Mask = 2^9 IPs= 

/16 Mask = 2^16 IPs=65,536


/0 Mask = 2^32 = All IPs

/32 - NO IP can change
/24 - last IP can change
/16 - last two IPs can change
/8 Last three IPs can change
/0 All IPs can change

E.g 192.168.32.1/32 ?
192.168.32.1

192.168.0.0/24 ?
192.168.0.0 - 192.168.10.255 (which means we can change the last IP in the range of 0-255)
192.168.0.0

Network: Cables, routers and servers connected with each other forms a network
Router: A networking device that forwards data packets between computer networks. They know where to send your packets on the internet.
Switch: takes a packet and send it to and send it to the correct server/client on the network.
