# **Router Configuration**:

•	Select one **PT-Router** and two **end devices** from the bottom left-hand corner and drag it to the screen. 

•	Connect the router to end devices using default connection option.

•	Then we have to config end device(PC0) with **Gateway**:10.0.0.1 and **Ip-address**:10.0.0.10  and PC1 with **Gateway**:20.0.0.1 and **Ip-address**:20.0.0.10  .

•	Then we need  click on the CLI tab to access the configuration menu.Then,

      1.	Type **enable**
      
      2.	Type **config terminal** to access the configuration menu.
      
      3.	Type **interface fa 0/0** to access Ethernet0/0
      
      4.	Type **ip address 10.0.0.1  255.0.0.0**
      
      5.	Type **no shutdown**
      
•	The router is configured properly.

•	Type **ping 10.0.0.1** in the command prompt to know whether it is sent to destination or not.


# **Outcomes**:

•	A router is the smartest and most complicated among hub and switch.

•	The router is generally located at gateways and uses the ICMP protocol to communicate .

•	We can check if the destination is active or not using ping message.

•	It sets TTL in the packet header.

