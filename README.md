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
![1](https://github.com/user-attachments/assets/95c0f9d6-5018-4dc0-b526-f0a6b6ca5202)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Alt text](img/1.png)

 dsniff:



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/user-attachments/assets/1ffccff8-b78d-4525-a8a4-1051989ca760)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="966" height="665" alt="{EC12060E-B9D7-4116-8A18-3D1A66A80335}" src="https://github.com/user-attachments/assets/537f387b-ebc7-4eea-b334-04c5fbc375d4" />



Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![5](https://github.com/user-attachments/assets/5a971b57-5f54-4648-a399-3b5abd43deca)
## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:
<img width="1280" height="800" alt="spi" src="https://github.com/user-attachments/assets/e664604d-718e-42c8-8814-10dcc68e9a76" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
