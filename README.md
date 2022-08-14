<h1>Configuring an Access Point</h1>


<h2>Description</h2>
In this lab, I learned to configure an access port. It is assigned to only one VLAN (virtual local area network). It carries traffic from the specified VLAN to the device connected to it or from the device to other devices on the same VLAN on that switch.
<br />



<h2>Environments Used </h2>

- <b>Ubuntu 20.04.2 LTS</b> 
- <b>PuTTY SSH Client</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar click PuTTY SSH Client and proceed to put in the IP address, port number, click Telnet and then click open: <br/>
<img src="https://i.postimg.cc/4Nhmy9cs/Screen-Shot-2022-08-13-at-9-19-47-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
<br />
In the IOU1 terminal window type the following commands <br/>
1. configure terminal <br/>
2. vlan 99 <br/>
3. name ucian <br/>
4. interface e0/3 <br/>
5. switchport mode access <br/>
6. switchport access vlan 99 <br/>
7. end <br/>
<img src="https://i.postimg.cc/s2ZMQGqp/Screen-Shot-2022-08-13-at-9-25-21-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the IOU1 terminal window tyoe the "show vlan" command to to display current vlans and their assignments <br/>
<img src="https://i.postimg.cc/9MMNYVPt/Screen-Shot-2022-08-13-at-9-28-12-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






  
  
 

  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
