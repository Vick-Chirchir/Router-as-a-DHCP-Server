
<h1>Router as a DHCP Server</h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project demonstrates how to configure a Cisco router as a DHCP server to dynamically assign IP addresses to multiple devices across two different network segments—Site A and Site B—within a Packet Tracer lab simulation. 
This project showcases my ability to deploy scalable and dynamic IP addressing across a multi-site enterprise network using Cisco devices, making it suitable for real-world branch-office scenarios.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/tmzOwfB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Config on the Router(Router 1):  <br/>
<img src="https://i.imgur.com/okCHFdZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface Config with Loopback interface as the IP address to the DHCP Server: <br/>
<img src="https://i.imgur.com/8QABK5s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Pool Config:  <br/>
<img src="https://i.imgur.com/Jb0naBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router on a Stick) using (ip helper-address:  <br/>
<img src="https://i.imgur.com/zpn4ucK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Communication between VLAN 10,20,30:  <br/>
<img src="https://i.imgur.com/kzTsRjw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

