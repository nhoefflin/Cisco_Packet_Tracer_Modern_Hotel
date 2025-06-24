![image alt](https://github.com/nhoefflin/Cisco_Packet_Tracer_Modern_Hotel/blob/921deb1e80905a8732395d0d124c1c80c9fca069/modern_hotel.jpg)<br><br>
<br><br>
Design and implement a modern hotel network. 
The hotel has three floors; on the first floor there are three departmnets (reception, store, and logistics), 
on the second floor there are three departments (finance, HR, and sales/marketing),
while the third floor hosts the IT and Admin.<br><br> 

1. There should be three routers connecting each floor

2. All routers should be connected to each other using serial DCE cables

3. the network between the routers should be:
10.10.10.0/30
10.10.10.4/30
10.10.10.8/30

4. Each floor is expected to have one switch

5. Each floor is expected to have WIFI networks connected to laptops and phones 

6. Each department is expected have a printer

7. Each department is expected to be in different VLANs with the following details:<br><br>  


1st floor:

Reception - VLAN 80,  Network 192.168.8.0/24

Store - VLAN 70, Network 192.168.7.0/24

Logistics - VLAN 60. Network 192.168.6.0/24<br><br> 


2nd floor:

Finance - VLAN 50, Network 192.168.5.0/24

HR - VLAN 40, Network of 192.168.4.0

Sales - VLAN 30, Network of 192.168.3.0/24<br><br> 


3rd floor: 

Admin - VLAN 20, Network 192.168.2.0/24

IT - VLAN 10, Network 192.168.1.0/24


8. Use OSPF as the routing protocol to advertise routes 

9. All devices in the network are expected to obtain IP addresses dynamically with their respective router configured as the DHCP server

10. All the devices in the network are expected to communicate with each other

11. Configure SSH in all the routers for remot login

12. In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login

13. Configure port security to IT-dept switch to allow only Yes-PC to access port fa0/1
 (use sticky method to  obtain mac-address with violation mode of shutdown)

