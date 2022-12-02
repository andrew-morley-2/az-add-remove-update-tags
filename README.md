<h1>Add, Remove and Update Tags for Resources in Azure</h1>

<!--
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)
 --!>

<h2>Description</h2>
In the scenario for this project, the finance department has reached out to you, requesting additional taxonomy information on a recent Azure bill, including who created the resources, which department budget should be used for the resources and if the resources are necessary for running business ciritcal systems. If there are any non-essential business systems, they ask that you signify that in some way.
<br />


<h2>Languages and/or Utilities Used</h2>

- <b>Azure Portal</b> 
- <b>Azure Cloud Shell</b> 


<h2>Environments Used </h2>

- <b>Azure</b>

<h2>Walkthrough:</h2>

<p align="center">
<b>Add Tags to the Resource Group</b>
<br/>
<br/>
- In Azure Cloud Shell, perform the command to list all resource groups for this lab.
<br/>
- Perform the CLI command that will apply the following tags to the resource group (replace YourName with your name):
Environment=Production
Dept=IT
CreatedBy=YourName <br/>
<img src="https://i.imgur.com/ulQwtCB.jpeg" height="80%" width="80%" alt="Add, Remove and Update Tags for Resources in Azure 1.1"/>
<br />
<br />

<b>Remove Tags for VM and Mark for Deletion</b>
<br />
<br />
- Perform the CLI command to list the existing tags for the virtual machines in this lab.
<br/>
- Remove the existing tags from the VM.
<img src="https://i.imgur.com/QJ8f60o.jpeg" height="80%" width="80%" alt="Add, Remove and Update Tags for Resources in Azure 2.1"/>
<br/>
<br/>
- Mark the VM for deletion by adding the tag MarkForDeletion=Yes.
CreatedBy=YourName <br/>
<img src="https://i.imgur.com/830eDEy.jpeg" height="80%" width="80%" alt="Add, Remove and Update Tags for Resources in Azure 2.2"/>
<br />
<br />

<b>Change Tags for the Virtual Network</b>
<br/>
<br/>
- Perform the CLI command to list the virtual networks and their associated tags
<br/>
- Perform the CLI command to overrite the existing tags with the following tags (replace YourName with your name):
Environment=Production
Dept=IT
CreatedBy=YourName
Dept=IT
CreatedBy=YourName <br/>
<img src="https://i.imgur.com/830eDEy.jpeg" height="80%" width="80%" alt="Add, Remove and Update Tags for Resources in Azure 3.1"/>

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
