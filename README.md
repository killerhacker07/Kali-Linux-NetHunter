![images (2)](https://user-images.githubusercontent.com/64261762/80286348-9840cc80-8748-11ea-9f0f-dcbf7396b1db.jpeg)
# Kali-Linux-NetHunter
Install Kali Linux on android Without Root Access

![images (1)](https://user-images.githubusercontent.com/64261762/80286373-aabb0600-8748-11ea-9573-19d96c847634.jpeg)


Install Apps From Play Store

Termux App
Link : https://play.google.com/store/apps/details?id=com.termux

bVNC Server App
Link : https://play.google.com/store/apps/details?id=com.iiordanov.freebVNC

Hacker's Keyboard
Link : https://play.google.com/store/apps/details?id=org.pocketworkstation.pckeyboard

Kali NetHunter Rootless Edition
Link : https://www.kali.org/docs/nethunter/nethunter-rootless/

Installation Steps

Install these apps 

Enable Hacker's Keyboard

Open Termux and type the commands 

- pkg update

- termux-setup-storage

- pkg install wget

- wget -O install-nethunter-termux https://offs.ec/2MceZW

- chmod +x install-nethunter-termux

- ./install-nethunter-termux

![010-NH-Rootless-Installation_Start](https://user-images.githubusercontent.com/64261762/80286759-d5a65980-874a-11ea-80ab-a6a322335626.jpg)

Commands & Usages

Command | To
-- | --
nethunter | start Kali NetHunter command line interface
nethunter kex passwd | configure the KeX password (only needed before 1st use)
nethunter kex & | start Kali NetHunter Desktop Experience user sessions
nethunter kex stop | stop Kali NetHunter Desktop Experience
nethunter <command> | run in NetHunter environment
nethunter -r | start Kali NetHunter cli as root
nethunter -r kex passwd | configure the KeX password for root
nethunter -r kex & | start Kali NetHunter Desktop Experience as root
nethunter -r kex stop | stop Kali NetHunter Desktop Experience root sessions
nethunter -r kex kill | Kill all KeX sessions
nethunter -r <command> | run <command> in NetHunter environment as root



