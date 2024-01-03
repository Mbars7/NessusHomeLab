<h1>Nessus Home Lab</h1>


<h2>Description</h2>
In this lab, I gained some hands-on experience with setting up and running credentialed scans using Nessus.  I started by creating a Windows 10 virtual machine with WMware Workstation 17 player and bridged the network settings so my home computer and the VM were on the same network.  I then created an account with Nessus and designed a credentialed scan for the Windows 10 VM.  At this point, I changed some settings on the VM, including disabling the firewall and adding a registry key (per Nessus instructions).  Before running the scan, I installed a deprecated version of Firefox and the results  came back as expected.  Finally, I remediated the vast majority of the vulnerabilities and ran a secondary scan for confirmation.    
<br /><br>

- Installed and configured Nessus Essentials to perform credentialed vulnerability scans on Windows 10 Hosts<BR>
- Implemented Vulnerability Management Function on sandbox networks:
     - Discover, Prioritize, Assess, Report, Remediate, Verify<br>
- Conducted vulnerability assessments with Nessus; remediated vulnerabilities<br>
- Developed automated remediation process to preemptively deal with vulnerabilities stemming from Windows updates and third-party software.<b></b>.

<h2>Languages and Utilities Used</h2>

- <b>Nessus</b> 
- <b>VMware Workstation 17 Player</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Project Snapshots:</h2>

<p align="center">
Oracle VM VirtualBox: <br/>
<img src="https://i.imgur.com/AL0Ssgs.jpg"/>
<br />
<br />
Installed Server Roles:  <br/>
<img src="https://i.imgur.com/C7cVUsC.jpg"/>
<br />
<br />
IP Settings: <br/>
<img src="https://i.imgur.com/zcGL1Q5.jpg"/>
<br />
<br />
DHCP Setup:  <br/>
<img src="https://i.imgur.com/rVYLS25.jpg"/>
<br />
<br />
Active Directory Users:  <br/>
<img src="https://i.imgur.com/xIVkb0N.jpg"/>
<br />
<br />
Active Directory Computers:  <br/>
<img src="https://i.imgur.com/zEnop5P.jpg"/>
<br />
<br />
Client Login:  <br/>
<img src="https://i.imgur.com/jQGki5m.jpg"/>
</p>

Credit for tutorial: [Josh Madakor](https://www.youtube.com/watch?v=lT6Px9zJM3s&t=127s&ab_channel=JoshMadakor)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
