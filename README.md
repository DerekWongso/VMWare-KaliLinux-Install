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
