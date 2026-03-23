# RDP-access-and-configuration

# Summary

Using Teamviewer to remote access another PC to diagnose and implement a fix to high memory usage Issue. Using task manager on accessed PC the issue was a program opening several instances, each using resources which slowed the PC down. After closing program memory usage returned to normal limits, client advised to only run two VMs at once to avoid further performance issues.

I learned how to use Teamviewer to give customer support and that a resource intense program can have several instances running, and can look normal if viewed along side program which run only one instance at a higher intensity

# Documentation

* Support PC and Client PC download and install Teamviewer
* Create log in for Support PC
* Ask client for ID number shown on thier own Teamviewer application and enter into Support PC
* Ask client for password ensuring case sensitivity
* Access achieved
* Open task manager and check resource usage, no unusal activity shown
* Looking through all programs running showed several instances of VMware running. Each instance taking a small portion of resources, but together took the majority available [Screenshot](https://github.com/ZakHollows/RDP-access-and-configuration/blob/8190a58a1c5ac2eb61b74d0f1be2120819b0b1a9/screenshot%201.png)
* Closed each instance, Memory usage back within normal parameters [Screenshot](https://github.com/ZakHollows/RDP-access-and-configuration/blob/75224344cfd8b78eef44f7a12c10314b32d0b235/screenshot%204.png)
* Client advised to run only two VMs at once to avoid further performance issues
* Sessions closed
* Documentation of steps taken

