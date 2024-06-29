**Azure Resources**

Azure resources are the building blocks of your cloud infrastructure in Microsoft Azure. These resources can be virtual machines, databases, storage accounts, or any other service offered by Azure. Each resource is a manageable item in Azure, and they are provisioned and managed individually.

**Resource Groups in Azure**

- A **Resource Group** in Azure is a logical container for resources that share the same lifecycle, permissions, and policies. It helps you organize and manage related Azure resources efficiently. Resources within a group can be deployed, updated, and deleted together as a single management unit.

- **Key Points about Resource Groups:**

	- **Lifecycle Management:** Resources within a group can be managed collectively, making it easy to handle deployments, updates, and deletions.
	- **Resource Organization:** Grouping resources based on projects, environments, or applications helps keep your Azure environment well-organized.
	- **Role-Based Access Control (RBAC):** Permissions and access control are applied at the resource group level, allowing you to manage who can access and modify resources within a group.

**Azure Resource Manager (ARM) Overview**

- **Azure Resource Manager (ARM)** is the deployment and management service for Azure. It provides a consistent management layer that enables you to deploy resources with declarative templates. ARM templates describe the resources you need and their configurations, allowing you to deploy and update resources in a predictable manner.

- **Key Features of Azure Resource Manager:**

	- **Template-Based Deployment:** ARM uses JSON templates to define the infrastructure and configuration of your Azure resources. This enables repeatable and consistent deployments.
	- **Dependency Management:** ARM automatically handles dependencies between resources, ensuring they are deployed in the correct order.
	- **Rollback and Roll-forward:** In case of deployment failures, ARM can automatically roll back changes to maintain the desired state, or roll forward to the last known good state.
	- **Tagging and Categorization:** You can use tags to label and categorize resources, making it easier to manage and organize your Azure environment.

- **Important Terminology**

	- **Resource:** A manageable item that is available through Azure. Examples include virtual machines, storage accounts, web apps, databases, and virtual networks. Resource groups, subscriptions, management groups, and tags are also considered resources.
	- **Resource Group:** A container that holds related resources for an Azure solution. The resource group includes those resources that you want to manage as a group. You decide which resources belong in a resource group based on what makes the most sense for your organization.
	- **Resource Provider:** A service that supplies Azure resources. For example, a common resource provider is Microsoft.Compute, which supplies the virtual machine resource. Microsoft.Storage is another common resource provider.
	- **Declarative Syntax:** Syntax that lets you state "Here's what I intend to create" without having to write the sequence of programming commands to create it. ARM templates and Bicep files are examples of declarative syntax. In those files, you define the properties for the infrastructure to deploy to Azure.
	- **ARM Template:** A JavaScript Object Notation (JSON) file that defines one or more resources to deploy to a resource group, subscription, management group, or tenant. The template can be used to deploy the resources consistently and repeatedly.
	- **Bicep File:** A file for declaratively deploying Azure resources. Bicep is a language that was designed to provide the best authoring experience for infrastructure as code solutions in Azure.
	- **Extension Resource:** A resource that adds to another resource's capabilities. For example, a role assignment is an extension resource. You apply a role assignment to any other resource to specify access.
