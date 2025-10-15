<h1>Group Policy Object Lab 1</h1>

<h2>Description</h2>
Project consists of creating a "disable domain firewall" rule, and applying it to a individual computer.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Azure Bastion</b> 
- <b>Windows Server Manager </b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Group Policy Manager <b/>
- <b>Windows Command Line Interface <b/>
   

<h2>Program walk-through:</h2>

<p align="center">
Creating a new Group Policy Object from our forest "lab.local": <br/>
<img src="https://i.imgur.com/p1Yj9Vf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/9D0QMbA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/CoiNEwt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Adding a user to the TEST GPO:<br/>
<img src="https://i.imgur.com/OF4uHto.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Creating a new GPO "Disable Domain Firewall":<br/>
<img src="https://i.imgur.com/ofJ1L45.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Going into the GPO, setting as a Computer Configuration, its policies and Windows settings: :<br/>
<img src="https://i.imgur.com/h4H1shl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/DW5XPna.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/CO298H8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  <br/>
<img src="https://i.imgur.com/1F7jPxY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/qd7TPKF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  <br/>
<img src="https://i.imgur.com/ugKDOQ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  Setting Firewall to "off":<br/>
<img src="https://i.imgur.com/99e2d58.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  <br/>
<img src="https://i.imgur.com/O17sjFR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> Checking in the GPO settings:<br/>
<img src="https://i.imgur.com/4TTuK2G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> Setting firewall rule to specific computer:<br/>
<img src="https://i.imgur.com/zogLitd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/AXWtqZL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  Adding PC:<br/>
<img src="https://i.imgur.com/W1xT9lt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
 Linking this GPO to Branch1 where our PC is located:<br/>
<img src="https://i.imgur.com/k2jqafZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  GPO is now "live":<br/>
<img src="https://i.imgur.com/SaqllFg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  Updating the policy through the CLI:<br/>
<img src="https://i.imgur.com/E05489J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
  :<br/>
<img src="https://i.imgur.com/IC03Jeu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
 Checking in Windows security settings:<br/>
<img src="https://i.imgur.com/oQ6aQHE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!
# GPO-Lab-1
