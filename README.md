# testing-foss-using-foss
How to setup a OpenSource testing environment to test OpenSource projects 

Like mentioned in the video I ran into two issues on Ubuntu 18.04 with the Gnome Boxes application 

- https://bugs.launchpad.net/ubuntu/+source/gnome-boxes/+bug/1762205
- https://bugs.launchpad.net/ubuntu/+source/gnome-boxes/+bug/1762205/comments/4

After that had some issues with the bridged virtual network adapter. The following link solves that one. 
- https://raffer.one/2020/03/gnome-boxes-with-bridged-networking-on-ubuntu-20-04/

# Testing connections

- Linux and Windows you can use telnet client on the latter you need to install it in Windows add and remove windows components menu. 
```
telnet <your guest vm's ip> 22 
```


# References: 
- https://youtu.be/SFBwr7A7U2c the youtube video
- Putty https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
- VirtualBox https://www.virtualbox.org/
- Gnome boxes https://wiki.gnome.org/Apps/Boxes
- Virt-Manager https://virt-manager.org/
