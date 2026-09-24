
# EXPT NO.3 A IMPLEMENTATION OF LINK STATE ROUTING PROTOCOL OSPF
# AIM

To connect computers in multiple networks using Open Shortest Path First Routing Protocol and to verify the connectivity between computers.

# EQUIPMENTS REQUIRED
EQUIPMENTS REQUIRED
S.NO	NAME	QUANTITY
1	Desktop computer	4
2	Cisco 1800 router	2
3	USB to serial converter	2
4	Cisco 2900 switch	2
5	CAT 6 patch cable	10
6	Console cable	2
# IP ASSIGNMENT


NAME	IP ADDRESS	SUBNET MASK	NETWORK	CLASS	GATEWAY
PC0	192.168.0.1	255.255.255.0	192.168.0.0	C	192.168.0.200
PC1	192.168.0.2	255.255.255.0	192.168.0.0	C	192.168.0.200
PC2	192.168.1.1	255.255.255.0	192.168.1.0	C	192.168.1.200
PC3	192.168.1.2	255.255.255.0	192.168.1.0	C	192.168.1.200
PC4	192.168.2.1	255.255.255.0	192.168.2.0	C	192.168.2.200
PC5	192.168.2.2	255.255.255.0	192.168.2.0	C	192.168.2.200
ROUTER0 — INTER F 0/0	192.168.0.200	255.255.255.0	192.168.0.0	C	—
ROUTER0 — SERIAL2/0	192.168.1.200	255.255.255.0	192.168.1.0	C	—
ROUTER1 — INTER F 0/0	192.168.1.201	255.255.255.0	192.168.1.0	C	—
ROUTER1 — SERIAL2/0	192.168.2.200	255.255.255.0	192.168.2.0	C	—
# NETWORK DIAGRAM


# PROCEDURE
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag two 2900 Switches, two Cisco 1800 Routers, four PC Terminals from tool bar and drop it in work area.
STEP 3: Connect all the PC Terminals and Routers through Switches as shown in the network diagram using CAT 6 Patch cables.
STEP 4: Configure IP address and Gateway in all PC Terminals.
STEP 5: Configure Delhi router IP address, save configuration and restart Delhi router. STEP 6: Configure Chennai router IP address, save configuration and restart Chennai router. STEP 7: Check the connectivity between the computers in network.
STEP 8: Configure OSPF in Delhi router, Save configuration and restart Delhi router.
STEP 9: Configure OSPF in Chennai router, Save configuration and restart Chennai router.
STEP 10: Verify the connectivity between PC Terminals in different networks using Ping command.
STEP 11: Check the routing table in Delhi router and Chennai router using show ip route command

# OUTPUT


<img width="2880" height="2160" alt="651477039-0567d944-8885-46a6-89ac-7656d5b18367" src="https://github.com/user-attachments/assets/6d7c88a2-209d-481d-be2a-22938e67820a" />




# RESULT
Thus the computers in multiple networks using Open Shortest Path First Routing Protocol is connected and the connectivity between the computers is verified.

