# Infrastructure

![Hard](https://img.shields.io/badge/Difficulty-◆%20Hard-grey?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you'll learn how to use cloud providers to orchestrate computing resources and create a scalable and resilient platform for your product.

<img width="1440" alt="Top-down view of shipping containers" src="https://user-images.githubusercontent.com/894178/138357403-29c2f0ab-0ade-4f72-ab1e-6a29932f8eba.png">

## Topics

<details open>
   <summary><b>Cloud Providers</b></summary><br/>

   With this topic, you'll learn about cloud computing and the wide range of services an application can use with this topic.
   
   #### Learning Outcomes
   * Describe Infrastructure as a Service (IaaS)
   * Describe Platform as a Service (PaaS)
   * Describe Software as a Service (SaaS)
   * List some typical cloud providers
   * List some commonly used services from cloud providers
   * Compare using cloud computing with on-premise computing

   #### Resources
   * [A Cloud Guru `Resource`](https://acloudguru.com/)
   * [AWS `Tool`](https://aws.amazon.com/)
   * [Azure `Tool`](https://azure.microsoft.com/en-us/)
   * [DigitalOcean `Tool`](https://www.digitalocean.com/)
   * [Google Cloud Platform `Tool`](https://cloud.google.com/)
   * [Kubernetes Explained in 100 Seconds `Video`](https://www.youtube.com/watch?v=PziYflu8cB8)
   * [Kubernetes starter kit `Tutorial`](https://github.com/digitalocean/Kubernetes-Starter-Kit-Developers)
   * [Top 50+ AWS Services Explained in 10 Minutes `Video`](https://www.youtube.com/watch?v=JIbIYCM48to)
   * [What is Kubernetes? `Video Series`](https://www.youtube.com/watch?v=cC46cg5FFAM&list=PLIivdWyY5sqLmnGdKSdQIXq2sd_1bWSnx)

   #### Exercises
   * [Virtual Machine Provisioning](../exercises/infrastructure/virtual-machine-provisioning.md)
</details>

----

<details open>
   <summary><b>Infrastructure as Code</b></summary><br/>

   With this topic, you'll learn how to provision cloud services quickly and reliably using infrastructure as code techniques.
   
   #### Learning Outcomes
   * Describe Infrastructure as Code
   * Use Terraform to provision infrastructure with a cloud provider
   * Explain some of the benefits of infrastructure as code compared to manually provisioning infrastructure
   
   #### Resources
   * [AWS CloudFormation `Tool`](https://aws.amazon.com/cloudformation/)
   * [Infrastructure as Code with Terraform `Tutorial`](https://learn.hashicorp.com/tutorials/terraform/infrastructure-as-code?in=terraform/aws-get-started)
   * [Terraform `Tool`](https://www.terraform.io/)
   * [Terraform in 100 Seconds `Video`](https://www.youtube.com/watch?v=tomUWcQ0P3k)

   #### Exercises
   * [Terraform the Cloud](../exercises/infrastructure/terraform-the-cloud.md)
</details>

----

<details open>
   <summary><b>Backing Services</b></summary><br/>

   With this topic, you'll learn how to work with the attached services required for an application to run.
   
   #### Learning Outcomes
   * Describe a backing service
   * Explain how you might create resilient backing services
   * Theorize how you might monitor backing services to ensure they are up
   
   #### Resources
   * [12 Factor App: Backing Services `Resource`](https://12factor.net/backing-services)

   #### Exercises
   * [Mapping Backing Services](../exercises/infrastructure/mapping-backing-services.md)
   * Setup Sentry.io and integrate it into your application (will your app go down if Sentry goes down?)
   * Setup a PostgreSQL database and integrate it into your application (will your app go down if the database goes down?)
</details>

----

<details open>
   <summary><b>Managing Multiple Environments</b></summary><br/>

   With this topic, you'll learn how to manage multiple environments such as dev, staging, and production for an application.
   
   #### Learning Outcomes
   * Describe what an environment is
   * Explain the purpose of development, staging, and production environments
   
   #### Resources
   * [Terraform Workspaces `Tool`](https://www.terraform.io/docs/cloud/workspaces/)
   * [12 Factor App: Dev/Prod Parity `Resource`](https://12factor.net/dev-prod-parity)

   #### Exercises
   * [Cloud Environment Replication](../exercises/infrastructure/cloud-environment-replication.md)
</details>

----

<details open>
   <summary><b>Working with Cloud Engineers</b></summary><br/>

   With this topic, you'll learn about the role of a cloud engineer and how to work with them on your team effectively.
   
   #### Learning Outcomes
   * Describe the role of a cloud engineer
   * Identify what you need from a cloud engineer to complete software engineering tasks
   * Explain how you might collaborate with a cloud engineer to design and provision infrastructure for an application

   #### Resources
   * [What is a Cloud Engineer? `Video`](https://www.youtube.com/watch?v=NBHc6tatwvo)
   * [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win `Book ($)`](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592)
   * [The Unicorn Project: A Novel about Developers, Digital Disruption, and Thriving in the Age of Data `Book ($)`](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving-ebook/dp/B07QT9QR41)

   #### Exercises
   * [Infrastructure Inventory](../exercises/infrastructure/infrastructure-inventory.md)
   * Pair with a Cloud Engineer on your team and solve an infrastructure problem with them!
</details>
