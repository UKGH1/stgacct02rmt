# Template Overview

The **Azure Storage Account Template** helps developers create a secure and scalable storage account in Azure using Backstage. This template supports parameterized configurations to meet diverse application needs.

## Template Structure

### 1. **Input Parameters**
The template accepts the following parameters for customization:
- `storageAccountName`: Unique name for the storage account.
- `resourceGroupName`: Azure resource group for the storage account.
- `location`: Azure region for deployment (e.g., `eastus`).
- `sku`: Storage SKU (e.g., `Standard_LRS`, `Standard_GRS`, `Premium_LRS`).
- `accessTier`: Storage access tier (`Hot` or `Cool`).
- `networking`: Optional VNet and firewall configurations.

### 2. **Resources**
The template provisions:
- Azure Storage Account
- Networking configurations (subnets, firewalls, private endpoints)

### 3. **Outputs**
After deployment, the following outputs are available:
- Storage account name
- Primary endpoint URL
- Resource group name

## Customization Options
Modify the `mkdocs.yaml` to add descriptions for additional resources if necessary.