# Intro to LAN

## Introduction
* This room is about local area network(LAN) topologies
* Gives insight in Switch, Router, A primer on subnetting, ARP, DHCP

## Objective
* Help us identify types of LAN topologies
* To make us understand how Switch, Router, A primer on subnetting, ARP, DHCP works
  
## Prerequisites
* This room is designed for complete beginners who have no knowledge about LAN, ARP, DHCP etc...
* The only requirement was a computer or desktop.

## What I Learned
1. ### Local Area Network (LAN) Topologies
    * When we refer to the term _topology_ we are talking about the design or the look of the network
    * In this room there was only 3 topologies lets see them one by one
      #### a, _Star Topology_
      * Devices are individually connected via a central network device such as hub or switch
      * Advantage : scalable in nature(very easy to add new devices)
      * Disadvantage : expensive, requires more maintenance, trouble shooting is hard(because of increase dependence on maintenance),
                       if the central device or transmitter fails then the whole system fails
      #### b, _Bus topology_
      * It relay on a single connection also know as backbone cable
      * Advantage : easy, cost efficient
      * Disadvantage : difficult troubleshooting, can become slow and bottlenecked(if devices within the topology requested data at the same time), little redundancy in place in case of failures
      #### c, _ring topology(token topology)_
       * Devices are directly connected to each other forming a loop
       * It uses other devices to transfer data to its destiny
       * Advantage : easy to troubleshoot, less prone to bottlenecks
       * Disadvantage : not efficient way that data can travel, one fault cuts all connection
         
  2. ### what is a switch
       * They are dedicated devices that connects devices within the same network using ethernet
       * Switches have ports in which it helps connect many devices at one time
       * More than hub/repeater switch is much more efficient the one reason is when a switch gets any data it doesn't send to  everyone like hub it sends to the targeted area
       * Both switches and routers can work together this increase the reliability of the connection even if one fails another way can be used but this has down side too packets takes               longer time to travel
      
  3. ### what is a router
       * connect two networks to pass data , when data travels from one device to another the process is called routing
       * when devices are connected by many path router is helpful
      
  4. ### A primer on subnetting
       * Subnetting means splitting up a network into a smaller one
       * Lets say we need to send data to another network so the network administrator use subnetting to categories and assign specific part of networks
       * Just like IP address its divided into 4 bytes
       * Subnets use IP addresses in three different ways:
         1. Identify the network address
         2. Identify the host address
         3. Identify the default gateway
        
  5. ### ARP (address resolution protocol)
       * This allows devices to identify themselves on a network
       * Allow devices to associate mac address with an IP address
       * Cache - is a stored information
       * When an _ARP request_ is sent, a message is broadcasted on the network to other devices asking, "What is the mac address that owns this IP address?"
       * When the other devices receive that message, they will only respond if they own that IP address and will send an _ARP reply_ with its MAC address.
       * The requesting device can now remember this mapping and store it in its _ARP cache_ for future use
      
  6. ### DHCP
       * Is used to assign IP address to our devices automatically
       * If it has not already been manually assigned an IP address, it sends out a request(DHCP Discover) to see if any DHCP servers are on the network.
       * The DHCP server then replies back with an IP address the device could use (DHCP Offer).
       * The device then sends a reply confirming it wants the offered IP Address (DHCP Request), and then lastly, the DHCP server sends a reply acknowledging this has been completed, and           the device can start using the IP Address (DHCP ACK).
       
## Conclusion
* This room is great to learn about how Switch, Router, ARP, DHCP works
* Also about types of LAN topology 
