# ComputerNetworKing
> A comprehensive repository covering computer networking from **basics to advanced**, aimed at **engineering/tech placements** and global networking certifications.

---

> 💡 A **computer network** is a collection of interconnected devices that enable **data exchange** and **resource sharing** among multiple devices.

# Basics

## Types of Network Topology

1. **Point to Point Topology**
    
    ![9ldbtosd](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/73ef1cb4-6fcc-4db1-95a2-2dd1b6841065)

    - ******Advantages:****** Have **high efficiency** with direct communication between devices, **enhanced security** by eliminating reliance on compromised intermediate devices, and **simple configuration** with minimal management or administration requirements.
    - ******Disadvantages:****** Have **limited scalability**, require **separate links for new devices**, leading to **time-consuming and expensive** processes, **difficult maintenance** due to managing each device separately, and a **lack of redundancy**, posing problems if a link fails or a device goes offline.
2. **Bus Topology**
    
    ![ekpst20i](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/ab12f9f1-6763-423f-917c-420ac79c7ffc)

    - ************************Advantages:************************ The **bus topology** is the easiest network topology for 
    connecting peripherals or computers in a linear fashion through a central **RJ-45** cable, and it works  very efficiently well when there is a small network. The length of cable required is less than a star topology, and it is easy to connect or remove devices in this network without affecting any other device. It is **very cost-effective** as compared to other network 
    topologies, such as mesh and star. Additionally, it is easy to 
    understand and expand by joining the two cables together.
    - ******************************Disadvantages:****************************** Bus topology is **not great** for **large networks**, where **identification of problems** becomes **difficult** if the **whole network goes down** and **troubleshooting individual device issues** is **very hard**. **Terminators** are required at **both ends of the main cable** and **additional devices** slow the network down, while **packet loss** is **high**. This network topology is **very slow** as compared to other topologies, and if the **main cable is damaged**, the **whole network fails or splits into two**.
    - Various **MAC (Media Access Control)** protocols are followed by LAN ethernet connections like **TDMA, Pure Aloha, CDMA, Slotted Aloha**, etc.
3. **Ring Topology**
    
    ![hkn7dg67](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/5119c696-042c-48fd-9da2-ce96f0c2e750)

    - **Advantages: Data flows** in one direction, reducing the chance of **packet collisions**. Additional workstations can be added without impacting network **performance**. It provides **equal access** to resources without the need for a controlling **server**. This topology is **cost-effective** for installation and expansion with **minimal collisions**. It offers high-speed **data transfer** and improved performance compared to a bus topology under heavy traffic due to **token passing**. It is **easy to manage** and ensures orderly organization with every device having access to the **ring network token** for transmission.
    - ****************Disadvantages:**************** Due to the **Uni-directional Ring**, a data packet (token) must have to pass through all the nodes. If one workstation shuts down, it affects **whole network** or if a node goes down **entire network goes down**. It is **slower in performance** as compared to the bus topology. It is **Expensive**. **Addition and removal** of any node during a network is **difficult** and may cause **issue** in network activity. **Difficult to troubleshoot** the ring. In order for all the computer to communicate with each other, all computer must be **turned on**. **Total dependence** in on one cable. They were not **Scalable**.
4. **Star Topology**
    
    ![orskwe1b](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/6d91de0c-da38-4f20-a04c-d82862b54d6f)

    - ************************Advantages:************************ It is very **reliable** – if one cable or device fails then all the others will still work. It is **high-performing** as no data collisions can occur. **Less expensive** because each device only needs one I/O port and wishes to be connected with a hub with one link. **Easier to put in**. **Robust** in nature. **Easy fault detection** because the links are often easily identified. No disruptions to the network when connecting or removing devices. Each device requires just one port i.e. to attach to the hub. If N devices are connected to every other in a star, then the amount of cables required to attach them is N. So, it’s easy to line up.
    - ******Disadvantages:****** Requires more cable than a linear bus. If the connecting network device (**network switch**) fails, nodes attached are disabled and can’t participate in network communication. More expensive than linear bus topology due to the value of the connecting devices (**network switches**). If **hub** goes down everything goes down, none of the devices can work without **hub**. **Hub** requires more resources and regular maintenance because it’s the central system of **star**. Extra hardware is required (**hubs** or **switches**) which adds to cost. Performance is predicated on the one concentrator i.e. **hub**.
    - Many popular Ethernet LAN protocols are used as **CD(Collision Detection), CSMA (Carrier Sense Multiple Access)**, etc.
    - Forms a Local Area Network (LAN)
5. **Mesh Topology**
    
    ![k0d9axhe](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/295bb949-aa0d-4f0c-8678-261a5e54e0d0)

    - **************Types:**************
        1. In a **full mesh**, all nodes are interconnected, creating **n-1** connections for each of the **n** nodes in the network. It offers **high redundancy** but is **expensive** and commonly used for **network backbones**. The **total number of links required** is **[n(n-1)]/2**.
        2. A **partial mesh** is a **more practical** and **cost-effective** option where not all nodes need to be directly connected. It allows for peripheral networks to be linked using a partial mesh while utilizing a full-mesh backbone for **added connectivity** and **redundancy**.
    - ************************Advantages:************************ Failure during a single device won't break the network. There is no traffic problem as each computer has a **dedicated point-to-point link**. **Fault identification** is straightforward, providing **multiple paths** to the destination with **tons of redundancy**. It ensures **high privacy and security**, while maintaining consistent **data transmission** even in the event of failure. Adding new devices won't disrupt transmissions, thanks to its **robust features**. A **mesh** topology operates without a centralized authority.
    - ******Disadvantages:****** It’s **costly** as compared to **star**, **bus**, and **point to point** network topologies. **Installation** is extremely difficult in the **mesh**, and the **power requirement** is higher as all the nodes need to remain active and share the load. It is a **complex process** and the **cost to implement mesh** is above other options. There is a **high risk of redundant connections**, and each node requires additional **utility cost**. **Maintenance** needs are challenging with a mesh.
    - The protocols used are **AHCP (Ad Hoc Configuration Protocols), DHCP**
6. ****Tree Topology****
    - It is the combination of bus and star topology.
      
    ![k70wid74](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/30fcf763-3077-4a50-acfb-76788a7adc5c)
    
7. **Hybrid Topology**
    
    ![1drq63g1](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/d2d72727-2675-4d19-ad01-bbdcbe69afb8)


---

## Types of Networks

1. **PAN (Personal Area Network)**
    - It enables data transmission through electronic devices; it can be **wired** or **wireless** (WPAN) and offers advantages like **ease of use**, **portability**, and **security**, but has limitations such as **limited range**, **slow data transfer**, and potential **interference** with radio signals and health issues.
    - It ranges from a few meters to typically covering a range of 10 meters.
    - **Bluetooth** and **Infrared** (IR) are the most common examples.
2. **LAN (Local-area Network)**
    - It is a computer network that connects personal computers and workstations within a small area, offering **high speed**, **privacy**, and support for different **transmission mediums**, but it has **setup costs**, **limited size**, **privacy concerns**, and potential **data security threats**.
    - LAN offers a much higher speed(around 100 mbps) and data transfer rate comparatively to WAN.
    - It ranges from a single building to covering a small area, such as a campus.
    - In a corporate office, employees connect their personal computers and workstations to a LAN to share resources like printers and exchange information efficiently within the building.
3. **MAN (Metropolitan Area Network)**
    - It is a computer network that connects multiple **LANs** in a city, providing high-speed data communication services and internet access, typically using **optical fibers**. It offers advantages such as **resource sharing**, **high-speed connectivity**, and **centralized management**, but faces challenges like **security threats**, **scalability issues**, and **high costs**. MANs can be **wired or wireless**, support various industries, and be interconnected with other networks.
    - It ranges from a city or metropolitan area to spanning several kilometers.
    - An example of a MAN is a **university campus** network that connects multiple buildings within the campus, providing high-speed data communication and resource sharing for students, faculty, and staff. Or a Cable TV network.
4. **WAN (Wide Area Network)**
    - It is a **computer network** that covers a **large geographical area**, facilitating **communication** between **LANs** and **MANs**, offering **broader reach**, **higher capacity**, **public carrier usage**, and **resource sharing**, but with disadvantages such as **traffic congestion**, **low fault tolerance**, **noise and errors**, and **slower data transfer rate** compared to LANs.
    - It ranges from multiple cities, countries, to continents.
    - An example of WAN is the **internet**, which connects computers and networks across the globe, enabling communication and data exchange on a global scale.

---

# TCP/IP Model & OSI Model

## 1. Physical Layer

### **Network Devices**

1. **Repeater**
    - Operates on the **physical layer**.
    - A **repeater** is a **2-port device** that **amplifies** and **regenerates** weak or corrupted signals at the **physical layer**. Its job is to extend the **transmission length** of the signal over the **same network** before it becomes too weak or corrupted, copying and regenerating it **bit by bit** at its **star topology connectors** to maintain the original strength.
    
    ![Untitled](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/708b3e8c-e11a-4502-a0a9-0a656c9c1aed)

    ![Untitled 1](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/25d6e01c-6d33-4253-b51e-1c073382b7f1)

2. **Hub**
    - Operates on the **physical layer**.
    - A **hub** functions as a **multi-port repeater** in a **star topology**, connecting multiple wires from different branches and sending data packets to all connected devices without filtering. This results in a shared **collision domain(***In a **collision domain**, network devices **compete for access** to the network, potentially causing **collisions** when **multiple devices transmit data simultaneously**, requiring all devices in the collision domain to **pay attention** to messages sent, regardless of their destination, resulting in **waiting** and **re-transmission** in a **half-duplex mode*)**, inefficiencies, and wastage as hubs lack intelligence for optimal data packet routing.
    - The different types of hubs include **Active Hub**, which acts as a repeater and wiring center, **Passive Hub**, which relays signals without cleaning or boosting them, and **Intelligent Hub**, which offers remote management capabilities, flexible data rates, traffic monitoring, and port configuration.
    
    ![Untitled 2](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/15e75f49-ef7b-4c16-a0ea-85a09d0f3559)

3. **Bridge**
    - It operates at the **data link layer.**
    - It functions as a **repeater** with the added ability to **filter content** based on **MAC addresses**, connecting **two LANs** working on the **same protocol** as a **2-port device**.
    - The **types of bridges** include **Transparent Bridges**, where stations are unaware of the bridge's presence, and **Source Routing Bridges**, where routing is performed by the source station and frames specify the route to follow. Transparent bridges utilize **bridge forwarding** and **bridge learning** processes, while Source Routing Bridges use **discovery frames** to spread through the network for route identification.
    
    ![Untitled 3](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/de0608ef-6835-4df4-90ee-ec7d5e7b1289)

   ![Untitled](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/0985840d-64c4-48a2-baf1-d4347e50a763)

    
5. **Switch**
    - It operates at the **data link layer.**
    - A **switch** is a **multiport bridge** with a buffer that enhances **efficiency** and **performance**, as it can perform **error checking** and selectively forward **good packets** to the correct port, effectively dividing the **collision domain** while maintaining the same **broadcast domain(**a **logical area** in a network where **broadcast packets** are delivered to all connected devices, which can create **congestion** and affect the **bandwidth** of the users in that network, commonly known as **LAN congestion)**.
    - Types of Switch:
        
        
        | Types | Description |
        | --- | --- |
        | Unmanaged switches | Simple plug-and-play switches without advanced configuration options, suitable for small networks or as an expansion to larger networks. |
        | Managed switches | Switches with advanced configuration options like VLANs, QoS, and link aggregation, suitable for larger and complex networks with centralized management. |
        | Smart switches | Switches with managed switch features but easier to set up and manage, suitable for small to medium-sized networks. |
        | Layer 2 switches | Operate at the Data Link layer, forwarding data between devices on the same network segment. |
        | Layer 3 switches | Operate at the Network layer, can route data between different network segments, used in larger and complex networks. |
        | PoE switches | Provide Power over Ethernet capabilities, supplying power to network devices over the same data cable. |
        | Gigabit switches | Support Gigabit Ethernet speeds, faster than traditional Ethernet speeds. |
        | Rack-mounted switches | Designed for server racks, suitable for data centers or large networks. |
        | Desktop switches | Designed for desktop or small office environments, smaller in size compared to rack-mounted switches. |
        | Modular switches | Have a modular design allowing for easy expansion or customization, suitable for large networks and data centers. |
    
    ![Untitled 4](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/35d87cf6-bf71-4b70-aef1-eda3eb96e381)

6. **Routers**
    - A **router** is a **Network Layer device** that routes data packets based on their **IP addresses**, connecting LANs and WANs, and making routing decisions using a **dynamically updating routing table** to divide broadcast domains.
    
    | Device | Seperates Collision Domain | Seperates Broadcast Domain |
    | --- | --- | --- |
    | Hub / Repeater | NO | NO |
    | Switch / Bridge | YES | NO |
    | Router | YES | YES |
    
    ![Untitled 1](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/a079c6aa-aede-469b-acf2-4045da5ad2ab)

    ![Untitled 5](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/20eac9e0-2a2c-4b8d-a35e-e1a5e5701abd)

7. **Gateway**
    - It operates at the **network layer (Layer 3)** or the **application layer (Layer 7)**.
    - At the network layer (Layer 3), it is a passage connecting two networks with **different networking models**, functioning as a **messenger agent** that interprets and transfers data between systems, also known as a **protocol converter.** Typically more complex than switches or routers.
    - At the application layer (Layer 7), it acts as an entry or exit point, facilitating **communication** and **protocol conversion** between applications or services using different protocols or data formats, commonly known as **application gateways** or **proxy servers**.
    
    ![Untitled 6](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/30820b67-13de-4f4f-83c6-47c6b02ff208)

   ![Untitled 7](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/622cffbf-26cd-4d4f-afe3-924234e67fed)

    
9. **Brouter**
    - A **bridging router** combines bridge and router features, capable of **routing packets** across networks and **filtering local area network traffic** at either the **data link layer** or **network layer**.
10. **NIC**
    - The **NIC** (network interface card) is a **layer 2 (data link)** network adapter that connects a computer to a network using a unique ID(**MAC address**) and cable interface(Ethernet or **RJ-45** port), enabling LAN establishment and communication with the router or modem at the **physical and data link layers** of the network model.
    
    ![Untitled 8](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/a4bb75a4-14a6-4ccf-8e70-be086c40b789)


---

### **Transmission Media**

A transmission medium is a physical path between the **transmitter** and the **receiver**.

### Types:

1. **Guided Media:** Or **Wired or Bounded transmission media** provides **high speed** and **secure** communication over **shorter distances**.
    1. **Twisted Pair Cable:** It is the **most widely used** transmission media.
        1. **UTP** (Unshielded Twisted Pair) is an **inexpensive** and **easy-to-install** cable consisting of two insulated copper wires twisted together, providing high-speed capacity but **susceptible to external interference**, with applications in telephony and LAN networks.
            
            ![Untitled 9](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/04798cae-08a8-4316-9b68-701c9c201d8c)

        2. **Shielded Twisted Pair (STP)** is a cable with a special jacket (copper braid or foil shield) that blocks external interference, providing **better performance at higher data rates** and **eliminating crosstalk**, but it is more difficult to install and manufacture, expensive, and bulky. It is commonly used in cold climates and for applications requiring additional shielding.
            
            ![Untitled 10](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/6b29a1a9-be8c-49bd-bcc8-610e030f9618)

    2. **Coaxial Cable:** It has parallel conductors and an outer plastic covering, provides **high bandwidth** and **noise immunity**, used in applications such as **cable TV**, **computer networks (like Ethernet)**, and **radio frequency signal transmission**, with advantages of **easy installation** and **expansion** but susceptible to network disruption if a single cable fails.        
        
        ![Untitled 11](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/d18f7696-df33-43e7-8bb9-a4b02bdf3812)

        ![Untitled 12](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/1a734897-0da5-4ea6-9cf7-d72912ef3399)

    3. **Optical Fiber Cable:** A cable with a core and cladding made of glass or plastic, offers **increased capacity** and **bandwidth**, lightweight design, low signal attenuation, immunity to electromagnetic interference, and resistance to corrosive materials, but has **difficult installation** and maintenance, high cost, and fragility. It finds applications in **medical instruments**, **aerospace data transmission**, **internet cables**, and **industrial lighting and automobile design**.
        
        ![Untitled 13](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/4792cbf5-f5a0-486a-b69d-eff14d8116d3)

        ![Untitled 14](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/d10c8de1-038a-4610-9bf8-f4167cc48f11)

2. **Unguided Media: Wireless or Unbounded transmission media** refers to transmitting **electromagnetic signals** through **air**, covering larger distances, but with **less security** compared to wired transmission
    1. **Radio waves**, easily generated and capable of penetrating buildings, are used for transmission in AM and FM radios, cordless phones, and categorized as **terrestrial** and **satellite,** with a frequency range of 3KHz - 1GHz. E.g. - WiFi and Bluetooth.
    2. **Microwaves,** are used for **line-of-sight transmission**, where proper alignment of **sending** and **receiving antennas** is required, with signal distance proportional to **antenna height**, operating in the frequency range of **1GHz to 300GHz**, primarily utilized for **mobile phone communication** and **television distribution**.
    3. **Infrared waves** are utilized for **short-range communication**, unable to penetrate obstacles, preventing **interference**, with a **frequency range** of **300GHz - 400THz**, commonly employed in devices such as **TV remotes, wireless mice, keyboards**, and **printers**.

---

### Transmission Modes

Also know as **Communication Modes**.

**Types:**

1. **Simplex Mode**
    
    Communication is **unidirectional**, allowing only one device to transmit while the other can only receive; it is **cost-effective**, **reliable**, and does not require coordination between devices, but lacks bidirectional communication and data verification.
    
    ![Untitled 2](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/c16744b1-4e5c-4b81-80e4-e08b034ac765)

2. **Half-Duplex Mode**
    
    Devices can **transmit and receive** but not simultaneously; it allows for **bidirectional communication** and is **more efficient** than simplex mode, but it's **less reliable**, has a **delay**, and requires **coordination** between devices.
    
    $Channel capacity=Bandwidth * Propagation Delay$
    
    ![Untitled 3](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/f6579ffe-bd41-4b39-91bf-896b8de9d7da)

3. **Full-Duplex Mode**
In **full-duplex mode**, both stations can **simultaneously transmit and receive**, making it ideal for **real-time applications**; it is the **most efficient** and provides **high reliability**, but is **expensive**, **complex**, and may not be necessary for all communication types.
    
    $Channel Capacity=2* Bandwidth*Propagation Delay$
    
    ![Untitled 4](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/27a8ca74-9d49-4a9e-aebf-8c0024ceed2d)


### Functions of Physical Layer

1. **Interface:** The physical layer defines the transmission interface between devices and transmission medium.
2. **Representation of Bits:** Data in this layer consist of stream of bits. The bits must be encoded into signals for transmission. It defines the type of encoding i.e. how 0’s and 1’s are changed to signals.
3. **Data Rate:** This layer defines the rate of transmission which is the number of bits per second.
4. **Transmission Modes:** Physical layer defines the direction of transmission between two devices such as Simplex, Half duplex, Full duplex.
5. **Line configuration:** This layer connects devices with the medium either it can be **point to point** configuration or **Multipoint** configuration.
6. **Topologies:** Devices must be connected through any topologies either it can be Mesh, Star, Bus, Ring or more.

### **Design Issues in Physical Layer**

- The physical layer is basically concerned with transmitting raw bits over a communication channel.
- Mainly the design issues here deal with **electrical, mechanical, timing
interfaces**, and the physical transmission medium, which lies below the
physical layer.
- Design issue has to do with making sure that when **1 bit send** from one side, it is **received 1 bit** by other side also **not as a 0 bit**.

### **Line Configuration in Computer Networks**

- A link is a communication pathway that transfers data from one device to another.
- There are two possible types of connections:
    1. **Point-to-Point Connection**
        
        A **point-to-point connection** links two devices with dedicated capacity for transmission. It typically uses wire, cable, microwave, or satellite. **Point-to-point network topology** is easy to establish and understand, making it a conventional choice. Example: **Point-to-point connection** between **remote control** and **television** for channel changing.
        
    2. **Multipoint Connection**
        
        Also known as **Multidrop configuration,** allows two or more devices to share a single link also called **'shared channel'**. In a **Multipoint Line configuration**, two possibilities arise:
        
        1. **Spatial Sharing**: Multiple devices can share the link simultaneously.
        2. **Temporal (Time) Sharing**: Users take turns using the link.

---

## 2. Data-link Layer

### **Services provided by Data Link Layer**

The **Data Link Layer** provides an interface to the **Network Layer** in the OSI model, facilitating the transmission of data frames from the sending machine's Data Link Layer to the receiving machine's Network Layer through either **actual communication** using a physical medium or **virtual communication** using a data link protocol.

![Untitled 5](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/d0ca731d-04ef-4396-9b67-09aa8fe55bb3)

**Types of Services provided by Data Link Layer :**

1. **Unacknowledged Connectionless Service:**  It provides **datagram-style delivery** without error, issue, or flow control, where the source machine transmits independent frames to the destination machine **without acknowledgment**; it **does not establish a connection** before or after data transfer and does not attempt to detect or recover from lost frames, as seen in **Ethernet**.
2. **Acknowledged Connectionless Service:** It provides **individual acknowledgments** for each transmitted frame, allowing the sender to know if the data frames were received safely; it is **reliable** and commonly used in **unreliable channels** such as wireless systems and **Wi-Fi services**.
3. **Acknowledged Connection-Oriented Service:** A **connection is established** between the sender and receiver before data transfer, ensuring that each transmitted frame is assigned individual numbers for guaranteed and ordered delivery.

### **Sub-layers of Data Link Layer**

1. **Logical Link Control (LLC):**
    
    This **sublayer** deals with **multiplexing**, the **flow of data** among **applications** and **other services**, and **LLC** is responsible for providing **error messages** and **acknowledgments** as well.
    
2. **Media Access Control (MAC):**
    
    MAC sublayer manages the device’s interaction, responsible for **addressing frames**, and also controls **physical media access**.
    

### **Functions of the Data-link Layer**

### 1. Framing

- **Frames** are units of digital transmission used in data link layer, representing **distinguishable blocks of information** in which data is transmitted as a **stream of bits**, providing error-checking codes and allowing for organized and controlled data delivery.
- **Problems in Framing:**
    - **Detecting the start of the frame**: Stations detect frames by looking for a special sequence of bits, the **Starting Frame Delimiter** (SFD), marking the beginning of the frame.
    - **Detecting the end of the frame**: Determining when to stop reading the frame.
    - **Handling errors**: Framing errors caused by noise or transmission errors require error detection and correction mechanisms like cyclic redundancy check (CRC) to ensure frame integrity.
    - **Framing overhead**: Frames have headers and trailers with control information, reducing available bandwidth for data transmission, especially for small-sized frames.
    - **Framing incompatibility**: Different devices and protocols using different framing methods can lead to compatibility issues when interpreting frames.
    - **Framing synchronization**: Stations must synchronize frame boundaries and timing to avoid collisions and ensure reliable communication, which can be challenging in complex networks with varying traffic loads.
    - **Framing efficiency**: Designing efficient framing methods minimizes data overhead and maximizes available bandwidth for optimal network performance and lower latency.
- ****Types of framing:****
    1. **Fixed-size:** The frame in this format uses its own length as a delimiter, eliminating the need for explicit boundaries, but it may suffer from **internal fragmentation** for smaller data sizes, which can be resolved through **padding**.
    2. **Variable size:** In this, there is a need to define the **end** of the **frame** as well as the **beginning** of the **next frame** to distinguish. This can be done in two ways:
        1. **Length field** – We can introduce a length field in the frame to indicate the length of the frame. Used in **Ethernet**(802.3). The problem with this is that sometimes the length field might get **corrupted**.
        2. **End Delimiter (ED)** – We can introduce an ED(pattern) to indicate the end of the frame. Used in **Token Ring**. The problem with this is that ED can occur in the data. This can be solved by:
            1. **Character/Byte Stuffing**: Used when frames consist of characters. If data contains ED then, a byte is stuffed into data to differentiate it from ED.
                - Let ED = “$”, if data contains ‘$’ anywhere, it can be escaped using ‘\O’ character.
                - If data contains ‘\O$’ then, use ‘\O\O\O$'($ is escaped using \O and \O is escaped using \O).
                - *Disadvantage* – It is very costly and **obsolete** method.
            2. **Bit Stuffing**:
                - Let ED = 01111 and if data = 01111
                - Sender stuffs a bit to break the pattern i.e. here appends a 0 in data = 0111**0**1.
                - Receiver receives the frame.
                - If data contains 011101, receiver removes the 0 and reads the data.
                - Example: If Data –> 011100011110 and ED –> 0111 then, data after bit stuffing. —> 011**0**100011**0**11**0**0

### 2. Addressing

- The data link layer encapsulates the source and destination’s **MAC address**/ physical address in the header of each frame to ensure **node-to-node** delivery.
- MAC addresses are **48-bit (6-byte)** values. For example, "*00:1A:2B:3C:4D:5E*" or "00-1A-2B-3C-4D-5E". The first half of the MAC address represents the manufacturer or vendor identifier, while the second half is the unique identifier for the device.
- The **uniqueness** is ensured by the Institute of Electrical and Electronics Engineers **(IEEE)**, which assigns blocks of MAC addresses to different manufacturers.

### 3. Error Control

- These **techniques** ensure accurate transmission of **data frames**, involving the **detection** and **re-transmission** of lost or corrupted frames through **Automatic Repeat Request (ARQ)**.

### **Ways of doing Error Control**

1. **Error Detection**
    - **Types of Errors**
        - **Single-Bit Error**
            
            ![Untitled 6](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/dfd106de-df20-4774-98d4-5ea1bb7000a6)

        - **Multiple-Bit Error**
            
            ![Untitled 7](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/4b19715a-7d95-4d3f-8e21-bc40b44a42c6)

        - **Burst Error** (consecutive bits****)****
            
            ![Untitled 8](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/b712a899-ef7d-4848-a179-84e5c215cdf2)

    - **Error Detection Methods**
        1. **Simple Parity Check**
            
            **It works as:**
            
            - 1 is added to the block if it contains an odd number of 1’s, and
            - 0 is added if it contains an even number of 1’s
            
            This scheme makes the total number of 1’s even, that is why it is called even parity checking.
            
            • Single Parity check is not able to detect even no. of bit error.
            
            ![Untitled 9](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/b2e708e4-667b-4bcd-9d9a-9d8c980347a9)

        2. **2D Parity Check**
            
            **2D Parity** check bits are calculated for **each row**, like a **simple parity check**. **Parity check** bits are also calculated for **columns**. Both are sent with the **data**. At the receiving end, they're compared to the calculated **parity bits**.
            
            ![Untitled 10](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/c5db70b5-fe1e-4bb2-9dfc-296efa076f5b)

        3. **Checksum**
            
            Sender’s Side:
            
            - Data is **divided** into k segments of m bits.
            - Segments are added using **1's complement** arithmetic to get the checksum.
            - Checksum is sent with the data segments.
            
            Receiver’s Side:
            
            - Received segments are added using **1's complement** arithmetic to get the sum.
            - The sum is **complemented**.
            - If the result is **zero**, the received data is accepted; otherwise, discarded.
            
            ![Untitled 11](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/87560d04-cba9-4f6a-832d-b4e2f67d108f)

        4. **Cyclic Redundancy Check (CRC)**
            
            ![detect14](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/a7ac291d-a689-469b-a347-e8dd400fdaf2)

            ![detect15](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/0ab2cd11-7465-4156-bc14-4f9cbde7120e)

2. **Error Correction**
    - It gives the receiver the ability to correct errors without needing a reverse channel to request re-transmission of data.
    - **Error Correction Techniques:**
        1. **Hamming Distance**: This technique requires a minimum **Hamming distance** of **2t + 1** to correct **t** errors. It involves sending a large amount of **redundant bits** with the data, making it rarely used due to the high redundancy it introduces.
        2. **XOR (Exclusive OR)**: This technique utilizes the **XOR property** to recreate data items. A packet is divided into **N chunks**, and the exclusive OR of all the chunks is created. **N+1 chunks** are then sent, and if any chunk is lost or corrupted, it can be recreated at the receiver side. For example, if **N=4**, **25 percent extra data** needs to be sent, and the data can be corrected if only one out of the four chunks is lost.
        3. **Chunk Interleaving**: In this technique, data packets are divided into **chunks**. The data is created chunk by chunk horizontally, but the chunks are combined into **packets** vertically. This allows each packet to carry a chunk from several original packets. If a packet is lost, only one chunk in each packet is missing, which is generally acceptable in multimedia communication. It allows for some small chunks to be missing at the receiver, with one chunk allowed to be missing in each packet.

### **Techniques for Error Control**

1. **Stop-and-Wait ARQ**
    - Useful Terms:
        
        >>>
        💡 **Propagation Delay:** Amount of time taken by a packet to make a physical journey from one router to another router.
        **RoundTripTime** (**RTT**) = Amount of time taken by a packet to reach the receiver + Time taken by the Acknowledgement to reach the sender
        **TimeOut** (**TO**) =  2* RTT
        **Time To Live** (**TTL**) = 2* TimeOut. (Maximum TTL is 255 seconds)
        >>>
        
    
    ### **Characteristics of Stop and Wait ARQ**
    
    - It uses a link between sender and receiver as a half-duplex link.
    - It is a special category of Sliding Window Protocol where its window size is 1.
    - Irrespective of the number of packets sender is having stop and wait for protocol requires only  2 sequence numbers 0 and 1
    
    ### **Working of Stop-and-Wait ARQ**
    
    1. Sender A **sends a data frame** or packet with sequence number **0**.
    2. Receiver B, after receiving the data frame, **sends an acknowledgement** with sequence number **1** (the sequence number of the next expected data frame or packet)
    
    ![Untitled 12](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/b7792c9d-07e9-4e65-a9d3-5ce3a7d05cc8)

    There is only a one-bit sequence number that implies that both sender and receiver have a buffer for one frame or packet only.
    
    ### Advantages of Stop and Wait ARQ
    
    1. **Simple Implementation** in both hardware and software, making it cost-effective and efficient.
    2. **Error Detection** in transmitted data using **checksums** or **cyclic redundancy checks (CRC)**.
    3. **Reliable** as the receiver acknowledges each packet before the sender proceeds with the next one, eliminating data corruption and maintaining order.
    4. **Flow Control,** allowing the receiver to regulate the rate at which data is transmitted, beneficial for systems with limited buffer space or processing power.
    5. **Backward Compatibility** with many existing systems and protocols.
    
    ### Disadvantages of Stop and Wait ARQ:
    
    1. **Low Efficiency:** Requires the sender to wait for acknowledgments, leading to a slow data transmission rate, especially for large data sets.
    2. **High Latency** as the sender waits for acknowledgments before sending the next packet, impacting real-time applications.
    3. **Limited Bandwidth Utilization:** Only allows one data packet to be transmitted at a time.
    4. **Limited Error Recovery:** Has limited error recovery capabilities, requiring retransmission of entire packets in case of loss or corruption.
    5. **Vulnerable to Channel Noise:** Prone to errors caused by channel noise, leading to frequent retransmissions and reduced overall efficiency.
2. **Sliding Windows ARQ**
    - Stop and Wait ARQ offers **error and flow control** but suffers from **performance issues** due to the sender **waiting for acknowledgments**, which can be addressed by using the **Sliding Window protocol** that allows for the simultaneous transmission of multiple packets, improving **efficiency** and **throughput**.
    - By implementing pipelining, a **window** of packets is transmitted without waiting for individual acknowledgements. The maximum number of packets that can be transmitted within a given cycle time can be calculated based on the **transmission time** and **propagation time**. Pipelining optimizes the transmission process, allowing for a continuous flow of packets and reducing idle time.
    - The **Sliding Window Protocol** is a theoretical concept that determines the optimal window size for the sender in order to improve the efficiency of the **Stop and Wait ARQ** protocol. In practice, this concept is implemented in two protocols:
        1. **Go Back N (GBN) Protocol**
            - The sender window size (WS) in GBN is N, where N is greater than 1 for pipelining.
            - The receiver window size (WR) in GBN is always 1.
            - GBN retransmits all packets from the last acknowledged packet if a packet is lost.
            - GBN uses two types of acknowledgements: cumulative ack and independent ack. **Cumulative ack** acknowledges **multiple** packets, reducing traffic but lowering reliability. While **Independent ack** acknowledges **each** packet independently, increasing reliability but causing higher traffic.
            - GBN requires a minimum of N+1 sequence numbers to avoid duplicate packet issues.
                
                ![Untitled 13](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/85bca7f3-73ea-4475-847e-664c40e2b40f)


        2. **Selective Repeat Protocol (SRP) :**
            - **Selective Repeat Protocol (SRP)** is a variation of the **Go Back N (GBN)** protocol.
            - SRP uses buffers at the receiver and sender, maintaining a **window** of a specific size.
            - SRP is effective in **unreliable links** where retransmissions are frequent.
            - SRP selectively retransmits specific frames instead of retransmitting all frames, improving **efficiency**.
            - SRP requires a **full-duplex** link and involves **backward acknowledgements**.
            - The sender can transmit new packets within the window of **unacknowledged packets**.
            - Sender retransmits unacknowledged packets after a **timeout** or upon receiving a **NAK**.
            - The receiver **acknowledges** all correct packets and stores them until they can be delivered in order.
            
            ![Untitled 14](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/8ce29590-c7de-4c13-9c0d-f65336b4dc3c)

### 4. Flow Control

**Flow control** at the **Data Link Layer** ensures proper data flow between **sender** and **receiver**, accommodating differences in **transmission speeds** and **processing capabilities**, preventing **data overload**, and coordinating **frame transmission** based on **receiver acknowledgements**. It acts as a **speed matching mechanism** for effective communication.

- **Approaches to Flow Control :**
    - **Feedback – based Flow Control**
        
        The **sender** **transmits** **data** to the **receiver**, which then sends **feedback** to the sender, allowing it to transmit more data based on receiver's **processing status** and **acknowledgements**.
        
    - **Rate – based Flow Control**
        
        When the **sender transfers data** at a **faster speed** than the receiver can handle, a **built-in mechanism** in the protocol **limits** the data transfer rate **without** requiring **feedback** or **acknowledgement** from the receiver.
        
- **Techniques of Flow Control:**
    1. **Stop-and-Wait Flow Control**
        - Messages are divided into **frames**, and the **receiver** signals **readiness** to receive data. The **sender** waits for **acknowledgment** before sending the next frame, with only one frame transmitted at a time. **Inefficiency** occurs if **propagation delay** exceeds **transmission delay**.
        - Advantages - **Simple** and **thorough** frame checking and **acknowledgment**, high **accuracy**.
        - Disadvantages - **Slow** transmission, limited to one **packet**/**frame** at a time, resulting in **inefficiency** and overall slow process.
    2. **Sliding Window Flow Control**
        - This method **reliable** and **in-order delivery** of **packets**, allowing the sender to transmit **multiple frames** before receiving any **acknowledgment**, increasing network **throughput**, while the receiver takes them one by one and acknowledges the **next frame number.**
        - Advantages - Improved performance compared to **stop-and-wait flow control**, increased efficiency, ability to send **multiple frames** consecutively.
        - Disadvantages - Increased complexity at sender and receiver due to **multiple frame transfer**, possibility of receiving **out-of-sequence** data frames or packets.

### 4. Access Control

- Multiple access protocols are essential for managing **simultaneous** data transmission on **non-dedicated channels**, preventing **collisions** and ensuring orderly data sharing, much like a **teacher** orchestrating students' turn to answer in a classroom.

### Types of Multiple Access Protocols

1. **Random Access Protocol**
    1. **ALOHA**(hello/goodbye in Hawaii)**:** All stations have **equal priority** and can send data depending on the medium's state (**idle** or **busy**). It includes two features:
        - No fixed time for sending data.
        - No fixed sequence of stations sending data.
        1. **Pure Aloha**
            
            When a station sends data, it waits for an **acknowledgement**. If the acknowledgement doesn't come within the allotted time, then the station waits for a random amount of time called **back-off time (Tb)** and **re-sends** the data. Since different stations wait for different amounts of time, the **probability of further collision** decreases.
            
        2. **Slotted Aloha**
            
            In this we **divide time into slots** and sending of data is allowed only at the **beginning of these slots**. If a station misses the allowed time, it must wait for the next slot, which **reduces the probability of collision**.
            
    2. **CSMA: Carrier Sense Multiple Access** minimizes collisions by requiring stations to **sense the medium** before transmitting data. If the medium is found **idle**, a station starts transmitting; otherwise, it waits until the channel becomes **idle**. However, despite these measures, collisions can still occur due to **propagation delay**. For instance, if **station A** begins transmitting and encounters a delay, **station B** may sense the idle medium and also start transmitting, resulting in a collision between their data.
        
        **CSMA access modes:**
        
        - **1-persistent**: The node immediately sends data if the channel is idle; otherwise, it **continuously** checks the medium for idleness and transmits as soon as it becomes idle (with **1 probability**).
        - **Non-Persistent**: The node sends data if the channel is idle; otherwise, it checks the medium after a **random time interval** and transmits when it finds the channel idle.
        - **P-persistent**: The node senses the medium and sends data with a probability of **p** if it is idle. If the data is not transmitted (with a probability of **1-p**), the node waits for a certain time and checks the medium again. If it is found idle, it sends data with probability **p**. This process repeats until the frame is sent. This mode is used in WiFi and packet radio systems.
        - **O-persistent**: Nodes have pre-determined superiority, and transmission occurs according to that order. When the medium is idle, a node waits for its allocated time slot to send data.
    3. **CSMA/CD**(*Collision Detection*)**:** It is a method where stations can **detect collisions** and **terminate data transmission**. CSMA/CD adds collision handling to the CSMA algorithm by ensuring that frames are **long enough to detect collisions** during transmission. The frame transmission delay must be **at least two times the maximum propagation delay**. In the worst-case scenario, **contention slots** are present due to collisions, which are the slots that are not able to transmit their journey due to the collision. Even though in the best-case scenario, a station successfully transmits a data packet to its destination.
    4. **CSMA/CA**(*Collision Avoidance*): It is a method where collisions are **detected** by the sender receiving **acknowledgement signals**. If only **one signal** (its own) is detected, the data is successfully sent, but if there are **two signals** (its own and the collided one), it indicates a collision. To differentiate between these cases, collisions must significantly impact the received signal. However, in **wired networks** where this impact is not prominent, CSMA/CA is utilized.
        
        **CSMA/CA avoids collision by:**
        
        1. **Interframe space (IFS)**: The station waits for the medium to become idle and, if found idle, it waits for a specific duration of time called **IFS** before transmitting data. The duration of IFS is based on the **priority** of the station.
        2. **Contention Window**: The transmission time is divided into **slots**. When the sender is ready to send data, it selects a random number of slots as the **waiting period**. If the medium remains busy, the waiting period is **doubled** for subsequent attempts. However, if the medium becomes idle, the **timer** is reset.
        3. **Acknowledgement**: If the sender does not receive an **acknowledgment** within a specified **time-out period**, it retransmits the data to ensure successful delivery.
    
    ---
    
2. **Controlled Access Protocol**
    - In this the **stations** seek information from one another to find which station has the **right to send**. It allows only **one node** to send at a time, to avoid the **collision of messages** on a **shared medium**.
    - The three controlled-access methods are:
        1. **Reservation:** 
            
            In this **stations** make **reservations** before sending data, with a fixed-length **reservation interval** divided into **slots**. Each station announces its intent to transmit during its designated slot, allowing for orderly **data transmission** without collisions. Advantages include **predictable network performance**, reduced **contention**, **QoS support**, efficient **bandwidth utilization**, and **multimedia application support**. Disadvantages include reliance on controlled **dependability**, decreased capacity and data rate under light loads, and increased **turn-around time**.
            
        2. **Polling:**
            
            It is a process where a **controller** sends messages to **nodes** one by one, similar to a roll-call. The controller selects a node and exchanges data exclusively through it. Advantages include fixed access time and data rates, maximum efficiency, and prioritization. Disadvantages include high **overhead**, reliance on the controller's **reliability**, increased time consumption, **biased link sharing**, and potential decrease in data rates under low loads.
            
        3. **Token Passing:**
            
            In this **stations** are logically connected in a **ring** and access is governed by **tokens**. Tokens circulate among stations in a predefined order, granting **permission to send**. **Frames** can be transmitted when a station receives the token. After sending a frame, stations wait for all **N stations** (including itself) to send the token. Challenges include **token duplication**, loss, and managing station **insertion or removal** for reliable operation.
            
    
    ---
    
3. **Channelization Protocol**
    1. **Frequency Division Multiple Access (FDMA):** 
        
        The **available bandwidth** is divided into equal **bands** to allocate each **station** its own band. **Guard bands** are added to prevent **overlap**, crosstalk, and noise.
        
    2. **Time Division Multiple Access (TDMA):** 
        
        In this, the **bandwidth** is shared between multiple **stations**. To avoid **collision**, time is divided into **slots** and stations are allotted these slots to transmit data. However, there is an overhead of **synchronization** as each station needs to know its time slot. This is resolved by adding **synchronization bits** to each slot. Another issue with TDMA is **propagation delay** which is resolved by the addition of **guard bands**.
        
    3. **Code Division Multiple Access (CDMA):**
        
        In a **single-channel transmission**, all data is transmitted simultaneously without dividing **bandwidth** or **time**. Multiple **stations** can transmit data simultaneously using different **code languages**, similar to people speaking different languages in a room without interference.
        
    4. **Orthogonal Frequency Division Multiple Access (OFDMA)**
        
        It divides the available **bandwidth** into small **subcarriers** for increased performance and is widely used in **5G** technology. Advantages include increased efficiency, high data rates, and suitability for multimedia traffic. Disadvantages include complexity in implementation.
        
    5. **Spatial Division Multiple Access (SDMA)**
        
        It utilizes **multiple antennas** to separate signals from users in different **spatial directions**. It is commonly used in **MIMO (Multiple-Input, Multiple-Output)** wireless communication systems. Advantages include effective **frequency band utilization**, improved **signal quality**, and increased **data rates**. Disadvantages include complexity in implementation and the need for accurate **channel information**.
        
    
    ---
    
- Multiple access protocols feature **contention-based access**, such as **Carrier Sense Multiple Access (CSMA)**, where devices listen for carrier signals and wait before transmitting to **avoid collisions**. Some protocols include **Collision Detection (CD)** to detect collisions, **Collision Avoidance (CA)** to prevent collisions, and **Token passing** to grant exclusive transmission rights. These protocols impact **bandwidth utilization**, with contention-based protocols potentially lowering it and token passing protocols potentially increasing it.

### What is Ethernet?

- Ethernet is the most widely used LAN technology defined under IEEE standards 802.3.
- Ethernet operates in the **Physical Layer** and **Data Link Layer** of the OSI model.
- Ethernet uses the **CSMA/CD** access control mechanism to handle collisions. **Manchester Encoding Technique** is used in Ethernet. Ethernet supports speeds of up to **100 Gbps**.
- ***Advantages*** : **speed**(faster then wireless), **energy-efficiency**, **good data transfer quality**(resistant to noise), **reliability**(uses error-correction), **cost-effectiveness**, **interoperability**, **security**(encryption & authentication), **manageability**, **compatibility**, **scalability**, **availability**, **simplicity**, and **standardization**.
- ***Disadvantages*** : **distance limitations**(max 100 m), **bandwidth sharing**, **security vulnerabilities**, **complexity**, **compatibility issues**, **cable installation**, and **physical limitations** in network design.

### **Ethernet (IEEE 802.3) Frame Format**

![Untitled 15](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/67810fb4-44ae-47a1-8377-ba5e85143301)

- **Preamble**: A 7-byte of alternative 0’s and 1’s pattern used for **bit synchronization** at the frame's start.
- **Start of Frame Delimiter (SFD)**: A 1-byte field (10101011) indicating the frame's beginning and **synchronization**.
- **Destination Address**: A 6-byte field containing the **MAC address** of the destination machine.
- **Source Address**: A 6-byte field containing the **MAC address** of the source machine (always **unicast**).
- **Length**: A 2-byte field indicating the frame's total **length** (up to 65534) but limited to **1500 bytes** in Ethernet.
- **Data**: The **payload** section where actual data is inserted, with a maximum length of **1500 bytes** (padding added if less than 46 bytes).
- **CRC (Cyclic Redundancy Check)**: A 4-byte field with a **hash code** generated over the Destination Address, Source Address, Length, and Data fields for **error detection**.
- **VLAN Tagging**: A 4-byte field inserted after the source address to separate a physical network into multiple **virtual networks**.
- **Jumbo Frames**: Frames with a payload larger than **1500 bytes**, increasing network throughput.
- **Ether Type Field**: Identifies the protocol carried in the payload (e.g., **IP** or **ARP**).
- **Multicast** and **Broadcast Frames**: Ethernet supports sending frames to specific groups or **all devices** on the network.
- **Collision Detection**: In **half-duplex Ethernet** networks, the CSMA/CD protocol is used to detect and manage **collisions** during data transmission.

>💡 **Size of frame** of Ethernet IEEE 802.3 varies **64 bytes** to **1518 bytes** including data length (46 to 1500 bytes).*

### VLAN

- **VLANs** divide devices logically on **layer 2**, allowing switches to separate **broadcast domains** and enabling **inter-VLAN routing** for forwarding packets between VLANs and different broadcast domains, resulting in smaller, manageable **sub-networks**.
    
    ![Untitled 16](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/fcd149c6-c18f-4be8-afbd-e3fd1e9db7c3)

    ![Untitled 17](https://github.com/rishabh0111/ComputerNetworKing/assets/115526596/627294a6-9646-44c4-a140-f371b9cbf48c)

- **VLANs** offer improved network security, better performance, simplified management, flexibility, cost savings, and scalability by logically **separating network traffic**, reducing **broadcast traffic**, simplifying **network management**, enabling **dynamic configuration**, reducing **hardware costs**, and facilitating **network segmentation**.
- Some of the key features of VLANs include **VLAN tagging** for distinguishing VLAN traffic, **VLAN membership** for assigning devices to VLANs, **VLAN trunking** for transmitting multiple VLANs over a single link, and **VLAN management** for configuration and administration of VLANs.
- **Types of connections in VLAN:**
    1. **Trunk Link**: All devices connected to a trunk link must be VLAN-aware. Frames on this link are tagged with a special header.
    2. **Access Link**: It connects VLAN-unaware devices to a VLAN-aware bridge. Frames on the access link are untagged.
    3. **Hybrid Link**: This link combines both trunk and access capabilities. It can connect both VLAN-aware and VLAN-unaware devices, supporting both tagged and untagged frames.
- ***Advantages*** : Improved **performance** by reducing unnecessary **broadcast** and **multicast** traffic, logical grouping of devices based on **departments**, enhanced **security**, increased **flexibility**, cost reduction by eliminating the need for expensive **routers**, and easier management of smaller **broadcast domains**.
- ***Disadvantages*: Complexity** in configuration and management, **limited scalability**, **limited security**, **limited interoperability**, **limited mobility**, **cost implications**, and **reduced visibility** for network monitoring and troubleshooting.
- Real-Time Applications of **VLANs** include improved **VoIP** quality, prioritized **video conferencing**, secure **remote access**, efficient **cloud backup and recovery**, prioritized **gaming**, and enhanced **IoT** security.

## 3. Network Layer

### Services provided by Network Layer

1. **Packet forwarding/Routing**: Relays data packets between network segments, determining the most efficient path for transfer.
2. **Connectionless communication (IP)**: Supports separate addressing and routing of data packets in **packet-switched networks**.
3. **Fragmentation**: Splits large data packets into smaller fragments for efficient transmission and reassembly.

### Switching Techniques

### 1. Circuit switching

- **Circuit switching** is a **communication method** where a **dedicated path** is established between devices for the **entire session**, preventing other devices from using it, commonly used in **voice** and **data communication**.
- **Advantages:** **guaranteed bandwidth** for the duration of the call, **low latency** due to a predetermined path without the need to establish connections for each packet, **predictable performance** without resource competition, and suitability for **real-time communication** like voice and video.
- **Disadvantages:** **inefficient use of bandwidth** as it reserves it for the entire call duration, **limited scalability** due to a finite number of circuits, and **high costs** associated with **dedicated resources** required throughout the call.

### 2. **Packet Switching**

- **Packet switching** is a method where data is divided into **packets** and transmitted over the network, with each packet containing **source and destination addresses** for routing, potentially resulting in **out-of-order delivery** and delays due to **network congestion**.
- **Advantages:** **efficient use of bandwidth**, **flexibility** in handling diverse data rates and packet sizes, **scalability** to accommodate large traffic volumes, and **cost-effectiveness** through resource sharing among multiple users.
- **Disadvantages:** **higher latency** due to routing through multiple nodes, limited **Quality of Service (QoS)** guarantees, potential **packet loss** due to network congestion or transmission errors, and unsuitability for **real-time communication** such as voice and video due to the risk of latency and packet loss.

### 3. Message Switching

### IPv4

- **IPv4** (Internet Protocol version four) was introduced in 1983 for ARPANET.
- IPv4 addresses are **32-bit integers** having an address space of 2^32 expressed in **decimal/hexadecimal notation**.
- Dotted decimal notation uses values between 0 and 255 for each segment, without preceding zeroes.
- Parts of IPv4:
    - **Network Part:** Identifies the network and its **class**.
    - **Host Part:** Identifies each machine on the network.
    - **Subnet number:** Local networks that have massive numbers of hosts are divided into subnets and subnet numbers are appointed to that.

### IP Addressing

### 1. Classful Addressing

- In a network, the **host ID** must be unique. The **network address** has all host ID bits set to 0 and is used for network identification, while the **broadcast address** has all host ID bits set to 1 and is used for broadcasting to all hosts on the network.
- This addressing divides the 32-bit IP address into **five sub-classes**:
    
    
    | CLASS | Leading Bits | Network ID bits | Host ID bits | No. of networks | Addresses per network | Default Subnet Mask | Start Address | End Address | Purpose | Additional Notes |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | A | 0 | 8 | 24 | 2^7 - 2 (126) | 2^24 - 2 | 255.0.0.0 | 1.0.0.0 | 126.255.255.255 | Networks that contain a large number of hosts. | 0.0.0.0 and 127.x.y.z are special addresses. From 127.0.0.0 to 127.255.255.255 is reserved for loopback addresses, used to test network connectivity on a local machine. 0.0.0.0 – 0.0.0.8 is used for communication within the current network. |
    | B | 10 | 16 | 16 | 2^14 | 2^16 - 2 | 255.255.0.0 | 128.0.0.0 | 191.255.255.255 | Medium to Large-sized networks | APIPA (Automatic Private IP Addressing) is a mechanism that enables devices to self-assign a link-local address within the range of 169.254.0.0 to 169.254.255.255 when a DHCP server is unavailable. |
    | C | 110 | 24 | 8 | 2^21 | 2^8 - 2 (254) | 255.255.255.0 | 192.0.0.0 | 223.255.255.255 | Small-sized networks | Test-net addresses are reserved IP ranges for testing/documentation (e.g., 192.0.2.0/24, 198.51.100.0/24, 203.0.113.0/24). |
    | D | 1110 | - | - | - | - | - | 224.0.0.0 | 239.255.255.255 | Reserved for multicast communication | Class D addresses do not have network or host portions in the same sense as Class A, B, and C. Instead, they are used for multicast group identification. |
    | E | 1111 | - | - | - | - | - | 240.0.0.0 | 255.255.255.255 | Reserved for experimental / research use | Not intended for public use and are reserved for future. |
    
    ![Untitled design.png](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled_design.png)
    

---

### 2. Classless Addressing

- **Reasons for Adopting Classes Addressing:**
    - *Reason 1:* **Classless** addressing **prevents wastage** of addresses by assigning a **variable-length of** block of addresses to the customer according to their requirement, unlike **classful** addressing which assigns a **fixed-size** block.
    - *Reason 2:* **Classless** addressing was adopted due to the need for a fair distribution of addresses to organizations and the introduction of **Internet Service Providers (ISPs)** that required variable-length blocks of addresses to cater to different customer needs.
- ****CIDR Notation:****
    - **Classless addressing** divides IPv4 addresses into **prefix(network id)** and **suffix(host address)** parts.
    - **Addresses** belonging to the **same block** persist the **same prefix** whereas **each host in a block** has a **different suffix**.
    - **Length of a prefix (n)** can be **0, 1, 2, 3, . . . . ., 32**. And **suffix** would be **(32 - n)**.
    - In classless addressing, the **prefix length** is included with each address using **slash notation** or **Classless Inter-Domain Routing (CIDR) notation**.
    - For 167.199.170.82/27, ‘**27**’ denotes the length of the **prefix**. So, the length of the **suffix** would be ‘**32-27= 5**‘.
- **CIDR Block:**
    
    For the correct working of CIDR blocks, three restrictions are implemented on the blocks of classless addressing.
    
    1. A block of addresses allocated to an organization must have the **contiguous unallocated addresses**.
    2. The number of addresses in a block allocated to an organization must be the **power of 2**.
    3. The **first address** of every block must be **divisible** by the **length of the block**.
- **Number of host addresses** in a block, $N = 2^{32-n}$ , n is the length of prefix.
- **First address of a block**
    
    $First Address = (any address) AND (network mask)$
    
- **Last address of a block**
    
    $Last Address = (any address) OR [NOT (network mask)]$
    
- ****Classless Addressing Example:****
    - Given IPv4 classless address: **167.199.170.82/27**
    - Prefix length of **27** indicates **32** addresses in the network block.
    - First address: **167.199.170.64** (calculated using given address and network mask)
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2018.png)
    
    - Last address: **167.199.170.95** (calculated using given address and complement of network mask)
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2019.png)
    
    - The network block has a range from **167.199.170.64** to **167.199.170.95**.
    - Total hosts in the network: **32**. CIDR block satisfies rules: power of 2 addresses, first address divisible by block size. The block also contains **32** contiguous unallocated addresses.

### IPv4 Header

![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2020.png)

***VERSION:** Version of the IP protocol (4 bits), which is 4 for IPv4*

***HLEN:** IP header length (4 bits), which is the number of 32 bit words in the header. The minimum value for this field is 5 and the maximum is 15.*

***Type of service:** Low Delay, High Throughput, Reliability (8 bits)*

***Total Length:** Length of header + Data (16 bits), which has a minimum value 20 bytes and the maximum is 65,535 bytes.*

***Identification:** Unique Packet Id for identifying the group of fragments of a single IP datagram (16 bits)*

***Flags:** 3 flags of 1 bit each : reserved bit (must be zero), do not fragment flag, more fragments flag (same order)*

***Fragment Offset:** Represents the number of Data Bytes ahead of the particular fragment in the particular Datagram. Specified in terms of number of 8 bytes, which has the maximum value of 65,528 bytes.*

***Time to live:** Datagram’s lifetime (8 bits), It prevents the datagram to loop through the network by restricting the number of Hops taken by a Packet before delivering to the Destination.*

***Protocol:** Name of the protocol to which the data is to be passed (8 bits)*

***Header Checksum:** 16 bits header checksum for checking errors in the datagram header*

***Source IP address:** 32 bits IP address of the sender*

***Destination IP address:** 32 bits IP address of the receiver*

***Option:** Optional information such as source route, record route. Used by the Network administrator to check whether a path is working or not.*

### **Unicast, Broadcast and Multicast**

1. **Unicast** is a network communication method where data is transmitted from a **single sender** to a **single recipient**, allowing **one-to-one transmission** between devices with unique **IP addresses**.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2021.png)
    
2. Broadcasting transfer (one-to-all) techniques can be classified into two types:
    1. **Limited Broadcasting** is a network communication method that sends data packets to **all devices** in a network using the destination address **255.255.255.255**, allowing information transfer from a **single sender** to **all recipients**.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2022.png)
        
    2. **Direct Broadcasting** is a network communication method where a device in one network sends a packet stream to **all devices** over another network by setting the **Host ID part bits** of the destination address to 1 in the datagram header.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2023.png)
        
3. **Multicasting** combines **unicast** and **broadcast**, enabling **one/more senders** and **recipients** to participate in data transfer. It allows servers to send **single data stream** copies to multiple hosts using protocols like **IGMP(Internet Group Management Protocol)**, **multicast routing**, and **Class D** in IP addressing.

### **IPv6**

- **IPv6**, a solution to **IPv4 exhaustion**, was developed by **IETF**, featuring a **128-bit** address space of **2^128** and using a **hexadecimal** format with **8 groups**, each representing **16 bits**, separated by **colons**.

![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2024.png)

- **IPv6** offers more efficient header format with separate **options**, new **functionalities**, **extensibility**, support for **resource allocation** and **real-time traffic**, and enhanced **security** through encryption and authentication options.
- **Addressing methods:**
    1. **Unicast Address**: Identifies a single network interface, with packets sent to this address delivered to the **specified** interface.
    2. **Multicast Address**: Used by multiple hosts in a **group**, packets sent to a multicast address are distributed to all interfaces corresponding to that address, allowing simultaneous transmission to multiple destinations.
    3. **Anycast Address**: Assigned to a group of interfaces, packets sent to an anycast address are delivered to only one member interface, typically the nearest host.
    Note: IPv6 does not define the concept of **broadcast** addresses.
- **IPv6 Header:**
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2025.png)
    
    - **Version (4-bits)**: Indicates the version of the Internet Protocol, currently represented by the bit sequence 0110.
    - **Traffic Class (8-bits)**: Indicates the class or priority of the IPv6 packet, allowing routers to handle traffic based on priority. Congestion controlled traffic is assigned values 0 to 7, while uncontrolled traffic, typically used for Audio/Video data, is assigned values 8 to 15. Priorities can be set by the source node but can be changed by routers along the way.
    - **Flow Label (20-bits)**: Used by the source to label packets belonging to the same flow, requesting special handling from intermediate routers. It helps distinguish different flows, as multiple flows may exist between a source and destination.
    - **Payload Length (16-bits)**: Indicates the total size of the payload, including extension headers and upper-layer packets. If the payload length exceeds 65,535(2^16-1) bytes, the field is set to 0, and the jumbo payload option is used.
    - **Next Header (8-bits)**: Indicates the type of extension header immediately following the IPv6 header or the protocols within upper-layer packets, such as TCP or UDP.
    - **Hop Limit (8-bits)**: Similar to the Time to Live (TTL) field in IPv4, it indicates the maximum number of intermediate nodes the packet is allowed to travel. The value is decremented by each forwarding node, and the packet is discarded if the value reaches 0.
    - **Source Address (128-bits)**: Represents the IPv6 address of the original packet source.
    - **Destination Address (128-bits)**: Indicates the IPv6 address of the final destination, used by intermediate nodes for correct routing.
    - **Extension Headers**: Introduced in IPv6 to address the limitations of the IPv4 Option Field, extension headers allow for additional functionality. The first extension header is pointed to by the Next Header field, and subsequent extension headers are linked in a chain.

### Routing

Routing is a process that is performed by layer 3 (or network layer) devices in order to deliver the packet by choosing an **optimal path** from one network to another.

### Types of Routing

1. **Static Routing**
    - Static routing is a process in which we have to **manually** add routes to the routing table.
    - Static routing offers *advantages* like reduced router **CPU overhead**, added **security** by limiting routing to specific networks, and no **bandwidth usage** between routers.
    - Disadvantages of static routing include the **manual effort** required for administrators to add routes to the routing table on each router in a large network and the need for administrators to possess **extensive knowledge** of the network's **topology**.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2026.png)
    
2. **Default Routing**
    - It is a method where all packets are forwarded to a single configured router (next hop), regardless of the destination network, commonly used with **stub routers** that have only one route to reach all other networks.
3. **Dynamic Routing**
    - It automatically adjusts routes based on the current state of the routing table using protocols like **RIP** and **OSPF**, allowing routers to exchange route information and adapt to changes in the network **topology**.
    - It offers advantages like easy configuration, effective route selection, and remote network discovery, but it **consumes more bandwidth** for neighbor communication and is **less secure** than static routing.

### Routing Protocols

### 1. Intra-domain / Interior-gateway Routing Protocols

- **Distance Vector Routing (DVR) Protocol**
    - This protocol requires that a router inform its **neighbors** of topology changes periodically.
    - Also know as **old ARPANET routing** algorithm (or **Bellman-Ford algorithm**).
    - **Distance Vector Algorithm –**
        1. A router transmits its distance vector to each of its neighbors in a routing packet.
        2. Each router receives and saves the most recently received distance vector from each of its neighbors.
        3. A router recalculates its distance vector when:
            - It receives a distance vector from a neighbor containing different information than before.
            - It discovers that a link to a neighbor has gone down.
    - **Example:**
        
        Consider 3-routers X, Y and Z
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2027.png)
        
        As we can see that distance will be **less** going from X to Z when Y is intermediate node(hop) so it will be update in routing table X.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2028.png)
        
        Similarly for Z also –
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2029.png)
        
        Finally the routing table for all –
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2030.png)
        
    - **Routing Information Protocol (RIP)**
        - It uses **hop count** as a routing metric to find the best path between the source and the destination network. RIP uses port number **520**.
        - Hop count in routing refers to the number of routers between the source and destination network, and **RIP** limits the number of hops to prevent **routing loops**, with a maximum hop count of **15** and a hop count of **16** indicating **network unreachable**.
        - Features of **RIP** include **periodic exchange** of network updates, **broadcast** of updates, sending **full routing tables** in updates, and routers **trusting** routing information received from neighbor routers, also known as **Routing on rumors**.
        - ****RIP versions:****
            
            
            | RIP v1 | RIP v2 | RIPng |
            | --- | --- | --- |
            | Sends update as broadcast | Sends update as multicast | Sends update as multicast |
            | Broadcast at 255.255.255.255 | Multicast at 224.0.0.9 | Multicast at FF02::9 (RIPng can only run on IPv6 networks)  |
            | Doesn’t support authentication of updated messages | Supports authentication of RIPv2 update messages | – |
            | Classful routing protocol | Classless protocol updated supports classful | Classless updates are sent |
        - **RIP** is commonly used in **small to medium-sized networks**, **legacy networks**, and **lab environments**. It is easy to configure, requires little maintenance, and serves as a **backup routing protocol** in certain networks.
        - It offers advantages such as **simplicity**, **easy implementation**, **fast convergence**, **automatic updates**, **low bandwidth overhead**, and **compatibility** with different network devices.
        - It has limitations in terms of **scalability**, **slow convergence**, **routing loops**, **limited load balancing support**, **security vulnerabilities**, and **inefficient bandwidth usage**.
- **Link State / Unicast Routing**
    - In this ****routing, **routers** exchange messages to learn the **network topology**, allowing them to compute **routing tables** based on **shortest path computation**.
    - It feature the use of **Link State Packets** containing routing information, which are used to build a **Link-State Database**. The **Shortest Path First Algorithm** (Dijkstra algorithm) is then applied to the database to determine the shortest path, resulting in a **Routing Table** listing known paths and interfaces.
    - **Example:**
        
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2031.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2032.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2033.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2034.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2035.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2036.png)
        
    - **Open Shortest Path First (OSPF)**
        - It **protocol** where routers exchange topology information with their nearest neighbors and calculate end-to-end paths using a **variant** of the Dijkstra algorithm.
        - The main **advantage** of OSPF is its ability to calculate routes based on specific criteria, making it useful for **traffic engineering** and quality of service requirements.
        - However, OSPF's main **disadvantage** is its lack of scalability as the number of routers increases, leading to larger and more frequent topology updates and longer route calculation times.
        - Each OSPF router distributes information about its local state through **Link State Advertisement (LSA**) messages, which are used to build an identical database of the topology.
        - Using the database, each router calculates its **routing table** using a Shortest Path First (SPF) algorithm, containing destinations, next hop IP addresses, and outgoing interfaces.
        - OSPF supports route **recalculation** when topology changes occur and minimizes routing protocol traffic.
- **Enhanced Interior Gateway Routing Protocol (EIGRP)**
    - **It** is a dynamic routing protocol that determines the optimal path between layer 3 devices using **metrics**, operating on the **network layer** of the OSI model with **protocol number 88**.
    - In EIGRP, various messages are used to communicate with neighbor devices. These include:
        - **Hello messages**: Exchanged between devices to discover/recover neighbors and determine if any device is operating EIGRP. They contain information such as AS number and k values. Hello messages can be multicast or unicast, and a hello with no data serves as an acknowledgment.
        - **NULL update**: Used to calculate Smooth Round Trip Timer (SRTT) and Retransmission Time Out (RTO). SRTT measures the time for a packet to reach the neighboring router and receive acknowledgment, while RTO is the waiting time for an acknowledgment in case multicast fails.
        - **Full Update**: Exchanged after hello messages or when the neighborship is formed. These messages contain all the best routes.
        - **Partial update**: Exchanged during topology changes or when new links are added. They only include new routes, not all routes, and are multicast.
        - **Query messages**: Multicast when a device is declared dead and there are no routes to it in the topology table.
        - **Reply messages**: Acknowledgments of query messages, providing the route to the network requested in the query.
        - **Acknowledgment messages**: Used to acknowledge EIGRP updates, queries, and replies. Hello packets serve as acknowledgments, while reply, query, and update messages require acknowledgment.
        
        It's important to note that hello and acknowledgment packets do not require acknowledgment, while reply, query, and update messages are considered reliable and require acknowledgment.
        

### 2. Inter-domain / Exterior-gateway Routing Protocols

1. **Border Gateway Protocol (BGP)**
    - BGP is an **Internet routing protocol** that exchanges **network reachability information** between **Autonomous Systems**, enabling connectivity across diverse **network topologies**.
    - It supports efficient routing by utilizing the **Next-Hop Paradigm**. It allows multiple BGP speakers within an AS to coordinate and exchange information. BGP includes **path information** in its advertisements and allows administrators to implement **custom policies**. It runs over **TCP** to ensure reliable communication and helps conserve **network bandwidth**. BGP supports the use of **CIDR** for efficient address allocation and provides built-in **security features** for protecting network connectivity.
    - BGP performs three main functions:
        1. Initial peer acquisition and authentication: BGP peers establish a TCP connection and exchange messages to ensure **mutual agreement** for communication.
        2. Sending **reachability information**: BGP exchanges information about available routes, both **positive and negative**, to enable proper routing.
        3. Verifying network **connectivity**: BGP checks the functionality of peers and the network connection between them to ensure proper operation.
    - BGP performs **route information management functions** including **route storage**, **route update**, **route selection**, and **route advertisement** to maintain accurate routing information within the network.

![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2037.png)

### **Network Address Translation (NAT)**

- Network Address Translation (NAT) allows multiple devices in a private network to **access the Internet** using a single **public IP address**. It **translates private IP addresses to public IP addresses** and vice versa, and also **masks port numbers** for routing. NAT is typically implemented on **routers** or **firewalls**.
- **NAT** **Working:**
    
    The **border router**, typically configured for **NAT**, **translates local IP addresses to global IP addresses** when packets leave the local network and **vice versa** when packets enter the network. If the **NAT address pool** is exhausted, packets are **dropped** and an **ICMP host unreachable** packet is sent to the destination.
    
- **Why mask port numbers ?**
    - Two hosts A and B in a network request the same destination on the same port number simultaneously.
    - If NAT only translates IP addresses, both hosts' IP addresses would be **masked** by the network's public IP address and sent to the destination.
    - The destination sends replies to the **public IP address of the router**.
    - When NAT receives a reply, it becomes unclear which reply belongs to which host because the **source port numbers** for both hosts are the same.
    - To solve this problem, NAT **masks the source port number** in addition to the IP address.
    - NAT maintains an **NAT table** to correctly associate incoming replies with their respective hosts.
- **NAT inside and outside addresses:**
    - **Inside local address –** An IP address that is assigned to a host on the Inside (local) network. The address is probably not an IP address assigned by the service provider i.e., these are private IP addresses. This is the inside host seen from the inside network.
    - **Inside global address –** IP address that represents one or more inside local IP addresses to the outside world. This is the inside host as seen from the outside network.
    - **Outside local address –** This is the actual IP address of the destination host in the local network after translation.
    - **Outside global address –** This is the outside host as seen from the outside network. It is the IP address of the outside destination host before translation.
- **Network Address Translation (NAT) Types:**
    1. **Static NAT**: Involves a one-to-one mapping between a single unregistered (**private**) IP address and a legally registered (**public**) IP address. Often used for **web hosting**, but can be expensive for organizations requiring many public IP addresses.
    2. **Dynamic NAT**: Translates unregistered IP addresses to registered (public) IP addresses from a pool. Limited number of private IP addresses can be translated at a given time. If the pool is full, packets may be dropped. Suitable when the number of users is fixed, but can still be costly due to the need for multiple public IP addresses.
    3. **Port Address Translation (PAT)**: Also known as NAT overload. Allows multiple local (private) IP addresses to share a single registered IP address by using different port numbers to distinguish traffic. Cost-effective as thousands of users can connect to the internet using only one public IP address. It is the most commonly used NAT type.
- *Advantages* of NAT include **conserving legally registered IP addresses**, providing **privacy** by hiding the device's IP address during traffic transmission, and **eliminating the need for address renumbering** when a network evolves.
- *Disadvantages* of NAT include **switching path delays**, **application incompatibility**, **complications with tunneling protocols** like IPsec, and the involvement of the router with **port number manipulation** beyond its network layer function.

### **Tunneling**

- Tunneling is a technique that enables the connection of source and destination networks of different types through an intermediate network. It involves **encapsulating data** at various protocol layers to facilitate communication between networks with different interfaces, following a layered protocol model such as OSI or TCP/IP.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2038.png)
    
- Tunneling abstracts the WAN as a "big tunnel" between multiprotocol routers M1 and M2, allowing hosts A and B to communicate without directly dealing with the WAN. It involves **encapsulating** IP packets within WAN packets, enabling communication between **different networks**.
- **Types of Tunneling Protocols:**
    1. ****Generic Routing Encapsulation (GRE):**** It encapsulates IP packets in a GRE header, hiding the original packet. It adds a delivery header with new source and destination addresses. Routers configured with GRE can encrypt and decrypt the GRE header, enabling the original packet to travel through a tunnel and emerge unchanged.
    2. ****Internet Protocol Security (IPsec):**** IPSec is an **IETF standard** protocol suite that secures communication between two points in an IP network. It provides **data authentication**, **integrity**, **confidentiality**, and includes **key exchange** and **management**.
    3. ****IP-in-IP:**** IP-in-IP is a Tunneling Protocol for encapsulating IP packets inside another IP packet.
    4. ****Secure Shell (SSH):**** It is a **cryptographic network protocol** used for **secure** and **encrypted data transfer** over the network, enabling seamless **remote login** to servers without the need to remember or enter passwords for each system.
    5. ****Point-to-Point Tunneling Protocol (PPTP): It**** is a widely used VPN protocol that creates a **tunnel** and secures **data packets**. It utilizes **Point-to-Point Protocol (PPP)** for data encryption and has been supported on **Windows, Mac, and Linux** operating systems.
    6. ****Secure Socket Tunneling Protocol (SSTP):**** A VPN protocol developed by Microsoft that uses SSL to secure the connection, but only available for Windows.
    7. ****Layer 2 Tunneling Protocol (L2TP):**** It is a computer networking protocol, published in 2000, that enables VPN connections over the Internet. It combines the best features of PPTP and L2F, allowing ISPs to support VPN operations.
    8. ****Virtual Extensible Local Area Network (VXLAN): It is a network virtualization technology that stretches layer 2 connections over layer 3 networks by encapsulating Ethernet frames in a VXLAN packet which includes IP addresses to address the scalability problem in a more extensible manner.****
- **What is SSL Tunneling?**
    - It involves a client that requires an SSL connection to a backend service or secures a server via a proxy server. This proxy server opens the connection between the client and the backend service and copies the data to both sides without any direct interference in the SSL connection.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2039.png)
    

### ARP & RARP

- **ARP-family:**
    1. **Address Resolution Protocol (ARP):**
        - **Address Resolution Protocol(**ARP) is a **protocol** used within the **same network** to discover the **MAC address** associated with an **IP address.** It operates from the **network layer** to the **data link layer**.
        - It enables the mapping process between **IP addresses** and **MAC addresses**, ensuring that the MAC address of the destination machine is known before sending an IP packet, by broadcasting an **ARP-discovery packet** and receiving a unicast **ARP-reply packet** from the intended receiver, resulting in the updating of the **ARP-cache** and subsequent sending of unicast messages to the destination.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2040.png)
        
    2. **Reverse Address Resolution Protocol (RARP):**
        - Reverse ARP (RARP) is a protocol used in local area networks to request an **IP address** from the gateway-router's **ARP table**. The **RARP server**, configured as a special host in the LAN, responds to broadcast packets containing the requester's **MAC address**, searching for a matching entry in the **IP-to-MAC address mapping table**.
        - RARP is supported by LAN technologies such as **Ethernet, Ethernet II, Token Ring, and Fiber Distributed Data Interface (FDDI)**. However, RARP is not widely used in modern networks due to the availability of more advanced protocols like **BOOTP (Bootstrap Protocol)** and **DHCP** that offer enhanced functionality.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2041.png)
        
    3. **Inverse Address Resolution Protocol (InARP)** finds an **IP address** from a **MAC address** in networks like **ATM** and **Frame Relay**. It maps local identifiers (**DLCIs**) to remote **IP addresses** when the IP address is unknown but the identifier is available, enabling efficient communication.
    4. **Proxy ARP** enables devices in different network segments connected by a router in the same IP network to communicate by resolving **IP addresses** to **MAC addresses**. It allows the "proxy router" to respond with its **MAC address**, facilitating data transmission between devices that would otherwise be unable to resolve addresses due to broadcast limitations.
    5. **Gratuitous Address Resolution Protocol (Gratuitous ARP)** is used during computer boot-up to **broadcast** the **MAC address**, enabling DHCP servers to allocate an **IP address**. It helps **detect IP conflicts** and updates **ARP** and **switch port MAC address tables**.
- **What is ARP poisoning (ARP spoofing)?**
    - ARP spoofing is a type of network attack where the attacker sends **falsified** **ARP requests** over the **LAN** to connect their MAC address to a legitimate server on the victim network.
    - This allows the attacker to intercept and access data intended for that **IP address**.
    - ARP poisoning, also known as ARP spoofing, enables the attacker to **intercept**, **modify**, or **halt** data in-transit.
    - ARP poisoning can serve as a gateway for more severe attacks such as **Man-in-the-Middle**, **denial of service**, or **session hijacking** attacks.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2042.png)
        
- **Difference between ARP and RARP**
    
    
    | ARP | RARP |
    | --- | --- |
    | Protocol to map an IP address to a physical (MAC) address | Protocol to map a physical (MAC) address to an IP address |
    | Obtains the MAC address of a network device with known IP | Obtains the IP address of a network device with known MAC |
    | Client broadcasts IP address and requests MAC address | Client broadcasts MAC address and requests IP address |
    | Server responds with corresponding MAC address | Server responds with corresponding IP address |
    | Resolves IP addresses to MAC addresses in modern networks | Rarely used as most devices have pre-assigned IP addresses |
    | Local host manages ARP table | RARP server manages RARP table |
    | Fetches receiver's MAC address in ARP | Fetches IP address in RARP |
    | ARP table uses ARP reply for updating | RARP table uses RARP reply for IP address configuration |
    | Used by hosts and routers to know MAC addresses in network | Used by small users with fewer facilities |
    | ARP is used in sender's side to map receiver's MAC address | RARP is used in receiver's side to map sender's IP address |

## 4. Transport Layer

### **Working of Transport Layer**

- *At the sender's side:* The **transport layer** receives data (message) from the **Application layer** and then performs **Segmentation**, which divides the actual message into segments. It adds the **source and destination's port numbers** into the header of the segment and transfers the message to the **Network layer**.
- *At the receiver's side:* The **transport layer** receives data from the **Network layer**, **reassembles** the segmented data, reads its header, **identifies the port number**, and forwards the message to the appropriate port in the **Application layer**.

### ****Responsibilities of a Transport Layer****

- ****1. The Process to Process Delivery****
    - The **Data Link Layer** requires the **MAC address** of the source-destination *hosts* to correctly deliver a ***frame***. And the **Network layer** requires the **IP address** for appropriate routing of ***packets***.
    - Similarly, the **Transport Layer** requires a **Port number** to correctly deliver the ***segments*** of data to the correct ***process*** among multiple processes running on a particular host.
    - A **port number** is a **16-bit address** used to identify any client-server program uniquely.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2043.png)
        
- ****2. End-to-end Connection between Hosts****
    - The **transport layer** is responsible for creating the end-to-end connection between hosts, primarily using **TCP** and **UDP.**
    - **TCP** is a secure, connection-oriented protocol that uses a **handshake protocol** to establish connection between two end hosts and it ensures **reliable delivery** of messages.
    - **UDP**, is a **stateless** and **unreliable protocol** that ensures **best-effort delivery**. It is suitable for applications that have little concern with flow or error control and require sending a bulk of data, such as video conferencing. It is often used in multicasting protocols.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2044.png)
        
- ****3. Multiplexing and Demultiplexing****
    - **Multiplexing** (many to one) is the process of acquiring data from several processes at the sender's side and merging it into one packet along with headers, sending it as a single packet.
    - Multiplexing enables the simultaneous use of different processes over a network on a host. The processes are differentiated by their **port numbers**.
    - **Demultiplexing** (one to many) is required at the receiver's side. It involves distributing the received message into different processes.
    - The **transport layer** receives segments of data from the network layer and **demultiplexes** them, delivering each segment to the appropriate process running on the receiver's machine.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2045.png)
        
- ****4. Congestion Control****
    - **Congestion** occurs when there are too many sources over a network trying to send data, causing the router buffers to **overflow** and resulting in **packet loss** and **retransmission**.
    - **Types of Congestion Control Algorithms**:
        1. **Leaky Bucket Algorithm**
            1. When host wants to send packet, packet is thrown into the bucket.
            2. The bucket leaks at a constant rate, meaning the network interface transmits packets at a constant rate.
            3. Bursty traffic is converted to a uniform traffic by the leaky bucket.
            4. In practice the bucket is a finite queue that outputs at a finite rate.
            
            ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2046.png)
            
        2. **Token bucket Algorithm**
            - The **token bucket algorithm** is a more flexible alternative to the leaky bucket algorithm for network traffic shaping or rate-limiting.
            - In the token bucket algorithm, packets are transmitted based on the availability of tokens in the bucket. Tokens are generated at each tick, and incoming packets need to capture a token to be transmitted at the same rate. This introduces flexibility in transmitting **bursty packets** if tokens are available.
            
            ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2047.png)
            
            **Figure (A):** Bucket holds 3 tokens, 5 packets wait. Packets require tokens for transmission. **Figure (B):** 3 packets transmitted, 2 packets wait for more tokens.
            
    - **TCP Congestion Control**
        - TCP **congestion control** manages data flow and prevents congestion by using a **congestion window** and involving both the **receiver** and the **network** to dictate the sender's window size.
        - **Approaches for Congestion Control:**
            1. **Slow Start Phase:** The sender sets congestion window size = maximum segment size (1 MSS) at the initial stage. The sender increases the size of the congestion window by 1 MSS after receiving the ACK (acknowledgment). The size of the congestion window increases **exponentially** in this phase. The **formula** for determining the size of the congestion window is Congestion window size = Congestion window size + Maximum segment size
                
                
                | Round trip time | Congestion window size | result |
                | --- | --- | --- |
                | After a round trip of 1 | (2)1 | 2 MSS |
                | After a round trip of 2 | (2)2 | 4 MSS |
                | After a round trip of 3 | (2)3 | 8 MSS |
                
                ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2048.png)
                
            2. **Congestion Avoidance Phase:** After the threshold is reached, the size of the congestion window is increased by the sender **linearly** in order to avoid congestion. Each time an acknowledgment is received, the sender increments the size of the congestion window by 1.
                
                The **formula** for determining the size of the congestion window in this phase is Congestion window size = Congestion window size + 1.
                
                This phase continues until the size of the window becomes equal to that of the receiver window size.
                
            3. **Congestion Detection Phase:** The sender identifies the segment loss and gives acknowledgment depending on the type of loss detected.
                1. Case-01: **Detection On Time Out**
                    
                    In this, the timer **time-out** expires even before receiving **acknowledgment** for a segment.
                    It suggests a stronger possibility of **congestion** in a network.
                    In this, there are chances that a segment has been **dropped** in the network.
                    *Reaction in response to Detection on time out:*
                    
                    - Setting the **threshold** to start to half of the current size of window
                    - Decreasing the size of the **congestion window** to **MSS**
                    - **Slow start** phase is resumed.
                2. Case-02: **Detection On Receiving 3 Duplicate Acknowledgements**
                    
                    This case suggests the weaker possibility of **congestion** in the network. In this, the sender receives three **duplicate acknowledgments** for a network segment. The chances are that fewer segments have dropped while the one sent later might have reached.
                    
                    Reaction on receiving 3 duplicate acknowledgments:
                    
                    - Setting the **threshold** to start to half of the current size of the window.
                    - Decreasing the size of the **congestion window** to that of the **slow start threshold.**
                    - The **congestion avoidance** phase is resumed.
                
                ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2049.png)
                
- ****5. Data integrity and Error Correction****
    - The **transport layer** performs error detection in messages from the **application layer** using **error detection codes** and **checksums**. It verifies that received data is not corrupted and utilizes **ACK** (Acknowledgment) and **NACK** (Negative Acknowledgment) services to inform the sender about the arrival status of the data. The transport layer also ensures the **integrity** of the data.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2050.png)
        
        - **Error Control in TCP**
            - TCP protocol has methods for finding out **corrupted segments**, **missing segments**, **out-of-order segments**, and **duplicated segments**.
            - Error control in TCP is mainly done through the use of three simple techniques:
                1. **Checksum:** Every segment contains a checksum field which is used to find corrupted segments. If the segment is corrupted, then that segment is discarded by the destination TCP and is considered lost.
                2. **Acknowledgement:** TCP has another mechanism called acknowledgement to affirm that the data segments have been delivered. Control segments that contain no data but have sequence numbers will be acknowledged as well but ACK segments are not acknowledged.
                3. **Retransmission:** Segments can be retransmitted when they are missing, delayed, or corrupted. Retransmission occurs when the sender receives three duplicate acknowledgements (ACK) or when a retransmission timer expires.
                    1. **Retransmission after RTO**: TCP maintains a retransmission time-out (RTO) timer for unacknowledged segments. When the timer expires, the earliest segment is retransmitted. RTO is dynamically updated based on the round trip time (RTT) of segments.
                    2. **Retransmission after Three duplicate ACK segments**: If the RTO value is large, the three duplicate acknowledgement method is used. When three duplicate ACK segments are received, the missing segment is immediately retransmitted instead of waiting for the timer to expire. This fast retransmission avoids unnecessary delays.
    
- ****6. Flow Control****
    - The transport layer provides **flow control** between adjacent layers of the TCP/IP model. TCP implements flow control techniques to prevent data loss when there is a speed difference between the sender and receiver. The **sliding window protocol** is used, where the receiver sends a window back to the sender, indicating the maximum amount of data it can receive.

### Port Numbers

- **Port numbers** are 16-bit integers ranging from 0 to 65,535.
    - **Servers** use **well-known ports**, which are the port numbers in the range of 0-1023 and are considered privileged.
    - **Clients** use **ephemeral (short-lived) ports**.
- The **Internet Assigned Numbers Authority (IANA)** maintains a list of port number assignments.
    - **Well-known ports** (0-1023) are controlled and assigned by IANA.
    - **Registered ports** (1024-49151) are registered and listed by IANA for convenience. The number 49151 represents three-fourths (¾) of the total 65,536 possible port numbers.
    - **Dynamic ports** (49152-65535) are ephemeral ports.

### **Socket in Computer Network**

- A **socket** is an endpoint of a two-way communication link between two programs running on a network.
- Each socket has a specific address, composed of an **IP address** and a **port number**.
- It enables **inter-process communication (IPC)** by establishing named contact points for communication.
- Sockets are created using the **'socket'** system call, similar to how 'pipe' is used to create pipes.
- Sockets provide bidirectional **FIFO communication** over the network.
- Sockets are commonly used in **client-server applications**.
    - The server creates a socket, attaches it to a network port, and waits for the client to contact it.
    - The client creates a socket and attempts to connect to the server socket.
    - Once the connection is established, data transfer takes place.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2051.png)
    
- **Types of Sockets :**
    - **Datagram Socket**: A network type with **connectionless communication**, similar to a **mailbox** where posted data packets are collected and delivered to a receiving socket.
    - **Stream Socket**: An interprocess or network socket that provides a **connection-oriented**, **sequenced flow of data** without record boundaries. It is similar to a **phone** where a connection is established between two ends and data is transferred during a conversation.
- **Socket Function Calls:**
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2052.png)
    
    | Function Call | Description |
    | --- | --- |
    | Socket() | To create a socket |
    | Bind() | It’s a socket identification like a telephone number to contact |
    | Listen() | Ready to receive a connection |
    | Connect() | Ready to act as a sender |
    | Accept() | Confirmation, it is like accepting to receive a call from a sender |
    | Write() | To send data |
    | Read() | To receive data |
    | Close() | To close a connection |

### TCP

- TCP (Transmission Control Protocol) is a reliable and **connection-oriented** network protocol that facilitates the secure and **orderly transmission** of data over interconnected networks, enabling **full duplex** data transmission).
- *Advantages*: **Reliable** and **error-checking** protocol with **recovery mechanisms**, provides **flow control**, ensures proper **delivery** and **order of data**, **open protocol** not owned by any organization or individual, assigns **IP addresses** and **domain names** for distinguishability on the network.
- *Disadvantages*: Size can be an issue for small networks with low resources, multiple layers can slow down network speed, limited to **TCP/IP suite** and cannot work with other protocol stacks like **Bluetooth**, lack of modifications since development around 30 years ago.

### **TCP Segment Structure**

- **Byte number**: All data bytes to be transmitted are assigned a number, starting from an arbitrary value.
- **Sequence number**: Segments are given sequence numbers to ensure proper reassembly of bytes at the receiver end, even if they arrive out of order. The sequence number of a segment corresponds to the byte number of the first byte being sent.
- **Acknowledgement number**: TCP provides full-duplex service, so an acknowledgement number is required. It represents the next byte number that the receiver expects to receive and serves as an acknowledgement for receiving the previous bytes.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2053.png)
    
    A sends acknowledgement number 1001, indicating it has received data bytes up to 1000 and expects 1001 next. B acknowledges receiving data bytes up to 13001 and sends acknowledgement number 13002 for the next expected byte from A.
    

![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2054.png)

- **Source Port Address –** A 16-bit field that holds the port address of the application that is sending the data segment.
- **Destination Port Address –** A 16-bit field that holds the port address of the application in the host that is receiving the data segment.
- **Sequence Number –** A 32-bit field that holds the sequence number, i.e, the byte number of the first byte that is sent in that particular segment. It is used to reassemble the message at the receiving end of the segments that are received out of order.
- **Acknowledgement Number –** A 32-bit field that holds the acknowledgement number, i.e, the byte number that the receiver expects to receive next. It is an acknowledgement for the previous bytes being received successfully.
- **Header Length (HLEN) –** This is a 4-bit field that indicates the length of the TCP header by a number of 4-byte words in the header, i.e if the header is 20 bytes(min length of TCP header), then this field will hold 5 (because 5 x 4 = 20) and the maximum length: 60 bytes, then it’ll hold the value 15(because 15 x 4 = 60). Hence, the value of this field is always between 5 and 15.
- **Control flags –** These are 6 1-bit control bits that control connection establishment, connection termination, connection abortion, flow control, mode of transfer etc. Their function is:
    - URG: Urgent pointer is valid
    - ACK: Acknowledgement number is valid (used in case of cumulative acknowledgement)
    - PSH: Request for push
    - RST: Reset the connection
    - SYN: Synchronize sequence numbers
    - FIN: Terminate the connection
- **Window size –** This field tells the window size of the sending TCP in bytes.
- **Checksum –** This field holds the checksum for error control. It is mandatory in TCP as opposed to UDP.
- **Urgent pointer –** This field (valid only if the URG control flag is set) is used to point to data that is urgently required that needs to reach the receiving process at the earliest. The value of this field is added to the sequence number to get the byte number of the last urgent byte.

### **TCP 3-Way Handshake Process**

- TCP utilizes **Positive Acknowledgement with Re-transmission** (PAR) which ensures reliable data transmission by confirming successful reception through acknowledgements and retransmitting lost or corrupted packets.
- The **Protocol Data Unit** (PDU) at the transport layer is called a **segment**.
- If a segment is damaged, the receiver discards it using the transport layer's checksum functionality for error detection.
- The sender retransmits the data unit until it receives a **positive acknowledgement** from the receiver.
- **Three** **segments** are typically exchanged between the sender (client) and receiver (server) to establish a reliable TCP connection.
- **Working**:
    - **Step 1 (SYN): T**he client wants to establish a connection with a server, so it sends a segment with SYN(Synchronize Sequence Number) which informs the server that the client is likely to start communication and with what sequence number it starts segments with.
    - **Step 2 (SYN + ACK):** Server responds to the client request with SYN-ACK signal bits set. Acknowledgement(ACK) signifies the response of the segment it received and SYN signifies with what sequence number it is likely to start the segments with
    - **Step 3 (ACK):** In the final part client acknowledges the response of the server and they both establish a reliable connection with which they will start the actual data transfer.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2055.png)
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2056.png)
    

### **TCP Connection Establishment & Termination**

### **Connection Establishment**

1. Sender initiates the process by sending a packet with the following information:
    - **Sequence number (Seq=521)**: Random initial sequence number generated by the sender.
    - **Syn flag (Syn=1)**: Requests receiver to synchronize its sequence number with the provided sequence number.
    - **Maximum segment size (MSS=1460 B)**: Sender informs its maximum segment size to avoid fragmentation.
    - **Window size (window=14600 B)**: Sender indicates its buffer capacity for storing messages from the receiver.
2. Receiver responds with its own packet containing:
    - **Sequence number (Seq=2000)**: Random initial sequence number generated by the receiver.
    - **Syn flag (Syn=1)**: Requests sender to synchronize its sequence number with the provided sequence number.
    - **Maximum segment size (MSS=500 B)**: Receiver informs its maximum segment size, agreeing on the minimum MSS.
    - **Window size (window=10000 B)**: Receiver indicates its buffer capacity for storing messages from the sender.
    - **Acknowledgement Number (Ack no.=522)**: Acknowledges the receipt of the sender's packet and requests the next expected sequence number.
    - **ACK flag (ACK=1)**: Indicates that the acknowledgement number field contains the next expected sequence number.
3. Sender sends a final reply for connection establishment, including:
    - **Sequence number (Seq=522)**: Next sequence number after the previous step.
    - **Acknowledgement Number (Ack no.=2001)**: Acknowledges the receiver's packet and specifies the next expected sequence number.
    - **ACK flag (ACK=1)**: Indicates that the acknowledgement number field contains the next expected sequence number.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2057.png)
    

### **Connection Termination**

TCP supports two types of connection releases:

1. **Graceful connection release**: The connection remains open until both parties have closed their sides of the connection.
2. **Abrupt connection release**: One TCP entity is forced to close the connection or one user closes both directions of data transfer.

**Abrupt connection release (using RST(**Reset**) segment)**:

- RST segment is sent when a non-SYN segment is received for a non-existing TCP c4onnection.
- RST segment is sent to prevent attacks when a segment with an invalid header is received.
- RST segment is sent when there's a lack of resources to support the connection or the remote host is unreachable.

**Graceful Connection Release (using FIN flag)**:

1. The client sends a TCP segment with the FIN bit set to 1 to the server, entering the **FIN_WAIT_1** state.
2. The server immediately sends an acknowledgment (ACK) segment to the client.
3. The client waits in the **FIN_WAIT_1** state for a TCP segment from the server with an acknowledgment.
4. The server sends a TCP segment with the FIN bit set to 1 to the client, entering the **TIME_WAIT** state.
5. The client acknowledges the server's segment and enters the **TIME_WAIT** state.
6. The client remains in the **TIME_WAIT** state for a certain period to allow for retransmission of the final acknowledgment.
7. After the wait, the connection formally closes, and all resources on the client-side are released.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2058.png)
    

### **Piggybacking**

- Piggybacking is the technique of **delaying outgoing acknowledgments** and **attaching them to the next data packet**, allowing the **acknowledgment to travel along** with the subsequent data frame.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2059.png)
    
- **Networking Communication:** Sliding window algorithms control network data transfer by allowing the sender to have **multiple acknowledgments** at a time. A **finite-size buffer** is maintained by both the sender and receiver to hold packets. **Timers** ensure unacknowledged packets are resent, while the sender can transmit a **window of packets** before receiving the first acknowledgment. This improves transfer rates, while the receiver advertises a **window size** to prevent buffer overflow.
- **How To Increase Network Efficiency?:** Efficiency can be improved by utilizing the **Full-duplex transmission mode**, which enables simultaneous **two-way communication**, similar to using **two half-duplex transmission nodes**.
- **Why Piggybacking?:** Efficiency is enhanced in full-duplex transmission by utilizing **piggybacking** or **two separate channels**, where each channel transmits **data frames** and **acknowledgments** bidirectionally with equal capacity. In piggybacking, the **receiver waits** until the next data packet before sending the acknowledgment, which travels alongside the **outgoing data frame**.
- *Advantages:* **better channel bandwidth utilization**, **reduced usage costs**, **improved data transfer latency**, and **avoidance of delay and rebroadcast** through the use of **short-duration timers**.
- *Disadvantage:* **additional complexity**, and if the data link layer waits too long before transmitting the acknowledgment, there is a risk of **frame rebroadcast**.

### UDP

- User Datagram Protocol (UDP) is a **connectionless** and **unreliable** Transport Layer protocol in the UDP/IP suite, offering **low-latency** and **loss-tolerating** communication without the need for prior connection establishment.
- **UDP Header:**
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2060.png)
    
    - **Source Port:** Source Port is a 2 Byte long field used to identify the port number of the source.
    - **Destination Port:** It is a 2 Byte long field, used to identify the port of the destined packet.
    - **Length:** Length is the length of UDP including the header and the data. It is a 16-bits field.
    - **Checksum:** Checksum is 2 Bytes long field. It is the 16-bit one’s complement of the one’s complement sum of the UDP header, the pseudo-header of information from the IP header, and the data, padded with zero octets at the end (if necessary) to make a multiple of two octets.
    
    <aside>
    💡 **Notes –** Unlike TCP, the Checksum calculation is not mandatory in UDP. No Error control or flow control is provided by UDP. Hence UDP depends on IP and ICMP for error reporting. Also UDP provides port numbers so that is can differentiate between users requests.
    
    </aside>
    
- ***Applications of UDP:***
    - Used for **simple request-response** communication when the size of data is less and there is lesser concern about flow and error control.
    - Suitable for **multicasting & broadcasting** as UDP supports packet switching.
    - Used for some **routing update protocols** like **RIP** (Routing Information Protocol).
    - Widely used in **online gaming** & streaming media applications, such as **IPTV, online radio,** VoIP (Voice over Internet Protocol) services, such as **Skype and WhatsApp,  and video conferencing**, where low latency and high-speed communication are essential.
    - **DNS (Domain Name System)** uses UDP for its query/response messages.
    - **DHCP (Dynamic Host Configuration Protocol)** uses UDP to dynamically assign IP addresses to devices on a network. And more protocols, including **NTP, BOOTP, NNP, TFTP, RTSP, RIP**.
    - UDP is suitable for tasks like **Trace Route, Record Route, and Timestamp** in the application layer.
- *Advantages of UDP*: **Faster transmission speed**, **lower latency**, **simpler protocol design**, **broadcast support**, and **smaller packet size** improve network performance.
- *Disadvantages of UDP*: **No reliability**, **no congestion control**, **no flow control**, **vulnerable to attacks**, and **limited use cases** restrict its suitability for certain applications.
- **TCP vs UDP**
    
    
    | Basis | Transmission Control Protocol (TCP) | User Datagram Protocol (UDP) |
    | --- | --- | --- |
    | Type of Service | https://www.geeksforgeeks.org/what-is-transmission-control-protocol-tcp/ is a connection-oriented protocol. Connection 
    orientation means that the communicating devices should establish a connection before transmitting data and should close the connection after transmitting the data. | https://www.geeksforgeeks.org/user-datagram-protocol-udp/is the Datagram-oriented protocol. This is because 
    there is no overhead for opening a connection, maintaining a connection, or terminating a connection. UDP is efficient for broadcast and multicast types of network transmission. |
    | Reliability | TCP is reliable as it guarantees the delivery of data to the destination router. | The delivery of data to the destination cannot be guaranteed in UDP. |
    | Error checking mechanism | TCP provides extensive error-checking mechanisms. 
    It is because it provides flow control and acknowledgment of data. | UDP has only the basic error-checking mechanism using checksums. |
    | Acknowledgment | An acknowledgment segment is present. | No acknowledgment segment. |
    | Sequence | Sequencing of data is a feature of Transmission Control 
    Protocol (TCP). this means that packets arrive in order at the receiver. | There is no sequencing of data in UDP. If the order is required, it has to be managed by the application layer. |
    | Speed | TCP is comparatively slower than UDP. | UDP is faster, simpler, and more efficient than TCP. |
    | Retransmission | Retransmission of lost packets is possible in TCP, but not in UDP. | There is no retransmission of lost packets in the User Datagram Protocol (UDP). |
    | Header Length | TCP has a (20-60) bytes variable length header. | UDP has an 8 bytes fixed-length header. |
    | Weight | TCP is heavy-weight. | UDP is lightweight. |
    | Handshaking Techniques | Uses handshakes such as SYN, ACK, SYN-ACK | It’s a connectionless protocol i.e. No handshake |
    | Broadcasting | TCP doesn’t support Broadcasting. | UDP supports Broadcasting. |
    | Protocols | TCP is used by https://www.geeksforgeeks.org/difference-between-http-and-https-2/,https://www.geeksforgeeks.org/file-transfer-protocol-ftp/, https://www.geeksforgeeks.org/simple-mail-transfer-protocol-smtp/ and https://www.geeksforgeeks.org/introduction-to-telnet/. | UDP is used by https://www.geeksforgeeks.org/details-on-dns/, https://www.geeksforgeeks.org/dynamic-host-configuration-protocol-dhcp/, TFTP, https://www.geeksforgeeks.org/simple-network-management-protocol-snmp/, https://www.geeksforgeeks.org/routing-information-protocol-rip/, and https://www.geeksforgeeks.org/voice-over-internet-protocol-voip/. |
    | Stream Type | The TCP connection is a byte stream. | UDP connection is a message stream. |
    | Overhead | Low but higher than UDP. | Very low. |
    | Applications | This protocol is primarily utilized in situations when a safe and trustworthy communication procedure is necessary, such as in email, on the web surfing, and in military services. | This protocol is used in situations where quick communication is necessary but where dependability is not a concern, such as VoIP, game streaming, video, and music streaming, etc. |

## 5. Application Layer

### Session Layer

- **Introduction**
    - The Session Layer is the **5th layer** in the OSI model.
    - The Session Layer facilitates **communication sessions** by **establishing** and **maintaining** connections between **end-user applications**, **handles data** from both Session Layer and Presentation Layer, and utilizes the Transport Layer for **session management**.
    - The Session Layer receives **streams of data**, marks them, and **resynchronizes** them to avoid initial message truncation and data loss.
    - To establish a session connection, the steps involve **mapping** addresses, **selecting** transport quality parameters(**packet loss, bit rate, transmission delay, jitter, throughput, availability**, etc.), **negotiating** session parameters, **transmitting** limited user data, and **monitoring** data transfer.
    - The ability to **send larger amounts of data files** is important and necessary.
- **Functions of Session Layer**
    - **Dialog control**: Enables communication in either half-duplex or full-duplex mode.
    - **Token management**: Prevents simultaneous access or conflicting critical operations.
    - **Synchronization**: Adds **checkpoints** for data streams and supports session **checkpointing** and **recovery**.
    - **Session management**: Opens, closes, and manages sessions between end-user application processes.
    - The services offered by Session Layer are generally implemented in application environments using **remote procedure calls (RPCs)**.
    - **Synchronizes information** from different sources.
    - **Connection control**: Manages single or multiple connections for each end-user application.
    - **Checkpoint procedures**: Establishes checkpoints for **adjournment**, **restart**, and **termination**.
    - **Fault tolerance**: Resumes communication sessions from specific checkpoints after failures.
    - **Data handling**: Receives data from the transport layer and passes it to the presentation layer.
- **Session Layer Protocols**
    - **AppleTalk Data Stream Protocol (ADSP)**: Enables self-configuring LAN connections with protocols like **AppleTalk Address Resolution Protocol (AARP)** and **Name Binding Protocol (NBP)**.
    - **Real-time Transport Control Protocol (RTCP)**: Provides out-of-band statistics and control information for multimedia sessions, transmitting feedback on quality of service (QoS).
    - **Point-to-Point Tunneling Protocol (PPTP)**: Establishes VPNs using a TCP control channel and **Generic Routing Encapsulation (GRE)** tunnel for secure remote access.
    - **Password Authentication Protocol (PAP)**: Used for user validation in PPP, widely supported for initial link establishment.
    - **Remote Procedure Call Protocol (RPCP)**: Facilitates procedure execution across different address spaces, enabling client-server interaction.
    - **Sockets Direct Protocol (SDP)**: Supports socket streams over **Remote Direct Memory Access (RDMA)** network fabrics, providing enhanced performance without application-level changes.

### Presentation Layer

- **Introduction**
    - The Presentation Layer also known as the **Translation layer** is the **6th layer** in the OSI model.
    - Data received from the Application Layer is **extracted and manipulated** in this layer.
    - It is also referred to as the **Syntax layer** as it ****ensures the proper **syntax** of the data it receives or transmits to other layers.
- **Functions of Presentation Layer**
    1. ***Translation:*** If the sender and receiver understand different code formats like **ASCII** and **EBCDIC**, the **presentation layer** translates the data to ensure effective understanding. This layer converts **ASCII codes** to **EBCDIC** or vice versa, enabling efficient utilization by the receiver.
    2. ***Encryption and Decryption:*** Data transmitted between the **sender** and **receiver** must be **secure** to prevent **hacking** and **data modification**. The **presentation layer** ensures data **encryption** and **decryption** for protection against **data leakage**. The **plaintext data** is encrypted into unreadable **ciphertext** and decrypted at the receiver's end. This prevents **hackers** from accessing or altering the data, ensuring its **integrity** and **security**.
    3. ***Compression and Decompression:*** If the **file size** is large, it becomes difficult to transmit the large file over the network. **Compression** reduces the file size for easier data transmission. Compressed data is reconstructed back to the original size at the receiver through **decompression**.
- **Sublayers of Presentation Layer**
    1. ***Common Application Service Element (CASE):*** This sublayer offers services to layer-7, i.e., the application layer, and requests services from layer-5, i.e., the session layer. It supports various application services, such as Reliable Transfer Service Element (RTSE), Remote Operation Service Element (ROSE), Association Control Service Element (ACSE), and Commitment Concurrency and Recovery (CCR).
    2. **Specific Application Service Element (SASE):** This sublayer offers application-specific protocols, such as Message Oriented Text Interchange Standard (MOTIS), Remote Database Access (RDA), File Transfer Access and Manager (FTAM), Common Management Information Protocol (CMIP), Virtual Terminal (VT), Distributed Transaction Processing (DTP), Job Transfer and Manipulation (JTM), and others.
- **Presentation Layer Protocols**
    - **Apple Filing Protocol (AFP)**: A proprietary network protocol designed for Mac-based platforms, providing file control services.
    - **Lightweight Presentation Protocol (LPP)**: Offers ISO presentation services over TCP/IP protocol stacks.
    - **NetWare Core Protocol (NCP)**: Facilitates access to file, print, directory, synchronization, messaging, and remote command execution services.
    - **Network Data Representation (NDR)**: Implementation of the presentation layer in the OSI model, defining data types and representations.
    - **External Data Representation (XDR)**: Standard for describing and encoding data, facilitating data transfer between diverse computer architectures.
    - **Secure Socket Layer (SSL):** This protocol provides security to the data that is being transferred between the **web browser** and the **server**. SSL **encrypts the link** between a web server and a browser, which ensures that all data passed between them remains private and free from attacks.

### Application Layer

- **Introduction**
    
    The **Application Layer** is the topmost layer in the OSI model. It enables user access to the network and interacts directly with applications, providing web services. It requests information from the **presentation layer**. It is the highest level of the open system, serving the application process.
    
- **Functions of Application Layer**
    - The **Application Layer** enables user access and data manipulation in a network, including **email forwarding, storage, and retrieval** and **remote file access**.
    - It facilitates user interaction with other software applications and provides **global information** and protocols for **meaningful data exchange**.
    - The Application Layer acts as an **abstraction layer**, defining **shared protocols and interfaces** for communication.
    - It presents data visually for better comprehension and collaborates with the **operating system** for data preservation.
    - The protocols in this layer depend on **desired information exchange** and support **host initialization** and **remote login**.
- **Features provided by Application Layer Protocols**
    - The **Application Layer protocol** establishes communication processes between parties.
    - These protocols specify the **message type** exchanged between source and destination hosts.
    - They define the **syntax** of forwarded or retrieved messages.
    - The protocols outline the **message sending process** and expected response.
    - They also govern **interaction** with the next layer.
- **Protocols in Application Layer**
    1. **TELNET**
        - **Telnet** stands for **TELetype NETwork** and is used for **terminal emulation**.
        - Telnet clients can access resources on Telnet servers, making it useful for **managing files on the internet** and performing **initial setup of devices** like switches.
        - The **telnet command** utilizes the Telnet protocol to communicate with remote devices or systems.
        - The **port number** associated with Telnet is **23**.
        
        ```bash
        telnet [\\RemoteServer]
        telnet 192.168.0.100
        ```
        
    2. **SSH (**Secure Shell)
        - It is a network protocol for secure remote access to devices.
        - Uses **Port number 22** by default.
        - Uses **TCP** for establishing connections.
        - Provides secure encrypted communication between the client and the server.
        - Supports various authentication methods such as password authentication, public-key authentication, and certificate-based authentication.
        - Allows remote command execution, file transfer, and tunneling of other protocols (e.g., X11).
        - Provides strong security measures to protect against unauthorized access and eavesdropping.
        - Can be used for secure remote administration of servers and secure file transfers.
        
        ```bash
        ssh username@hostname
        ssh john@example.com
        ssh john@192.168.0.100
        ```
        
    3. **FTP (**File Transfer Protocol**) / How file tranfer works?**
        - **FTP** is an application layer protocol that transfers files between local and remote file systems.
        - It uses two parallel TCP connections: the **control connection** (port 21) for sending control information, and the **data connection** (port 20) for sending the actual file.
        - FTP is preferred over other protocols like HTTP for file transfer due to its **clarity**, **focus**, and ability to handle **heterogeneity** in systems.
        - FTP supports different file formats, including **ASCII**, **EBCDIC**, and **image files**.
        - The FTP session starts with the client initiating a **control TCP connection**, and the server establishing a **data connection** for file transfer.
        - FTP operates on a **client-server model**, where the **FTP client** program runs on the user's computer to establish connections and transfer files.
        - FTP supports three types of data structures: **file structure**, **record structure**, and **page structure**.
        - FTP uses **TCP** as a transport layer protocol and operates through a well-known **port 21**.
        - Advantages of FTP include **speed**, **file sharing**, and **efficiency**, while disadvantages include file size limitations, lack of support for multiple receivers, and lack of encryption.
        - **Anonymous FTP** allows public access to files on certain sites without requiring a username or password.
    4. **TFTP (**Trivial File Transfer Protocol**)**
        - It is a **stripped-down** and **simplified version** of FTP. It is used for transferring files between network devices when you have a clear understanding of what you need and its location.
        - TFTP serves as a **technology** for file transfer and operates on **port number 69**.
    5. **NFS (**Network File System)
        - It enables remote hosts to **mount file systems** over a network and interact with them as if they were locally mounted.
        - NFS facilitates the consolidation of resources onto centralized servers in a network, providing system administrators with greater control and efficiency.
        - The **port number** associated with NFS is **2049**.
    6. SNMP (Simple Network Management Protocol)
        - It collects data by polling network devices from a management station, disclosing specific information.
        - It allows servers to **share information** about their current state and enables administrators to **modify predefined values**.
        - The **port numbers** for SNMP are **161 (TCP)** and **162 (UDP)**.
    7. **HTTP/HTTPS (**Hypertext Transfer Protocol / Hypertext Transfer Protocol Secure)
        - **HTTP** is used to access data from the World Wide Web.
        - **Hypertext** is a well-organized documentation system used to link pages in a text document.
        - **HTTP** is based on the client-server model.
        - **TCP** is used by **HTTP** for establishing connections.
        - **HTTP** is a stateless protocol, meaning the server doesn't maintain information about previous client requests.
        - **HTTP** uses **port number 80** and ************HTTPS************ uses ************************port number 443************************ for establishing connections.
        
        | HTTP | HTTPS |
        | --- | --- |
        | Hyper-text exchanged using HTTP goes as plain text i.e. anyone between the browser and server can read it relatively easily if one intercepts this exchange of data and due to which it is Insecure. | HTTPS is considered to be secure but at the cost of processing time because Web Server and Web Browser need to exchange encryption keys using Certificates before actual data can be transferred. |
        | HTTP Works at the Application Layer. | HTTPS works at Transport Layer. |
        | HTTP does not use encryption, which results in low security in comparison to HTTPS. | HTTPS uses Encryption which results in better security than HTTP. |
        | HTTP speed is faster than HTTPS. | HTTPS speed is slower than HTTP. |
        | HTTP does not use data hashtags to secure data. | HTTPS will have the data before sending it and returning it to its original state on the receiver side. |
        | HTTP is used to transfer text, video, and images via web pages. | HTTPS is used to transfer data securely via a network. |
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2061.png)
        
    8. **SMTP (**Simple Mail Transfer Protocol)
        - It is a part of the **TCP/IP protocol**. It uses a **"store and forward"** process to move email across networks.
        - SMTP works in conjunction with the **Mail Transfer Agent (MTA)** to ensure that your emails are sent to the correct computer and delivered to the intended email inbox.
        - The **port number** associated with SMTP is **25**.
    9. **POP (**Post Office Protocol)
        - It is used for **message retrieval** from mail servers.
        - Latest version: **POP3** (Post Office Protocol version 3).
        - Uses **Port number 110** and **TCP** for establishing connections.
        - Works in **dual mode**: Delete mode (messages are deleted from the mail server after downloading to the local system) and Keep mode (messages are not deleted from the mail server, allowing users to access them later).
    10. **IMAP** (Internet Message Access Protocol)
        - It is used for message retrieval and synchronization from mail servers.
        - Latest version: **IMAP4** (Internet Message Access Protocol version 4).
        - Uses **Port number 143** and **TCP** for establishing connections.
        - Works in **synchronization mode**, allowing users to access and manage emails directly on the mail server.
        - Supports **server-side folder management**, enabling users to create, delete, and organize folders on the mail server.
        - Provides **multi-device synchronization**, ensuring that changes made on one device are reflected on all other devices.
        - Allows for **offline access**, where users can access previously synchronized messages without an active internet connection.
    11. **MIME** (Multipurpose Internet Mail Extension)
        - It extends the capabilities of **SMTP** by allowing **non-ASCII data** transmission. Users can send/receive various files like **audio, video, programs**, etc. MIME collaborates with other protocols to enhance their capabilities.
    12. DNS
    13. DHCP

### DNS (**Domain Name System)**

- **DNS** is a collection of **distributed databases** implemented in a hierarchy of **name servers** that translate **domain names** to **IP addresses**, playing a crucial role in the functioning of the **Internet**.
- **Why DNS?**
    
    Hosts are identified by **IP addresses**, but remembering numbers is challenging for people. Additionally, IP addresses are not static, necessitating the use of **DNS** to map **domain names** to IP addresses for websites.
    
- **Why does DNS use UDP and not TCP?**
    
    DNS primarily uses **UDP** on **port 53** for serving requests due to its **faster speed**, **ability to handle small queries**, **scalability**, and **lack of connection management overhead**, even though UDP is considered unreliable, as reliability can be added at the application layer through **timeout** and **resending** mechanisms, where the application waits for a response and retransmits if needed.
    
- **Types of DOMAIN:**
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2062.png)
    
    1. **Generic domains:** .com(commercial), .edu(educational), .mil(military), .org(nonprofit organization), .net(similar to commercial) all these are generic domains.
    2. **Country domain:** .in (India) .us .uk
    3. **Inverse domain:** It is used to map an address to a name. When a server receives a request from a client, it checks if the client is authorized by sending a query to the **DNS server** for mapping the address to the name.
- **Components of DNS:**
    - **DNS record:** It contains the **domain name**, **IP address**, **validity**, **time to live**, and all the information associated with that domain name. These records are stored in a **tree-like structure**.
    - **Domain Namespace:** Set of possible names, **flat** or **hierarchical**. The naming system maintains a collection of **bindings** of names to **values** – given a name, a **resolution mechanism** returns the corresponding value. The tree can have only 128 levels: level 0 (root) to level 127.
    - **Name server: It** implements the **resolution mechanism** in the **DNS**, serving as the Internet's name service. It maintains a **DNS database** with various names and corresponding IP addresses. The database is distributed among multiple DNS servers, following the hierarchy of names and divided into **zones**.
- **Fully Qualified Domain Name (FQDN)**: A complete and unambiguous domain name in the DNS hierarchy, including all labels and subdomains leading to the root domain.
    - **www.example.com**
    - mail.google.com
    - ftp.microsoft.com
- **Partially Qualified Domain Name (PQDN)**: A domain name that is not fully specified with all necessary labels, often used in local network configurations or internal systems.
    - www (without specifying the domain or top-level domain)
    - mailserver (without specifying the domain or top-level domain)
    - dbserver.internal (without specifying the higher-level domains or top-level domain)
- **DNS Architecture**
    - A **domain** is a unique name for an area of control, while a **zone** is a collection of **nodes** (subdomains) under a main domain, each with its own **zone file database** on the server; if a domain lacks subdomains, the terms domain and zone are used interchangeably.
        
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2063.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2064.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2065.png)
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2066.png)
        
    - **Hierarchy & Types of Name Servers:**
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2067.png)
        
        1. **Root Server**: The top-level server in the DNS hierarchy that consists of the entire DNS tree. It does not contain the information about domains but **delegates the authority** to other servers. **13 global root servers** form the top-level of the DNS hierarchy.
        2. **Primary Server**: An Authoritative server that stores a file about its zone, having the authority to **create, maintain, and update** the zone file. A primary server loads all information from the **disk file**.
        3. **Secondary Server**: An Authoritative server that transfers complete information about a zone from another server, which may be a primary or secondary server. The secondary server does not have authority to create or update a zone file. It loads all information from the **primary server**.
    - **Advantages of Distributed DNS Architecture** include **load balancing** to handle the enormous global DNS traffic, faster DNS query replies through **proximity** to geographical locations, **redundancy** to prevent a single point of failure, and simplified **maintenance** and **updates** for DNS servers.
- ****Address Resolution in DNS****
    - The **hierarchy of name servers** includes **root name servers** contacted by name servers that cannot resolve the name, **top-level domain (TLD) servers** responsible for com, org, edu, etc., and **authoritative name servers** maintained by organizations or service providers, which provide authoritative hostnames to IP mapping.
    - **RESOLVER:**
        - DNS is designed as a **client-server** application. A host that needs to map an address to a name or a name to an address calls a DNS client called a **resolver**. The resolver accesses the closest DNS server with a mapping request.
        - If the server has the information, it **satisfies** the resolver; otherwise, it either **refers** the resolver to other servers or **asks** other servers to provide the information.
        - After the resolver receives the mapping, it interprets the response to see if it is a **real resolution** or an **error**, and finally delivers the result to the process that requested it.
    - **Mapping Names to Addresses:**
        
        When the resolver receives a domain name, the server checks **generic domains** or **country domains** for mapping. For a domain in the **generic section** like "chal.atc: fhda.edu", the resolver queries the **local DNS server**; if unresolved, it **refers** or **asks** other servers. Likewise, for a **country domain** like "ch.fhda.cu.ca.us", the resolver follows the same process.
        
    - **Mapping Addresses to Names:**
        
        A client can send an IP address to a server for mapping to a domain name through a **PTR query**. DNS uses the **inverse domain**, where the IP address is **reversed** and appended with "**in-addr.arpa**" labels. For instance, if the resolver receives the IP address **132.34.45.121**, it sends the domain name "**121.45.34.132.in-addr.arpa**" to the local DNS for resolution.
        
    - **Types of Resolution:**
        1. **Recursive Resolution**
            
            The **client** requests the **Local Server** for a mapping or error message, generating a **DNS Query** to the resolver. The query is forwarded to the **local DNS Server**, and if the **IP Address** is known, a response is sent. Otherwise, it is sent to the **root name server** and then to the respective **Top-Level Domain** server. If the mapping is found, it is returned; otherwise, the **IP Address** of the destination's local DNS Server is provided, and the process is reversed back to the host's Local DNS Server, and finally to the host.
            
            ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2068.png)
            
        2. **Iterative Resolution**
            
            In **iterative resolution**, servers pass the **IP Address** of the next server, allowing the client to receive the best match or referral. A **DNS Query** is generated and forwarded through the **local DNS Server**, **root name server**, and **Top-Level Domain** server to obtain the destination host's **IP Address**. The response is then delivered from the host's **local DNS server** to the **resolver** and finally to the host.
            
            ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2069.png)
            
        
        | Property | Iterative Resolution | Recursive Resolution |
        | --- | --- | --- |
        | Server Response | Returns best match or referral | Returns requested mapping or error message |
        | Query Propagation | Each server sends IP address of next server | Only local server sends query to next server |
        | Server Load | Higher load on servers, multiple servers queried | Lower load on servers, only local server queried |
        | Response Time | Longer response time, multiple servers queried | Shorter response time, fewer servers queried |
        | Cache Usage | Lower cache hit rate, referrals returned | Higher cache hit rate, mappings returned directly |
        | Security | Lower security, multiple servers potentially modify response | Higher security, only local server trusted for valid response |
    - **Caching Mechanism**
        - In both **iterative** and **recursive resolution**, servers employ a **caching mechanism** to store mapping information in memory for faster future lookups. When a server receives a mapping response, it **caches** the information to reduce search time for subsequent requests, marking the cached response as **Unauthoritative**.
        - Efficient caching with **TTL** ensures **up-to-date responses** by periodically **removing mappings** with expired TTL, preventing servers from providing clients with outdated mappings and **improving resolution speed** while maintaining **cache integrity** for accurate DNS mappings.
- **DNS Delegation:** It occurs when the **authoritative name server** for a **domain** responds to a request for **subdomain records** by providing **Name Server records** that point to other name servers, effectively passing on **authority** for the subdomain to another set of name servers.
- **Types of** **DNS Attacks**
    1. **Denial of Service (DoS)**, where the attacker renders a computer inaccessible by overwhelming it or making resources unavailable;
    2. **Distributed Denial of Service (DDoS)**, where the attacker controls numerous computers to flood the victim's system with traffic;
    3. **DNS spoofing**, It means getting a wrong entry or IP address of the requested site from the DNS server. Attackers find out the flaws in the DNS system and take control and will redirect to a malicious website.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2070.png)
        
        To prevent DNS spoofing, **DNS Security Extensions (DNSSEC)** add an additional layer of security by digitally 'signing' data, implementing **source authentication** using techniques like **IPsec or TLS**, utilizing **response rate limiting** to reduce DNS amplification attacks, implementing **DNS filtering** to block traffic to known malicious domains or IP addresses, employing **DNS monitoring and analysis** to detect anomalies, and regularly updating **DNS software and patches** to prevent known vulnerabilities from being exploited.
        
    4. **Fast flux**, a technique that constantly changes location-based data to conceal the attacker's origin; 
    5. **Reflected attacks**, where spoofed IP addresses and the victim's source address are used to redirect queries to the victim; and
    6.  **Reflective amplification DoS**, which triggers an amplification effect by overwhelming the victim's system infrastructure with larger answers compared to the original queries.
    
    Measures against DNS attacks include using **digital signatures and certificates** to authenticate sessions and protect private data, regularly updating and using the latest software versions like **BIND**, installing patches and fixing bugs, **replicating data** in multiple servers to prevent data loss, blocking **redundant queries** to prevent spoofing, and **limiting the number of possible queries**.
    

### DHCP (**Dynamic Host Configuration Protocol)**

- **DHCP** is an **application layer protocol** that enables the **allocation of IP addresses** to client devices in an enterprise network, following a **client-server model** that is used to provide:
    
    ```markup
    Subnet Mask (Option 1 - e.g., 255.255.255.0)
    Router Address (Option 3 - e.g., 192.168.1.1)
    DNS Address (Option 6 - e.g., 8.8.8.8)
    Vendor Class Identifier (Option 43 - e.g., 
    'unifi' = 192.168.1.9 ##where unifi = controller)
    ```
    
- **Why Use DHCP?**
    
    **DHCP** automates and centralizes the process of **managing IP addresses** by providing **lease offers** to **DHCP-enabled clients**, allowing for the maintenance of **unique IP addresses** for hosts.
    
- **Components of DHCP**
    1. **DHCP Server**: A server that holds IP addresses and configuration information.
    2. **DHCP Client**: A device that receives configuration information from the server.
    3. **DHCP Relay**: Works as a communication channel between DHCP Client and Server.
    4. **IP Address Pool**: A container of IP addresses possessed by the DHCP Server.
    5. **Subnets**: Smaller portions of the IP network used for network partitioning.
    6. **Lease**: The duration of validity for the information received from the server.
    7. **DNS Servers**: DHCP servers can provide DNS server information to clients, allowing them to resolve domain names to IP addresses..
    8. **Default Gateway**: Information about the device to send packets to when outside the local network.
    9. **Options**: Additional configuration options provided by DHCP servers, such as the subnet mask, domain name, and time server information.
    10. **Renewal**: The process of requesting to extend the lease before it expires.
    11. **Failover**: Configuration where two servers provide redundancy for uninterrupted service.
    12. **Dynamic Updates**: DHCP servers can update DNS records with client IP addresses.
    13. **Audit Logging**: DHCP servers keep logs of transactions for monitoring and management.
- **Working of DHCP**
    
    Automatic IP address assignment process undergoes four message exchange. These messages are abbreviated as DORA.
    
    | Message | Detail |
    | --- | --- |
    | Discover | This is message sent by DHCP client to discover a DHCP server. |
    | Offer | Sent by DHCP server to lease unique IP address and other parameters needed to client. |
    | Request | Sent by DHCP client asking server to lease parameters listed in Offer message. |
    | Acknowledgement | Sent by DHCP server to assign IP address, mask, default router & DNS server address to client. |
    - DHCP IP address leasing uses layer 3 protocol, the **Internet Protocol (IP)**, and operates using **IP packets**.
    - Initially, hosts without an IP address use the reserved IP address **0.0.0.0** as the sender's address.
    - The local broadcast IP address **255.255.255.255** is used for broadcasting packets over the local data link.
    - To handle the situation when the DHCP server is not available on the local LAN and is located outside, the **"IP helper address"** is configured in routers.
    - The IP helper address is the IP address of the DHCP server and is used as the destination address for packets containing **255.255.255.255**.
    - By updating packets with the IP helper address, **DORA messages** (Discover, Offer, Request, Acknowledge) can be exchanged with the DHCP server located outside the local LAN.
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2071.png)
    
    1. PC1 sends Discover message but doesn’t find DHCP server in local LAN.
    2. R1 now receive IP packet and change destination address to DHCP server address i.e., 14.0.10.1 and sender address to its own outgoing interface address i.e., Gi0/2 interface address. R1 does this because of configuration of IP helper address.
    3. IP packet forwarded by R1 is received by DHCP server and respond to this Discover message.
    4. Server now send Offer message with source address as its own IP address and destination address as Gi0/2 interface address of R1. Actually it reverse the address of IP packet received.
    5. R1 receive the Offer message and forward it to PC1.
    6. Request and Acknowledge message are also exchanged further.
- **The 8 DHCP Messages (How DHCP server dynamically assigns IP address to a host?)**
    1. **DHCP discover message:** The **first message** in the communication process between the **server** and **client** is a **broadcasted DHCP discovery message** (**342 or 576 bytes long**) sent by the **client** to **find DHCP server(s)**, with specific **source** and **destination MAC addresses** (**08002B2EAF2A** and **FFFFFFFFFFF**) and **IP addresses** (**0.0.0.0** and **255.255.255.255**).
    2. **DHCP offers a message:** The server responds with a **broadcasted DHCP OFFER message** (342 bytes) specifying an **unleased IP address** and **TCP configuration information**, including the **server ID**, with **source IP** 172.16.32.12, **destination IP** 255.255.255.255, **source MAC** 00AA00123456, and **destination MAC** FFFFFFFFFFFF, offering **IP** 192.16.32.51 with a **72-hour lease time**, using **client identifier** 08002B2EAF2A.
    3. **DHCP request message:** Upon receiving an offer message, the client broadcasts a **DHCP request message**, performing a **gratuitous ARP** to check for conflicting IP addresses, and if no reply is received, the client broadcasts the acceptance of the IP address to the server, including a **Client ID**, with source IP **0.0.0.0**, destination IP **255.255.255.255**, source MAC **08002B2EAF2A**, and destination MAC **FFFFFFFFFFF**, ensuring no other host is using the offered IP address before accepting it.
    4. **DHCP acknowledgment message:** In response to the **request message**, the server will **bind** the offered **IP address** with a **lease time** for the specified **client ID**, granting the client the provided IP address. The server will make an **exclusive entry** for the client host with the offered IP address and lease time, using **destination MAC** FFFFFFFFFFFF and **destination IP** 255.255.255.255, and **source IP** 172.16.32.12 and **source MAC** 00AA00123456 (server MAC address).
    5. **DHCP negative acknowledgment message:** Whenever a DHCP server receives a request for an **invalid IP address**, it sends a **DHCP Nak message** to the client, for example when the server has **no unused IP address** or the pool is **empty**.
    6. **DHCP decline:** If the DHCP client detects different or invalid **configuration parameters**, it sends a **DHCP decline** message to the server. If there is a reply to the **gratuitous ARP**, indicating that the **IP address** is already in use, the client sends a **DHCP decline** message to the server.
    7. **DHCP release:** A DHCP client sends a DHCP **release packet** to the server to release the IP address and cancel any remaining lease time.
    8. **DHCP inform:** If a client manually obtains an IP address, it uses DHCP information for other **local configuration parameters**, such as the **domain name**. The server responds with a unicast **DHCP ack** message, providing a suitable local configuration for the client without assigning a new IP address.
    
    <aside>
    💡 All the messages can be unicast also by the **DHCP relay agent** if the server is present in a **different network**.
    
    </aside>
    
    ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2072.png)
    
- **Advantages & Disadvantages of DHCP**
    - *Advantages* of using **DHCP** include **centralized management** of IP addresses, **automated TCP/IP configuration**, ease of **adding new clients**, **reuse of IP addresses**, efficient handling of **IP address changes**, simple reconfiguration of the IP address space, and easy handling of **new users**.
    - *Disadvantage* of using **DHCP** includes the potential for **IP conflicts**, security risks due to acceptance of connections from **unauthorized servers**, inability to access the network without a **DHCP server**, and the lack of automatic **machine name updates** when a new IP address is assigned.
- **RPC (Remote Procedure Call)**
    - **RPC** (Remote Procedure Call) is an inter-process communication technique used for building distributed, client-server applications.
    - It allows clients to communicate with servers using conventional **procedure calls**.
    - RPC works similar to a **function call**, where arguments are passed to a remote procedure and the caller waits for a response.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2073.png)
        
    - Features/Characteristics of RPC include a **well-defined interface**, execution within the **server process**, communication between processes on the same or different **machines**, and passing parameters by **values**.
    - Advantages of RPC include facilitating communication between clients and servers, supporting **process and thread-oriented models**, hiding internal message passing mechanisms from the user, enabling usage in **distributed environments**, and minimizing re-writing efforts.
    - Drawbacks of RPC include potentially higher calling time compared to local procedures, vulnerability to failures due to involving different machines and processes, lack of standardization in implementation, limited flexibility for **hardware architecture**, and increased process cost.
    - Types of RPC include **Callback RPC** (enabling Peer-to-Peer paradigm), **Broadcast RPC** (processing requests by multiple servers), and **Batch-mode RPC** (queuing and transmitting requests in batches).
    - The RPC architecture includes a **client** (making requests), a **server** (responding to requests), **client stub** (module for making RPC calls), **runtime library** (managing RPC), and **server stub** (module containing server functions).

# How a packet travels?

1. Sender: The packet originates from the sender, which can be any device connected to a network, such as a computer or server.
2. Encapsulation: The sender encapsulates the data into packets. Each packet typically includes a header containing control information, such as source and destination addresses, and a payload that carries the actual data.
3. Sender to Switch: If the sender and receiver are connected to the same local area network (LAN), the packet is sent from the sender's device to the local switch. The switch operates at the Data Link layer (Layer 2) of the OSI model.
4. Switch Examination: The switch examines the destination MAC address in the packet's header to determine the appropriate port to which the packet should be forwarded.
5. Switch Forwarding: The switch forwards the packet to the specific port connected to the receiver's device, based on the destination MAC address. This allows for direct communication between the sender and receiver within the same LAN.
6. Switch to Router: If the sender and receiver are on different networks or subnets, the packet needs to be sent to a router. The switch delivers the packet to the router connected to the sender's LAN.
7. Router Examination: The router examines the destination IP address in the packet's header to determine the appropriate path to reach the receiver's network.
8. Routing Decision: The router uses routing tables, routing protocols, and other information to make a routing decision. It determines the next hop or router to which the packet should be forwarded.
9. Router to Router: The router forwards the packet to the next router along the determined path, typically using protocols like RIP or OSPF to exchange routing information between routers.
10. Router to Switch: Eventually, the packet reaches the router connected to the receiver's LAN. The router examines the destination IP address again to determine the appropriate outgoing port to reach the receiver's network.
11. Switch to Receiver: The router sends the packet to the switch connected to the receiver's LAN. The switch examines the destination MAC address in the packet's header and forwards it to the specific port connected to the receiver's device.
12. Receiver: The packet reaches the receiver's device, where it is processed and unpacked to retrieve the original data.

# M****iscellaneous****

- **What’s difference between The Internet and The Web ?**
    
    The **Internet** is a global network of networks, while the **Web** (World Wide Web) is a collection of information accessed via the Internet, with the Internet serving as **infrastructure** and the Web as **software**; the Web uses **HTTP protocol** on port **80** to communicate with data in **HTML**, **CSS**, and **JavaScript**, while the Internet allows for communication using various protocols and ports.
    
- **What is a Client? What is a Server? What is a Host? And What is a Peer?**
    - A **client** is a computer hardware device or software that accesses a service made available by a **server**, which is often (but not always) located on a separate **physical computer**.
    - A **server** is a dedicated **physical computer** that runs **services** to meet the needs of other computers, such as **file storage**, **databases**, **media sharing**, **printing**, or **serving websites**.
    - A **host** is a **computer** that provides **data** or **services** to other computers over a network, distinguishing it from devices like **modems**, **hubs**, and **switches**, as it requires an assigned **IP address**.
    - A **peer** is a **computer** on a network that can both **request** and **provide** **data** or **services** to other computers, operating as both a **client** and a **server** without a **hierarchical relationship**, allowing for **resource sharing** and **collaboration** with other peers.
    
- ****What is Network Bandwidth?****
    
    **Network bandwidth** is the maximum capacity of a communications link to transmit **data** over a network connection, determining the **data transfer rate** and the ability to support multiple devices. Bandwidth is measured in bits per second (bps) or its higher units. In **symmetrical** connections, upload and download capacities are equal, while in **asymmetrical** connections, upload capacity is typically smaller than download capacity.
    
- **What is Jitter?**
    
    **Jitter** is the **time delay** and **inconsistency** in sending **data packets** over a network connection, caused by **network congestion** or **route changes**, affecting the quality of **video** and **audio** transmission, particularly in tasks like **conference calls** and **VoIP communication**.
    
- **What is Local Host?**
    - When calling the IP address **127.0.0.1** (http://**localhost**), you communicate with the **local host** on your own computer, serving as a **server** for testing web applications, **blocking malicious websites** using the host's file, and **simulating connections** without network errors, facilitated by the **loopback interface**.
    - Localhost has a separate IP address within your network, such as **192.168.0.1**, assigned by the internet service provider (ISP).
    - Software like **XAMPP** is commonly used to set up a test server on localhost.
    
- ****What is Noise?****
    - **Noise** refers to any undesired signal or unwanted disturbances that interfere with a **transmission signal**, diminishing **transmission strength** and disturbing **communication efficiency**.
    - **Thermal noise** occurs in all transmission media and equipment due to temperature, while **intermodulation (IM) noise** is caused by spurious frequency energy components generated by nonlinear devices or media.
    - **Crosstalk** is a disturbance caused by electromagnetic interference in a circuit or cable pair, resulting in the confusion and overlapping of signals.
    - **Impulse noise** is sudden and brief signal disturbances that cause momentary interference in communication systems.
- **What is Distortion? What Is Attenuation?**
    - **Distortion** describes an interruption of transmitting signals that cause an unclear reception. Distortion is commonly found in **sound**, **video**, and **display signals** as well as **data cables** such as **network cables**.
    - **Attenuation** is the loss of **signal strength** in networking cables or connections, leading to signal **distortion** or degradation, and can be mitigated by using efficient cables or applying **amplifiers/repeaters**.
- **What is API Gateway?**
    - An **API gateway** provides a **centralized entry point** for **clients**, routing requests to different **API versions** and ensuring secure and scalable communication with **microservices**. It optimizes responses by aggregating results from multiple services.
    - ****Basic Capabilities of an API Gateway:****
        
        API gateways can be used for both monolithic and microservices-based apps. API gateways perform several functions, including:
        
        - Authenticating the requesters making API calls (AuthN)
        - Verifying that the requester is authorized to make the request (AuthZ)
        - Routing requests to appropriate backends
        - Applying rate limits to prevent overloading of your systems
        - Applying rate limits to mitigate DDoS attacks
        - Offloading SSL/TLS traffic to improve performance
        - Handling errors and exceptions
- **What is SSL/TLS?**
    
    **SSL (Secure Sockets Layer)** and its successor, **TLS (Transport Layer Security)**, are protocols for establishing authenticated and encrypted links between networked computers. Although the SSL protocol was deprecated with the release of TLS 1.0 in 1999, it is still common to refer to these related technologies as “SSL” or “SSL/TLS.” The most current version is **TLS 1.3**, defined in **[RFC 8446](https://tools.ietf.org/html/rfc8446)** (August 2018).
    
- ****What is a reverse proxy?****
    - A **proxy server** acts as a middleman between client machines and web servers, intercepting and forwarding requests on behalf of clients, often used to **bypass restrictions**, **control access to content**, or enhance online **anonymity**.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2074.png)
        
    - A **reverse proxy** intercepts client requests and forwards them to **origin servers**, providing benefits such as **load balancing**, protection from **attacks**, **global server load balancing (GSLB)**, **caching**, and **SSL encryption**.
        
        ![Untitled](#%20Computer%20Networks%206673ce922d3b4685abdb77ad0a1fef94/Untitled%2075.png)
        
- ****What Is Load Balancing?****
    
    Load balancing efficiently distributes network traffic across multiple **servers**, ensuring high **availability**, scalability, and reliability, while providing benefits such as reduced **downtime**, **redundancy**, **flexibility**, and improved **efficiency**.
    
- **What VIP in computer networks?**
    
    A **VIP (Virtual IP)** is an **IP address** that is not assigned to a specific physical device or interface, but can be shared by multiple devices or interfaces. A VIP can be used to provide **high availability**, **load balancing**, or **failover** for network services or applications. For example, a web server cluster can use a VIP as the common address for clients to access, while the actual requests are distributed among different servers in the cluster. If one server fails, another server can take over the VIP and continue to serve the clients.
    
- **Caching & How does a website is cached**
    
    **Caching** is the process of storing copies of files or data in a temporary storage location, called a **cache**, so that they can be accessed more quickly. A website is cached by **browsers**, **DNS servers**, or **CDNs**, which save a copy of the website's content on their local or nearby storage. This way, when a user requests the website, the content can be delivered faster from the cache instead of from the original server.
    
- **REST API vs HTTP API**
    
    
    | REST API | HTTP API |
    | --- | --- |
    | An architectural style for distributed hypermedia systems, stand for Representational State Transfer | A communication protocol for transferring data over the internet |
    | Not a standard or a specification, but a set of principles and constraints | A standard with well-defined rules and methods |
    | Can use any protocol that supports a uniform interface, such as HTTP | Uses only HTTP as the protocol |
    | Requires stateless operations (without storing client state) and unique identification of resources | Allows stateful operations (can store client state using cookies and sessions) |
    | Supports multiple data formats, such as XML, JSON, and HTML | Supports only one data format, which is usually JSON or XML |
    | Uses HTTP verbs, such as GET, POST, PUT, DELETE, etc., to perform operations on resources | Uses only GET and POST methods to perform operations on resources |
    | Offers greater scalability due to statelessness and resource identification | May have scalability challenges due to session-based state management |
    | E-commerce platform's API - GET /products for product info, POST /orders for placing orders. | Email service's API - POST /send-email for sending customized emails with parameters. |
- **Performance vs Scalability**
    
    
    | Performance | Scalability |
    | --- | --- |
    | Defined by measures of response, throughput, availability, or requests over time | Defined by the ability to overcome performance limits by adding resources |
    | Affected by system load, resource consumption, and application state | Affected by application topology, synchronization, and consistency |
    | Improved by optimizing the efficiency of request processing and resource utilization | Improved by scaling up or scaling out the application nodes |
- **Latency vs Throughput**
    
    
    | Latency | Throughput |
    | --- | --- |
    | The time taken for a packet to be transferred across a network | The quantity of data being sent and received within a unit of time |
    | Measured in milliseconds (ms) | Measured in bits per second (bps) |
    | Affected by the distance, number of routers, and network design | Affected by the bandwidth, hardware performance, and network congestion |
    | Indicates how fast the packets reach their destination | Indicates how many packets are processed successfully within a time period |
    | High latency causes slow and choppy services | Low throughput causes poor service quality and packet loss |
- **2G vs 3G vs 4G vs 5G**
    
    
    | Generation | Key Features |
    | --- | --- |
    | 1G | Analog technology with poor battery life and voice quality. Maximum speed: 2.4 Kbps. |
    | 2G | Digital networks with CDMA and GSM. Introduced SMS and internal roaming. Maximum speed: 50 Kbps (GPRS) or 1 Mbps (EDGE). |
    | 3G | UMTS core network architecture. Introduced web browsing, email, and multimedia services. Speed requirement: at least 200 Kbps. Maximum speed: 2 Mbps stationary, 384 Kbps mobile (true 3G). |
    | 4G | Significant technological leap with high-speed connectivity. Introduced IP telephony, mobile web access, and HD mobile TV. Speeds up to 100 Mbps in motion and 1 Gbps stationary. |
    | 5G | Faster speeds (up to 20 Gbps), lower latency, increased capacity, and support for massive IoT and AR applications. Offers network slicing and mMTC. In development stage with potential for transformative applications. |
- **How a VPN works?**
    
    A VPN creates a **secure tunnel** between your device and the internet. It connects to a **VPN server** that encrypts your data, hiding your IP address and protecting your online activity from ISPs and third parties.
    
- **How Bluetooth Works?**
    - **Bluetooth** uses **radio waves** for device communication.
    - Devices form **ad-hoc networks** (temporary network formed by devices without the need for a centralized infrastructure) called piconets, with one device as the **master** and up to seven others as **slaves**.
    - The **master** controls timing and frequency hopping and can switch roles with **slaves**.
    - Multiple piconets can be linked to form a **scatternet**.
    - Bluetooth operates in the **2.4 GHz ISM band** and uses spread spectrum techniques for interference avoidance and increased security.
    - Bluetooth supports different **data rates** and **ranges** based on device class and version.
- **How Hotspot Works?**
    - A **hotspot** provides **wireless internet access** to devices within its range.
    - A hotspot can be a **device** (e.g., smartphone, router, dongle) that shares its **cellular data connection** with other devices.
    - A hotspot can also be a **location** (e.g., coffee shop, hotel, park) that offers **public WiFi access** to customers or visitors.
    - Using a hotspot allows users to connect to the internet without using their own **data plan** or wired connection.
    - However, a hotspot may have limitations on **speed**, **bandwidth**, **security**, and **availability**.
- **How ATM Works?**
    
    ***Asynchronous Transfer Mode (ATM)*** is a technology that allows *call relay* and *multiple service types* such as data, video, or voice to be transmitted in *small fixed-size packets* called cells. ATM uses *virtual circuits* and *cell switching* to create end-to-end connections and handle different traffic types with *quality of service*. ATM has four main layers:
    
    - The *adaption layer* isolates higher-layer protocols from ATM details and converts user data into cells.
    - The *physical layer* manages the transmission and reception of bits in the physical medium and packages cells into frames.
    - The *layer* handles the transmission, switching, congestion control, and header processing of cells and shares the virtual circuits over the physical link.
    - The *WAN layer* enables ATM service over long distances, routers, and broadband networks.
    
    ATM can be used for various purposes, such as *WAN*, *multimedia VPN*, *frame relay backbone*, *residential broadband*, and *carrier infrastructure*.
    

# ****Networking Commands****

1. **Ping**
    - Ping is a network utility used to test the **connectivity** and **reachability** of a host by sending **echo packets** and receiving **replies**, providing insights into potential **networking issues**.
    - For example, if there is an issue with the Internet connection in an office, the **ping utility** is used to determine if the problem exists in the **office** or the **Internet provider's network**.
    
    | Options | Description |
    | --- | --- |
    | target | This is the destination IP address or a hostname user want to ping. |
    | -a | This option resolves the hostname of an IP address target. |
    | -t | This ping command option will ping the target until you stop it by pressing Ctrl-C. |
    | -n count | This option is used to set the number of ICMP Echo Requests to send, from 1 to 4294967295. If -n is not specified, the ping command will return 4 by default. |
    | -l  size | This option is used to set the size, in bytes, of the echo-request packet from 32 to 65,527. If the -l option is not specified, the ping command will send a 32-byte echo request. |
    | -s count | This option is used to report the time in the Internet Timestamp format that each echo request is received and an echo reply is sent. The maximum count value is 4, i.e. only the first four hops can be time stamped. |
    | -r count | This command uses the ping command option to specify the number of hops between the source computer and the target computer. The maximum count value is 9; the Tracert command can also be used if the user wants to view all the hops between two devices. |
    | -i TTL | This ping command option sets the Time to Live (TTL) value; the maximum value is 255. |
    | -f | Use this ping command option to prevent ICMP Echo Requests from being fragmented by routers between the source and the target. The -f option is often used to troubleshoot Path Maximum Transmission Unit (PMTU) issues. |
    | -w timeout | A timeout value must be specified while executing this ping command. It adjusts the amount of time in milliseconds. If the -w option is not specified, then the default timeout value of 4000 is set, which is 4 seconds. |
    | -p | To ping a Hyper-V Network Virtualization provider address. |
    | -S srcaddr | This option is used to specify the source address. |
2. ****NetStat****
    - **Netstat** is a common **TCP/IP** networking command-line method present in most **Windows**, **Linux**, **UNIX**, and other operating systems. The netstat provides the **statistics** and **information** about the **current TCP/IP** connections and network protocols.
    
    | Option | Description |
    | --- | --- |
    | -a | Displays all connections and ports |
    | -b | Shows the executable involved in each connection or listening port |
    | -e | Combines with -s to display Ethernet statistics |
    | -n | Displays the address and port number in numerical form |
    | -o | Displays the ID of each connection for the ownership process |
    | -r | Displays the routing table |
    | -v | When used with -b, shows the link or listening port sequence for every executable. |
3. ****Ip Config****
    - The command **IP config** displays basic details about the device's **IP address configuration**, including the **IP address**, **subnet mask**, and **default gateway**. Typing **IP config** in the Windows prompt will present the information for the current device. To view the full information, use the command prompt and type **config-all**. Additionally, there are options available to help resolve **DNS** and **DHCP** issues.
4. ****Hostname****
    - To communicate with each other, computers require a unique address, known as a **hostname**, which can be alphabetic or alphanumeric and may contain specific symbols. A hostname typically consists of a **top-level domain (TLD)** and can be between one and 63 characters when used in the **Domain Name System (DNS)** or on the **Internet**.
    
    | Command | Description |
    | --- | --- |
    | hostname | Provides the name of your computer. The result consists of the computer name and the domain name. |
    | hostname -s | Retrieves only the computer name. The output will be "localhost". |
    | hostname -d | Determines the domain system running on the computer. |
    | hostname -i | Retrieves the IP address for the hostname. |
    | hostname -a | Displays all the aliases for the computer. |
5. ****Tracert****
    - The **tracert** command is a **Command Prompt** command used to trace the network packet's path and the number of hops required for it to reach the target. It provides detailed information about the packet's route from the source to the specified destination. The tracert command is available in all **Windows** operating systems.
    
    ```bash
    tracert [-d] [-h MaxHops] [-w TimeOut]  target
    ```
    
    Options for tracert Command are as follows-
    
    - **target:** This is the destination, either an IP address or hostname.
    - –**d:** This option prevents Tracert from resolving IP addresses to hostnames to get faster results.
    - **h MaxHops:** This Tracert option specifies the maximum number of hops in the search for the target. If the MaxHops option is not specified the target has not been found by 30 hops, then the tracert command will stop looking.
    - **w timeout:** A timeout value must be specified while executing this ping command. It adjusts the amount of time in milliseconds.
6. ****Nslookup****
    - The **Nslookup** command is a network utility command used to obtain information about internet servers, providing name server information for the **DNS (Domain Name System)**, including the default DNS server's name and IP address.
    
    ```bash
    Nslookup
    or
    Nslookup [domain_name]
    ```
    
7. ****Route****
    - The **Route** command provides IP networks' routing tables, which direct packets between subnets. Typing **route print** retrieves the routing table, and commands like **Route Add**, **Route Delete**, and **Route Change** allow modifying the table as needed.
8. ****ARP****
    - **ARP** (Address Resolution Protocol) resolves IP addresses to **MAC addresses** for network communication. The **arp -a** command retrieves information about remote host **IP addresses** and provides details like **Address**, **Flags**, **Mask**, **Interface**, **Hardware Type**, **Hardware Address**, etc.
9. ****Path Ping****
    
    The **pathping** command combines the best aspects of the **Ping** and **Tracert** commands. It gathers statistics for 300 seconds and provides detailed reports on **latency** and **packet loss** at intermediate hops between the source and target, offering more comprehensive information than Ping or Tracert commands.
    
    ```bash
    path ping [-n] [-h] [-g <Hostlist>] [-p <Period>] [-q <NumQueries> [-w <timeout>] [-i <IPaddress>] [-4 <IPv4>] [-6 <IPv6>][<TargetName>]
    ```
    
    - **N:** Prevents path ping functioning from attempting to resolve routers’ IP addresses to their names.
    - **h MaxHops:** This tracert option specifies the maximum number of hops in the search for the target. If the MaxHops option is not specified the target has not been found by 30 hops then the tracert command will stop looking.
    - **w timeout:** A timeout value must be specified while executing this ping command. It adjusts the amount of time in milliseconds.
    - **ip <IPaddress>:** Indicates the source address.
    - **target:** This is the destination IP address or a hostname user want to ping.
