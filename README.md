### NAT

![image](https://user-images.githubusercontent.com/49310101/137576189-41fb5cab-41ff-4f30-bf6c-bb014c9892a4.png)

Assign the ip address for each interface with below mentioned zones.

Public NW 100.1.1.0/24
DMZ 10.1.10.0/24
Internal 192.168.1.0/24


1. Create nat for internet access
2. Created policy for accessing DMZ zone ip on port number 443 only block others.
3. alow public user to access DMZ zone IP 10.1.10.2 on port 443 only
