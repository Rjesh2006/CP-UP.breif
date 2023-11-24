# [Here we will understand whats the control plane and user plane exactly in well defined way :-]()
   - ## Also we will  learn waht's( UP and CP plane ) in 5G networking 

# plane in networking:- 
 - in networking , a plane is not a physicl component but an intangible idea that helps concenptualize traffic flows through a network  it refers to a part of the physical network architecture or an area of opereation where certain activities and processes take place. The data plane, the control plane and the management plane are the three basic components of a telecommunications architecture.

    - Here we will look  for the user palne ( data plane) and the Control plane.


## User plane( data plane) : - 
  the  date plane sometimes whiich  known as the user plane forwding plane ,carriers plane or bearer plane this is the part of network that carries 
  (user traffic.)

  
  -The data plane controls all the functions and processes that determine how to 
   forward packets from one interface to another thats why user plane or data plane also knows as the( forwadding plane).
    



## Control  plane: - 
  -The control plane is the part of a network that carries signaling traffic and is responsible for network routing. 

 
   -The main function of the control plane is to create logic and to program actions 
    for the data plane Thus while the data plane actually forwards the packets, the 
    control plane determines or controls, how the packets should be forwarded.





# work's b/w Control plane and User plane ( data plane):-
   - we can  also visualiza by this image--

     
     ![image](https://github.com/Rjesh2006/CP-UP.breif/assets/143868643/55f8848f-4f13-4a9e-9ba6-b90dc268a3d3)

     
Once the control plane determines how and to which ports packets should be forwarded the data 
plane refers to the logic and actually forwards the 
packets This is why it is also known as the forwarding plane. Thus the network layer handles all traffic and moves packets from source to destination based on the actions and logic programmed and supplied to it by the control plane.

After sourcing the traffic the data plane sends it on to other network supported devices Routers 
then forward the packets downstream to their 
appropriate destinations. All data plane packets go through routers and the traffic is tightly controlled to protect the network from malicious network 
traffic.
