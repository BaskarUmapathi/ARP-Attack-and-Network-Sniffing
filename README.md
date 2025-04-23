# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
```
Name: Baskar U
Reg.no: 212223220013
```
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

![Screenshot 2025-04-23 210039](https://github.com/user-attachments/assets/701dd94d-f7f8-429a-9e0c-ab87587ca174)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2025-04-23 220854](https://github.com/user-attachments/assets/b76b474e-59d5-4d3b-8689-64cfdfad3028)

## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2025-04-23 224300](https://github.com/user-attachments/assets/5d86792b-7891-4ce0-953d-f70cbc72ce25)

In Kali issue the following commands:
sudo dsniff
## OUTPUT:

![Screenshot 2025-04-23 230051](https://github.com/user-attachments/assets/013074d2-5b7a-4892-979d-ae7956930319)

Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT:

![Screenshot 2025-04-23 225317](https://github.com/user-attachments/assets/d1b56777-a149-426d-abeb-18eafe1eca75)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
