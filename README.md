# Sample of Cloud services extend support with Azure devops 

- Uses this sample https://github.com/Azure-Samples/cloud-services-extended-support/tree/main/101-cses-multirole-rdp 
- Follows the tutorial from [https://learn.microsoft.com/en-gb/azure/cloud-services-extended-support/deploy-prerequisite](https://learn.microsoft.com/en-us/troubleshoot/azure/cloud-services/azure-devops-publish-cloud-service-extended)

# 101-cses-multirole-rdp

	• Cloud Services (extended support) is a new Azure Resource Manager based deployment model for Azure Cloud Services product and is currently in public preview.
	• Through this sample, you can create a cloud service (extended support) by deploying the ARM templates (using attached cscfg/cspkg) through powershell or using attached cscfg/csdef/cspkg through portal
	• Resources such as Vnet, PublicIP get created by the ARM template and RDP extension is added at the time of cloud service create
Please note that virutal network has been added to the cscfg as it is mandatory for creating cloud service (extended support)

