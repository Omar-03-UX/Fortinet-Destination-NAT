# Fortinet Destination NAT

<h1> Destination NAT Lab </h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab, we will create a simulated network environment to demonstrate the implementation of Destination Network Address Translation (DNAT) for external users to securely access web servers and services, such as HTTP and SSH, located in the DMZ (Demilitarized Zone). The DMZ acts as an intermediary network segment that separates the untrusted external network (typically the internet) from the trusted internal network, and it houses publicly accessible servers. The lab's primary objective is to showcase how DNAT can be used to forward external requests to the appropriate DMZ servers while maintaining the security of the internal network.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Fortinet Firewall</b> 
  
<h2>Environments Used </h2>

- <b>Eve ng</b> (21H2)
- <b>VM workstation </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Network Setup: <br/>
<img src="https://i.imgur.com/gBvrXPN.png" height="80%" width="80%" alt="Network setup"/>
<br />
<br />
DNAT Configuration:  <br/>
<img src="https://i.imgur.com/ZAbFryI.png" height="80%" width="80%" alt="DNAT"/>
<br />
<br />
Virtual IP for Web Servers: <br/>
<img src="https://i.imgur.com/4Jl9516.png" height="80%" width="80%" alt="Virtual IP"/>
<br />
<br />
Accessing Services: <br/>
<img src="https://i.imgur.com/dml4Uo2.png" height="80%" width="80%" alt="ServicesP"/>
<br />
<br />


