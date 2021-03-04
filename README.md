# Networking
Computer Networking lessons.

Open system:
A system which is connected to the network and is ready for communication. 

Closed system: 
A system which is not connected to the network and can’t be communicated with. 

Computer Network: 
An interconnection of multiple devices, also known as hosts, that are connected using multiple paths for the purpose of sending/receiving data or media. Computer networks can also include multiple devices/mediums which help in the communication between two different devices; these are known as Network devices and include things such as routers, switches, hubs, and bridges. 

Network Topology:
The layout arrangement of the different devices in a network. Common examples include: Bus, Star, Mesh, Ring, and Daisy chain. 
 
What are the network layers?
While TCP/IP is the newer model, the Open Systems Interconnection (OSI) model is still referenced a lot to describe network layers. The OSI model was developed by the International Organization for Standardization. There are 7 layers:

1. Physical (e.g. cable, RJ45)
2. Data Link (e.g. MAC, switches)
3. Network (e.g. IP, routers)
4. Transport (e.g. TCP, UDP, port numbers)
5. Session (e.g. SYN/ACK)
6. Presentation (e.g. encryption, ASCII, PNG, MIDI)
7. Application (e.g. SNMP, HTTP, FTP)

People have come up with tons of mnemonic devices to memorize the OSI network layers. One popular mnemonic, starting with Layer 7, is “All People Seem To Need Data Processing.” But one that I’m partial to, which starts with Layer 1, is “Please Do Not Throw Sausage Pizza Away.”

The TCP/IP model is a more concise framework, with only 4 layers:

1. Network Access (or Link)
2. Internet
3. Transport (or Host-to-Host)
4. Application (or Process)

One mnemonic device for the TCP/IP model is “Armadillos Take In New Ants.”

APPLICATION (LAYER 7)

OSI Model, Layer 7, supports application and end-user processes. Communication partners are identified, quality of service is identified, user authentication and privacy are considered, and any constraints on data syntax are identified. Everything at this layer is application-specific. Everything at this layer is application-specific. This layer provides application services for file transfers, e-mail, and other network software services. Telnet and FTP are applications that exist entirely in the application level. Tiered application architectures are part of this layer.

<i>Layer 7 Application examples include WWW browsers, NFS, SNMP, Telnet, HTTP, FTP</i>

PRESENTATION (LAYER 6)

This layer provides independence from differences in data representation (e.g., encryption) by translating from application to network format, and vice versa. The presentation layer works to transform data into the form that the application layer can accept. This layer formats and encrypts data to be sent across a network, providing freedom from compatibility problems. It is sometimes called the syntax layer.

<i>Layer 6 Presentation examples include encryption, ASCII, EBCDIC, TIFF, GIF, PICT, JPEG, MPEG, MIDI.</i>

SESSION (LAYER 5)

This layer establishes, manages and terminates connections between applications. The session layer sets up, coordinates, and terminates conversations, exchanges, and dialogues between the applications at each end. It deals with session and connection coordination.

<i>Layer 5 Session examples include NFS, NetBios names, RPC, SQL.</i>

TRANSPORT (LAYER 4)

OSI Model, Layer 4, provides transparent transfer of data between end systems, or hosts, and is responsible for end-to-end error recovery and flow control. It ensures complete data transfer.

<i>Layer 4 Transport examples include SPX, TCP, UDP.</i>

NETWORK (LAYER 3)

Layer 3 provides switching and routing technologies, creating logical paths, known as virtual circuits, for transmitting data from node to node. Routing and forwarding are functions of this layer, as well as addressing, internetworking, error handling, congestion control and packet sequencing.

<i>Layer 3 Network examples include AppleTalk DDP, IP, IPX.</i>

Layer 3 provides switching and routing technologies, creating logical paths, known as virtual circuits, for transmitting data from node to node. Routing and forwarding are functions of this layer, as well as addressing, internetworking, error handling, congestion control and packet sequencing.

<i>Layer 3 Network examples include AppleTalk DDP, IP, IPX.</i>

 LINK (LAYER 2)

At OSI Model, Layer 2, data packets are encoded and decoded into bits. It furnishes transmission protocol knowledge and management and handles errors in the physical layer, flow control and frame synchronization. The data link layer is divided into two sub layers: The Media Access Control (MAC) layer and the Logical Link Control (LLC) layer. The MAC sub layer controls how a computer on the network gains access to the data and permission to transmit it. The LLC layer controls frame synchronization, flow control and error checking.

<i>Layer 2 Data Link examples include PPP, FDDI, ATM, IEEE 802.5/ 802.2, IEEE 802.3/802.2, HDLC, Frame Relay.</i>

PHYSICAL (LAYER 1)

OSI Model, Layer 1 conveys the bit stream – electrical impulse, light or radio signal through the network at the electrical and mechanical level. It provides the hardware means of sending and receiving data on a carrier, including defining cables, cards and physical aspects. Fast Ethernet, RS232, and ATM are protocols with physical layer components.

<i>Layer 1 Physical examples include Ethernet, FDDI, B8ZS, V.35, V.24, RJ45.</i>