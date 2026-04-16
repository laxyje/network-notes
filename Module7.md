# Module 7 - The Access Layer

## What I learned

### Encapsulation
Encapsulation is the process of placing one message format inside another message format before it is sent across the network.  
It adds the information needed for delivery, such as addressing and control information.

### De-encapsulation
De-encapsulation is the reverse process.  
The receiving device removes the added headers and processes the original data.

### Ethernet frame
An Ethernet frame is the Layer 2 format used to carry data across a local Ethernet network.  
It contains important fields such as the source MAC address, destination MAC address, type/length, data, and frame check sequence.

### Source and destination MAC addresses
The source MAC address identifies the sender on the local network.  
The destination MAC address identifies the intended receiver on the local network.

### Frame Check Sequence (FCS)
FCS is used to detect transmission errors in an Ethernet frame.  
It helps the receiving device check whether the frame was damaged in transit.

### Access layer
The access layer is where end devices connect to the network.  
In Ethernet networks, this includes communication between hosts and switches.

### Ethernet hub
An Ethernet hub sends traffic out of every port.  
Because this causes collisions and poor performance, hubs are now considered obsolete.

### Ethernet switch
A Layer 2 switch makes forwarding decisions based on MAC addresses.  
It reads the destination MAC address of a frame and forwards it through the correct port.

### MAC address table
A switch stores learned MAC addresses in a MAC address table.  
This table maps MAC addresses to switch ports.

### How a switch learns
A switch learns by examining the source MAC address of incoming frames and the port where the frame was received.  
It then stores that information in the MAC address table.

### Flooding
If the destination MAC address is unknown, the switch forwards the frame out all ports except the incoming port.  
This process is called flooding.

## Key terms

- **Encapsulation** – adding headers and other information to data before transmission  
- **De-encapsulation** – removing those headers at the receiving device  
- **Ethernet frame** – Layer 2 message format used in Ethernet  
- **MAC address** – physical address of a network interface  
- **Source MAC address** – MAC address of the sender  
- **Destination MAC address** – MAC address of the receiver  
- **FCS** – field used to detect frame errors  
- **Access layer** – network layer where end devices connect  
- **Hub** – old device that sends traffic out all ports  
- **Switch** – Layer 2 device that forwards frames based on MAC addresses  
- **MAC address table** – table used by a switch to map MAC addresses to ports  
- **Flooding** – forwarding a frame out all ports except the incoming one when the destination is unknown  

## My summary
This module explained how data is encapsulated in Ethernet frames and how communication works at the access layer.  
It also showed how switches learn MAC addresses, build MAC tables, and forward frames across a local network.
