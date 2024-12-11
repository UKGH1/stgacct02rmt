# Deployment Guide

Follow these steps to deploy the Azure Storage Account Template using Backstage.

## Prerequisites
1. Ensure Backstage is configured with Azure authentication.
2. Verify Contributor access to the Azure subscription.
3. Install Terraform CLI if provisioning through Terraform.

## Deployment Steps
1. **Select the Template**
   - Navigate to the **Software Templates** section in Backstage.
   - Select the "Azure Storage Account Template."

2. **Input Parameters**
   - Fill in the required parameters, such as `storageAccountName`, `location`, and `sku`.

3. **Review and Deploy**
   - Click **Preview** to validate the parameters.
   - Click **Submit** to deploy the template.

4. **Monitor Deployment**
   - Use the Azure Portal or the Backstage dashboard to track progress.

## Post-Deployment Verification
- Validate the storage account in the Azure Portal.
- Verify the outputs (e.g., endpoint URLs) in the deployment logs.