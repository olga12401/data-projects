# What is it Vnet

VNet (Virtual Network) is a fundamental building block used to logically isolate and securely connect Azure resources. It allows гs to create your own private space in the cloud, similar to an on-premises network, where we can launch Azure services, like virtual machines (VMs), databases, and more.

№№ Key components of a VNet include:

**Subnets:** Segments within the VNet that help organize and manage resources. Subnets can be used to allocate resources logically and apply different network security configurations.

**Network Security Groups (NSGs):** These act as firewalls for controlling inbound and outbound traffic to Azure resources. NSGs allow or deny traffic based on rules that you define.

**Virtual Network Gateways:** These enable secure connectivity between Azure VNets and other networks, such as on-premises networks or other Azure VNets. They can also be used for establishing site-to-site or point-to-site VPN connections.

VNets provide features like network isolation, segmentation, and control over IP addressing, DNS settings, security policies, and routing. They play a crucial role in designing and implementing Azure infrastructure, offering flexibility and scalability while ensuring secure communication between resources.

# Steps

1. Create a basic parametrs

![image](https://github.com/olga12401/data-projects/assets/86374953/603886ff-90f2-46f5-b5f9-d27341180cb3)

2. Create IP and Subnets . Default subnet I rename to public + change size 

![image](https://github.com/olga12401/data-projects/assets/86374953/c4536b0f-ff1c-4121-b9f1-89436c29f2f6)

3. Add private subnet

![image](https://github.com/olga12401/data-projects/assets/86374953/fe6bb9c8-81c6-41ca-ae61-167ccf0f29d8)

4. Security: All disable 
4. Review+Create
5. Create 



