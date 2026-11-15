<h1>Intune - Homelab</h1>

<h2>Description</h2>
This is documentation of me setting up my Intune homelab. 
<br />


<h2>Languages and Utilities Used</h2>
 
- <b>Intune</b>
- <b>Entra ID</b>
- <b>Azure</b>


<h2>Environments Used </h2>

- <b>Windows 11</b> (25H2)

<h2>Walk-through:</h2>

<p align="center">
Setting up Intune Administrator security group in Entra ID. Added admin account to the group as a member and owner of the SG - Intune - Intune Administrator group. Associated the Intune Administrator role to the SG - Intune - Intune Administrator group in Entra ID: <br/>
<img src="https://i.imgur.com/tuGUA39.png" height="100%" width="100%" alt="Setting up Intune Administrator security group in Entra ID"/>
<br />
<br />
<p align="center">
Setting up Windows automatic Intune enrollment. This is configured in Entra ID > Overview > Manage > Mobility (MDM and WIP): <br/>
<img src="https://i.imgur.com/jsUY9Gr.png" height="100%" width="100%" alt="Setting up Intune Administrator security group in Entra ID"/>
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
