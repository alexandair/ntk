# How to set up your environment

## Install Azure PowerShell from PowerShell Gallery

### System requirements

Azure PowerShell version 6.0.0 requires version 5.0 (or higher) of PowerShell.

```powershell
# Install the Azure Resource Manager modules from the PowerShell Gallery
Install-Module -Name AzureRM -AllowClobber
```

## Install Visual Studio Code and its extensions

If you're on Windows 7 or greater with the PowerShellGet module installed, you can easily install both Visual Studio Code and the PowerShell extension by running the following command:

```powershell
Install-Script Install-VSCode -Scope CurrentUser; Install-VSCode.ps1
```

[Installation script on GitHub](https://github.com/PowerShell/vscode-powershell/blob/develop/scripts/Install-VSCode.ps1)

[Installation script on the PowerShell Gallery](https://www.powershellgallery.com/packages/Install-VSCode/1.2/DisplayScript)

Manually install [Visual Studio Code](https://code.visualstudio.com/)

## Visual Studio Code extensions

Search Extensions (Ctrl+Shift+X)

[PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)

[Azure CLI Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli)

[Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account) (On Windows, it requires [Node.js 6 or later](https://nodejs.org/en/) for Cloud Shell)

[Azure Resource Manager Tools](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools)

[Azure Storage](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestorage)

[Azure Terraform](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureterraform)

[Ansible](https://marketplace.visualstudio.com/items?itemName=vscoss.vscode-ansible)

## Azure Cloud Shell

Configure [Azure Cloud Shell](https://docs.microsoft.com/en-us/azure/cloud-shell/overview)