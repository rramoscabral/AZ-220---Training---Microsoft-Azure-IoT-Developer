# Software list to run the labs 

Is recomended that you use [Windows 10](https://www.microsoft.com/software-download/windows10) not all software are available for Linux Distribution like [CentOS](https://www.centos.org/), [Fedora](https://getfedora.org/), [OpenSuse](https://www.opensuse.org/), [RHEL](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux), [SLES](https://www.suse.com/products/server/) or [Ubuntu](https://ubuntu.com/). 

<br>

| Software | Link |
| --- | --- |
| Azure CLI | https://docs.microsoft.com/cli/azure/install-azure-cli |
| Azure Storage Explorer | https://azure.microsoft.com/en-us/features/storage-explorer/ |
| Azure PowerShell | https://docs.microsoft.com/powershell/azure/install-az-ps |
| Docker Community Edition | https://www.docker.com/products/docker-desktop |
| Dot NET Core 3 SDK | https://dotnet.microsoft.com/download |
| Git for Windows | https://git-scm.com/download/win |
| Node.js & npm | https://nodejs.org/en/download/ |
| Power BI Desktop | https://powerbi.microsoft.com/en-us/desktop/ |
| PowerShell Core (Windows, Linux) | https://github.com/PowerShell/PowerShell/releases |
| Python 3.7| https://www.python.org/downloads/release/python-370/ |
| Visual Studio Code | https://code.visualstudio.com/ |
| Visual Studio Code Azure Account Extension | https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account |
| Visual Studio Code Azure CLI Tools Extension | https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli 
| Visual Studio Code Azure Cosmos DB Extension | https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-cosmosdb |
| Visual Studio Code Azure IoT Tools Extension | https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.azure-iot-tools|
| Visual Studio Code Azure Resource Manager Tools Extension | https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools |
| Visual Studio Code Azure Storage Extension | https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestorage |
| Visual Studio Code C# Extension | https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp |
| Visual Studio Code Docker Extension | https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker |
| Visual Studio Code PowerShell Extension | https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell |


**Notes:**
 1. The software list is ordered alphabetically and is not ordered by the installation sequence
 2. .NET Core 3 SDK is not 100% compatible with Visual Studio 2017, you can use it by enable "previews of the .NET Core SDK"
 

<br>


**Using Linux on Windows 10**

If you are going to use the Windows 10 operating system, it is recommended to activate Microsoft Windows Subsystem Linux and install a distribution of your choice (For Az-220 it is recommended Ubunto LTS)

  How-to Install:
  
  1. Before installing any Linux distros for WSL, you must ensure that the "Windows Subsystem for Linux" optional feature is enabled
  ```powershell
    Install-Module PowerShellGet -Force
    Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
  ```
  2. You can install Linux distros from the Microsoft Store app or you can download and manually install Linux distros by clicking these links:
      * [Ubuntu 18.04](https://aka.ms/wsl-ubuntu-1804)
      * [Ubuntu 18.04 ARM](https://aka.ms/wsl-ubuntu-1804-arm)
      * [Ubuntu 16.04](https://aka.ms/wsl-ubuntu-1604)
      * [Debian GNU/Linux](https://aka.ms/wsl-debian-gnulinux)
      * [Kali Linux](https://aka.ms/wsl-kali-linux-new)
      * [OpenSUSE Leap 42](https://aka.ms/wsl-opensuse-42)
      * [SUSE Linux Enterprise Server 12](https://aka.ms/wsl-sles-12)
     * [Fedora Remix for WSL](https://github.com/WhitewaterFoundry/WSLFedoraRemix/releases/)


<br>


**Visual Studio IDE (Community, Professional, Enterprise)** 

It is not mandatory to use the Visual Studio IDE.
With Visual Studio Code you can perform all labs. However, the following list is for the Visual Studio IDE only.
 
| Software | Link |
| --- | --- |
| Visual Studio IDE  | https://visualstudio.microsoft.com/vs/
| Visual Studio Code Azure IoT Edge Tools Visual Studio 2017 | https://marketplace.visualstudio.com/items?itemName=vsc-iot.vsiotedgetools |
| Visual Studio Code Azure IoT Edge Tools Visual Studio 2019 | https://marketplace.visualstudio.com/items?itemName=vsc-iot.vs16iotedgetools |
