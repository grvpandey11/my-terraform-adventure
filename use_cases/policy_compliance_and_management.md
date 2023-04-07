# Policy Compliance and Management

Policies are rules that Terraform Cloud enforces on Terraform runs. You can use policies to validate that the Terraform plan complies with security rules and best practices.

You can use two policy-as-code frameworks to define fine-grained, logic-based policies: **Sentinel** and **Open Policy Agent (OPA)**. Depending on the settings, policies can act as advisory warnings or firm requirements that prevent Terraform from provisioning infrastructure.

Sentinel: You define policies with the Sentinel policy language and use imports to parse the Terraform plan, state, and configuration.

Sentinel is a policy as code framework for Terraform that enables users to define, implement, and enforce policies across their infrastructure resources. Sentinel policies can be written in a high-level language, allowing users to define complex policies that are easy to understand and manage.

Sentinel provides several features for implementing policy as code in Terraform:

1. **Custom policies:** Sentinel allows users to define custom policies for their infrastructure resources, such as access control, security, and compliance policies.

1. **Policy enforcement:** Sentinel policies can be enforced at various stages of the Terraform workflow, such as during planning, validation, and apply.

1. **Integration:** Sentinel integrates with various third-party tools, such as GitLab, to enable policy enforcement and reporting.

1. **Collaboration:** Sentinel policies can be shared and managed collaboratively, enabling teams to manage infrastructure policies more efficiently.

OPA (Open Policy Agent): You define policies with the Rego policy language.
