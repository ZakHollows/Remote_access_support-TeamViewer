# RDP-access-and-configuration

# Summary

Using Teamviewer to remote access another PC to diagnose and implement a fix to high memory usage Issue. Using task manager on accessed PC the issue was a program opening several instances, each using resources which slowed the PC down. After closing program memory usage returned to normal limits, client advised to only run two VMs at once to avoid further performance issues.

# Documentation

Support PC and Client PC download and install Teamviewer
Create log in for Support PC
Ask client for ID number shown on thier own Teamviewer application and enter into Support PC
Ask client for password ensuring case sensitivity
Access achieved
Open task manager and check resource usage
[Screenshot] (https://github.com/ZakHollows/RDP-access-and-configuration/blob/8190a58a1c5ac2eb61b74d0f1be2120819b0b1a9/screenshot%201.png)
Some processes taking large amounts of resources, these tasks dont account for total memory usage
Several instances of VM ware running taking up memory resources
Closed each instance, Memory usage back within normal parameters [Screenshot] ()
Client advised to run only two VMs at once to avoid further performance issues
Sessions ended
