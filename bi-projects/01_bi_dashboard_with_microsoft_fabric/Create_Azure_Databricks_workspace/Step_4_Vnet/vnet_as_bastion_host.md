# Azure Virtual Network with VM as a bastion host

Using a VM as a bastion host within an Azure Virtual Network (VNet) is a common security practice. A bastion host serves as a secure gateway to access and manage other VMs within the VNet. Instead of exposing multiple VMs to the public internet, you can route all your administrative access through the bastion host, which acts as a single entry point, thereby reducing the attack surface.

   ![image](https://github.com/olga12401/data-projects/assets/86374953/bdcbeb0d-72f8-4251-b038-3234d3680b5c)

# Steps 

## Create a virtual network and bastion host

1. Select Virtual networks + Create
2. Create new Resource group for vnet
   
   ![image](https://github.com/olga12401/data-projects/assets/86374953/8746f3de-19fb-48ed-9b5f-7cdea423f435)

3. Add bastion in Security

   ![image](https://github.com/olga12401/data-projects/assets/86374953/40e5e1e7-4e16-4527-836b-2a32979a2bcc)

4. IP Addresses tab. I don't change IP adress, but I need to rename defauly subnet to subnet-1

   ![image](https://github.com/olga12401/data-projects/assets/86374953/7eea5bc8-e870-474f-9fdc-892b9c9d6de7)
5. Review + create . If it'll be OK -> Create.

   ![image](https://github.com/olga12401/data-projects/assets/86374953/5a7b3c89-9e39-43fe-9b25-012e828cf841) 


##  Create virtual machines  1

1. Home -> Select Virtual machine -> Create
2. Choose Azure virtual machine
3. Create Vm

   ![image](https://github.com/olga12401/data-projects/assets/86374953/34a978f5-1365-418b-aff0-169a0582a84d)

   ![image](https://github.com/olga12401/data-projects/assets/86374953/e658f4a1-2cc6-4a3e-8abc-1f6f66b7b1e9)

   ![image](https://github.com/olga12401/data-projects/assets/86374953/3948e5ed-e8ba-4db2-890f-cf91de7c1b28)

4. Select the Networking for Vm

   ![image](https://github.com/olga12401/data-projects/assets/86374953/675b605a-826a-41c1-b1d4-b40614a06540)

   ![image](https://github.com/olga12401/data-projects/assets/86374953/30986fb7-d792-4616-a6f6-d252d1e5bf5c)

   Configure network security group: We create new group -> change name, but leave the rest at the defaults and select OK.

5. Select "Review + create".

   ![image](https://github.com/olga12401/data-projects/assets/86374953/133e7b65-4c4c-42d2-9272-fdd8a67b9713)

   ![image](https://github.com/olga12401/data-projects/assets/86374953/76293303-9e87-4728-82a4-f0b9d1268032)


##  Create virtual machines  2 

1. 3. Create new Vm

![image](https://github.com/olga12401/data-projects/assets/86374953/e14c442a-5824-41bd-9ce0-ca3b7fb325d1) 

![image](https://github.com/olga12401/data-projects/assets/86374953/a3113586-d2fc-4723-843d-bb224d916944) 

2. Select the Networking for Vm 
![image](https://github.com/olga12401/data-projects/assets/86374953/4b25d52d-fd04-4356-a5df-f457178b40d3) 

![image](https://github.com/olga12401/data-projects/assets/86374953/7b12d2ae-b3d7-48f2-b7b9-0bcb4ac6fd18) 

3. 5. Select "Review + create".
![image](https://github.com/olga12401/data-projects/assets/86374953/ebeedc11-4f6d-4a02-ba14-e983820b09a9)


##  Connect to a virtual machine





   

   


