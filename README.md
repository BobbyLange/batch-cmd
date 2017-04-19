# batch-cmd
Batch file for starting programs in windows

````batch
@echo off
color 40
Title Admin : AdminName
start chrome
Pause
````


## Ipconfig

This command relays the IP address that your computer is currently using. However, if you’re behind a router (like most computers today), you’ll instead receive the local network address of the router.

Still, ipconfig is useful because of its extensions. “ipconfig /release” followed by “ipconfig /renew” can force your Windows PC into asking for a new IP address, which is useful if your computer claims one isn’t available. You can also use “ipconfig /flushdns” to refresh your DNS address. These commands are great if the Windows network troubleshooter chokes, which does happen on occasion.
