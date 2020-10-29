# win2019-smalldisk
ARM template to deploy a Windows Server 2019 VM with relatively low cost and relatively good performance

- Deploys a Standard B2s VM with a 64GB OS disk, which is unavailable in the portal
- Creates accompanying resources with sane names
- Designed for use with Visual Studio Professional $50 monthly credit (VM and OSDisk should consume around $40/mo)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbaf%2Farm-templates%2Fmaster%2Fwin2019-smalldisk%2Fwin2019-smalldisk-existingVNET.json)