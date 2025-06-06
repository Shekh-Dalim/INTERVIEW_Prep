🟢1. Define network
```
    Network refers to interconnection computing device that can exchange 
    data and share resources with each other.
    ```

🟢2. What do you mean by network topology, and explain types of them
```
    Network topology refers to the physical and logical arrangement of nodes (like computers, switches, routers)
    and connections (cables, wireless links) in a network.
    
    Bus Topology – All devices share a single communication line (one backbone).
    Star Topology – All nodes connect to a central device (like a switch).
    Ring Topology – Devices form a circular loop, data travels in one direction.
    Mesh Topology – Every node connects to every other node directly.
    Tree Topology – Hierarchical structure combining star and bus.
    Hybrid Topology – Mix of two or more topologies.
    ```
    
🟢3. Define bandwidth, node and link
```
     
    Bandwidth:-  
    Bandwidth is the maximum data transfer rate of a network.
    It shows how much data can be sent in a given time 

    Node:-
    A node is any device connected to a network.
    Examples: computers, switches, routers, printers, etc.

    Link:-
    A link is the physical or logical connection between two nodes.
    It can be a cable, fiber, or wireless signal.
    ```
     
🟢4. Explain TCP model
```
    It is a 4-layer model used to describe how data travels across a network like the internet.

    video(3,64,65) copy (4,66,67)
    ```

🟢5. Layers of OSI model
```
      copy(5)
      ```

🟢6. Significance of Data Link Layer
```
    video(21) copy(22)
    ```

🟢7. Define gateway, difference between gateway and router
```

    Gateway:- 
    A gateway is a device that connects two different networks that use different protocols.
    It translates data so both networks can understand each other.

    Router:-
    A router is a network device that forwards data packets between different networks based on
    their IP addresses.

    video(14) copy(15)

    Feature	                Router	                                            Gateway

    Function	     Connects similar networks	                         Connects different networks
    Main Job	     Routes data between devices in the same protocol	 Translates data between different protocols
    Example	         Connects home network to the internet	             Connects a private network to an external system
    Works at Layer	 Network Layer (Layer 3)	                         All layers (mostly Application & Network Layer)
    ```



🟢8. What does ping command do?
```
    The ping command is used to check if a device is reachable over a network.
    It sends test packets to the target IP address and shows if a response is received.
    ```

🟢9. What is DNS, DNS forwarder, NIC?
```

    DNS:- 
    DNS stand for Domain Name system. that translates human-friendly domain names (like google.com)
    into IP addresses (like 172.217.3.110) that computers use to identify each other.
  
    DNS forwarder:-
    A DNS forwarder is a server that receives DNS queries from local devices and forwards them to 
    external DNS servers to resolve domain names.

    NIC:-
    A NIC is a hardware component inside a computer or device that connects it to 
    a network (wired or wireless).
    ```

🟢10. What is MAC address?
```
      A MAC (Media Access Control) address is a unique hardware identifier assigned 
      to a network interface card (NIC).
      ```
     
🟢11. What is IP address, private IP address, public IP address, APIPA?
```

    IP Address
        An IP address is a unique number assigned to each device on a network to identify it 
        and allow communication.

    Private IP address:- 
    A private IP address is used inside a local network and is not routable on the internet.
    Examples: 192.168.x.x, 10.x.x.x, 172.16.x.x to 172.31.x.x    

    Public IP Address:- 
    A public IP address is assigned by an ISP and is used to identify your device or network 
    on the internet.

    APIPA (Automatic Private IP Addressing):- 
    When a device can’t get an IP from a DHCP server, it assigns itself an IP automatically 
    in the range 169.254.x.x to communicate locally.
    ```

🟢12. Difference between IPv4 and IPv6
```
       Ans in note book
       ```

🟢13. What is subnet?
```
    Subnet
        A subnet (short for subnetworks) is a smaller division of a larger network that groups 
        devices together to improve organization and performance.
        ```

🟢14. Firewalls
```
    A firewall is a security system (hardware or software) that monitors 
    and controls incoming and outgoing network traffic based on set rules.

    It acts like a security guard that blocks unwanted traffic and allows safe data. 
    ```
  
🟢15. Different type of delays
```

    Processing Delay
        – Time to process the packet header at a router or switch.
🧠 Think: Router checks where the data should go.

    Queuing Delay
        – Time the packet waits in a queue before being sent.
        🧠 Think: Waiting in line at a traffic signal.

    Transmission Delay
        – Time to push all bits of the packet onto the link.
        🧠 Think: Time to load data onto the wire.

    Propagation Delay
        – Time for the signal to travel from sender to receiver.
        🧠 Think: Time it takes for data to physically move through the cable.
        ```


🟢16. 3 way handshaking
```
    It is the process used to establish a reliable connection between a client and a server before data transfer.

    SYN – Client sends a request to connect (SYN = synchronize).
    SYN-ACK – Server responds with acknowledgment (SYN + ACK).
    ACK – Client sends final acknowledgment.
    ```

🟢17. Server-side load balancer
```
    A server-side load balancer is a device or software that distributes incoming network 
    traffic across multiple servers to ensure no single server gets overloaded.

    🧠 Think: Like a traffic cop sending cars to different roads to avoid jams.
    ```

🟢18. RSA Algorithm
```

    RSA is a popular encryption algorithm used to secure data by using a public key and a private key.

        Public key is used to encrypt data.
        Private key is used to decrypt data.
        ```

🟢19. What is HTTP and HTTPS protocol?
```
    ✅ HTTP (HyperText Transfer Protocol)
        HTTP is a protocol used to transfer data (like web pages) between a web server and a browser.
        It is not secure — data is sent in plain text.

    ✅ HTTPS (HyperText Transfer Protocol Secure)
        HTTPS is the secure version of HTTP.
        It uses encryption (like SSL/TLS) to protect data from hackers.

    🧠 Think: HTTPS = HTTP + Security (the "S" stands for Secure)
    ```

🟢20. What is SMTP protocol?
```
    SMTP (Simple Mail Transfer Protocol)
        SMTP is a protocol used to send emails from one server to another.

    🧠 Think: It’s like a digital postman that delivers your email to the right address.
    ```

🟢21. TCP and UDP protocol, prepare differences
```
       copy(74);
       ```
🟢22. What happens when you enter “google.com” (very famous question)
```

    DNS Resolution
        – The browser asks DNS to get the IP address of google.com.

    Browser Connects to Server
        – Using the IP, it sends a request to Google’s server (via TCP connection using 3-way handshake).

    HTTP/HTTPS Request Sent
        – Browser sends an HTTPS request to get the web page.

    Server Responds
        – Google’s server sends back the webpage content (HTML, CSS, images, etc.).

    Browser Renders Page
        – Your browser displays the page on your screen. 
        ```

🟢23. Hub vs Switch
```
      hub(copy 12)  switch(copy 14)
      ```
🟢24. VPN, advantages and disadvantages of it
```
      VPN stand for Virtual Private Network

      ✅ Advantages of VPN:
            Security – Encrypts your data and protects it from hackers.
            Privacy – Hides your IP address and online activity.
            Access – Lets you access blocked or restricted websites.
            Remote Access – Connects employees to office networks securely.

      ❌ Disadvantages of VPN:
            Slower Speed – Encryption can reduce internet speed.
            Cost – Good VPNs often require payment.
            Trust Issues – Some free VPNs may log your data.
            Complex Setup – May require technical knowledge.    
            ```  

🟢25. LAN
```
     A LAN is a network that connects computers and devices within a small area, like a home, office, or school.
     ```