# Computer Network - *CN*

### Introduction to Networks vs. Computer Networks

- **Network**: A system that carries a commodity or information between two or more entities.
   - Examples: Transportation networks, postal systems, telephone networks.
- **Computer Network**: A system that carries information between two or more entities in the form of electric signals.

### Analogies Between Transportation and Computer Networks

- **Vehicles/People** ↔ **Packets/Payload**
- **Street address** ↔ **IP address**
- **Intersection** ↔ **Bridge/router**
- **Traffic jam** ↔ **Network congestion**
- **Stop and go traffic light** ↔ **Flow control**
- **Taking alternative path** ↔ **Alternative route**
- **Accident** ↔ **Collision of packets**
- **Following a route to destination** ↔ **Routing algorithm**

### Why Study Computer Networks?

- **Potential Benefits**:
   - Good-paying jobs in network administration, programming, or research.
   - Increasing usage in daily life and business.
- **Usage Examples**:
   - **User Level**:
      - Email, web browsing, social networks, video-on-demand, online banking/shopping, online gaming.
   - **Business Level**:
      - Accessibility of data, programs, and equipment irrespective of physical location.
      - E-commerce companies like Amazon, eBay, Flipkart.
   - **Futuristic Usage**:
      - Sensor networks for environmental monitoring, health monitoring, interplanetary internet.

### Impact of Computer Networks (As of 2010)

- 2 billion Internet users.
- 294 billion emails sent per day.
- 255 million websites.
- 2 billion videos watched per day on YouTube.
- 600 million Facebook users.
- (As of 2013) 1 billion YouTube users (15% of Earth's population).

#### Job Opportunities in Networking

- **Deployment, Maintenance, and Debugging**:
   - Network administrators, network technicians, field engineers, network analysts.
- **Design and Development**:
   - Network programmers, research scientists, professors.

### Benefits of Networking

- Connectivity and communication.
- Data sharing and hardware sharing.
- Internet access.
- Data security and management.
- Performance enhancement.
- Entertainment.

### Disadvantages of Networking

- Hardware, software, and setup costs.
- Management costs for hardware and software.
- Undesirable sharing.
- Data security concerns.

### Requirements for Computer Communication

- **Hardware**:
   - **Communication End Points**: Servers, desktops, laptops, smartphones, etc.
   - **Network Interface Card**: Hardware that connects a device to a network.
   - **Communication Links**: Physical media interconnecting computing devices (e.g., co-axial cable, fiber optics, twisted-pair, wireless).
   - **Switches/Routers**: Interconnect networks made up of hosts and links.
- **Software**:
   - **Protocol**: Defines the format and rules for exchanging messages.
      - What to send ::(Format).::
      - When to send and how to act ::(Rules).::
   - **Example of Protocol Interaction**:
      - Human protocol vs. computer network protocol (e.g., "Hi", "Hi", "Got the time?", "2:00").
      - TCP connection request and response for web pages.

   ### **Types of Networks:**

   - Mobile Network
   - Home Network
   - Global ISP
   - Regional ISP
   - Institutional Network

   ### Network Components

   **Network Edge:**

   - **End Systems (Hosts):** Run application programs (e.g., Web, email) at the edge of the network.
   - **Client/Server Model:**
      - Client hosts request and receive services from always-on servers (e.g., Web browser/server; email client/server).
   - **Peer-Peer Model:**
      - Minimal or no use of dedicated servers (e.g., Skype, BitTorrent).

   **Access Network:**

   - Wired and wireless communication links.

   **Network Core:**

   - Mesh of interconnected routers.
   - **Data Transfer Methods:**
      - **Circuit Switching:** Dedicated circuit per call (e.g., telephone network).
      - **Packet Switching:** Data sent through the network in discrete "chunks."

   ### Types of Computer Networks

   ## **Distinguished by Geographical Area:**

   - **Personal Area Network (PAN):**
      - Smallest network, personal to a user.
      - Examples: Wireless computer keyboard and mouse, Bluetooth enabled headphones, wireless printers, and TV remotes.
   - **Local Area Network (LAN):**
      - Spans inside a building, operated under a single administrative system.
      - Useful for sharing resources like printers, file servers, scanners, and internet among computers.
      - Examples: Organizational offices, schools, colleges/universities.
   - **Metropolitan Area Network (MAN):**
      - Expands throughout a city (e.g., cable TV network).
      - Helps organizations connect offices within a city.
   - **Wide Area Network (WAN):**
      - Covers a wide area, possibly spanning a whole country.
      - Provides connectivity to MANs and LANs.
      - Examples: Telecommunication networks.
   - **Internet:**
      - A network of networks connecting all WANs, with potential connections to LANs and home networks.
      - Enables worldwide information sharing and access.

      ### Computer Network Topologies

   ## **Types of Network Topologies:**

   - **Point-to-Point:** Direct connection between two hosts.
   - **Bus:** Single communication line or cable shared by all devices; failure of the line affects all devices.
   - **Star:** All hosts connected to a central hub device (hub, switch, router); hub failure affects all hosts.
   - **Ring:** Each host connects to exactly two other hosts in a circular structure; failure of one host affects the whole network.
   - **Mesh:** Hosts have point-to-point connections (full mesh or partial mesh); provides high reliability.
   - **Tree:** Combination of bus and star topologies; hierarchical structure.

   ### Switching in Computer Networks

   **Types of Switching:**

   - **Circuit Switching:**
      - Dedicated communication path between two nodes (e.g., telephone).
   - **Message Switching:**
      - Whole message is received, buffered, and forwarded when resources are available (e.g., email).
      - Requires significant storage and is slower due to store-and-forward technique.
   - **Packet Switching:**
      - Message is broken into smaller packets.
      - Intermediate devices store smaller packets, requiring fewer resources.
      - Used by the internet; packets may take different paths and need re-sequencing upon arrival.

   ### **Message vs Packet Switching:**

   - **Message Switching:**
      - Lower overhead, higher reliability, and lower complexity.
      - Entire message stored at each hop point until fully received.
   - **Packet Switching:**
      - More complex, as packets may take different paths.
      - Packets received out of order are sequenced using embedded sequence numbers.
      - Generally faster than message switching.

   #### OSI (Open Systems Interconnection) Stack

   - **Purpose:** Specifies the functionality of the layers and the interface between them.

   **Layers of OSI Model:**

   1. **Presentation:**
      - Delivery and formatting of information.
      - Example: Convert rich text format (RTF) to ASCII.
   2. **Session:**
      - Manages sessions between processes.
      - Example: Combining audio, video streams; authentication.

   ### Internet Protocol Stack

   ## **Layers of Internet Protocol Stack:**

   1. **Application:**
      - Supports application processes which generate messages.
      - Examples: Email, Web, File-transfer.
   2. **Transport:**
      - Supervises process-to-process communication (multiplexing/demultiplexing messages, reliability).
      - Examples: TCP, UDP.
   3. **Network:**
      - Enables end-to-end routing of messages (from source to destination hosts).
      - Example: IP.
   4. **Link:**
      - Enables hop-to-hop message transfer (between neighbors).
      - Examples: Ethernet, 802.11.
   5. **Physical:**
      - Enables bit transmissions on media (wire/air).
      - Examples: 10Base-T, OFDM.

   **Layer Interaction:**

   - **Encapsulation/Decapsulation:** Process of adding/removing headers as data passes through layers.
   - **End to End vs Hop to Hop:**
      - **End to End:** Communication from source to destination.
      - **Hop to Hop:** Communication between intermediate devices.

   ### Data Units at Different Layers

   - **Message:** Application layer data.
   - **Segment:** Transport layer data.
   - **Datagram:** Network layer data.
   - **Frame:** Link layer data.

   **Example:**

   - **Application Layer:** M (Message)
   - **Transport Layer:** T M (Segment)
   - **Network Layer:** N T M (Datagram)
   - **Link Layer:** L N T M (Frame)

   ### Protocols in Different Layers

   - **Multiplexing/Demultiplexing:**
      - **Port Number:** Identifies specific processes or services.
      - **Protocol:** Specifies the rules for data communication.
      - **Frame Type:** Indicates the format of the frame for data transmission.

   ***Summary:** The OSI and Internet Protocol Stacks define the structured approach to communication in networks, specifying different layers and their functions. Each layer has specific responsibilities, from physical transmission of bits to application-level message generation and processing. Data encapsulation and decapsulation ensure proper handling of data across the network, with protocols ensuring reliable and efficient communication.*

### Application Layer Overview

## Application Architecture

Three types of application architectures:

1. **Client-Server:**
   - **Examples:** Web, Email, FTP.
2. **Peer-to-Peer:**
   - **Examples:** File distribution (e.g., BitTorrent), IPTV (e.g., PPLive).
3. **Hybrid of Client-Server and Peer-to-Peer:**
   - **Examples:** Skype, Instant Messenger.

### Client-Server Architecture

- **Client:**
   - Initiates connection to server.
   - Dynamic IP address.
- **Server:**
   - Provides specific services (e.g., Google server provides search functionality).
   - Always on, with a fixed IP address.
   - Infrastructure intensive and costly to provide.

### Peer-to-Peer Architecture

- No central server; end-systems coordinate to provide the required service.
- Cost-effective, requiring minimal server infrastructure and bandwidth.
- Can have dynamic IP addresses.
- Scalable but complex system.

### Hybrid Architecture

- Initial contact with a central server to determine information about other end systems (e.g., tracking IP addresses of users).
- End-systems communicate directly after initial contact.

### Application Protocols

- **Define types of messages exchanged:**
   - **Examples:** Request, response.
- **Message Syntax:**
   - Fields in messages.
- **Message Semantics:**
   - Meaning of information in fields.
- **Rules for when to send and how to act on messages.**

### **Companion Protocols:**

- Specify the format of data exchanged.
- **Examples:**
   - HTML (companion protocol of HTTP).
   - RFC 822 and MIME (define format of email messages; companions of SMTP).

### Application Process/Program

- **Application programs** use the application protocol to achieve the intended task.
   - **Examples:** Internet Explorer, Chrome, Firefox all use HTTP for web access.
- **Processes identified by IP address:Port:**
   - Popular services have well-known port numbers (e.g., 80 for web, 25 for email server).

### Transport Services Available to Applications

- The upper layer uses services of the lower layer to achieve requisite functionality.
- Transport layer services are classified along four dimensions:
   1. **Reliable Data Transfer:**
      - Guaranteed data delivery service.
   2. **Throughput:**
      - **Bandwidth-sensitive applications:** Applications that have throughput requirements.
      - **Elastic applications:** Throughput as available (e.g., Email, file transfer, and web transfers).
   3. **Timing:**
      - Real-time applications require tight timing constraints (e.g., Internet telephony, teleconferencing).
      - Non-real-time applications prefer lower delay but have no tight constraints (e.g., file transfer).
   4. **Security:**
      - Provides confidentiality, data integrity, and end-point authentication.

**Note:** Today's Internet transport protocols do not provide guaranteed throughput or timing services.

#### Content

- Transport Layer Services
- Flow Control in Transport Layer
   - Stop-and-Wait
   - Go-Back-N
   - Selective Repeat
- UDP: Services and Applications
- TCP:
   - Services, Features, and Applications
   - TCP Connection
   - State Transition Diagram
   - Windows in TCP
   - Flow Control
   - Congestion Control

### Logical Connection at the Transport Layer

## Transport Layer Services

- The transport layer is responsible for:
   - Providing services to the application layer and receiving services from the network layer.
   - Enabling process-to-process communication between two application layers.
   - Providing communication using a logical connection.
   - Multiplexing at the source and demultiplexing at the destination host.
   - Providing flow and error control services.
   - Providing congestion control.

### Types of Data Deliveries

- Example: FTP, DNS

### Client/Server Paradigm

- **Client/Server Paradigm:**
   - Client: The process on the local host.
   - Server: The process on the remote host.
   - Example: To get the day and time from a remote machine, a Daytime client process runs on the local host, and a Daytime server process runs on a remote machine.
- ### **Communication Requirements:**
   - Define local host, local process, remote host, remote process.
   - **Addressing:**
      - Like MAC and IP addresses at the Data Link Layer (DLL) and Network Layer, we need a transport layer address called a port number to choose among the multiple processes running on the destination host.
      - **Port Number:**
         - Destination port number is needed for delivery; the source port number is needed for the reply.
         - Port numbers are 16-bit integers between 0 to 65,535.
         - Client port numbers are chosen randomly, known as ephemeral port numbers, usually greater than 1023.
         - Server port numbers are well-known and not chosen randomly.

### IP Addresses versus Port Numbers

### Questions

1. **What do you understand by socket address?**
2. **What is the socket address if you want to access email having port number 1400 from Google server with IP address 192.10.10.142? Assume your IP address is 172.10.10.191.**
   - **Answer:** Socket Address is 192.10.10.142:1400

### ICANN Port Ranges

1. **Well-known Port:** Assigned and controlled by ICANN, range is from 0-1023.
2. **Registered Port:** Not assigned or controlled by ICANN, only registered to avoid duplication, range is 1024-49151.
3. **Dynamic Port:** Temporary port numbers, not assigned or registered by ICANN, range is 49152-65535.

### Multiplexing & Demultiplexing at Transport Layer

### Connectionless vs. Connection-Oriented Service

- **Connectionless Service:**
   - Packets are sent without the need for connection establishment or release.
   - Packets are not numbered and may be delayed, lost, or arrive out of sequence.
   - No acknowledgment (e.g., UDP - User Datagram Protocol).
- **Connection-Oriented Service:**
   - A connection is established before data transfer and released afterward.
   - Example protocols: TCP (Transmission Control Protocol), SCTP (Stream Control Transmission Protocol).

### Reliable vs. Unreliable Service

- **Reliable Service:**
   - Implements flow and error control at the transport layer for guaranteed data delivery, making it slower and more complex.
   - Example protocols: TCP, SCTP (connection-oriented and reliable).
- **Unreliable Service:**
   - No flow or error control at the transport layer for faster service, suitable for applications with their own control mechanisms or real-time requirements.
   - Example protocol: UDP (connectionless and unreliable).

?descriptionFromFileType=function+toLocaleUpperCase()+{+[native+code]+}+File&mimeType=application/octet-stream&fileName=Computer+Network+-+CN.md&fileType=undefined&fileExtension=md