# lede-on-virtualbox

### How to setup a LEDE software based router using Virtual box and MS Windows Internet Sharing (ICS)

This is a simple tutorial about how to setup a LEDE on VirtualBox (or maybe other virtual machine software)
and forward the virtual NIC port to a real NIC port using Microsoft Internet Connection Sharing (ICS).
So you'll be able to build a software based router without buying a dual-NIC-Port computer.

But you'll have to be aware that you still need two NICs if you want your PC (running LEDE VM) to server as a real router.
Aka, other physical devices will connect to your PC using one of your NICs.

But if you don't need to provide routing services for other devices, the LEDE is running ONLY on your local machine, and provide 
routing services for your PC, you dont have to have at least to NICs.

Tips: If you have a wireless NIC, and also have a cable NIC, you are considered to have two NICs. :-)

All disc images mentioned and uploaded in this project belongs to the original author and/or builder.

All plugins mentioned and uploaded in this project belongs to the original author and/or builder.

This repo is ONLY used for learning / or backup purpose. Please DO NOT maliciously speculate the author's original purpose.  
 
### 如何使用 VirtualBox 与 Windows Internet 连接共享 （ICS） 搭建一个软路由并对外提供服务
 
该文章为使用 VirtualBox 搭建一个 LEDE 软路由，并通过增加一块物理网卡，将虚拟机软路由用于真正对外提供服务的简单教程

仓库中所涉及到的镜像一切权利归原作者所有

仓库中所涉及到的插件代码包一切权利归原作者所有

该仓库仅方便自用 & 备份。请勿恶意揣测和演绎。


