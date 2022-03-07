# ARM

Prerequisites
1. A Virtual Network
2. A domain controller VM
3. Subnets for VMs         (vmCount = subnetCount)


Multi subnet template(nested.json) has these features:
1. Create multiple SQL VMs
2. Join the domain
3. Setup AG prerequisites - Failover cluster, configuration
5. Create AG, AGListener



[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/?feature.armendpointprefix=eastus2euap#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fshiva08%2FARM%2Fmain%2Fnested.json)


Maximum VMs = 9

Listenername length <=15

![image](https://user-images.githubusercontent.com/7246619/156675179-59ffccb2-2b2a-4db5-9146-c6b765ba48c2.png)
