# How does Terraform work?

Terraform is a tool that uses a declarative language to define and manage infrastructure resources.

Terraform creates and manages resources on cloud platforms and other services through their application programming interfaces (APIs). Providers enable Terraform to work with virtually any platform or service with an accessible API.

![How terraform works](../assets/terraform_work.png)

A general overview of how Terraform works:

1. **Define infrastructure resources:** Terraform configuration files describe the infrastructure resources to be provisioned. These configuration files use a simple, declarative syntax that defines the desired state of the infrastructure.

1. **Initialize Terraform:** Before Terraform can manage infrastructure resources, it needs to be initialized. During initialization, Terraform downloads the required provider plugins and sets up the environment to manage resources.

1. **Plan infrastructure changes:** After initialization, Terraform can create a plan for changes to infrastructure resources. This plan shows what actions Terraform will take to bring the infrastructure resources to the desired state.

1. **Apply changes:** Once a plan is reviewed and approved, Terraform applies the changes to the infrastructure resources. Terraform makes changes by communicating with the provider APIs to create, modify, or delete resources as necessary.

1. **Store state:** As Terraform makes changes to infrastructure resources, it tracks the current state of those resources in a state file. The state file is used to track the current state of infrastructure resources and to plan future changes.

1. **Destroy infrastructure:** When infrastructure resources are no longer needed, Terraform can destroy them. Terraform will use the state file to identify and delete the resources.

Terraform enables infrastructure as code, which means that changes to infrastructure resources can be made through code, rather than manually through a user interface. This approach allows for version control, collaboration, and automation, and can make infrastructure management more efficient and scalable.

Terraform Workflow:

![Terraform Workflow](../assets/terraform_workflow.png)

### Using IaC with Terraform offers several benefits:

1. **Version control:** Infrastructure changes are managed through code, so changes can be tracked and managed through version control systems like Git.

1. **Reusability:** Infrastructure modules can be created and reused across different projects and teams, saving time and effort.

1. **Consistency:** Infrastructure resources can be created and managed consistently across different environments, reducing the likelihood of errors and inconsistencies.

1. **Automation:** Infrastructure changes can be automated through continuous integration and delivery pipelines, making it easier to manage complex infrastructure environments.

Overall, Infrastructure as Code with Terraform enables teams to manage infrastructure resources more efficiently, reliably, and collaboratively, improving the overall agility and scalability of infrastructure management.