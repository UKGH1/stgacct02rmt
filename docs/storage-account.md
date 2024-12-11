# Storage Account Configuration

Azure Storage Accounts provide scalable and durable cloud storage. This template supports General-purpose v2 storage accounts with customizable redundancy and performance options.

## Supported SKUs
- **Standard_LRS**: Locally redundant storage for cost-effective durability.
- **Standard_GRS**: Geo-redundant storage for disaster recovery.
- **Premium_LRS**: High-performance SSD-backed storage for low-latency scenarios.

## Access Tiers
- **Hot Tier**: Optimized for frequently accessed data.
- **Cool Tier**: Optimized for infrequently accessed data, offering lower storage costs.

## Configuration Parameters
| Parameter        | Description                          | Example             |
|------------------|--------------------------------------|---------------------|
| `storageAccountName` | Unique name for the storage account | `myuniqueacct123`  |
| `resourceGroupName`  | Azure resource group name          | `my-resource-group` |
| `location`          | Azure region                      | `eastus`            |

## Security Features
- Enable HTTPS-only traffic.
- Configure Azure AD for identity-based access.
- Optionally, enable private endpoints for secure access.
