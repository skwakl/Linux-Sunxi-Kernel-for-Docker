# Linux-Sunxi-Kernel-for-Docker
For pcduino3 nano (Allwinner A20)

Kernel sunxi-v3.4.103-r1 configured for Docker (no overlay or aufs), tested only with archlinux. 

I can upload the modules as well as the config if needed. 

Check out and read:

http://forum.linksprite.com/index.php?/topic/4151-anyone-got-kernel-v34103-running/#entry10208

http://forum.lemaker.org/thread-4252-1-1-.html

http://blog.xebia.com/2014/08/25/docker-on-a-raspberry-pi/

Usage:
* Make mmc boot from board-config.sh
* Replace uImage on mmc partition 1
* Replace mmc partition 2 fs with ArchLinux rootfs 
