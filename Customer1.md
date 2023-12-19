# Project Cx 
    
## Customer One 
Customer One required a complete network rebuild and design for a Small Office/Home Office (SOHO), with all phases from Rough-in wiring to logical topology design, including the use of multiple VLANs to ensure network stability and security.

## Physical Design and Installation 
This was a remodel and expansion of an existing SOHO, which enabled the customer (referred to as "C" from this point forward) and I to design the network to their exact needs. 
The location consisted of two buildings, the main being a two story house, approximately 2400 square feet, and a small outbuilding "C" used as their office. The ISP (used by "C" prior to the remodel) is Starlink. "C"'s needs were as follows:
1. Reliable and consistent speeds, especially in the office, as they are a PM for a large multinational corporation, communicating remotely with multiple teams on separate continents. This circumstance also entails the need for a level of network security higher than a typical residential LAN.
2. Wireless access throughout the main residence.
3. The use of 5 POE surveillance cameras, as well as a smart lock and video doorbell (also POE) to ensure the comfort and security of "C" and their family. The cameras also necessitated some sort of storage for all footage.
4.  A large number of IOT devices ranging from smart speakers to appliances.
With these needs in mind, "C" and I came to the conclusion that an Ubiquiti "Dream Wall" would be the best choice of equipment to provide the base of the network, due to the user-friendly nature of the product, the number of available ports, the Wifi 6 capabilities and Ubiquitis NVR capabilities to handle the security footage. It would be installed at a point that was central to both the main residence and the outbuilding, without being a nuisance to the daily life in the home, while still ensuring that the equipment would be in a space adequate for the physical requirements of the unit, with the need for dedicated power, adequate ventilation and ease of use all being considered.
Cabling, except the proprietary Starlink cabling, is all CAT6, custom cut to length with RJ45 connectors, and was run as follows:
Two WAPs at either end of the first floor of the residence.
5 indivitual POE Security cameras
One POE Video doorbell
One POE Chime for doorbell
One Cat6 connection for hardlined WAP in outbuilding office for professional use.

## Logical Design and Implementation
After construction on the remodel was finished, the installation of the Ubiquiti unit was completed, and all physical connection points were in place, the logical portion of the process was conducted.  As network security and stability were high prority items for "C", I created five VLANs on the network using Ubiquiti software. For simplicity, all networks were /28. 
VLAN1- The main residence private WiFi space
VLAN2- The security device network
VLAN3- The IOT network
VLAN4- The office WAP
VLAN5- The "Guest" network, which was isolated from all other VLAN's on the network.

## After Action
ALl in all, the implemetation went smoothly. 
A bit more cable than necessary was intalled at the initial stage, but there were no issues with cabling being too short for easy use. 
While I ran all cabling to standard in wall junction boxes, some of Ubiquitis hardware, namely the doorbell chime, could be served better by simply having the cable stubbed out of the drywall so that an exact cut could be made to fit the unit. In order to ensure a clean fit, I cut for the unit directly adjacent to the box, ran the cable through the sidewall into the unit and put a blank plate over the juction box for a clean finish. 
Starlinks proprietary cable is designed with two angled connectors, both of which are relatively large, necessetating the installation of a secondary 1" conduit to allow for a clean pull and installation.
Ubiquiti's products are extremely user friendly and intuitive to install and use. Would highly recommend for small scale LANs such as this project.