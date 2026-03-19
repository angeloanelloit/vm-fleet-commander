# VM Fleet Commander Project
## Details

This repo will be used to create an Azure VM fleet for the angeloanelloitgmail.onmicrosoft.com tenant.
This project is taken from the Cloud Engineering Projects provided by madebygps.  
Link:  https://github.com/madebygps/cloud-engineering-projects/blob/main/az-104/vmfleetcommander.md


### Tasks include:

1. Initial Setup:

Ensure you have Azure CLI installed with Bicep support.
Set up a version control system (e.g., Git) to track changes in your Bicep and ARM templates.

2. Bicep Basics:

Start with learning the basics of Bicep syntax and structure.
Convert a basic ARM template (like one that deploys a single VM) to Bicep to understand the differences.

3. Resource Group and Naming Conventions:

Define a Bicep file to create an Azure Resource Group for your VMs.
Implement naming conventions for your resources using Bicep's string functions.

4. Virtual Machine Provisioning:

Create a Bicep module for deploying Azure VMs, allowing for parameterized input like VM size, name, and region.
Use loops in Bicep to deploy multiple VM instances based on a specified count.

5. Network Resources:

Design Bicep modules for associated networking resources like Virtual Network, Subnet, and Network Security Groups.
Ensure your VMs are provisioned within the designated VNet and have the necessary security rules applied.

6. Parameter Files and Validation:

Create separate parameter files for your Bicep templates, allowing for different environment deployments (e.g., dev, test, prod).
Use the Azure CLI to validate your Bicep files before deploying, catching any structural errors.

7. Deployment:

Use the Azure CLI to deploy your Bicep templates, creating all designated resources.
Test the reproducibility by deploying the same infrastructure to a different region or resource group.

8. Maintenance & Updates:

Make changes to your Bicep files (e.g., VM size or count) and redeploy. Observe how Azure handles updates and maintains state.
Regularly pull updates to the Bicep language and Azure CLI to stay updated with new features and improvements.

9. Documentation & Cleanup:

Document your Bicep modules, their purpose, and any parameters required.
After testing, ensure to delete resources or resource groups to avoid incurring unnecessary costs.