<p align = "center">
<img src = "https://github.com/banksii/implementing-active-directory/assets/120074266/db900248-87e9-4154-9c8c-e146bd84c007">
</p>

<h1> Setting up Active Directory in the Cloud </h1>

This tutorial will walk through the implementation of Active Directory using Azure virtual machines.


<h2> Environments and Technologies Used </h2>
	<ul>
	  <li>Microsoft Azure</li>
	  <li>Virtual Machines</li>
	  <li>Active Directory Domain Services</li>
	  <li>Powershell</li>
	</ul>

<h2> Operating Systems Used </h2>
	<ul><li>Windows 10</li>
	    <li>Windows Server 2022</li>
	</ul>


<h2> Navigation </h2>
	<ol>
	    <li><a href = "#step_1">Set up virtual machines</a></li>
	    <li><a href = "#step_2">Install Active Directory Domain Services on the domain controller (DC-1)</a></li>
	    <li><a href = "#step_3">II</a></li>
	    <li><a href = "#step_4">Fi</a></li>
	    <li><a href = "#step_5">Cle</a></li>
	</ol>


<h2> Installation Steps </h2>
	<ol>
	  <li><h3 id = "step_1">Set up virtual machines</h3>
		We need two machines to begin, a windows server acting as the domain controller (named "DC-1" in the example) and one running Windows 10 (named "Client-1"). Make sure they are set up in the same region and virtual network.
		<br><br>
		<img width="764" alt="dc1-setup" src="https://github.com/banksii/implementing-active-directory/assets/120074266/66e0a20e-f678-4ed7-be9b-5034cc804627">
		<img width="764" alt="client1-setup1" src="https://github.com/banksii/implementing-active-directory/assets/120074266/3573c28c-ebcb-4740-8e09-008b2f208621">
		<img width="581" alt="client-1-on-dc-network" src="https://github.com/banksii/implementing-active-directory/assets/120074266/a52e548f-f735-4ab0-b362-052ec672c6cf">
		<blockquote>
			Client-1 needs to be on the same network as the domain controller.
		</blockquote>
		<br><br>
		Assign the domain controller (DC-1) a static IP address. To do this, go to the networking tab of the DC-1 controller, navigate to 
	  </li>
	  <li><h3 id = "step_2">Install Active Directory Domain Services on the domain controller (DC-1)</h3>
	  </li>
	
	
	
	
	</ol>
