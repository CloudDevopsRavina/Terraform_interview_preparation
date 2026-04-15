What is Terraform?

Terraform is an open-source tool used for infrastructure as code (IaC), developed by HashiCorp.
Terraform allow us to write configuration file that describe our infrasturcture and then it automatically builds and manage resources for us.

explain Terraform workflow?
The Terraform workflow is the sequence of steps you follow to define, preview, and apply infrastructure changes using code.

🔁 Terraform Workflow (Step-by-Step)
1. Write Configuration

You define your infrastructure in .tf files using Terraform’s language.

Example: define a server, database, or network.

2. Initialize (terraform init)

This step:

Downloads required plugins (providers like Amazon Web Services)
Sets up your working directory

👉 Run:

terraform init
3. Validate (terraform validate)

Checks whether your configuration is syntactically correct.

terraform validate
4. Plan (terraform plan)

Terraform shows what changes it will make before actually doing anything.

👉 It compares:

Your code
The current infrastructure (state)
terraform plan
5. Apply (terraform apply)

Executes the plan and creates/updates infrastructure.

terraform apply
6. State Management

Terraform keeps a state file (terraform.tfstate) to track what it created, so future changes are accurate.

7. Destroy (terraform destroy)

If you want to remove everything Terraform created:

terraform destroy
🔄 Simple Flow Diagram
Write Code → Init → Validate → Plan → Apply → Manage State → (Destroy if needed)
🧠 In One Line

The Terraform workflow is:
👉 Write → Preview → Apply → Manage → Destroy

