--- Simple functional code written in C to automate the configuration of a Cisco Access level Switch---
	--- Written by Zahid in 2016 as part of a 2nd Semester University project ---
			--- Pushed to GitHub on the 15th of Nov, 2024 ---

How to Use the .exe file:

Step 0: Open bin/Debug/AccessSWITCH.exe

Step 1: It will ask you to define the vlan range. enter a vlan range
according to the senario (number of ports on the switch). or just define a 20 vlan range
it will be fine.

Step 2: Sheck on the switch how many fast eth ports are there, if there are no
fe ports, only ge ports, then enter 0, otherwise enter the number of fe ports on the
switch.

Step 3: Be carefull here. if its a 28 port switch, 2 ports per vlan would be fine,
if its a 48 port switch, 3 ports per vlan will be fine. if you want to assign
2 ports per vlan then you have to increase the vlan range to say about 30.

Step 4: Just type 1 or 2 here, check on the switch what sequence number
is being used (0/1 or 0/0/1 etc).

Step 5: Look on the switch and enter the first fe port seuence number

Step 6: Type 0 here. if assigning ports/vlan for gig ports, restart the program
and type 0 when asked how many fe ports are there. the procedure is the
same for gig ports.