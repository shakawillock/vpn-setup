<p align="center">
<img src="https://i.imgur.com/u9kahr4.jpg" alt="osTicket logo"/>
</p>

<h1>Virtual Private Network (VPN)</h1>
This tutorial outlines the prerequisites and installation using a VPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2> Steps </h2>

- Step 1: Locate Local IP
- Step 2: Setting up Virtual Machine using Azure
- Step 3: Locating IP through Virtual Machine
- Step 4: Connecting to VPN
- Step 5: Locating IP through VPN

<h2>Installation Steps</h2>

Step 1: Locate your own personal IP address by going to www.whatismyipaddress.com

Example 1A
<p>
  <img src="https://i.imgur.com/uJtu8aa.png" alt="What Is My IP Address" />
</p>

<p>Next we will setup a virtual machine on Azure</p>

Step 2: Go to www.portal.azure.com and find Virtual Machines

Example 2A

<p>
  <img src="https://i.imgur.com/frwQenh.png" alt="Microsoft Azure Virtual Machine"/>
</p>

Creating the Virtual Machine on Example 2B the VM as "VM-North-Europe" and select that for the Region as well. Ensure the other items are selected as shown in Example 2B and 2C.

Example 2B

<p>
  <img src="https://i.imgur.com/vmlkc3d.png" alt="Create a Virtual Machine"/>
</p>

For the Username and Password you can create your own information

Example 2C

<p>
  <img src="https://i.imgur.com/r5wjtlV.png" alt="Create a Virtual Machine" />
</p>

Click on the Networking Tab towards the top of the page and view Example 2D inputs to match

Example 2D

<p>
  <img src="https://i.imgur.com/5INXu4g.png" alt="Create a Virtual Machine" />
</p>

Then click on the Review and Create button, once it passes validation select Create at the bottom

At the Virtual Machine we find that the IP Address to the Virtual Machine is "20.234.61.102"

Example 2E

<p>
  <img src="https://i.imgur.com/ZxYdyDT.png" alt="Microsoft Azure Virtual Machine"/>
</p>

Step 3: Log into the Virtual Machine and Find IP Address

Now that we have setup the Virtual Machine we will connect into it using the Remote Desktop Application and enter the IP address for the Virtual Machine that we located in Example 2E. We will then input the credentials 
we set when creating the Virtual Machine. Once we are logged in we will open the web browser and look up our IP Address again using www.whatismyipaddress.com

Example 3A

<p>
  <img src="https://i.imgur.com/a21UquN.png" alt="Remote Desktop Connection" />
</p>

Example 3B

<p>
  <img src="https://i.imgur.com/kxRUzd3.png" alt="Remote Desktop Connection"/>
</p>

<br />
