
1. Depending on the choose hosting service like Microsoft Azure/AWS, first, create an account. A quick
guide on how an account is created on Microsoft Azure.
2. If your hosting service has App services, then a WordPress instance can be created. 
3. If the host services do not offer capabilities of in-built app services, a Virtual Machine can be used to 
set up the system. Here is a documentation link on how to create a VM from scratch.
4. For domain name, create an account on the website Freenom to acquire the necessary custom domain 
name for any required time. Details on records can be input under the Record Management section. 
The picture below shows an example. Here is a link that illustrates in detail with regards to DNS 
Record Management.
5.Creating a free Cloudflare account and signing up.
6. Use a Cloudflare account to obtain an SSL certificate and secure the newly obtained domain name.
7. DNS Records pointing to the public IP address created from Azure VM to the Cloudflare account in 
the DNS Management Section. The following link can be helpful in this regard.

While on the WordPress Dashboard( Steps to restore the system with exisiting Plugin)
1.Activate the WPVivid plugin in the plugins tabs of the WordPress Dashboard
2.After activating the plugin, go to the general setting of the WPVivid plugin and check the following 
general settings to avoid any problems occurring in the future for the plugin.
3.  The obtained zip file from the backup folder can be used to restore the system on the developers local 
system and will also the process having to deploy the website from scratch. After the system has been 
restored correctly the developer can continue working on implementing future changes to the website
4.Backup also can be performed with the help of the same plugin manually or automatically based on 
the developers wishes. The picture shown below show how backup can be performed through the 
same plugin. 

Other forms of backup include manually generating an FTP hostname and password with the help of the "Get 
Publish Profile" feature available on the hosting services and can be used with file transferring services such 
as FileZilla to manually download the required files to the local system and backing them up. This process, 
however, takes a lot of time as it involves downloading several files manually storage, and segregation. All 
individual files can be uploaded on Github via Github Desktop which may also serve as online backup 
storage.
