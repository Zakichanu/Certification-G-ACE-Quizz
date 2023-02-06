# Google Cloud Fundamentals : Core Infrastructure

## Table of Contents

- [Google Cloud Fundamentals : Core Infrastructure](#google-cloud-fundamentals--core-infrastructure)
  - [Table of Contents](#table-of-contents)
  - [Introducing Google Cloud](#introducing-google-cloud)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
    - [Question 4](#question-4)
    - [Question 5](#question-5)
    - [Question 6](#question-6)
  - [Resources and Access in Google Cloud](#resources-and-access-in-google-cloud)
    - [Question 1](#question-1-1)
    - [Question 2](#question-2-1)
    - [Question 3](#question-3-1)
    - [Question 4](#question-4-1)
    - [Question 5](#question-5-1)
    - [Question 6](#question-6-1)
    - [Question 7](#question-7)
    - [Question 8](#question-8)
  - [Virtual Machines and Networks in the Cloud](#virtual-machines-and-networks-in-the-cloud)
    - [Question 1](#question-1-2)
    - [Question 2](#question-2-2)
    - [Question 3](#question-3-2)
    - [Question 4](#question-4-2)
    - [Question 5](#question-5-2)
    - [Question 6](#question-6-2)
  - [Storage in the Cloud](#storage-in-the-cloud)
    - [Question 1](#question-1-3)
    - [Question 2](#question-2-3)
    - [Question 3](#question-3-3)
    - [Question 4](#question-4-3)
    - [Question 5](#question-5-3)
    - [Question 6](#question-6-3)
  - [Containers in the Cloud](#containers-in-the-cloud)
    - [Question 1](#question-1-4)
    - [Question 2](#question-2-4)
    - [Question 3](#question-3-4)
    - [Question 4](#question-4-4)
    - [Question 5](#question-5-4)
    - [Question 6](#question-6-4)
    - [Question 7](#question-7-1)
  - [Application in the Cloud](#application-in-the-cloud)
    - [Question 1](#question-1-5)
    - [Question 2](#question-2-5)
    - [Question 3](#question-3-5)
    - [Question 4](#question-4-5)
    - [Question 5](#question-5-5)
    - [Question 6](#question-6-5)
  - [Developing and Deploying in the Cloud](#developing-and-deploying-in-the-cloud)
    - [Question 1](#question-1-6)
    - [Question 2](#question-2-6)
    - [Question 3](#question-3-6)
    - [Question 4](#question-4-6)
  - [Logging and Monitoring in the Cloud](#logging-and-monitoring-in-the-cloud)
    - [Question 1](#question-1-7)
    - [Question 2](#question-2-7)
    - [Question 3](#question-3-7)
    - [Question 4](#question-4-7)
    - [Question 5](#question-5-6)



## Introducing Google Cloud

### Question 1

`Which one of the following statements is true regarding the ability to scale cloud computing resources up and down?`

- Only storage resources are elastic.

- Cloud computing does not provide a way to scale resources.

- CPU, memory, and storage resources are elastic.

- Only CPU and memory resources are elastic.

<details>
    <summary>Answer</summary>

    CPU, memory, and storage resources are elastic.
</details>

### Question 2

`Who benefits the most from billing by the second for cloud resources, such as virtual machines?`

- Customers who create too few virtual machines to get discounts

- Customers who create virtual machines that run commercially licensed operating systems

- Customers who create and run many virtual machines

- Customers who create many virtual machines and leave them running for months

<details>
    <summary>Answer</summary>

    Customers who create and run many virtual machines
</details>

### Question 3

`Select two fundamental characteristics of cloud computing from this list.`

- All resources are open source.

- Providers always dedicate physical resources to each customer.

- Customers are required to commit to multi-year contracts.

- Resources are available from anywhere over the network.

- Customers can scale their resource use up and down.

<details>
    <summary>Answer</summary>

    - Resources are available from anywhere over the network.
    - Customers can scale their resource use up and down.

</details>

### Question 4

`What cloud computing service binds application code to libraries that give access to the infrastructure an application needs?`

- Software as a service

- Virtualized data centers

- Hybrid cloud

- Platform as a service

- Infrastructure as a service

<details>
    <summary>Answer</summary>

    Platform as a service

</details>

### Question 5

`What cloud computing service provides raw compute, storage, and network resources that are organized similarly to physical data centers?`

- Software as a service

- Database as a service

- Infrastructure as a service

- Platform as a service

<details>
    <summary>Answer</summary>

    Infrastructure as a service

</details>

### Question 6

`Why might a Google Cloud customer use resources in several zones within a region?`

- For expanding services to customers in new areas

- For getting discounts on other zones

- For improved fault tolerance

- For better performance

<details>
    <summary>Answer</summary>

    For improved fault tolerance

</details>

## Resources and Access in Google Cloud

### Question 1

`How does the resource hierarchy control how IAM policies are inherited?`

- IAM policies that are implemented by lower-level policies can override the policies defined at a higher level.

- IAM policies that are implemented higher in the resource hierarchy deny access that is granted by lower-level policies.

- IAM policies are only implemented at the project level; they cannot be amended by lower levels of the resource hierarchy.

<details>
    <summary>Answer</summary>

    IAM policies that are implemented by lower-level policies can override the policies defined at a higher level.

</details>

### Question 2

`Which statement best describes how Google Cloud resources are associated within the resource hierarchy?`

- All Google Cloud resources are associated with a folder.

- All Google Cloud resources are associated with a project.

- All Google Cloud resources are associated with an organization.

- Google Cloud resources are not associated with the resource hierarchy.

<details>
    <summary>Answer</summary>

    All Google Cloud resources are associated with a project.

</details>

### Question 3

`Select the option that displays IAM roles from general to specific.`

- Custom roles, predefined roles, basic roles

- Basic roles, predefined roles, custom roles

- Predefined roles, custom roles, basic roles

<details>
    <summary>Answer</summary>

    Basic roles, predefined roles, custom roles

</details>

### Question 4

`Consider a single hierarchy of Google Cloud resources. Which of these situations is possible? (Choose 3 responses.)`

- There is no organization node, but there is at least one folder.

- There is no organization node, and there are no folders.

- There is an organization node, and there are no folders.

- There are two or more organization nodes.

- There is an organization node, and there is at least one folder.


<details>
    <summary>Answer</summary>

    - There is an organization node, and there are no folders.
    - There is an organization node, and there is at least one folder.
    - There is no organization node, and there are no folders.

</details>

### Question 5

`What is the difference between Identity and Access Management (IAM) basic roles and IAM predefined roles?`

- Basic roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification.

- Basic roles affect all resources in a Google Cloud project. Predefined roles apply to a specific service in a project.

- Basic roles only apply to the owner of the Google Cloud project. Predefined roles can be associated with any user.

- Basic roles can only be granted to single users. Predefined roles can be associated with a group.

<details>
    <summary>Answer</summary>

    Basic roles affect all resources in a Google Cloud project. Predefined roles apply to a specific service in a project.

</details>

### Question 6

`When would you choose to have an organization node? (Select two)`

- When you want to organize resources into projects

- When you want to create folders

- When you want to centrally apply organization-wide policies

- There’s no choice; organization nodes are mandatory.

<details>
    <summary>Answer</summary>

    - When you want to centrally apply organization-wide policies
    - When you want to create folders

</details>

### Question 7

`Which way of accessing Google Cloud lets you control services through the code you write?`

- The Cloud SDK and Cloud Shell

- The Cloud Console

- APIs

- The Cloud Console mobile app

<details>
    <summary>Answer</summary>

    APIs

</details>

### Question 8

`Your company has two Google Cloud projects and you want them to share policies. What is the least error-prone way to set this up?`


- Place both projects into a folder, and define the policies on that folder.

- Duplicate all the policies from one project onto the other.

- Create shared resource policies on the common resources that are used in both projects.

- Define the new shared policy in the organization node.

<details>
    <summary>Answer</summary>

    Place both projects into a folder, and define the policies on that folder.

</details>

## Virtual Machines and Networks in the Cloud

### Question 1

`A Google Cloud customer wants to load-balance traffic among the backend VMs that form part of a multi-tier application. Which load-balancing option should this customer choose?`

- The global TCP proxy

- The global SSL proxy

- The global HTTP(S) load balancer

- The regional load balancer

- The regional internal load balancer

<details>
    <summary>Answer</summary>

    The regional internal load balancer

</details>

### Question 2

`Which interconnect option is a service level agreement (SLA) available for?`

- Carrier Peering

- Direct Peering

- Dedicated Interconnect

- Standard Network Tier

<details>
    <summary>Answer</summary>

    Dedicated Interconnect

</details>

### Question 3

`Select the true statement about Google’s VPC networks and subnets.`

- Networks are global, and subnets are zonal.

- Networks are regional, and subnets are zonal.

- Networks are global, and subnets are regional.

- Both networks and subnets are global.

<details>
    <summary>Answer</summary>

    Networks are global, and subnets are regional.
    
</details>

### Question 4

`Which statement best describes how VPC routers and firewalls work?`

- They are managed by Google in virtual machines and customers cannot modify them.
 
- They are managed by Google in virtual machines and customers can tune or deactivate them.

- They are managed by Google as a built-in feature.

- Customers provision virtual machines and run their routers and firewalls in them.

<details>
    <summary>Answer</summary>

    They are managed by Google as a built-in feature.

</details>

### Question 5

`Which term describes a secure, individual, private cloud-computing model hosted within a public cloud?`

- Domain name system (DNS)

- Content delivery network (CDN)

- Virtual private cloud (VPC)

- Virtual private network (VPN)

<details>
    <summary>Answer</summary>

    Virtual private cloud (VPC)

</details>

### Question 6

`Preemptible VMs can offer advantages over a standard Compute Engine VM. What is a reason customers choose preemptible VMs?`

- To reduce cost on premium operating systems

- To use custom machine types
 
- To improve performance

- To reduce cost

<details>
    <summary>Answer</summary>

    To reduce cost

</details>

## Storage in the Cloud

### Question 1

`Which SQL database service can scale to petabyte database sizes?`

- Cloud SQL

- Cloud Spanner

- Bigtable

- Firestore

<details>
    <summary>Answer</summary>

    Cloud Spanner

</details>

### Question 2

`Your application needs to store data with strong transactional consistency, and you want seamless scaling up. Which storage option is the best choice for your application?`

- Cloud Spanner

- Cloud SQL

- Cloud Storage

- Firestore

<details>
    <summary>Answer</summary>

    Cloud Spanner

</details>

### Question 3

`Why would a customer consider the Coldline Storage class?`

- To save money on storing infrequently accessed data

- To save money on storing frequently accessed data

- To improve security

- To use the Coldline Storage API

<details>
    <summary>Answer</summary>

    To save money on storing infrequently accessed data

</details>

### Question 4

`Which statement describes the correct Cloud Storage use case?`

- Cloud Storage provides the root file system of a Linux virtual machine.

- Cloud Storage provides durable and highly available object storage.

- Cloud Storage provides data warehousing services.

- Cloud Storage provides RDBMS (Relational Database Management System) services.

<details>
    <summary>Answer</summary>

    Cloud Storage provides durable and highly available object storage.

</details>

### Question 5

`How are Firestore and Bigtable alike? (Select two answers.)`

- They are both NoSQL databases.

- They are both highly scalable.

- They both offer SQL-like queries.

- They both have a free daily quota.

<details>
    <summary>Answer</summary>

    - They are both NoSQL databases.
    - They are both highly scalable.

</details>

### Question 6

`You manufacture devices with sensors and need to stream huge amounts of data from these devices to a storage option in the cloud. Which storage option is the best choice for your application?`

- Bigtable

- Firestore

- BigQuery

- Cloud Spanner

<details>
    <summary>Answer</summary>

    Bigtable

</details>

## Containers in the Cloud

### Question 1

`What is a Kubernetes pod?`

- A group of clusters

- A group of VMs

- A group of containers

- A group of nodes

<details>
    <summary>Answer</summary>

    A group of containers

</details>

### Question 2

`Select two reasons for using containers to deploy applications. (Choose 2 responses.)`

- It provides tight coupling between applications and operating systems.

- Migrating workloads is simpler.

- It creates consistency across development, testing, and production environments.

- Allocating resources in which to run containers is not necessary.

<details>
    <summary>Answer</summary>

    - It creates consistency across development, testing, and production environments.
    - Allocating resources in which to run containers is not necessary.

</details>

### Question 3

`How do containers access an operating system?`

- Containers use a shared base operating system stored in a shared kernel layer.

- Containers use a shared base operating system stored in a shared runtime layer.

- Each container has its own instance of an operating system.

- Containers use a shared base operating system stored in a Cloud Storage bucket.

<details>
    <summary>Answer</summary>

    Containers use a shared base operating system stored in a shared kernel layer.
</details>

### Question 4

`How do you keep your Kubernetes version updated in Google Kubernetes Engine?`

- You are required to set up a cron job to periodically check the Kubernetes version in your cluster.

- You cannot update a running cluster. You need to create a copy of the cluster with the updated Kubernetes version.

- The Google Kubernetes Engine team periodically performs automatic upgrades of your cluster to newer stable versions.

- You need to stop your cluster and manually update the Kubernetes version in your cluster.

<details>
    <summary>Answer</summary>

    The Google Kubernetes Engine team periodically performs automatic upgrades of your cluster to newer stable versions.

</details>

### Question 5

`What is a Kubernetes cluster?`

- A group of containers that provide high availability for applications.

- A group of machines where Kubernetes can schedule workloads.

- A group of pods that manage the administration of a Kubernetes application.

<details>
    <summary>Answer</summary>

    A group of machines where Kubernetes can schedule workloads.

</details>

### Question 6

`Anthos provides a rich set of tools for monitoring and maintaining the consistency of your applications across which of the following locations?`

- Applications hosted with one cloud provider only.

- Applications hosted on-premises, in the cloud, or in multiple clouds.

- Applications hosted on-premises only.

- Applications hosted with multiple cloud providers only.

<details>
    <summary>Answer</summary>

    Applications hosted on-premises, in the cloud, or in multiple clouds.

</details>

### Question 7

`Where do the resources used to build Google Kubernetes Engine clusters come from?`

- App Engine

- Cloud Storage

- Compute Engine

- Bare metal servers

<details>
    <summary>Answer</summary>

    Compute Engine

</details>


## Application in the Cloud

### Question 1

`Which statements are true about App Engine? (Select 2).`

- App Engine requires you to supply or code your own application load balancing and logging services.

- App Engine charges you based on the resources you preallocate instead of the resources you use.

- The daily billing for an App Engine application can drop to zero.

- Developers who write for App Engine do not need to code their applications in any particular way to use the service.

- App Engine manages the hardware and networking infrastructure required to run your code.

<details>
    <summary>Answer</summary>

    - The daily billing for an App Engine application can drop to zero.
    - App Engine manages the hardware and networking infrastructure required to run your code.

</details>

### Question 2

`Cloud Run can only pull images from:`

- Self-hosted registries

- GitHub

- Docker Hub

- Artifact Registry

<details>
    <summary>Answer</summary>

    Artifact Registry


</details>

### Question 3

`Select the managed compute platform that lets you run stateless containers through web requests or Pub/Sub events.`

- Cloud Endpoints

- Cloud Source Repositories

- Apigee Edge

- Cloud Run

<details>
    <summary>Answer</summary>

    Cloud Run

</details>

### Question 4

`App Engine is best suited to the development and hosting of which type of application?`

- Applications that require full control of the hardware they are running on

- Applications that require at least one instance running at all times.

- A long-running batch processing application

- A web application

<details>
    <summary>Answer</summary>

    A web application

</details>

### Question 5

`What are the advantages of using App Engine’s flexible environment instead of its standard environment? (Select 3).`

- You can install third-party binaries.

- Google provides automatic in-place security patches.

- Your application can write to the local disk.

- Your application can execute code in background threads.

- You can use SSH to connect to the virtual machines on which your application runs.

<details>
    <summary>Answer</summary>

    - You can install third-party binaries.
    - Your application can write to the local disk.
    - You can use SSH to connect to the virtual machines on which your application runs.

</details>

### Question 6

`Which Google Cloud service should you choose to perform business analytics and billing on a customer-facing API?`

- Compute Engine API

- Cloud Run API

- Cloud Endpoints

- Apigee Edge

<details>
    <summary>Answer</summary>

    Apigee Edge

</details>

## Developing and Deploying in the Cloud

### Question 1

`Why would a developer choose to store source code in Cloud Source Repositories? (Select 2)`

- To reduce work

- To keep code private to a Google Cloud project

- To have total control over the hosting infrastructure

- It is the only way to access your source code in a repository.


<details>
    <summary>Answer</summary>

    - To keep code private to a Google Cloud project
    - To reduce work

</details>

### Question 2

`Why might a Google Cloud customer choose to use Terraform?`

- Terraform can be used as an infrastructure management system for Google Cloud resources.

- Terraform can be used as an infrastructure management system for Kubernetes pods.

- Terraform can be used as a version-control system for your Google Cloud infrastructure layout.

- Terraform can be used to enforce maximum resource utilization and spending limits on your Google Cloud resources.

<details>
    <summary>Answer</summary>

    Terraform can be used as an infrastructure management system for Google Cloud resources.

</details>

### Question 3

`Why might a Google Cloud customer choose to use Cloud Functions?`

- Their application contains event-driven code that they don't want to provision compute resources for.

- Cloud Functions is a free service for hosting compute operations.

- Cloud Functions is the primary way to run Node.js applications in Google Cloud.

- Their application has a legacy monolithic structure that they want to separate into microservices.

<details>
    <summary>Answer</summary>

    Their application contains event-driven code that they don't want to provision compute resources for.

</details>

### Question 4

`Select the advantage of putting the event-driven components of your application into Cloud Functions.`

- Cloud Functions handles scaling these components seamlessly.

- In Cloud Functions, code can be written in C# or C++.

- In Cloud Functions, processing is always free of charge.

- Cloud Functions eliminates the need to use a separate service to trigger application events.

<details>
    <summary>Answer</summary>

    Cloud Functions handles scaling these components seamlessly.

</details>

## Logging and Monitoring in the Cloud

### Question 1

`Which option describes a commitment made to your customers that your systems and applications will have only a certain amount of “downtime”?`

- Service level indicator

- Service level agreement

- Service level objective

- Key performance indicator

<details>
    <summary>Answer</summary>

    Service level agreement

</details>

### Question 2

`You want to create alerts on your Google Cloud resources, such as when health checks fail. Which is the best Google Cloud product to use?`

- Error Reporting

- Cloud Monitoring

- Cloud Trace

- Cloud Functions

<details>
    <summary>Answer</summary>

    Cloud Monitoring

</details>

### Question 3

`Select the two correct statements about Cloud Logging.`

- Cloud Logging lets you define metrics based on your logs.

- Cloud Logging lets you view logs from your applications and filter and search on them.

- Cloud Logging requires you to store your logs in BigQuery or Cloud Storage.

- Cloud Logging lets you define uptime checks.

- Cloud Logging requires the use of a third-party monitoring agent.

<details>
    <summary>Answer</summary>

    - Cloud Logging lets you define metrics based on your logs.
    - Cloud Logging lets you view logs from your applications and filter and search on them.
</details>

### Question 4

`Which definition best describes a service level indicator (SLI)?`

- A percentage goal of a measure you intend your service to achieve

- A time-bound measurable attribute of a service

- A contract with your customers regarding service performance

- A key performance indicator; for example, clicks per session or customer signups

<details>
    <summary>Answer</summary>

    A time-bound measurable attribute of a service

</details>

### Question 5

`There are “Four Golden Signals” that measure a system’s performance and reliability. What are they?`

- Latency, traffic, saturation, errors

- Availability, durability, scalability, resiliency

- Get, post, put, delete

- KPIs, SLIs, SLOs, SLAs

<details>
    <summary>Answer</summary>

    Latency, traffic, saturation, errors

</details>
