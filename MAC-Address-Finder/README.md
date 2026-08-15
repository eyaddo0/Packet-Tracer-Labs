MAC Address Finder

A simple cisco packet tracer lab demonstrating basic communication between
devices on the same local network and how MAC address can be discovered using
Address Resolution Protocol (ARP)

-------------------------

Lab setup

• 1 switch
• 3 End devices (X, Y, Z)

-------------------------

What i did
 
• Connected all devices to the switch
• Assigned IPv4 addresses for each device (X: 192.168.1.10 / Y: 192.168.1.20 / Z: 192.168.1.30)
• Checked device X ARP cache by using "arp -a" in CMD (No device MAC Address was found)
• Pinged device Y & Z by using "ping" command
• Did the same for each device and pinged missing devices MAC Addresses
• Checked each device ARP cache and made sure all device can communicate with each other

-------------------------

Concepts practiced

• IPv4 Addressing
• MAC Address
• ICMP Ping
• Layer 2 Switching
• Basic network connectivity

-------------------------
