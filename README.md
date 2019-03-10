# Azure_VMSS_PUB_Provision_ARM
Provisioning a Ubuntu, Centos and Redhat Virtual Machine Scale Sets (Public IP Per Instance=True) using ARM Template

Provisioning a
    "Ubuntu-17.10",
    "Ubuntu-18.04-LTS",
    "RHEL-7.5",
    "RHEL-7.6",
    "Centos-7.3",  
    "Centos-7.5" 
Virtual Machine Scale Sets (Public IP Per Instance=False) using ARM Template

New Virtual Network,Virtual Subnet,Network Security Group will be created.New Load Balancer Created and attached with VMSS

Each Instance in ScaleSet has its own Public IP
