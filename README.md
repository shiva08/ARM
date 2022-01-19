# ARM

Single subnet template(parent) has these features:
1. Create multiple SQL VMs
2. Join the domain
3. Setup AG prerequisites
4. Create Load Balancer
5. Create AG, AGListener

Before deploying, ensure these are present:
1. A valid Virtual Network with a subnet
2. A domain controller VM is present

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fshiva08%2FARM%2Fmain%2Fnested.json)


If createVM is false, generateVMNames is false.
Maximum VMs = 9
Listenername length <=15
