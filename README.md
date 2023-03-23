# KaliPurple-AWS-Cloudformation-SOC-Template
Cloudformation Template to Launch the SOC from Kali Purple

Launching the SOC in AWS could be an cost effective option for people that do not have access to a Proxmox server. 

![Screenshot_20230323_173403](https://user-images.githubusercontent.com/47893772/227368991-d61666b2-c12d-4051-91ce-629e8815347d.png)


Consists of 2 files. 

  1 - Launch KaliPurple-VPC.yml - This will configure the VPC. Used the same IP ranges suggested in the documentation. 
  
  2 - Launch KaliPurple-NAT-EC2 - This will configure the instances acording to the requirements
  
  This is the diagram of the VPC
  
  
  
  
  ![new-designer](https://user-images.githubusercontent.com/47893772/227371698-4484616c-314f-46de-bb46-8b76dc111772.png)

  
  
  
  
  
  
  Please note that this repository is still work in progress. At this point, the VPC has been created succesfully. In regards to the VMs, the KaliPurple and the KaliHeliotrope are created but haven't been totally configured yet. A Guacamole Bastion has also been created but not yet configured. 
  
  
  Reference:  https://gitlab.com/kalilinux/kali-purple/documentation/-/wikis/home
  
Desired final SOC Configuration:


![Kali-Purple-03-Architecture](https://user-images.githubusercontent.com/47893772/227374044-259a9c52-7d28-4f2d-b6e1-11aef05c74aa.png)

