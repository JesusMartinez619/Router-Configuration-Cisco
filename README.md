<div align="center">
  <img width="253" alt="image" src="https://github.com/user-attachments/assets/369fccf4-73ce-435f-80d1-386e9d5ae1c1" />
</div>


# Router-Configuration-Cisco

This tutorial will demonstrate how to configure routers/switches/PCs to create a connection from 2 different networks.

# Environments and Technologies Used

- TDX Arena (Virtual Machines)
- Cisco Packet Tracer

# High-Level Deployment and Configuration Steps
- Connecting cables from S1 & S2 to R1 (S=Switch, R=Router)
- Configure router
- Configure PCs
- Ping

# Deployment and Configuration Steps

- In this First image I demonstrate how I have 2 functioning networks via switches, each switch has 2 hosts (PCs) connected. In the Second Image I demonstrate how I connect the Switches to the Router with a Copper-Straight-Through cable. The red triangles mean that there is still no connection from router to switches.

<img width="631" alt="image" src="https://github.com/user-attachments/assets/dd08dc77-74a3-4c52-b8cb-c0e69936b282" /> <img width="632" alt="image" src="https://github.com/user-attachments/assets/e73bcfd3-c19d-4652-8421-d9f3bd46d2a2" />

-In this section I will be connecting the Router to the switches, In the first image I head over to the CLI for the Router to start configuring. In these next pictures I demonstrate the commands I input to connect the switches with the router, Input of the IPs and Subnets. The next picture demonstrates how after I configure the router the triangles turn green meaning there is a functioning connection between these two networks.

<img width="628" alt="image" src="https://github.com/user-attachments/assets/c0828a42-d8d0-4e09-946c-0125b8cd8117" /><img width="157" alt="image" src="https://github.com/user-attachments/assets/d26e9b14-e337-4081-920f-553162f8d67a" /> <img width="144" alt="image" src="https://github.com/user-attachments/assets/f6a1e7ed-2eef-489f-a015-c9087fa418a8" /> <img width="284" alt="image" src="https://github.com/user-attachments/assets/fe202cea-b72c-4e88-aca5-830c98314981" />

-In this Next section I will be configuring the PCs through "IP configuration" on "desktop" to establish connection to the other PCs on the other network through the Router. In these first pictures I input the IPs/Subnet mask/Default Gateway, to match the routers configuration to allow access. 

<img width="497" alt="image" src="https://github.com/user-attachments/assets/7bf8608c-db30-4e28-ab83-3ff506054e4e" /> <img width="254" alt="image" src="https://github.com/user-attachments/assets/9698e960-eaf1-433c-8682-4a4bca594320" />

- In this last section I go over to PC1 from S1 to ping the other network S2 PC4 to check if there is connection, and the ping was successful.

<img width="294" alt="image" src="https://github.com/user-attachments/assets/cb3237bc-fd7b-4053-a5db-96aa2cf34a28" /> <img width="359" alt="image" src="https://github.com/user-attachments/assets/8033fd8d-4edf-4bd9-b0ab-31c23239922b" />







