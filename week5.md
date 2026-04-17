# Week 5 Tutorial

## Task 1: Setup VLANs on Switch

- Exported project:
  - [file](/images/Vlan-Basics-12312905.gns3project)

- Screenshot of the network:
  - ![Screenshot](/images/Vlan-Basics-12312905-network.png)

- Screenshot showing the ports and tags on the switch
   - ![Screenshot](/images/Vlan-Basics-12312905-ports.png)
 

## Task 2: Setup VLANs on a Router

- Exported project:
    - [file](/images/Vlan-Router-12312905.gns3project)
 
 - Screenshot of the network:
     - ![Screenshot](/images/Vlan-Router-12312905-network.png)

 - Screenshot showing the ports and tags on the switch
    - ![Screenshot](/images/Vlan-Router-12312905-ports.png)
  
### Reflection

- In this week’s tutorial, I learned how VLANs are used to separate network traffic logically even when devices share the same physical switch. By checking the port and tag output, I could confirm which interfaces were assigned to each VLAN and how the router handled inter-VLAN routing. I found that understanding the relationship between ports, tags, and router configuration was the key to making the network work correctly. One challenge was making sure the trunk and access settings matched the intended design, because a small mismatch could stop communication between hosts. After reviewing the output carefully, I was able to verify that the VLAN configuration was correct and that the network behaved as expected.
