# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

From kali linux issue the command : sudo arpspoof -i eth0 -t

![image](https://github.com/Irenejecinthamerlin/ARP-Attack-and-Network-Sniffing/assets/128350225/e7ccbcb3-f3f7-44d6-a97c-1c1127f68561)

From Kali linux issue the command : sudo arpspoof -i etho -t

![image](https://github.com/Irenejecinthamerlin/ARP-Attack-and-Network-Sniffing/assets/128350225/3be000ca-f2ad-4264-ac08-c44e6f75a8a5)

dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:


 ![image](https://github.com/Irenejecinthamerlin/ARP-Attack-and-Network-Sniffing/assets/128350225/2403d0b6-91f6-4a08-92dd-a1799638fc45)


In Kali issue the following commands: sudo dsnifff

## Output:

![image](https://github.com/Irenejecinthamerlin/ARP-Attack-and-Network-Sniffing/assets/128350225/2b085dc0-5951-4b8f-8104-5c004b62a673)

Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Irenejecinthamerlin/ARP-Attack-and-Network-Sniffing/assets/128350225/ecccdce3-3dae-49cb-b8d1-bdb479fff33d)




## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
