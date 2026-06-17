Please reuse the the code in infra/modules/network in this GitHub Repo: [Code Mod infra/modules/network folder](https://github.com/microsoft/Modernize-your-code-solution-accelerator/tree/main/infra/modules/network). This folder contains below BICEP code modules

- bastionHost.bicep: code to create bastion host. 
- jumpbox.bicep: code to create jumpbox
- virtualNetwork.bicep: code to create a virtual netowork
- main.bicep: code that you call from your bicep which invokes the above three bicep programs. 