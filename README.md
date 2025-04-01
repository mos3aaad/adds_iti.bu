--  Project Overview & Objectives

overall architecture and the main goals aimed to achieve during Windows Server Administration project.
servers and clients involved, their roles, and the configurations needed to fulfill the domain requirements for ITI.local. 




--  Project Foundation 

As a base for our Windows Server Administration project: created a foundational environment consisting of three servers and one client machine:

DC1 (Domain Controller)

RODC (Read-Only Domain Controller)

WS (Web Server)- PC1 (Client Computer)

All three servers were installed with Windows Server 2022 Desktop Edition, while PC1 was installed with Windows 10 Pro Edition. 

--  Initial Server Configuration 

After setting up the virtual machines, we proceeded with the initial configuration for all servers to ensure proper communication and compatibility within the network environment. 
The following changes were applied to each server: 

•	Assigned static IPv4 addresses to avoid IP conflicts and ensure stability within the internal network. 

•	Configured static DNS settings, pointing to the domain controller once it was set up. 

•	Set the system time zone to (UTC+02:00) Cairo and synchronized system clocks to avoid time-related authentication issues. 

•	Disabled the Windows Defender Firewall, which was done to prevent interference during service setup and testing. 

-> Note: Disabling the firewall is a security risk in a real-world deployment and should only be done in lab or testing environments. 


•	Enabled Remote Desktop and Remote Management on all servers to allow easier access and configuration. 
•	Configured each machine with appropriate naming conventions
