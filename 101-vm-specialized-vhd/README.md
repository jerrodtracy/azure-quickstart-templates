# Create a VM from a specialized VHD disk

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FStrongholdData%2Fazure-quickstart-templates%2Fmaster%2F101-vm-specialized-vhd%2Fazuredeploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FStrongholdData%2Fazure-quickstart-templates%2Fmaster%2F101-vm-specialized-vhd%2Fazuredeploy.json" target="_blank"><img src="http://armviz.io/visualizebutton.png"/></a>

## Prerequisite 
- VHD file that you want to create a VM from already exists in a storage account.

```
NOTE

This template will create an additional Standard_LRS storage account for enabling boot diagnostics each time you execute this template. To avoid running into storage account limits, it's best to delete the storage account when the VM is deleted.
```

This template creates a VM from a specialized VHD. The VHD file can be located in a storage account using a tool such as Azure Storage Explorer http://storageexplorer.com/
