# Preparing for Your Associate Cloud Engineer Journey

## Table of Contents

- [Preparing for Your Associate Cloud Engineer Journey](#preparing-for-your-associate-cloud-engineer-journey)
  - [Table of Contents](#table-of-contents)
  - [Setting Up a Cloud Solution Environment Quizz](#setting-up-a-cloud-solution-environment-quizz)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
  - [Planning and Configuring a Cloud Solution Quizz](#planning-and-configuring-a-cloud-solution-quizz)
    - [Question 1](#question-1-1)
    - [Question 2](#question-2-1)
    - [Question 3](#question-3-1)
  - [Implementing a Cloud Solution Quizz](#implementing-a-cloud-solution-quizz)
    - [Question 1](#question-1-2)
    - [Question 2](#question-2-2)
    - [Question 3](#question-3-2)
  - [Ensuring Solution Security Quizz](#ensuring-solution-security-quizz)
    - [Question 1](#question-1-3)
    - [Question 2](#question-2-3)
    - [Question 3](#question-3-3)
  - [Configuring Access and Security Quizz](#configuring-access-and-security-quizz)
    - [Question 1](#question-1-4)
    - [Question 2](#question-2-4)
    - [Question 3](#question-3-4)

## Setting Up a Cloud Solution Environment Quizz

### Question 1

`Fiona is the billing administrator for the project associated with Cymbal Superstore’s eCommerce application. Jeffrey, the marketing department lead, wants to receive emails related to budget alerts. Jeffrey should have access to no additional billing information. What should you do?`


- Add Jeffrey and Fiona to the budget scope custom email delivery dialog.
- Use Cloud Monitoring notification channels to send Jeffrey an email alert.
- Change the budget alert default threshold rules to include Jeffrey as a recipient.
- Send alerts to a Pub/Sub topic that Jeffrey is subscribed to.

<details>
    <summary>Answer</summary>

    Use Cloud Monitoring notification channels to send Jeffrey an email alert.

    > Correct! You can set up to 5 Cloud Monitoring channels to define email recipients that will receive budget alerts

</details>

### Question 2

`Stella is a new member of a team in your company who has been put in charge of monitoring VM instances in the organization. Stella will need the required permissions to perform this role. How should you grant her those permissions?`

- Add Stella to a Google Group in your organization. Bind that group to roles/compute.viewer.

- Assign Stella compute.instances.get permissions on all of the projects she needs to monitor.

- Assign Stella a roles/compute.viewer role.

- Assign the “viewer” policy to Stella.

<details>
    <summary>Answer</summary>

    Add Stella to a Google Group in your organization. Bind that group to roles/compute.viewer.

    > Correct! Best practice is to manage role assignment by groups, not by individual users.

</details>

### Question 3

`Jane will manage objects in Cloud Storage for the Cymbal Superstore. She needs to have access to the proper permissions for every project across the organization. What should you do?`

- Assign Jane the roles/editor at the organizational level.

- Assign Jane the roles/viewer on each project and the roles/storage.objectCreator for each bucket.

- Assign Jane the roles/storage.objectCreator on every project.

- Add Jane to a group that has the roles/storage.objectAdmin role assigned at the organizational level.


<details>
    <summary>Answer</summary>

    Add Jane to a group that has the roles/storage.objectAdmin role assigned at the organizational level.

    > Correct! This would give Jane the right level of access across all projects in your company.

</details>

## Planning and Configuring a Cloud Solution Quizz

### Question 1

`Cymbal Superstore is piloting an update to its ecommerce app for the flagship store in Minneapolis, Minnesota. The app is implemented as a three-tier web service with traffic originating from the local area and resources dedicated for it in us-central1. You need to configure a secure, low-cost network load-balancing architecture for it. How do you proceed?`

- Implement a proxied external TCP/UDP network load balancer connected to the web tier as the frontend and a premium network tier ssl load balancer between the web tier and the backend.

- Configure a standard tier proxied external https load balancer connected to the web tier as a frontend and a regional internal load balancer between the web tier and the backend.

- Implement a premium tier pass-through external https load balancer connected to the web tier as the frontend and a regional internal load balancer between the web tier and backend.

- Configure a proxied SSL load balancer connected to the web tier as the frontend and a standard tier internal TCP/UDP load balancer between the web tier and the backend.

<details>
    <summary>Answer</summary>

    Configure a standard tier proxied external https load balancer connected to the web tier as a frontend and a regional internal load balancer between the web tier and the backend.

    > Correct! This is the best solution for this scenario. The standard tier external load balancer is the best choice for this scenario because it is the most cost-effective option. The regional internal load balancer is the best choice for this scenario because it is the most cost-effective option.

</details>


### Question 2

`Cymbal Superstore decides to migrate their supply chain application to Google Cloud. You need to configure specific operating system dependencies. What should you do?`

- Implement an application using code on App Engine.

- Implement an application using containers on Google Kubernetes Engine.

- Implement an application using containers on Cloud Run.

- Implement an application using virtual machines on Compute Engine.

<details>
    <summary>Answer</summary>

    Implement an application using virtual machines on Compute Engine.

    > Correct! Compute Engine gives you full control over operating system choice and configuration.

</details>

### Question 3

`Cymbal Superstore decides to pilot a cloud application for their point of sale system in their flagship store. You want to focus on code and develop your solution quickly, and you want your code to be portable. How do you proceed?`

- Package your code to a container image and post it to Cloud Run.

- Implement a deployment manifest and run kubectl apply on it in Google Kubernetes Engine.

- SSH into a Compute Engine VM and execute your code.

- Code your solution in Cloud Functions.


<details>
    <summary>Answer</summary>

    Package your code to a container image and post it to Cloud Run.

    > Correct! Cloud Run provides serverless container management. It lets you focus on code and you can deploy your solution quickly.

</details>

## Implementing a Cloud Solution Quizz

### Question 1

`Cymbal Superstore’s sales department has a medium-sized MySQL database. This database includes user-defined functions and is used internally by the marketing department at Cymbal Superstore HQ. The sales department asks you to migrate the database to Google Cloud in the most timely and economical way. What should you do?`

- Find a MySQL machine image in Cloud Marketplace and configure it to meet your needs.

- Configure a Compute Engine VM with an N2 machine type, install MySQL, and restore your data to the new instance.

- Use gcloud to implement a Compute Engine instance with an E2-standard-8 machine type, install, and configure MySQL.

- Implement a database instance using Cloud SQL, back up your local data, and restore it to the new instance.

<details>
    <summary>Answer</summary>

    Configure a Compute Engine VM with an N2 machine type, install MySQL, and restore your data to the new instance.

    > Correct! N2 is a balanced machine type, which is recommended for medium-large databases.
</details>

### Question 2

`Which Virtual Private Cloud (VPC) network type allows you to fully control IP ranges and the definition of regional subnets?`

- Default Project network

- Custom mode network

- An auto mode network converted to a custom network

- Auto mode network


<details>
    <summary>Answer</summary>

    Custom mode network

    > Correct! A custom mode network gives you control over regions that you place your subnets in and lets you specify IP ranges for them as well.

</details>

### Question 3

`You require a Cloud Storage bucket serving users in New York City. There is a need for geo-redundancy. You do not plan on using ACLs. What CLI command do you use?`

- Run a gcloud mb command specifying the name of the bucket and accepting defaults for the other mb settings.

- Run a gsutil mb command specifying a dual-region bucket and an option to turn ACL evaluation off.

- Run a gsutil mb command specifying a dual-region bucket and accepting defaults for the other mb settings.

- Run a gsutil mb command specifying a multi-regional location and an option to turn ACL evaluation off.


<details>
    <summary>Answer</summary>

    Run a gsutil mb command specifying a dual-region bucket and an option to turn ACL evaluation off.

    > NAM4 implements a dual-region bucket with us-east1 and us-central1 as the configured regions.

</details>

## Ensuring Solution Security Quizz

### Question 1

`You have a Cloud Run service with a database backend. You want to limit the number of connections to your database. What should you do?`

- Set Min instances.

- Set Concurrency settings.

- Set Max instances.

- Set CPU Utilization.


<details>
    <summary>Answer</summary>

    Set Max instances.

    > Correct! Max instances control costs, keeping you from starting too many instances by limiting your number of connections to a backing service.

</details>

### Question 2

`Cymbal Superstore has a subnetwork called mysubnet with an IP range of 10.1.2.0/24. You need to expand this subnet to include enough IP addresses for at most 2000 new users or devices. What should you do?`

- gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 20

- gcloud compute networks subnets expand-ip-range mysubnet --region us-cetnral1 --prefix-length 22

- gcloud networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

- gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21


<details>
    <summary>Answer</summary>

    gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

    > Correct! This command gives a total of 2046 addresses available and meets the requirement.

> <a href="https://www.freecodecamp.org/news/subnet-cheat-sheet-24-subnet-mask-30-26-27-29-and-other-ip-address-cidr-network-references/">Follow the link</a>

</details>


### Question 3

`Cymbal Superstore’s supply chain management system has been deployed and is working well. You are tasked with monitoring the system’s resources so you can react quickly to any problems. You want to ensure the CPU usage of each of your Compute Engine instances in us-central1 remains below 60%. You want an incident created if it exceeds this value for 5 minutes. You need to configure the proper alerting policy for this scenario. What should you do?`


- Choose resource type of VM instance and metric of CPU load, condition trigger if any time series violates, condition is below, threshold is .60, for 5 minutes.

- Choose resource type of VM instance and metric of CPU utilization, condition trigger if any time series violates, condition is above, threshold is .60 for 5 minutes.

- Choose resource type of VM instance and metric of CPU utilization, condition trigger all time series violates, condition is above, threshold is .60 for 5 minutes.

- Choose resource type of VM instance, and metric of CPU utilization, condition trigger if any time series violates, condition is below, threshold is .60 for 5 minutes.


<details>
    <summary>Answer</summary>

    Choose resource type of VM instance and metric of CPU utilization, condition trigger if any time series violates, condition is above, threshold is .60 for 5 minutes.

    > Correct! All the values of this statement match the scenario.

</details>


## Configuring Access and Security Quizz

### Question 1

`You have a custom role implemented for administration of the dev/test environment for Cymbal Superstore’s transportation management application. You are developing a pilot to use Cloud Run instead of Cloud Functions. You want to ensure your administrators have the correct access to the new resources. What should you do?`

- Delete the custom role and recreate a new custom role with required permissions

- Copy the existing role, add the new permissions to the copy, and delete the old role

- Make the change to the custom role locally and run an update on the custom role

- Create a new role with needed permissions and migrate users to it.


<details>
    <summary>Answer</summary>

    Make the change to the custom role locally and run an update on the custom role

    > Correct! There is a recommended process to update an existing custom role. You get the current policy, update it locally, and write the updated policy back into Google Cloud. The gcloud commands used in this process include the get and update policy subcommands.
</details>

### Question 2

`Which Cloud Audit log is disabled by default with a few exceptions?`

- Data Access audit logs

- System Event audit logs

- Admin Activity audit logs

- Policy Denied audit logs


<details>
    <summary>Answer</summary>

    Data Access audit logs

    > Correct! Data Access audit logs are disabled by default except for BigQuery.

</details>

### Question 3

`Which of the scenarios below is an example of a situation where you should use a service account?`

- For development environments

- For interactive analysis

- To directly access user data

- For individual GKE pods


<details>
    <summary>Answer</summary>

    For individual GKE pods

    > Correct! When configuring access for GKE, you set up dedicated service accounts for each pod. You then use workload identity to map them to dedicated Kubernetes service accounts.

</details>
