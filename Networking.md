CIDR -IPV4 subnet Masks
/32 Mask = 2^0 IPs =1
/31 Mask = 2^1 IPs =2
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
