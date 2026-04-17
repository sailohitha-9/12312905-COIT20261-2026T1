# Week 4 Tutorial

## Task 1 : View Routing Table

- Exported project:
   - [file](/images/View-route-12312905.gns3project)

- Screenshot of the Network:
   - ![Screenshot](/images/View-Routes-12312905-network.png)
   
- Record of the IP addresses and routing tables of each host and router:
   - ![Screenshot](/images/host1.png)
   - ![Screenshot](/images/host2.png)
   - ![Screenshot](/images/host3.png)
   - ![Screenshot](/images/router.png)

- Screenshot of a successful ping from a host one one subnet to a host on the other subnet:
  - ![Screenshot](/images/View-Routes-12312905-ping.png)
  

## Task 2: Dynamic Routing with OSPF

- Exported project :
  - [file](/images/OSPF-Basics-12312905.gns3project)

- Screenshot of the network:
  - ![Screenshot](/images/OSPF-Basics-12312905-network.png)
- Output of showing neigbour routers of FRR1:
  - ![Screenshot](/images/neighbourRouters.png)
- Output showing routing table for two routers:
   - ![Screenshot](/images/RoutingTable.png)
- A table that summarises the routers for all routers:
  - ![Screenshot](/images/task2.png)
- Output of traceroute commands before and after the link is disconnected:
  - ![Screenshot](/images/traceroute.png)
 
### Reflection

- In this week’s tutorial, I learned how dynamic routing works using OSPF and how routers share information to build routing tables automatically. The neighbour and routing table outputs helped me confirm that the routers had established adjacencies and were learning paths correctly. The traceroute results were especially useful because they showed how the traffic path changed after a link was disconnected, which helped me understand route recalculation and convergence. I also learned that when a link fails, OSPF can find an alternate route if one exists, which makes the network more resilient. One challenge was checking that every interface and IP address was set correctly, because a small mistake could stop the routing from working. By comparing the routing table, neighbour status, and ping results, I could verify that the network was behaving as expected.
