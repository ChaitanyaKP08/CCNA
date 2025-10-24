**Basic Switch Connection**

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-57-59.png?raw=true)

This lab demonstrates basic Layer 2 switch connectivity using the EVE-NG network simulator. Two Windows Server 2012 machines are connected to a virtual switch running Cisco vIOS. The goal is to verify connectivity between the servers by assigning IP addresses and testing with ICMP (ping). The switch is running Cisco vIOS, which is a virtualized version and may not fully reflect real-world switch behavior.
The .unl file included in this repository is the exported topology from the EVE-NG environment.

**Assigning IP addresses to devices running Windows Server 2012**

1.Open Control Panel and select Network and Sharing Center.

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/pic1.png?raw=true)

2.Go to Change adapter Settings.

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/2.png?raw=true)

3.Select the device interface that connects to a network (Ethernet in this case) 

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-51-04.png?raw=true)

4.Right click on it to select properties.Select the IP protocol and go to its properties(IPV4 OR IPV6)

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-51-49.png?raw=true)

5.Obtain an IP automatically is set to recieve ip by DHCP server.Select Use the following IP address and assign the IP address to the device.Select ok and close all the remaining windows.

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-53-14.png?raw=true)

**IP Configurations performed:**

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-53-14.png?raw=true) ![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/Screenshot%20from%202025-10-24%2018-57-36.png?raw=true)

**Verification of Connectivity**

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/d1.png?raw=true)

![image_alt](https://github.com/ChaitanyaKP08/CCNA/blob/main/BasicConnections/SwitchConnectivity/Images/d2.png?raw=true)

**Things to remember**

1.Since Switch is a level 2 device,both devices should be under the IP address of the same class.

