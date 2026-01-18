Configure routing on the routers in three separate lab files using the same physical topology to ensure full connectivity using:

1. Static Routing only
2. Dynamic Routing – OSPF only
3. Dynamic Routing – BGP only

**Lab 1: The Topology with No route**

**Lab 2: Static Routing**
1.Configure IP addresses on all interfaces
2.Add static routes manually on both routers for all remote networks
3. No dynamic routing protocols enabled

**Lab 3: OSPF Routing**
1. Configure IP addresses on all interfaces
2. Enable OSPF on both routers
3. Place all interfaces in OSPF area 0
4. Advertise all connected networks via OSPF
5. No static routes or BGP configured

**Lab 4: BGP Routing**
1. Configure IP addresses on all interfaces
2. Establish eBGP session between Router0 (AS 100), Router1 (AS 200) and Router2 (AS 300)
3. Advertise each router's local networks via BGP
4. No static routes or OSPF configured

**Verification Tasks (for each lab) - For each configuration file/lab, verify:**
1. All PCs can ping each other
2. Routing tables show appropriate routes (static, OSPF, or BGP)
3. Neighbor relationships (OSPF/BGP) are established
4. Traceroute shows correct paths

![image_alt](https://github.com/rezaul1871/Network-Topology-Configuration-Static-BGP-and-OSPF-Routing/blob/adcdf728da841846947c7ef57522d51f0d6c5560/Topology.png)

