1. What is Azure DevOps, and how does it support the DevOps lifecycle?
Azure DevOps is a comprehensive set of development tools and services provided by
Microsoft. It facilitates collaboration among development, testing, and operations teams by
offering features like version control, build automation, release management, and more.
This integrated platform streamlines the entire DevOps lifecycle, from planning and coding
to building, testing, and deployment.

2. Explain the key components of Azure DevOps and their roles.
Azure DevOps consists of several essential components: Azure Repos for version control,
Azure Pipelines for continuous integration and continuous deployment (CI/CD), Azure
Boards for work tracking, and Azure Test Plans for testing. Each component plays a vital
role in supporting different aspects of the software development lifecycle.

3. What is Continuous Integration, and how does Azure Pipelines enable it?
Continuous Integration (CI) is the practice of automatically integrating code changes from
multiple contributors into a shared repository. Azure Pipelines automates this process by
allowing developers to define build pipelines. These pipelines automatically build, test, and
validate code changes, ensuring that the application remains functional and error-free with
each update.

4. How does Azure DevOps ensure code quality through code reviews?
Azure Repos provides a robust pull request mechanism for code reviews. Developers can
create pull requests to propose changes, and team members can review the code, leave
comments, and suggest modifications. This collaborative approach helps maintain code
quality and encourages knowledge sharing within the development team.

5. What is the significance of Release Management in Azure DevOps?
Release Management in Azure DevOps automates the deployment of applications across
different environments. It ensures consistency and reliability in the deployment process,
allowing teams to deploy their applications with confidence. This feature helps in achieving
continuous delivery by automating the release process.

6. How can you use Azure Boards for project management in Agile environments?
Azure Boards provides a flexible and powerful platform for managing work in an Agile
manner. It supports various Agile methodologies, including Scrum and Kanban. With
features such as backlogs, sprint planning, and task boards, Azure Boards enables teams
to plan, track, and manage their work efficiently throughout the development lifecycle.

7. Explain the concept of YAML pipelines in Azure DevOps.

YAML pipelines in Azure DevOps allow developers to define CI/CD pipelines as code using
a YAML file. This provides a version-controlled, human-readable representation of the build
and release processes. YAML pipelines enhance reproducibility, versioning, and
collaboration in the CI/CD setup.

8. How does Azure DevOps enhance collaboration between development and
operations teams?
Azure DevOps promotes collaboration by bringing development and operations teams
together in a unified platform. It provides visibility into the entire application lifecycle, from
planning to deployment and monitoring. This shared environment fosters communication,
reduces silos, and enables both teams to work collaboratively towards common goals.

9. What are the benefits of using Azure Repos for version control?
Azure Repos provides Git for version control. It offers a centralized repository for source
code, enabling collaborative development. The benefits include code versioning, branch
management, code history tracking, and seamless integration with other Azure DevOps
services.

10. How does Azure DevOps support the concept of DevSecOps?
Azure DevOps integrates security practices into the DevOps workflow, promoting the
concept of DevSecOps. It includes features such as static code analysis, vulnerability
scanning, and integration with security tools like Github advanced security. By addressing
security concerns early in the development process, Azure DevOps helps build more
secure and resilient applications.

11. How can you manage secrets and sensitive information in Azure DevOps?
Azure DevOps provides a secure way to manage secrets and sensitive information through
Azure Key Vault integration. Developers can store and retrieve sensitive information such
as API keys, connection strings, and certificates securely, reducing the risk of exposure
and unauthorized access. We can integrate azure Key Vault into azure devops pipeline
using the variable groups in libraries.

12. What is the significance of Azure DevOps Service Connections?
Azure DevOps Service Connections allow integration with external services and platforms,
such as Azure, GitHub, or Docker Hub. These connections streamline the deployment
process by providing a secure and centralized way to access external resources and
services required during the CI/CD pipeline.

13. What is the branching strategy you have followed?

We have multiple branching strategies based on the project requirements. For some we
follow Dev, QA and Prod and for some projects we follow Dev Staging QA Pre-Prod and
Prod.

GIT

1.git init
Initializes a new Git repository in the current directory.

2.git clone <repository-url>
Clones a remote repository to your local machine.

3.git add <file>
Adds a file to the staging area.

4.git add .
Adds all modified files in the current directory and subdirectories to the staging area.

5.git commit -m "message"
Commits the changes in the staging area with a descriptive message.

6.git status
Shows the status of changes in your working directory and staging area.

7.git log
Displays the commit history for the current branch.

8.git diff
Shows the differences between the working directory and the staging area.

9.git diff <file>
Shows the differences in a specific file.

10.git reset
Resets the staging area to the last commit (but keeps changes in the working directory).

11.git branch
Lists all branches in the repository.

12.git branch <branch-name>
Creates a new branch.

13.git checkout <branch-name>
Switches to the specified branch.

14.git checkout -b <branch-name>
Creates a new branch and switches to it.

15.git merge <branch-name>
Merges changes from the specified branch into the current branch.

16.git rebase <branch-name>
Reapplies commits on top of another branch.

17.git branch -d <branch-name>
Deletes the specified branch.

18. git stash
Save the changes without committing so that we can checkout to another branch.

**In Some interview questions-**

Difference between merge and rebase
Difference between pull and fetch

**PORTS and their use cases**

SSH (Secure Shell)
Port: 22
Purpose: Used for secure remote login and command execution on Linux servers.
Use Case: Admin access to servers, deploying code, configuration management.
Example Tool: ssh, scp, rsync.

HTTP (Hypertext Transfer Protocol)
Port: 80
Purpose: Used by web servers to serve unencrypted HTTP traffic.
Use Case: Web applications, load balancing, reverse proxy setup.
Example Tool: nginx, apache2.

HTTPS (Hypertext Transfer Protocol Secure)
Port: 443
Purpose: Encrypted web traffic, used for secure communications.
Use Case: Hosting secure web applications, SSL/TLS termination.
Example Tool: nginx, apache2, letsencrypt.

FTP (File Transfer Protocol)
Port: 21
Purpose: Used for transferring files between servers.
Use Case: File transfer between systems (though often replaced by SFTP for security
reasons).
Example Tool: vsftpd, proftpd.

SFTP (SSH File Transfer Protocol)
Port: 22 (Same as SSH)
Purpose: Secure file transfer using SSH.
Use Case: Secure file uploads/downloads to remote systems.

DNS (Domain Name System)
Port: 53
Purpose: Resolves domain names to IP addresses.
Use Case: Networking, troubleshooting, service discovery.
Example Tool: bind9, dnsmasq, systemd-resolved.

MySQL / MariaDB
Port: 3306
Purpose: Default port for MySQL and MariaDB databases.
Use Case: Database management, application backends.
Example Tool: mysql, mariadb.
PostgreSQL
Port: 5432
Purpose: Default port for PostgreSQL databases.
Use Case: Application backends, data storage.
Example Tool: postgresql.

Redis
Port: 6379
Purpose: Default port for Redis in-memory data store.
Use Case: Caching, message brokering, session management.
Example Tool: redis-server.

MongoDB
Port: 27017
Purpose: Default port for MongoDB NoSQL database.
Use Case: NoSQL data storage.
Example Tool: mongod.

Jenkins
Port: 8080
Purpose: Default port for Jenkins CI/CD server.
Use Case: Continuous integration and deployment.
Example Tool: jenkins.

Docker
Port: 2375 (unencrypted), 2376 (encrypted)
Purpose: Default port for Docker daemon's REST API.
Use Case: Docker container orchestration, remote management.
Example Tool: docker, docker-compose.

Kubernetes API Server
Port: 6443
Purpose: Default port for the Kubernetes API server.
Use Case: Kubernetes cluster management, service discovery.
Example Tool: kubectl, helm.

ElasticSearch
Port: 9200 (HTTP), 9300 (Internal communication)
Purpose: Default port for Elasticsearch REST API and cluster communication.
Use Case: Full-text search, log aggregation.
Example Tool: elasticsearch.

RabbitMQ
Port: 5672
Purpose: Default AMQP (Advanced Message Queuing Protocol) port.
Use Case: Messaging queues, event-driven architectures.
Example Tool: rabbitmq.

**General scenario based questions**

1.Explain YAML pipeline structure.
Triggers section- specify the triggers based on branches or none. Triggers allow us to
initiate the build automatically after a developer pushes the changes which is called
continuous integration.
Pool- in this we specify the pool information whether to use a Microsoft hosted agent or a
Self-hosted agent.
Stages- specify the stages the build stage deploy stage
Jobs- we specify the jobs which contain the different tasks for building and deploying
operations.

2. Difference between Microsoft Hosted and self-Hosted agents.
MS hosted agents are hosted in MS cloud and are fully managed by MS(Microsoft) and
self-hosted agents are the ones we host on our machines or VMs. Self hosted are mainly
used where there are specific dependencies needed for the building of the code and also if
there are network restrictions.

3. How can we improve security for the pipelines.
We can increase security for the pipelines by configuring approvals for the stages and
configuring branch policies in azure devops and we can set build validations so that
incorrect changes are not merged into the code.

4.How would you manage permissions for a team working on an Azure DevOps project?
Use Project-level Permissions:Assign roles like Contributor, Reader, or Project
Administrator.
Use Area Paths: Restrict access to work items by setting permissions on specific area
paths.
Use Repository Policies: Control who can push, merge, and approve pull requests.
For sensitive pipelines, use Environment Approvals to require manual approvals or
automated checks.
Audit permissions regularly and remove unnecessary access.

5.What would you do if a pipeline deployment to production fails due to insufficient
permissions?
Identify the Issue: Check logs to find where the permissions issue occurred (e.g., accessing
Key Vault, deploying resources).
Verify Service Connections: Ensure the pipeline's service connection (e.g., Service
Principal) has the required role (e.g., Contributor, Key Vault Reader).
Fix Role Assignment: Update permissions in the Azure portal or using CLI commands:

az role assignment create --assignee <service-principal-id> --role <role> --scope <resource>
Test Access: Validate the deployment after fixing permissions.
Implement Pre-Deployment Validation: Add pipeline tasks to validate access to resources
before deployment.

6.Describe how you would set up a CI/CD pipeline for a .NET application in Azure DevOps.
Create a Repository: Host your .NET code in Azure Repos (Git or TFVC).
Set Up Build Pipeline (CI): Use the tasks such as .net restore VSbuild task for building the
code.
Set Up Release Pipeline (CD): Use environments (Dev, QA, Prod) and deploy stages.
For IIS, use a task like Azure App Service Deploy or FTP upload.
Integrate approvals before deploying to higher environments.
Automation:
Trigger CI on code commits.
Trigger CD when a build artifact is ready.
Validation: Add testing steps (unit, integration).
Monitor deployments with Azure Monitor or Application Insights.

TERRAFORM

1. What is Terraform?
Terraform is an open-source infrastructure as code (IaC) tool developed by HashiCorp that
allows users to define and provision data center infrastructure using a high-level
configuration language called HCL (HashiCorp Configuration Language) or JSON.

2. What are the main features of Terraform?
Terraform's main features include Infrastructure as Code (IaC), execution plans, resource
graphs, change automation, and state management.

3. What is the difference between Terraform and other IaC tools like Ansible, Puppet, and
Chef?
Terraform focuses on infrastructure provisioning, is declarative, and uses HCL. Tools like
Ansible, Puppet, and Chef focus on configuration management and are procedural.

4. What is a provider in Terraform?
A provider is a plugin that Terraform uses to manage an external API. Providers define the
resources and data sources available.

5. How does Terraform manage dependencies?
Terraform uses a dependency graph to manage dependencies between resources. It

automatically understands the order of operations needed based on resource
dependencies.

6. What is a state file in Terraform?
A state file is a file that Terraform uses to keep track of the current state of the
infrastructure. It maps the resources defined in the configuration to the real-world
resources.

7. Why is it important to manage the state file in Terraform?
Managing the state file is crucial because it ensures consistency between the
infrastructure's real state and the configuration. It also enables features like change
detection and planning.

8. How can you secure the state file in Terraform?
State files can be secured by storing them in remote backends with proper access controls
and encryption, such as AWS S3 with server-side encryption and access control policies.

9. What are modules in Terraform?
Modules are reusable packages of Terraform configurations that can be shared and
composed to manage resources efficiently.

10. What is the purpose of the terraform init command?
terraform init initializes a working directory containing Terraform configuration files,
downloads the necessary provider plugins, and prepares the environment.

11. What does the terraform plan command do?
terraform plan creates an execution plan, showing what actions Terraform will take to
achieve the desired state defined in the configuration.

12. What is the terraform apply command used for?
terraform apply applies the changes required to reach the desired state of the
configuration. It executes the plan created by terraform plan.


13. What is the purpose of the terraform destroy command?
terraform destroy is used to destroy the infrastructure managed by Terraform. It removes
all the resources defined in the configuration.

14. How do you define and use variables in Terraform?
Variables in Terraform are defined using the variable block and can be used by referring to
them with var.<variable_name>.

15. What are output values in Terraform and how are they used?
Output values are used to extract information from the resources and make it accessible
after the apply phase. They can be used to output resource attributes.

16. How do you manage different environments (e.g., dev, prod) in Terraform?
Different environments can be managed using workspaces or separate directories with
different variable files and state files.

17. What is remote state and how do you configure it in Terraform?
Remote state allows Terraform to store the state file in a remote storage backend, enabling
team collaboration and secure storage.

18. How do you import existing resources into Terraform?
Existing resources can be imported using the terraform import command, which maps the
existing resource to a Terraform resource in the state file.

19. What are data sources in Terraform?
Data sources allow Terraform to fetch data from existing infrastructure or services to use
in resource definitions.

20. What are provisioners in Terraform?
Provisioners are used to execute scripts or commands on a local or remote machine as
part of the resource lifecycle.

21. How do you handle secrets in Terraform?
Secrets can be managed using environment variables, secure secret management services
(e.g., Azure Key Vault), or Terraform's sensitive attribute.

22. What is a backend in Terraform?
A backend in Terraform defines where and how state is loaded and stored. It can be local
or remote (e.g., S3, Consul, etc.).
