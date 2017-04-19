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

<hr>


nbstat — “for looking u names of computers on your network.”

netstat -ano | find “est” — “to get a list of processes with established CP connections.”

tasklist | find “[process id]” — “to get the name of the executable associated with the particular process id that I’m interested in.”

cacls — “most handy to manually access hidden files and folder.” 

net use — “to map drives of networked CNC machines.”

chkdsk /f C: — “checks your (C: partition) hard disk for errors and fixes bad sectors.”

systeminfo — “this command gives you a thorough list of info about your computer.”
