# VM Fleet Commander Project
## Terraform files location

Setup Terraform files for use with my Azure tenant


### Tasks include:

1. Initial Setup:

Ensure you have Azure CLI installed with Terraform support.
Set up a version control system (e.g., Git) to track changes in your Terraform templates.

2. Terraform Basics:

Start with learning the basics of Terraform syntax and structure.

3. Resource Group and Naming Conventions:

Define a Terraform file to create an Azure Resource Group for your VMs.
Implement naming conventions.

4. Virtual Machine Provisioning:

Create a Terraform module for deploying Azure VMs, allowing for parameterized input like VM size, name, and region.

5. Network Resources:

Design Terraform files for associated networking resources like Virtual Network, Subnet, and Network Security Groups.
Ensure your VMs are provisioned within the designated VNet and have the necessary security rules applied.

6. Files and Validation:

Create separate files for Terraform, allowing for different environment deployments (e.g., dev, test, prod).
Use the Azure CLI to validate your Terraform files before deploying, catching any structural errors.

7. Deployment:

Use the Azure CLI to deploy your Terraform templates, creating all designated resources.
Test the reproducibility by deploying the same infrastructure to a different region or resource group.

8. Maintenance & Updates:

Make changes to your Terraform files (e.g., VM size or count) and redeploy. Observe how Azure handles updates and maintains state.
Regularly pull updates to the Terraform language and Azure CLI to stay updated with new features and improvements.

9. Documentation & Cleanup:

Document your Terraform modules, their purpose, and any parameters required.