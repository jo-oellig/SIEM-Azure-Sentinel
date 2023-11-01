<h1>Microsoft Sentinel Lab</h1>

<h2>Description</h2>
In this project, I will create a live virtual machine using Azure and use the VM as a honeypot to attract attackers. I will set up a SIEM system using Microsoft Sentinel and use it to observe live attacks on the honeypot from all over the world. Then, I will use a custom PowerShell script to find the locations where the attacks are coming from and I will plot them on the Microsoft Sentinel map.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure</b>
- <b>Microsoft Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
Creating the virtual machine <br/>
<img src="https://imgur.com/UZe1TZV.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Creating inbound security rule that allows all inbound traffic <br/>
<img src="https://imgur.com/qsXPNTk.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
  
<p align="center">
Creating log analytics workspace <br/>
<img src="https://imgur.com/XWRkf8J.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
  
<p align="center">
Enable gathering VM logs in Microsoft Defender for Cloud <br/>
<img src="https://imgur.com/DFrkfVj.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
<img src="https://imgur.com/R3wrB6q.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Connecting log analytics to virtual machine <br/>
<img src="https://imgur.com/KmKlQGK.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
<br />
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
