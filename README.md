# CCNP-Enterprise
CCNP Labs / Theories

This includes daily updates of CCNP Enterprise's Labs and Theories.

# Day 1
![Day 1 UI](https://github.com/Htin2001/CCNP-Enterprise-/blob/ee511024c0821c6bcac03a9a09ce0bf263574e98/Day%201.png)

According to this lab, we want to make a connection between PC_0 and PC_1 and we use static routes for all routers and setting AD number - 2 for the backup route which is also called AD Tuning. 

Command Line: ip route (destination network) (subnetmask) (next hop / interface name) 2-255

Where do we use the Administrative Distance? 
- We use AD number in choosing of best route including backup route.
- We use AD number in comparing of Routing Protocol (i.e. Three routers running both OSPF and EIGRP, we want to choose EIGRP route for these three routers, we compare AD numbers at that time. So AD number of EIGRP is 90 / 170 which AD number of OSPF is 110. Routers will choose EIGRP for routing)
 
