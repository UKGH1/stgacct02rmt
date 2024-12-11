# Troubleshooting

This guide helps resolve common issues during deployment.

## Common Errors and Solutions

### 1. Invalid Storage Account Name
**Error Message**: `Storage account name must be between 3 and 24 characters and use only lowercase letters and numbers.`  
**Solution**: Ensure the name meets Azure's naming conventions.

### 2. Missing Permissions
**Error Message**: `The client does not have authorization to perform action on this resource.`  
**Solution**: Verify that your Azure account has Contributor access to the subscription.

### 3. Networking Errors
**Error Message**: `Access denied from this IP address.`  
**Solution**: Check firewall rules and ensure your IP is added.

## Debugging Tips
- Use the Backstage logs to trace issues.
- Enable diagnostic logs for the storage account in Azure for detailed error information.

## Contact Support
For unresolved issues, contact your system administrator or Azure support team.