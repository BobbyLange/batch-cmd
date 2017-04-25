# What Is Batch?

For those who don't know, a Batch file is a text file containing a series of commands to be executed by Command Prompt (CMD). When a batch file is run, CMD reads the file and executes its commands.

To open your CMD, click START > RUN > type "CMD" > OK
(some of you may need to type "CMD.EXE")
(or you can click START > ALL PROGRAMS > ACCESSORIES > COMMAND PROMPT).

### Batch file for starting programs in windows

````batch
These are some VERY basic commands you need to know:
(please try out some of these commands in your CMD).

@echo off - This gets rid of that "c:\documents....etc"

echo - This displays a message, (e.g "echo hello" = "hello") because if you type "hello" into CMD it will interpret "hello" as the command

cls - Clears the CMD of all text.

color - Changes the color (type "help color" for a list of colors).

goto - Goes to a particular word in your text

pause - Pauses the command prompt and displays the message: "Press any key to continue..."
````


## Ipconfig

This command relays the IP address that your computer is currently using. However, if you’re behind a router (like most computers today), you’ll instead receive the local network address of the router.

Still, ipconfig is useful because of its extensions. “ipconfig /release” followed by “ipconfig /renew” can force your Windows PC into asking for a new IP address, which is useful if your computer claims one isn’t available. You can also use “ipconfig /flushdns” to refresh your DNS address. These commands are great if the Windows network troubleshooter chokes, which does happen on occasion.

<hr>


**nbstat** — For looking names of computers on your network.

**netstat -ano | find "est"** — To get a list of processes with established CP connections.

**tasklist | find "[process id]"** — To get the name of the executable associated with the particular process id that I'm interested in.

**cacls** — Most handy to manually access hidden files and folder.

**net use** — To map drives of networked CNC machines.

**chkdsk /f C:** — Checks your (C: partition) hard disk for errors and fixes bad sectors.

**systeminfo** — This command gives you a thorough list of info about your computer.

<hr>

### Comments

REM To skip the following command, put "REM" before them 

another alternative is ::

````batch
your codes here :: your comment
````

<hr>

### VER
This batch command shows the version of MS-DOS you are using.

### ASSOC
This is a batch command that associates an extension with a file type (FTYPE), displays existing associations, or deletes an association.

### CD
This batch command helps in making changes to a different directory, or displays the current directory.

### CLS
This batch command clears the screen.

### COPY
This batch command is used for copying files from one location to the other.

### DEL
This batch command deletes files and not directories.

### DIR
This batch command lists the contents of a directory.

### DATE
This batch command help to find the system date.

### ECHO
This batch command displays messages, or turns command echoing on or off.

### EXIT
This batch command exits the DOS console.

### MD
This batch command creates a new directory in the current location.

### MOVE
This batch command moves files or directories between directories.

### PATH
This batch command displays or sets the path variable.

### PAUSE
This batch command prompts the user and waits for a line of input to be entered.

### PROMPT
This batch command can be used to change or reset the cmd.exe prompt.

### RD
This batch command removes directories, but the directories need to be empty before they can be removed.

### REN
Renames files and directories

### REM
This batch command is used for remarks in batch files, preventing the content of the remark from being executed.

### START
This batch command starts a program in new window, or opens a document.

### TIME
This batch command sets or displays the time.

### TYPE
This batch command prints the content of a file or files to the output.

### VOL
This batch command displays the volume labels.

### ATTRIB
Displays or sets the attributes of the files in the curret directory

### CHKDSK
This batch command checks the disk for any problems.

### CHOICE
This batch command provides a list of options to the user.

### CMD
This batch command invokes another instance of command prompt.

### COMP
This batch command compares 2 files based on the file size.

### CONVERT
This batch command converts a volume from FAT16 or FAT32 file system to NTFS file system.

### DRIVERQUERY
This batch command shows all installed device drivers and their properties.

### EXPAND
This batch command extracts files from compressed .cab cabinet files.

### FIND
This batch command searches for a string in files or input, outputting matching lines.

### FORMAT
This batch command formats a disk to use Windows-supported file system such as FAT, FAT32 or NTFS, thereby overwriting the previous content of the disk.

### HELP
This batch command shows the list of Windows-supplied commands.

### IPCONFIG
This batch command displays Windows IP Configuration. Shows configuration by connection and the name of that connection.

### LABEL
This batch command adds, sets or removes a disk label.

### MORE
This batch command displays the contents of a file or files, one screen at a time.

### NET
Provides various network services, depending on the command used.

### PING
This batch command sends ICMP/IP "echo" packets over the network to the designated address.

### SHUTDOWN
This batch command shuts down a computer, or logs off the current user.

### SORT
This batch command takes the input from a source file and sorts its contents alphabetically, from A to Z or Z to A. It prints the output on the console.

### SUBST
This batch command assigns a drive letter to a local folder, displays current assignments, or removes an assignment.

### SYSTEMINFO
This batch command shows configuration of a computer and its operating system.

### TASKKILL
This batch command ends one or more tasks.

### TASKLIST
This batch command lists tasks, including task name and process id (PID).

### XCOPY
This batch command copies files and directories in a more advanced way.

### TREE
This batch command displays a tree of all subdirectories of the current directory to any level of recursion or depth.

### FC
This batch command lists the actual differences between two files.

### DISKPART
This batch command shows and configures the properties of disk partitions.

### TITLE
This batch command sets the title displayed in the console window.

### SET
Displays the list of environment variables on the current system.
