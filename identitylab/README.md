# identitylab
ARM template to deploy a lab environment for use with Microsoft cloud identity proof-of-concepts

- Deploys a VM for use as an AD DS domain controller and AAD Connect server
- Designed for use with Visual Studio Professional $50 monthly credit (VM and OSDisk should consume around $40/mo)
- Includes Azure Bastion for RDP access to the VM (only in the "non-lite" version; note that including Bastion will cost more than the $50 credit allows)

*Full version (including Azure Bastion)*
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbaf%2Farm-templates%2Fmaster%2Fidentitylab%2Ftemplate.json)

*Light version (excludes Bastion)*
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbaf%2Farm-templates%2Fmaster%2Fidentitylab%2Ftemplate-lite.json)