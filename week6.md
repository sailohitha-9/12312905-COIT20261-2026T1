# Week 6 Tutorial

## Task 1: Resolving IP Addresses to Hardware Addresses

- Screenshot of ARP tables of Host A at different time points that illustrate the changes in the ARP table as device communicate
  
  - ![Screenshot](/images/ARP-Basics-12312905-HostA-Table.png)

## Task 2: Default Gateways

- Exported Project:
   - [file](/images/Default-Gateway-12312905.gns3project)
 
- Screenshot of the network
   -![Screenshot](/images/Default-Gateway-12312905-network.png)

- IP addresses and Routing tables of each host and router
   -![Screenshot](/images/host1.png)
   -![Screenshot](/images/host2.png)
   -![Screenshot](/images/host3.png)
   -![Screenshot](/images/host4.png)
   -![Screenshot](/images/router1.png)
   -![Screenshot](/images/router2.png)

- Screenshot of a succesful ping from a host one one subnet to a host on the other subnet.
   -![Screenshot](/images/Default-Gateway-12312905-ping.png)

### Reflection

- In this week’s tutorial, I learned how ARP helps a host discover the MAC address of another device on the local network, and how the default gateway is used when communicating with a different subnet. By comparing the ARP table before and after sending traffic, I could see how the entries were learned dynamically. The ping results showed that the hosts were able to communicate across subnets through the router, which confirmed that the IP addressing and gateway settings were correct. I also learned that routing tables and ARP tables work together at different layers of the network stack. One challenge was checking that each host had the correct gateway and subnet settings, because a small mistake would stop the communication from working. After reviewing the routing and ARP outputs carefully, I was able to verify that the network behaved as expected.
