# CN Asif Notes

1. **Data Communications:**
   - **Telecommunication:** Communication over distances.
   - **Data:** Information exchanged between devices.
   - **Components:** Sender, Receiver, Message, Communication Medium, and Protocols.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/0958e4b7-36df-48a0-aa96-66479e8b05af)

   #### Data Flow

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/ab5b84c8-998d-4333-9f19-9f7dbb57f14e)

2. **Networks:**
   - **Definition:** A set of interconnected devices (nodes) that exchange data.
   - **Network Criteria:** Performance (transit time, response time), reliability, and security.
   - **Distributed Processing:** Tasks are divided among multiple computers.
3. **Physical Structure of Networks:**
   - **Types of Connections:**
      - Point-to-Point
      - Multipoint
   - **Topologies:**
      - Mesh, Star, Bus, Ring, and Hybrid.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/94e10915-a0e5-465c-9989-b3d154526440)

   - **Advantages and Disadvantages** of each topology are detailed.
4. **Network Models:**
   - **OSI Model:** Seven layers.
   - **Internet Model (TCP/IP):** Five layers.
5. **Categories of Networks:**
   - **PAN (Personal Area Network):** Small range, personal devices.
   - **LAN (Local Area Network):** Data communication within a building or campus.
   - **MAN (Metropolitan Area Network):** Covers a town or city.
   - **WAN (Wide Area Network):** Covers larger geographical areas, including countries.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/42114b32-eb2b-4f32-b700-a02c1ce49026)

6. **The Internet:**
   - **Definition:** A network of networks using TCP/IP protocol suite.
   - **Service Providers:** Local, Regional, National, International ISPs.
7. **Protocols and Standards:**
   - **Protocol:** Rules governing data communication (e.g., HTTP, TCP, FTP).
   - **Standards:** Ensure compatibility between products from different manufacturers, created by organizations like ISO, IEEE, and ANSI.
   - **Internet Standards:** Drafts and RFCs for stakeholder feedback.
1. **Layered Architecture**:
   - The OSI model is divided into seven layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/cbbae4d3-5326-4bc8-a822-9b2294127348)

   - Each layer serves a specific function and interacts with the layers directly above and below it.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/a4ee2d02-e4d2-4893-b839-ff21a347d840)

2. **OSI Model**:
   - **Physical Layer**: Handles the transmission of raw bits over a physical medium.
   - **Data Link Layer**: Responsible for node-to-node data transfer, framing, error detection, and MAC addressing.
   - **Network Layer**: Manages packet routing, logical addressing (IP), and internetworking.
   - **Transport Layer**: Ensures reliable data transfer, flow control, and error correction across the network.
   - **Session Layer**: Manages sessions, dialogue control, and synchronization between communicating systems.
   - **Presentation Layer**: Deals with data translation, encryption, and compression.
   - **Application Layer**: Provides network services directly to applications, including file transfer, email, and directory services.
3. **TCP/IP Protocol Suite**:
   - The TCP/IP model, often compared to the OSI model, consists of four layers: Physical, Data Link, Network, and Application.
   - **Protocols**: Different layers have associated protocols, such as IP, TCP, UDP, ARP, and FTP.
   - **Addressing**: TCP/IP uses four types of addresses: Physical, Logical (IP), Port, and Specific (e.g., URLs).
4. **Encapsulation**:
   - Data is encapsulated with headers and trailers as it moves down through the layers during transmission. For example, data at the transport layer is divided into segments, each with a header containing control information.
5. **Interaction and Communication**:
   - Peer-to-peer processes communicate at the same layer across different systems.
   - Logical and port addresses usually remain the same from the source to the destination, while physical addresses may change as data passes through different network devices.

### **Functions of Data Link Layer:**

- **Framing:** Divides data from the network layer into frames.
- **Physical Addressing:** Utilizes MAC (Media Access Control) addresses.
- **Flow Control:** Manages the data flow between sender and receiver.
- **Error Control:** Ensures error-free data transmission.
- **Congestion Control:** Manages network traffic to prevent congestion.
- **Access Control:** Determines which device has control over the link in a shared network environment.

### **Sub-layers of Data Link Layer:**

1. **Logical Link Control (LLC):**
   - Interface between the MAC sublayer and network layer.
   - Manages error and flow control.
   - Supports multiplexing.
2. **Media Access Control (MAC):**
   - Handles physical addressing.
   - Manages multiple access control.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/6b03c413-a878-4837-861d-0654d9c195a9)

#### Different Figure Images

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/9215b767-d4d1-436b-ac48-86bc03db3e19)

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/d50131c4-573b-46f1-94ec-03005fb5219b)

### **Functions of Network Layer:**

- **Logical Addressing:** Uses IP addresses for identifying devices on the network.
- **Routing:** Determines the path for data to travel from source to destination.

### **Functions of Transport Layer:**

- **Service Point Addressing:** Facilitates process-to-process communication via port numbers.
- **Segmentation and Reassembly:** Breaks down messages into segments and reassembles them at the destination.
- **Connection Control:** Manages connection-oriented or connectionless data transmission.
- **Flow Control:** Ensures smooth data flow from end to end.
- **Error Control:** Provides error correction through retransmission.

### **Connection-Oriented vs. Connectionless:**

- **Connection-Oriented:** Requires a dedicated path before data transmission.
- **Connectionless:** Data is transmitted without establishing a dedicated path.

### **Functions of Session Layer:**

- **Dialog Control:** Manages communication sessions, supporting half-duplex or full-duplex modes.
- **Synchronization:** Adds checkpoints to ensure data integrity during transmission.

### **Functions of Presentation Layer:**

- **Translation:** Converts data between different encoding formats.
- **Encryption:** Secures data by converting it into a coded format.
- **Compression:** Reduces the size of data for efficient transmission.

### **Functions of Application Layer:**

- **Network Virtual Terminal:** Enables remote login to hosts.
- **File Transfer, Access, and Management:** Facilitates file operations on remote systems.
- **Mail Services:** Supports email forwarding and storage.
- **Directory Services:** Provides access to distributed databases for information retrieval.

### **Devices Used in Each Layer:**

- **Physical Layer:** Hubs, Repeaters, Cables, Fibers.
- **Data Link Layer:** Bridges, Modems, Network Cards, Layer-2 Switches.
- **Network Layer:** Routers, Brouters, Layer-3 Switches.
- **Transport Layer:** Gateways, Firewalls.
- **Session Layer:** Gateways, Firewalls.
- **Presentation Layer:** Gateways, Firewalls.
- **Application Layer:** Gateways, Firewalls.

#### Summary Of OSI Models

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/87d5a9ff-b30d-4cb8-a070-ec3275ac67b2)

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/ac16e096-0416-48b1-9174-d1c0ad7f615f)

### **TCP/IP Protocol Suite Layers:**

- **Physical Layer**
- **Data Link Layer**
- **Network Layer**
- **Transport Layer**
- **Application Layer**

### **Key Protocols of TCP/IP Layers:**

- **Physical Layer:** V.92, 802.11, Wi-Fi.
- **Data Link Layer:** PPP, IEEE 802.11, Token Ring, FDDI.
- **Network Layer:** IP, ICMP, IGMP, ARP, RARP.
- **Transport Layer:** TCP, UDP, SCTP.
- **Application Layer:** FTP, SMTP, HTTP, DNS, Telnet.

### **Addressing in TCP/IP:**

- **Physical Address:** MAC address used for device identification within a network.
- **Logical Address:** IP address used for identifying devices across networks.
- **Port Address:** 16-bit identifier for specific processes in network communication.
- **Specific Address:** Identifiers like URLs or email addresses for applications.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/8a5aa2fb-a40c-4233-ae4d-1fadd94ca621)

### **Examples and Figures:**

- Various figures illustrate concepts such as hop-to-hop delivery, source-to-destination delivery, and address relationships in the TCP/IP model.

![image.png](https://res.craft.do/user/full/d004d7c7-d66b-5a9b-f430-0d25abf60ab1/doc/5dbacced-eda6-43e4-9a68-8eac7bb6454f/d90e2af6-0800-4238-b0b6-2db36919a2bb)

## **Data and Signals**

- Data can be classified as **analog** or **digital**.
   - **Analog data**: Example: Voice
   - **Digital data**: Example: Binary (0101)
- **Transformation**: Data must be transformed into signals before transmission across a network.
- **Types of Signals**:
   - **Analog signal**
   - **Digital signal**

## **Analog and Digital Signals**

- **Analog Signals**: Take on continuous values (infinite values in a range).
- **Digital Signals**: Take on discrete values (e.g., 0, 1).
- Common usage in data communications includes **periodic analog signals** and **non-periodic digital signals**.

### P**eriodic vs. Non-periodic Signals**

- **Periodic Signal**:
   - Completes a pattern in a measurable time frame (called a period).
   - Repeats the pattern in subsequent identical periods.
   - Example: **Sine Wave**.
- **Non-periodic Signal**:
   - Changes without a repeating pattern.

### S**ine Wave**

- The most fundamental form of a periodic analog signal.

#### Signal Attributes

| Property        | Definition                                 | Symbol | Measured In    |
| --------------- | ------------------------------------------ | ------ | -------------- |
| Displacement    | Distance a particle moves from equilibrium |        | Meters (m)     |
| Amplitude       | Maximum displacement                       |        | Meters (m)     |
| Wavelength      | Length of one full wave (cycle)            | λ      | Meters (m)     |
| Frequency (f)   | Number of full cycles per second           |        | Hz             |
| Time Period (T) | Time to complete one full cycle            |        | Seconds        |
| Phase           | Position of waveform relative to time 0    | ϕ      | Degrees/Radian |

### F**requency and Period**

- **Frequency (f)**: Number of full cycles per second. Formula: Period=1f\text{Period} = \frac{1}{f}Period=f1​
- Example: If **f = 6 Hz**, then **Period = 16\frac{1}{6}61​ seconds**.

### P**hase**

- Indicates the position of the waveform relative to time 0.
- One complete cycle = 360 degrees.

### **Wavelength**

- Distance between repetitions of the shape of the wave (e.g., peaks).

### **Composite Periodic Signal**

- Composed of multiple sine waves.
- Can be periodic or non-periodic.

### **Bandwidth**

- The range of frequencies contained in a composite signal.
- Bandwidth B=fh−flB = f_h - f_lB=fh​−fl​, where fhf_hfh​ is the highest frequency and flf_lfl​ is the lowest frequency.

## **Digital Signals**

- Digital signals represent information using binary digits (0s and 1s).
- Example: A 1 can be represented by a positive voltage, and a 0 by zero voltage.
- **Multiple Levels**: A digital signal can have more than two levels; Number of bits per level=log⁡2N\text{Number of bits per level} = \log_2 NNumber of bits per level=log2​N, where NNN is the number of levels.

### **Bit Rate**

- **Bit Rate**: Number of bits transmitted in 1 second, measured in bits per second (bps).

## 4. **Transmission Impairment**

- **Impairment**: Signals experience changes during transmission, leading to discrepancies between the transmitted and received signals.
- **Causes of Impairment**:
   - **Attenuation**: Loss of energy as a signal travels through a medium.
   - **Distortion**: Change in the form or shape of a signal, particularly in composite signals.
   - **Noise**: Various types (thermal noise, induced noise, crosstalk, impulse noise) that corrupt the signal.

### 4.1 **Signal-to-Noise Ratio (SNR)**

- **Definition**: Compares the level of a desired signal to the level of background noise.
- Formula: SNRdB=10log⁡10SNRSNR_{dB} = 10 \log_{10} SNRSNRdB​=10log10​SNR

## 5. **Data Rate Limits**

- **Data Rate Limit**: Maximum speed of data transmission, measured in bits per second (bps).
- Influencing factors:
   - Bandwidth available
   - Levels of signals used
   - Quality of the channel (noise level)

### 5.1 **Theoretical Formulas**

1. **Nyquist Rate** (for noiseless channels):
   - Formula: Bit Rate=2×Bandwidth×log⁡2L\text{Bit Rate} = 2 \times \text{Bandwidth} \times \log_2 LBit Rate=2×Bandwidth×log2​L where LLL is the number of signal levels.
2. **Shannon's Theorem** (for noisy channels):
   - Provides a more realistic estimation considering noise.

### Examples

- **Nyquist Calculation**: Given a channel with bandwidth of 3000 Hz and 2 signal levels, calculate maximum bit rate.

### Noisy Channel: Shannon Capacity

- **Shannon Capacity**: A formula introduced by Claude Shannon in 1944 to calculate the theoretical highest data rate for a noisy channel.
- **Signal-to-Noise Ratio (SNR)**: A key factor in determining channel capacity. For extremely noisy channels with SNR near zero, the channel capacity approaches zero.

### Network Performance Metrics

- **Bandwidth**: The maximum rate of data transfer across a network, measured in bits per second (bps).
- **Throughput**: The actual rate at which data is successfully transferred, typically less than the bandwidth due to various inefficiencies.
- **Latency (Delay)**: The time it takes for an entire message to travel from the source to the destination, composed of propagation time, transmission time, queuing time, and processing delay.
- **Jitter**: The variation in packet delay at the receiver, which can be problematic for time-sensitive applications like audio and video streaming.
- **Error Rate**: The number of corrupted bits as a percentage or fraction of the total sent.

### Bandwidth-Delay Product

- **Bandwidth-Delay Product**: The product of a link's bandwidth and its delay, representing the amount of data that can be in transit in the network at any one time.

### Signal Conversion

- **Digital-to-Digital Conversion**: Involves techniques like line coding, block coding, and scrambling to convert digital data into digital signals.
- **Analog-to-Digital Conversion**: Techniques like Pulse Code Modulation (PCM) and Delta Modulation (DM) are used to convert analog signals into digital data.
- **Digital-to-Analog Conversion**: This process changes one characteristic (amplitude, frequency, phase) of an analog signal based on digital data, using techniques like Amplitude Shift Keying (ASK), Frequency Shift Keying (FSK), and Phase Shift Keying (PSK).
- **Analog-to-Analog Conversion**: Analog modulation techniques like Amplitude Modulation (AM), Frequency Modulation (FM), and Phase Modulation (PM) convert analog signals within different frequency bands.

### Multiplexing

- **Multiplexing**: A technique to combine multiple data streams over a single transmission medium.
   - **Frequency-Division Multiplexing (FDM)**: An analog technique where the available bandwidth is divided into multiple frequency channels.
   - **Time-Division Multiplexing (TDM)**: A digital technique where multiple connections share the bandwidth of a link using time slots.

### Switching

- **Switching**: The process of forwarding data packets from one network port to another toward the destination in a switched network, which is more efficient than using star, bus, or mesh topologies for large networks.

### **Circuit Switching**

- **Dedicated Path**: In circuit switching, a dedicated path or circuit is established before any data transmission occurs. This involves reserving resources like buffer space and transmission rate for the entire duration of communication.
- **Phases of Circuit Switching**:
   1. **Setup Phase**: Establishes the circuit by reserving resources.
   2. **Data Transfer Phase**: Data is transmitted across the reserved circuit.
   3. **Teardown Phase**: The circuit is disconnected, releasing the reserved resources.
- **Example**: Traditional telephone networks operate using circuit switching.
- **Transmission Characteristics**:
   - The connection gets a fixed share of the link's transmission capacity (e.g., 250 kbps on a 1 Mbps link if divided into four circuits).
   - **Delay**: Minimal during data transfer as the circuit is pre-established and dedicated, so there's no need to wait at each switch.

### **Packet Switching**

- **Packet Transmission**: Data is divided into smaller packets, each of which is transmitted independently across the network. There is no need for a pre-established path, and resources are allocated dynamically as needed.
- **Store-and-Forward**: Packet switches use this method, where a switch must receive the entire packet before forwarding it to the next link.
- **Delays**:
   - **Transmission Delay**: Time taken to push the entire packet onto the communication medium. Delaytr=Packet lengthTransmission rate\text{Delay}_{tr} = \frac{\text{Packet length}}{\text{Transmission rate}}Delaytr​=Transmission ratePacket length​
   - **Propagation Delay**: Time for a signal to travel from the source to the destination. Delaypg=DistancePropagation speed\text{Delay}_{pg} = \frac{\text{Distance}}{\text{Propagation speed}}Delaypg​=Propagation speedDistance​
   - **Processing Delay**: Time to process the packet at a router or network device.
   - **Queueing Delay**: Time a packet spends in queues waiting for transmission. It occurs when the incoming rate of packets exceeds the transmission capacity of the link.

### **Throughput in Packet-Switched Networks**

- **Definition**: Throughput refers to the rate at which data is successfully transmitted over a network link, typically measured in bits per second (bps).
- **Factors Affecting Throughput**:
   - **Link Capacity**: The maximum data rate that a physical link can support.
   - **Network Congestion**: High congestion leads to increased queueing delays, reducing throughput.
   - **Protocol Overheads**: Protocols add overhead, slightly reducing throughput.
   - **Routing Efficiency**: Efficient routing leads to faster packet delivery and better throughput.
- **Bottleneck Effect**: Throughput is determined by the slowest link in the path. For instance, if three links have capacities of 200 Kbps, 100 Kbps, and 150 Kbps respectively, the overall throughput is limited to 100 Kbps, the rate of the slowest link.

?descriptionFromFileType=function+toLocaleUpperCase()+{+[native+code]+}+File&mimeType=application/octet-stream&fileName=CN+Asif+Notes.md&fileType=undefined&fileExtension=md