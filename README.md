# VMWare and Kali Linux Installation

This project will demonstrate how to properly install both **VMWare Workstation** and **Kali Linux.** **VMWare** allows the users to set up virtual machines on a single physical machine and have its own operating system. **Kali Linux** is an operating system based on Debian Linux that is mainly designed for tasks such as forensics and penetration testing.

## VMWare Installation

You can go to https://www.vmware.com/products/workstation-player.html and download **VMWare** from there.
Locate the installation file and run the program

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vmwarepro.png)

You can choose to have the enhanced keyboard options, which enables users to have better handeling with international keyboards. I opted not to install the driver

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vmwarepro2.png)

The next step asks if you want to have update checks on startup. I opted to keep it checked to have opportunities to improve my experience of **VMWare** with updates.

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vmwarepro3.png)

After the setup it should look like this:

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vmwarepro5.png)

Go to the Help option and choose the Licensce Key option. You can choose to do the 30 day trial or input the key if you bought the product. If you don't input the key, you will not be able to utilize all of **VMWare's** functionalities.  

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/key.png)


## Kali Linux Installation 

Go to https://www.kali.org/get-kali/ and scroll down until you find the Kali Linux Changelog. Depending on what type of system you have, you may want the 64x or 32x version of **Kali Linux**

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kldl.png)

Go to **VMWare** and create a new virtual machine with the option of custom installation checked

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/custom.png)

Choose the hardware compatability. In this case, I chose Workstation 16.x as it is the most recent edition.

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/ws16.png)

Choose to install the Operating System later.

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/later.png)

When choosing the guest operating system, make sure to choose Linux. For the version, make sure to choose Debian or Ubuntu as it is what Kali Linux is based off of.

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/debian.png)

Name your virtual machine. In this example, I named my VM **DWKaliLinux**

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vmname.png)

Input the number of processors and cores you want to give to your virtual machine. The amount you can give depends on the specifications of your computer. In this case, I gave my virtual machine 2 processors and 2 cores. 

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/core.png)

Input how much virtual memory or VRAM you want to give your virtual machine. This determines how fast your VM will run. The more VRAM you can provide, the better the speed

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vram.png)

Choose NAT if you want to utilize the internet on your VM. 

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/nat.png)

For disk and I/O controller settings, I used the reccommended settings

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/iocon.png)
![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/SCSI.png)

Input how much disk capacity you want for the VM. For the demonstration, I used 100 Gb of disk capacity. 20 is the reccommended 

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/vdisksize.png)

Go to the CD/DVD settings and set the ISO image path to the **Kali Linux** ISO.

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/isopath.png)

Power up Kali Linux and choose advanced installer, and then graphical installer

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kalistart.png)
![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kalistart2.png)

Once the installer loads up, choose the language you want and location

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap1.png)

Choose the keyboard configuration you want. I chose American English

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/Kaligap2.png)

Enter a hostname for the system. For my hostname, it is **DWKali.**

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/Kaligap3.png)

Create a domain name for part of your internet address

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap4.png)

Create your username

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap5.png)

Create your login password

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap6.png)

Set up your time zone

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap7.png)

Use the entire disk to partition and put all the files in one partition as reccommended

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap8.png)
![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap10.png)

Now, write the changes to disk 

![github-small](https://github.com/DerekWongso/VMWare-KaliLinux-Install/blob/main/images/kaligap11.png)

