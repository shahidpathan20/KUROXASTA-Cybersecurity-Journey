LAN(Local area network) is a network that connect devices in a small area like:- home, school, office


it allows devises to share data, file, printer and network 


## TOPOLOGY

how devises are arranged in a network

<h2>
1.⭐Star Topology 
</h2>

All devises are connected to a central device (switch/hub)


Advantages

<ul>
<li>
Easy to manage 
</li>
<li>
Easy to Expand (we can add new devises)
</li>
<li>
Fast performance 
</li>
</ul>



Disadvantage

<ul>
<li>
If central devise fails —whole network stop 
</li>
<li>
more expensive (more cable and switches)
</li>
</ul>




<h2>
2 .🚌Bus topology 
</h2>

All devises share one main cable (Backbone)


Advantages 

<ul>
<li>
cheap 
</li>
<li>
Easy to install
</li>
</ul>



Disadvantages 

<ul>
<li>
slow when traffic increases 
</li>
<li>
Hard to troubleshoot 
</li>
<li>
If backbone fails —network fails  
</li>
</ul>


<h2>
3.⭕Ring topology  
</h2>


Devises form a circle 



Advantages

<ul>
<li>
no heavy traffic 
</li>
<li>
Easy to troubleshoot than bus topology 
</li>
</ul>



Disadvantages 

<ul>
<li>
If one device/cable fails — whole network affected 
</li>
<li>
data must pass through multiple devices (slow)
</li>
</ul>


<h3>
WHAT IS SWITCH 
</h3>

A switch connects multiple devises in a LAN


send data only to the correct device not everyone 



benefits 


<ul>
<li>
reduce network traffic 
</li>
<li>
faster and efficient communication 
</li>
<li>
used in school, offices, companies 
</li>
</ul>

<h3>
WHAT IS ROUTER 
</h3>


A router connect different networks together 



example:-home network— internet 


functions:

direct data between networks (This is called routing)

<h3>
ROUTING 
</h3>


process of sending data between networks 


<ul>
<li>
help data find best path 
</li>
<li>
works like GPS for internet packets 
</li>
</ul>


IMPORTANTS POINTS TO REMEMBER 


- LAN = small network area
- Topology = network design
- Switch = smart internal traffic controller
- Router = connects LAN to internet
- Star topology is most commonly used today



<h2>
SUBNETTING 
</h2>

subnetting is dividing a large network into smaller networks (subnet)


why this is in use 


<ul>
<li>
Better network management 
</li>
<li>
improves speed 
</li>
<li>
reduces traffic 
</li>
<li>
improves security 
</li>
</ul>


example 



big school-divided into classes 



each class=a student 


now, subnet has 3 main thing

<h3>
1\. Network Address 
</h3>

<ul>
<li>
This is a ID of the student 
</li>
<li>
it identifies the whole network 
</li>
<li>
it is not assigned to any network 
</li>
</ul>


example :

192.168.1.0/24


here,192.168.1.0 is a network address 


<h3>
2\. Host address 
</h3>

<ul>
<li>
These are the usable IPs for devises 
</li>
<li>
computer, phone, printers, use these IPs 
</li>
</ul>


Example:


192.168.1.- first device 



192.168.1.2- second device 



192.168.1.254- last devices 



these are called host address 


<h3>
3\. Default Gateway 
</h3>

<ul>
<li>
This is the Exit point of the network 
</li>
<li>
usually the router’s IP address 
</li>
</ul>

Example:

192.168.1.1(often gateway)





simple to understand 


<ul>
<li>
Network address—start 
</li>
<li>
hosts —usable devises 
</li>
<li>
gateway—exit to internet
</li>
</ul>



### ARP(address resolution protocol)

<ul>
<li>
find MAC address from IP address 
</li>
<li>
works inside LAN only 
</li>
<li>
used when devices wants to talk to another device
</li>
</ul>

### DHCP(Dynamic Host Configuration Protocol)

Automatically assigns:

<ul>
<li>
IP address 
</li>
<li>
Subnet mask 
</li>
<li>
Gateway 
</li>
<li>
DNS
</li>
</ul>


Makes network setup automatic 



now the explanation of how everything works together 


<ol>
<li>
devises join network 
</li>
<li>
DHCP gives IP 
</li>
<li>
ARP find MAC address 
</li>
<li>
Switch send data inside LAN 
</li>
<li>
Router send data outside LAN (internet)
</li>
</ol>




one shot revision 


<ul>
<li>
LAN = small network
</li>
<li>
switch=connect devices 
</li>
<li>
router = connects network 
</li>
<li>
ARP = find MAC 
</li>
<li>
DHCP= gives IP 
</li>
<li>
Subnetting=divides networks 
</li>
</ul>
