# Networking Configuration

Proper networking ensures secure access to the storage account while enabling scalability.

## Virtual Network (VNet) Integration
Use VNets to restrict access to the storage account to specific subnets.

### Configuration Parameters
| Parameter    | Description                           | Example              |
|--------------|---------------------------------------|----------------------|
| `vnetName`   | Name of the virtual network           | `my-vnet`           |
| `subnetName` | Name of the subnet                   | `my-subnet`         |

### Subnet Recommendations
- CIDR range: `/24` or smaller to allow sufficient IP addresses.
- Network Security Group (NSG): Restrict traffic to trusted sources.

## Firewall Rules
Allow specific IP ranges to access the storage account.

### Configuration Example
```yaml
firewallRules:
  - name: AllowMyIP
    ipRange: 192.168.1.0/24