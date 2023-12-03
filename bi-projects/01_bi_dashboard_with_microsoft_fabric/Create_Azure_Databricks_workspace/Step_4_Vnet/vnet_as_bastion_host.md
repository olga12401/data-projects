# Azure Virtual Network with VM as a bastion host

Using a VM as a bastion host within an Azure Virtual Network (VNet) is a common security practice. A bastion host serves as a secure gateway to access and manage other VMs within the VNet. Instead of exposing multiple VMs to the public internet, you can route all your administrative access through the bastion host, which acts as a single entry point, thereby reducing the attack surface.

   ![image](https://github.com/olga12401/data-projects/assets/86374953/bdcbeb0d-72f8-4251-b038-3234d3680b5c)

## Steps 

1. Select Virtual networks + Create
2. Create new Resource group for vnet
   
   ![image](https://github.com/olga12401/data-projects/assets/86374953/8746f3de-19fb-48ed-9b5f-7cdea423f435)

3. Add bastion in Security

   ![image](https://github.com/olga12401/data-projects/assets/86374953/40e5e1e7-4e16-4527-836b-2a32979a2bcc)

4. IP Addresses tab. I don't change IP adress, but I need to rename defauly subnet to subnet-1

   ![image](https://github.com/olga12401/data-projects/assets/86374953/7eea5bc8-e870-474f-9fdc-892b9c9d6de7)
5. Review + create . If it'll be OK -> Create.

   ![image](https://github.com/olga12401/data-projects/assets/86374953/5a7b3c89-9e39-43fe-9b25-012e828cf841) 


   


