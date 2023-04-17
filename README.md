# Deploying-Active-Directory-and-Creating-Users
The purpose of the lab below was to show I set up an Active Directory 

<h2> Software, Environments, and Technologies used</h2>

<br>1. The first thing I did for this lab was create all of the Azure Resources necessary to create a virtual AD environemnt. I created one resource group, one virtual network and subnet, a domain controller VM, and one client VM. Below is a screenshot of those resources.</br>

![2023-04-17](https://user-images.githubusercontent.com/55405034/232587409-52125d7e-9024-4d7b-a115-e553e5d46772.png)

<br>2. Next I set the Domain Controller (DC1) IP address to be static so it wouldn't change.</br>

![2023-04-17 (1)](https://user-images.githubusercontent.com/55405034/232588050-7e15701b-e108-4a4b-97af-a4b2d90c2f2f.png)

<br>3. Next I logged into DC1 and enabled ICMPv4 to allow myself to ping from the client VM and just ensure that the client and communicate with the DC. </br>

<br>
