# Computer-Networking-Project
Computer Networking Project (Topology, Static &amp; Dynamic Routing) for CSE421 (Topic 5)



                        Shakib Al Hasan
                        
                        
Shakib Al Hasan wants to provide high-speed internet to some districts of the Khulna division.
He aims to fund welfare projects in those areas and is willing to build offices to smoothen the
workflow. All these offices will have access to the internet, so they must be able to send and
receive information among those offices situated in different districts whenever required. This is
where you come in. Mr. Shakib has personally hired you as the network engineer, whose task is
to implement the network architecture per his requirements.
Given below are the names of the districts where offices will be made and the number of hosts
required in each of those offices:
• Magura (128)
• Kushtia (40)
• Jashore (560)
• Faridpur (210)
• Narail (350)
• Satkhira (80)
While creating the network infrastructure, there are specific rules that you need to follow:
• Since Shakib Al Hasan is from Magura, he wants the main/head office to be situated
here. Therefore, Magura will act as a centerpiece for all the other offices.
• Kushtia, Jashore and Magura will be interconnected, to ensure 24/7 connectivity between
these offices.
• On the special request of Mr. Shakib, Satkhira will be directly connected to Magura.
• Satkhira will also be connected to Faridpur and Narail, to ensure less cost in setting up
connections in those two districts.
• Choose an appropriate network address and create subnets to assign to each of the district
offices so that the least amount of IP addresses are wasted.
• The offices in Kushtia and Satkhira districts will use static addressing to ensure security
while the other offices will get their IP addresses through a dedicated DHCP server.
This DHCP server will be present in Kushtia.
• Email can be exchanged between all the offices. So an Email server has to be set up and
it will be located in Satkhira.
• Jashore and Narail offices will require printers to print campaign posters in large
numbers.
• Kushtia will also have a web server and a DNS server. If anyone types the URL
www.papon.com, they will see a webpage that says ‘Nazmul Hasan Papon says Hi!’
• All servers will have to be configured manually
• Routing in the whole network should follow these rules:
o Jashore and Kushtia must use static routing. Kushtia will be directly connected to
Magura, and Jashore will communicate with Magura via Kushtia.
o Jashore and Magura will also be connected, as mentioned earlier, but it will not be
the primary route. A backup route has to be configured here.
o The rest of the offices i.e. Satkhira, Faridpur and Narail will use dynamic routing.
o You have to remember the default route cannot be used while exchanging
packets. Data will be delivered using static or dynamic routes only.
• Showing 2 end devices per network is good enough to represent the whole population
• You need to be able to ping each office from another after all the configurations are
complete
Deliverables
• The network mentioned above should be implemented in Cisco Packet Tracer, with
necessary devices and full configuration.
• After completion you should be able to test the conditions imposed.
• You will have to submit the followings:
o Network topology diagram with proper labels
o The configuration commands of all the routers that you have implemented.
o VLSM tree
o IP address table
