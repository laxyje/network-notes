# Module 5 - Communication Principles

## What I learned

### Communication protocols
Protocols are the rules that allow devices to communicate correctly over a network.  
They define how messages are sent, received, formatted, and understood.

### Why protocols matter
Devices on a network must follow common rules to communicate successfully.  
Without shared protocols, different devices would not understand each other.

### Message format
A message must follow a specific structure or format.  
This helps the receiving device understand what kind of data it is getting.

### Message size
Protocols define how large a message can be.  
If a message is too large, it may be divided into smaller pieces before being sent.

### Timing
Communication depends on timing.  
Protocols help control how fast data is sent and when devices can transmit.

### Encoding
Before data is sent, it is converted into signals.  
Depending on the network media, data may be encoded as electrical signals, light, or radio waves.

### Encapsulation
When data is sent, extra information is added to it, such as the source and destination.  
This process is called encapsulation.

### Message patterns
Some communication requires a request and a response.  
Other types may use acknowledgments or stream data continuously.

### Communication standards
Standards are shared technical rules that ensure devices and software work together correctly.  
They make it possible for different companies and technologies to communicate over the internet.

### RFC
RFC stands for Request for Comments.  
RFC documents are used to describe internet standards, protocols, and technical ideas.

### Standards organizations
Different organizations create and maintain standards used in networking and the internet.  
Examples include IETF and IEEE.

### TCP/IP model
The TCP/IP model is used to describe how internet communication works.  
It has four layers:
- Application
- Transport
- Internet
- Network Access

### TCP/IP application layer
This layer includes services and protocols used directly by applications and users.

### TCP/IP transport layer
This layer supports communication between end devices.  
It is responsible for dividing and reassembling data and supports reliable delivery.

### TCP/IP internet layer
This layer is responsible for logical addressing and selecting the best path through the network.

### TCP/IP network access layer
This layer handles access to the physical network, including hardware and media such as Ethernet and Wi-Fi.

### OSI model
The OSI model is a more detailed reference model used to describe network communication.  
It has seven layers:
- Application
- Presentation
- Session
- Transport
- Network
- Data Link
- Physical

### OSI and TCP/IP comparison
The TCP/IP model is more practical and closely related to real internet protocols.  
The OSI model is more detailed and is often used for learning and troubleshooting.

The layers map like this:
- OSI Application + Presentation + Session = TCP/IP Application
- OSI Transport = TCP/IP Transport
- OSI Network = TCP/IP Internet
- OSI Data Link + Physical = TCP/IP Network Access

## Key terms

- **Protocol** – a set of rules for communication  
- **Standard** – a shared rule or guideline used by devices and systems  
- **Message format** – the structure of a message  
- **Message size** – the allowed size of transmitted data  
- **Timing** – the speed and order of communication  
- **Encoding** – converting data into signals for transmission  
- **Encapsulation** – adding addressing and control information to data  
- **Message pattern** – the way messages are exchanged, such as request and response  
- **RFC** – a document that describes internet standards and protocols  
- **IETF** – an organization that develops and manages internet standards  
- **IEEE** – an organization that creates technical networking standards  
- **TCP/IP** – the model used to describe internet communications  
- **OSI** – a seven-layer reference model for network communication  
- **Transport layer** – the layer responsible for segmenting and reassembling data  
- **Network Access layer** – the layer related to hardware, media, and local transmission  

## My summary
This module explained that network communication depends on shared protocols and standards.  
It also introduced the TCP/IP and OSI models as ways to understand how communication is organized in layers.
