# Azure Functions and Serverless

## Getting Started

## Configure Environment


### Node

``` bash
node --version
```

### Azure CLI

#### Windows

https://aka.ms/installazurecliwindows

#### MacOS

```zsh
brew update && brew install azure-cli
```

#### Linux

**Ubuntu / Debian**

```bash
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```

**Fedora / RHEL**

```bash
# MS Keys
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
# Repository
sudo dnf install -y https://packages.microsoft.com/config/rhel/8/packages-microsoft-prod.rpm
# Install
sudo dnf install azure-cli
```

https://docs.microsoft.com/en-us/cli/azure/install-azure-cli


### Azure Functions Core Tools

> [!tip] The Azure Functions Core Tools provide a local development experience for creating, developing, testing, running, and debugging Azure Functions.

https://docs.microsoft.com/en-in/azure/azure-functions/functions-run-local?tabs=v4

https://github.com/Azure/azure-functions-core-tools

```bash
npm i -g azure-functions-core-tools@4 --unsafe-perm true
```

### vs-code extensions

Azure Functions - https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions

## Check

```bash

func --version

az --version

```
