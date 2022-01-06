## Network Fundamentals
**Socket** -> The combination of IP and Port together called Socket.

**nslookup www.goolge.com**   -> To check the IP adress of the dns server.

**netstat -a**   -> To check the used port numbers.

**ipconfig**  -> To get the IP adress   -> Unique adress to identify a host.

**ipconfig/all**  -> To get the mac adress  -> MAC Address is the unique identifier of each host and is associated with its NIC (Network Interface Card). A MAC address is assigned to the NIC at the time of manufacturing. 

**IP adress** -> 32 bits (ipv4) , 128 bits (ipv6)  -> means we can have 2^32 ip adresses.

**Port**  -> 16 bits -> 2^16  ports available.

**Mac adresses** -> 12-nibble/ 6 bytes/ 48 bits.

**ARP** -> Adress Resolution Protocol -> It is used to convert an IP address to its corresponding physical address(i.e., MAC Address). ARP is used by the Data Link Layer to identify the MAC address of the Receiver’s machine. 

* Computer Network means an interconnection of autonomous (standalone) computers for information exchange. The connecting media could be a copper wire, optical fiber, microwave, or satellite. 
* **Network Criteria:**
  *  **Performance** -  It is measured in terms of transit time and response time.
  *  **Reliability** - It is measured in terms of Frequency of failure, Recovery from failures, Robustness during catastrophe.
  *   **Security** – It means protecting data from unauthorized access. 

## Types of Network Topology
* The arrangement of a network that comprises nodes and connecting lines via sender and receiver is referred to as network topology.
* **Mesh Topology :** - In a mesh topology, every device is connected to another device via a particular channel. 
 ![image](https://user-images.githubusercontent.com/60296821/148342410-e3379b59-5d15-4aef-935f-a4cb0dd5c209.png)
 
* **Star Topology :** - In star topology, all the devices are connected to a single hub through a cable.
 ![image](https://user-images.githubusercontent.com/60296821/148342911-920b180a-a435-4efb-aaaf-2be963e809f9.png)
 
* **Bus Topology :** - Bus topology is a network type in which every computer and network device is connected to a single cable.
 ![image](https://user-images.githubusercontent.com/60296821/148343283-c1958856-ed54-4db1-a435-b0c2780ada45.png)
 
* **Ring Topology** - In this topology, it forms a ring connecting devices with its exactly two neighboring devices.
 ![image](https://user-images.githubusercontent.com/60296821/148343369-d8e0e3ed-6eeb-4916-b162-35b7db859d94.png)
 
* **Tree Topology** - This topology is the variation of Star topology. This topology has a hierarchical flow of data. 
 ![image](https://user-images.githubusercontent.com/60296821/148343612-7b0e5012-dd4f-40b7-b294-aeb58304b4a6.png)

## Types of Area Networks
* The network allows computers to connect and communicate with different computers via any medium. **LAN, MAN, and WAN** are the three major types of networks designed to operate over the area they cover. There are some similarities and dissimilarities between them. One of the major differences is the geographical area they cover, i.e. **LAN covers the smallest area; MAN covers an area larger than LAN and WAN comprises the largest of all**. 
* There are other types of Computer Networks also, like : 
  * PAN (Personal Area Network)
  * SAN (Storage Area Network)
  * EPN (Enterprise Private Network)
  * VPN (Virtual Private Network)

### Mobile Adhoc Network (MANET)
* MANET stands for Mobile Adhoc Network also called a wireless Adhoc network or Adhoc wireless network that usually has a routable networking environment on top of a Link Layer ad hoc network.. They consist of a set of mobile nodes connected wirelessly in a self-configured, self-healing network without having a fixed infrastructure. MANET nodes are free to move randomly as the network topology changes frequently. Each node behaves as a router as they forward traffic to other specified nodes in the network. 
* ![image](https://user-images.githubusercontent.com/60296821/148353519-e50530fc-6030-4c2a-bccf-d82107b0a7e3.png)
**Types**:
**1.Vehicular Ad hoc Network (VANETs)** – Enable effective communication with another vehicle or with the roadside equipments. Intelligent vehicular ad hoc networks(InVANETs) deals with another vehicle or with roadside equipments. 

**2.Smart Phone Ad hoc Network (SPANC)** –  To create peer-to-peer networks without relying on cellular carrier networks, wireless access points, or traditional network infrastructure. Here peers can join or leave the network without destroying it. 
 
**3.Internet based Mobile Ad hoc Network (iMANETs)** – It supports internet protocols such as TCP/UDP and IP. To link mobile nodes and establish routes distributed and automatically. 
 
**4.Hub-Spoke MANET:** - Multiple sub MANET’s may be connected in hub-spoke VPN to create a geographically distributed MANET. Normal Ad-hoc routing algorithm does not apply directly. 
 
**5.Military or Tactical MANETs** – This is used by the military units. Emphasis on data rate, real-time demand, fast re-routing during mobility, security, radio range, etc. 
 
**6.Flying Ad hoc Network (FANETs)** – This is composed of unmanned aerial vehicles (commonly known as drones). Provides links to remote areas and mobility. 

### DSL
Digital Subscriber Line (DSL, originally, digital subscriber loop) is a communication medium, which is used to transfer internet through copper wire telecommunication line. Along with cable internet, DSL is one of the most popular ways ISPs provide broadband internet access. 
* If we ask that how we gonna achieve such a thing i.e., both telephone and internet facility, then the answer is by using ****splitters or DSL** filters**(shown in the below diagram). Basically, the use splitter is to splits the frequency and make sure that they can’t get interrupted.
![image](https://user-images.githubusercontent.com/60296821/148416445-3b6ea1ed-9a36-472b-a90f-b5b6e2ace358.png)

