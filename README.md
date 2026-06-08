# Networking-Task1
Networking Internship Task 01 Report
Date: 05 June 2026
Intern: Riddhi Kshatriya

Task Objectives
The objectives of this task were:
• To understand the basic structure of a computer network.
• To identify the network configuration of a local system.
• To learn important networking terms and their functions.
• To perform network troubleshooting using networking commands.
• To create a simple network topology diagram.
• To document and analyze network connectivity results.


Task 1: Understanding the Network Environment
Tools and Commands Used
The following tools and commands were used during this task:
• ipconfig – Used to display IP configuration details of the system.
• ping – Used to verify connectivity between the local device and a remote server.
• tracert – Used to trace the route taken by packets to reach the destination.

Network Configuration Details

The following network information was obtained from the local system:
Property                          | Configuration Value
Hostname                       | RIDDHI-LAPTOP
IPv4 Address                   | 192.168.0.25
MAC Address                  | 3C:52:82:7A:91:B4
Default Gateway            | 192.168.0.1
DNS Server                      | 1.1.1.1


Sample IP Configuration Output

Ethernet Adapter Wi-Fi

Connection-specific DNS Suffix : home.local

IPv4 Address . . . . . . . . . : 192.168.0.25

Subnet Mask . . . . . . . . . : 255.255.255.0

Default Gateway . . . . . . . : 192.168.0.1

Physical Address . . . . . . . : 3C-52-82-7A-91-B4

DNS Server . . . . . . . . . . : 1.1.1.1


Basic Networking Concepts
1.	IP Address:An Internet Protocol (IP) Address is a unique numerical identifier assigned to every device connected to a network. It enables communication between devices and helps in identifying their location on the network.

2.	MAC Address:A Media Access Control (MAC) Address is a unique hardware address assigned to a network interface card by the manufacturer. It is used for communication within the local network.

3.	Default Gateway:The Default Gateway acts as an entry and exit point between a local network and external networks. It forwards data packets to destinations outside the local network.

4.	DNS Server:A Domain Name System (DNS) Server translates human-readable website names such as google.com into numerical IP addresses that computers can understand.

5.	Private IP Address:A Private IP Address is used within a local network for internal communication. These addresses are not directly accessible through the internet.

6.	Public IP Address:A Public IP Address is assigned by an Internet Service Provider (ISP) and is used to identify a network on the internet.


Basic Network Diagram

                     [ RIDDHI-LAPTOP ]
                      IP: 192.168.0.25
                               │
                               │ Wi-Fi Connection
                               ▼
                    [ Wireless Router ]
                       IP: 192.168.0.1
                               │
                               │
                               ▼
                     [ ISP Network ]
                               │
                               ▼
                          [ INTERNET ]


Network Connectivity Test
ifconfig
<img width="992" height="623" alt="Screenshot 2026-06-08 113513" src="https://github.com/user-attachments/assets/b2b193c3-0ac8-45d2-aa90-b9a660d2ff93" />


Ping Test
<img width="915" height="308" alt="Screenshot 2026-06-08 105242" src="https://github.com/user-attachments/assets/4460f328-c75d-4a05-8019-56f2898ce0d7" />
 

Traceroute Test
<img width="1021" height="486" alt="Screenshot 2026-06-08 105520" src="https://github.com/user-attachments/assets/02fc4cd3-5b96-4656-954c-1357e2c866b2" />


Questions and Answers

1. Was the ping successful?
Yes, the ping operation was successful. All packets were received successfully with 0% packet loss, confirming a stable network connection.

2. How many hops were shown in the traceroute?
The traceroute displayed a total of 5 hops before reaching the destination server.

3. What is the purpose of traceroute?
Traceroute is a network diagnostic tool used to identify the route taken by packets from the source device to the destination. It helps in detecting delays, routing issues, and network failures.

Conclusion
This networking task provided practical knowledge about network configuration, IP addressing, DNS functionality, routing mechanisms, and connectivity testing. Through the use of commands such as ipconfig, ping, and tracert, I was able to analyze network communication and understand how devices connect and exchange data across networks. The task also improved my documentation and troubleshooting skills, which are essential in networ
