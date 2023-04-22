**Later 7 - Application:** - used by app developer - data
- Closest layer to the end user
- Interacts with software appl;ications, for exemple the web browser
- HTTP and HTTPS are Layer 7 protocols
- Functions of Layer 7 include: 
	- Identifying communication partners
	- Synchronizing communication

**Layer 6 - Presentation:** - used by app developer - data
- Data in the application layer is in "application format".
- It need to be "translated" to a different format to be sent over the network
- The presentation Layer's job is to translate between application and network format
- For example, encryption of data as it is sent, and decryption of data as it is received
- Also translated between different Application - Layer formats

**Layer 5 - Sesssion:** - used by app developer - data
- Controls dialogues (sessions) between communicating hosts
- Establishes, managed, and terminates connections between the local application (for example, your web browser) and the remote application (for example, YouTube)

**Layer 4 - Transport:** - used by network engineer - segments
- Segments and reassembles data for communications between end hosts
- Breaks large pieces of data into smaller segments which can be mmore easily sent over the network and are less likely to cause transmission problems if error occur.
- Provide host-to-host communication
| Data | L4 header |
|------|-----------|

**Layer 3 - Network:** - used by network engineer - packets
- Provides connectivity between end hosts on different networks (IE. outside of the LAN)
- Provides logical addressing (IP addresses)
- Provides path selection between source and destination
- Routers operate at layer 3
| Data | L4 header | L3 header |
|------|-----------|-----------|

**Layer 2 - Data Link:** - used by network engineed - frames
- Provides node-to-node connectivity and data transfer (for example, PC to switch, switch to router, router to router)
- Defines how data is formatted for transmission over a physical medium (for example, copper UTP cables)
- Detects and (possibly) corrects Physical Layer errors
- Uses Layer 2 addressing, separate from layer 3 addressing (MAC addresses)
- Switches operate at Layer 2
| L2 trailer | Data | L4 header | L3 header | L2 header |
|------------|------|-----------|-----------|-----------|

**Layer 1 - Physical:** - used by network engineer - bits
- Defines physical characterictics of the medium used to transfer data between devices
- For example, voltage levels, maximum transmission distances, physical connector, cable specifications, etc.
- Digital bits are converted into electrical (for wired connections) or radio (for wireless connections) signals
- Cables, pin, layouts, etc. are related to the physical Layer
