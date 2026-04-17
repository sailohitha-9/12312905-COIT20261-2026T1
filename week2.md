# Week 2 Tutorial

## Task 1- Outputs

- Exported Project file:
  - [file](/images/SettingIP-12312905.gns3project)

- Screenshot of the Network:
   - ![Screenshot](/images/SettingIP-12312905-network.png)

  - Screenshot of the console of each of the four hosts showing the IP addresses from ip address show command:
     
    -![Screenshot](/images/SettingIP-12312905-host1.png)
    -![Screenshot](/images/SettingIP-12312905-host2.png)
    -![Screenshot](/images/SettingIP-12312905-host3.png)
    -![Screenshot](/images/SettingIP-12312905-host4.png)

## Task 2- Outputs

- Screenshot of the console of one host showing the ping command
   - ![Screenshot](/images/Ping-Basics-12312905-simple.png)
   - Ping Command used- ping 10.101.1.2

- Screenshot showing the ping command (and output) to a wrong IP address
  - ![Screenshot](/images/Ping-Basics-12312905-error.png)
 
- Screenshot showing the ping command (and output) when limiting the count, setting the data size and interval to non-default values
  - ![Screenshot](/images/Ping-Basics-12312905-options.png)

### Reflection

- This week I learned how to assign IPv4 addresses to multiple hosts and verify the configuration using both `ip addr show` and ping tests. The successful ping results confirmed that the hosts were communicating on the same network, while the failed ping to the wrong IP showed that connectivity depends on correct addressing. I also learned the importance of checking interface output carefully, because a small configuration mistake can affect the entire network. Next time, I would document each step more clearly while building the topology so my work is easier to review.
