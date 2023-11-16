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
<p align="center"><br/><img src="https://imgur.com/R3wrB6q.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Connecting log analytics to virtual machine <br/>
<img src="https://imgur.com/KmKlQGK.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Setting up Microsoft Sentinel <br/>
<img src="https://imgur.com/MbkigId.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Logging into VM using Remote Desktop Connection <br/>
<img src="https://imgur.com/PwQng7s.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
<p align="center"><br/><img src="https://imgur.com/fsqa67m.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Turning off Windows Defender Firewall on VM <br/>
<img src="https://imgur.com/gl4YFa7.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Downloading custom PowerShell script onto VM to convert IP addresses to geolocation <br/>
<img src="https://imgur.com/vpVl5WS.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Running script to extract geodata <br/>
<img src="https://imgur.com/nCIetIW.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
<p align="center"><br/><img src="https://imgur.com/lQDUbNw.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Creating custom log in Log Analytics Workspace <br/>
<img src="https://imgur.com/ow6F8a4.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Now I am able to view custom log data <br/>
<img src="https://imgur.com/9V7MEqF.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>
  
<p align="center"><br/><img src="https://imgur.com/8NElLlb.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>


<p align="center">
Running a custom query to extract the log data categorically <br/>
<img src="https://imgur.com/GgN0OFH.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Creating workbook using the same query <br/>
<img src="https://imgur.com/T8pGrjO.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<p align="center">
Visualizing the workbook as a map <br/>
<img src="https://imgur.com/b6P5PSo.png" height="80%" width="80%" alt="Microsoft Sentinel Lab"/>

<br/>

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
