<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, I observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Creating File with Various Permissions
- File shares as a Normal User
- Creating an Accountants Security Group

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/2kVYGV6.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I decided to set folder permissions for the Domain Users group. The first folder "read-access" and permission is read only. The second folder "write-access" and the permissions for this folder is read/write. The third folder is "no-access" and the permissions for this folder is read/write.
</p>
<br />

<p>
<img src="https://i.imgur.com/Y6gvMaC.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created an accounting group and practiced configuring access permissions for certain users. I signed into different user accounts to see if the access permissions were in effect for that particular user.
</p>
<br />

<p>
<img src="https://i.imgur.com/wFGrgAO.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating a security group that is strictly for users who are accountants; I tested the durability of the security measures I implemented. 
</p>
<br />
