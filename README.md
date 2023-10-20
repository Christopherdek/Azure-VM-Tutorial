# Azure Virtual Machine Tutorial

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/c30046ef-7881-4feb-ae2f-722603d4ca58)


Today, we're diving into the world of Azure Virtual Machines. No need for a lengthy introduction—let's jump right in! First up, a brief overview of Azure, then we'll get into the Azure Virtual Machine. After that, we'll explore its benefits, take a closer look at its components, and cap it off with a hands-on demo.

## What is Azure?

Azure is a Microsoft cloud service designed for building, testing, and managing applications through data centers. It's flexible, letting you pay for what you use and adapt to business changes. Azure boasts reliability, 24/7 support, and cost-effective pay-as-you-go pricing.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/98b931c3-9b0a-4768-89e5-3a5186e222f3)


## Azure Virtual Machine

It's a service that offers a variety of virtual machines for your needs. Think of a virtual machine as a computer file, mimicking a real computer but running within a window on another system. You get your own hardware—CPUs, memories, and more. It's flexible and adapts to your requirements.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/265efc87-1338-495f-94cc-d63274afcf56)


### Why use Azure Virtual Machine?

- **Easy Development and Test:** It provides a quick and easy setup for coding and testing applications.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/ac0dc1f3-f954-4d69-a766-6a2a1544cc40)

- **Agility and Scale:** You can clone and create multiple instances rapidly, scaling services efficiently and cost-effectively.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/82711b3c-6e32-4a87-ba54-a3048e612266)

- **Enhanced Performance:** Connect easily to your organization's network, set up redundant infrastructure, and get disaster recovery at a fraction of the cost.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/27d88282-429a-484a-a231-32bea17fc7a4)

## Components

1. **Operating System (OS):** It's the crucial starting point, connecting to the remote desktop session host. Choose from various OS options.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/72214d85-08a7-444f-89c7-3a13c6ebf654)


2. **Disks:** These are the storage units. Images are templates for new virtual machines, while disks are bootable virtual hard disks. They inherit benefits like high availability and durability.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/78088db5-a180-426e-a46d-35e133c1fa52)


3. **Virtual Network:** This ensures scalable and secure operations. It includes components like load balancers and firewalls, deploying into an Azure virtual network.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/4093a7a3-e962-4a17-8b11-4665e10fdc43)

4. **Availability Sets:** These come into play to avoid failures. If a server fails, the platform migrates the virtual machine to a healthy host for continuity.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/a73c654d-6197-4bc7-b519-e7cc33bd7dcd)


## Demo on Creating an Azure Virtual Machine

1. **Log into Azure:** Type: [wwww.azureportal.com](https://portal.azure.com/) Use your credentials to access Microsoft Azure.

Enter Username:
![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/940af90d-71b2-4fe2-a977-a76ea1b39ae4)

Enter Password:
![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/b8923df1-83c3-461c-8467-7cbc7e72396d)

2. **Create a Virtual Machine:** Set up a new virtual machine with pay-as-you-go pricing, specifying details like region, image, and size.

From the Home Page navigate to 'Azure Services' and select the icon 'Virtual Machines'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/71504519-4610-49a1-8819-5454ee2ad4cf)

Or simply type 'Virtual Machines' in the search bar

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/cb579ef3-3528-4b8f-8e2c-1f1d239420c8)

Select 'Create' 

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/dc67c262-e177-426e-8b7f-8bfa4bed4a39)

Select your chosen option, for this instance select 'Azure virtual machine'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/5ede38c4-815e-455b-89cc-f4bcd6364a89)

Project details

Select your subscription 
![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/7775556d-5796-4877-bb48-77448fdf1d83)

Either select a resource group you have already made or 'create new' 'Resource group'.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/ae5ea2c6-937b-4f4c-b08d-5104321d8c94)

Instance Details

Name the Virtual Machine & select a region 

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/55b08afa-fb73-415e-98e9-798c3d5cd6da)

Select 'Security type' 'trusted launch virtual machines'
For 'image' you can choose from a variety of different Operating systems, for this tutorial use 'Windows 10'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/b6e3de08-8bed-407a-a3eb-75f36e97ffe9)

Depending on the scale of your project select a 'size' for this tutorial 'Standard_D4s_v3 - 4 vcpus, 16 GiB memory' cpu's and memory the higher the performance will be.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/f22803e3-9466-47f6-b510-bf13605097b1)

Administrator account

Enter a Username and Password, remember these as you will need them for future use of the Virtual Machine.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/963dbec2-a45f-435b-8fe8-abcbe7270ec9)

Check the 'licencing agreement' box and select 'next'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/f063e40d-792a-4653-b428-967d849eb672)

There are a variety of changes you can make before 'Reviewing and creating', these are mostly outside of the scope of this Tutorial.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/ab73f371-889f-4fe9-9fc9-d19eae358fc6)

Under the heading 'Networking' you can select & create 'Virtual network', 'Subnet', and 'public IP'. we will not make any changes here for the purposes of this Tutorial.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/ab502d1f-87af-4dea-84e5-dc9f5a9dc37e)

Select 'Review + create', allow the machine to 'pass validation'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/5daf5e73-54c6-4e43-b3de-acdb737929b0)

Observe the pricing of the virtual machine before selecting 'Create'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/d0b49dfd-7d1f-463f-aa5f-57a2184f6c95)


3. **Deployment:** Wait a few minutes for the deployment to complete.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/b60dd4a7-d7a3-4cc2-89af-d108ea1c3ead)

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/3e9f0fae-65b9-4dea-909f-0fb272baf250)

4. **Connect and Configure:** 

Access the virtual machine , copy the IP address

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/925e3721-c76c-483a-8837-b2fe0e3b5ec9)

Search and open ' Remote Desktop'.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/bf80ce60-cad0-422a-980d-9c58bed09087)

Paste the public IP address of your Virtual Machine and select 'connect'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/04280f46-8982-41d9-ad53-d8f78423bcb6)

Enter the Username and Password you used to set up your Virtual Machine and select 'OK'

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/a3155a6a-9562-4398-8a26-31aea3cc0d80)

Accept the certificate

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/554bc9ed-06cb-4d1f-9654-14d23ca62604)

Allow the remote desktop to load and select your preferences

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/029e7d95-587f-44ef-a538-ccf8a0884349)

5. **Web Application Demo:** 

Open the Microsoft Edge, enter https://whatismyipaddress.com/ Observe the IP Adress of your newly created Virtual Machine.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/83216659-f0f5-41cc-b5e4-80934fccece3)

I would also suggest that you clean up your azure account by deleting anything that you do not need open.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/17875b14-b35f-4c21-9eba-5f00da51a9a9)

Tick the box and delete.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/5bb83ad2-b2b6-4e99-9190-0b15a3945739)

Refresh until the Virtual machine page is clear once again.

![image](https://github.com/Christopherdek/Azure-VM-Tutorial/assets/148359456/a7993089-e17e-4400-9577-8cb5a90c8fc4)


And that's it! We've covered the basics of Azure, explored Azure Virtual Machine and its benefits, dived into its components, and wrapped it up with a practical demo. Hope you enjoyed the tutorial!
