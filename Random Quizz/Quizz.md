# Random Questions

## Question 1

`Your organization plans to migrate its financial transaction monitoring application to Google Cloud. Auditors need to view the data and run reports in BigQuery, but they are not allowed to perform transactions in the application. You are leading the migration and want the simplest solution that will require the least amount of maintenance. What should you do?`

A. Assign roles/bigquery.dataViewer to the individual auditors.

B.  Create a group for auditors and assign roles/viewer to them.

C. Create a group for auditors, and assign roles/bigquery.dataViewer to them.

D. Assign a custom role to each auditor that allows view-only access to BigQuery.

<details>
    <summary>Answer</summary>

    C. Create a group for auditors, and assign roles/bigquery.dataViewer to them.

</details>

## Question 2

`You are managing your company’s first Google Cloud project. Project leads, developers, and internal testers will participate in the project, which includes sensitive information. You need to ensure that only specific members of the development team have access to sensitive information. You want to assign the appropriate Identity and Access Management (IAM) roles that also require the least amount of maintenance. What should you do?`

A. Assign a basic role to each user.

B. Create groups. Assign a basic role to each group, and then assign users to groups.

C. Create groups. Assign a Custom role to each group, including those who should have access to sensitive data. Assign users to groups.

D. Create groups. Assign an IAM Predefined role to each group as required, including those who should have access to sensitive data. Assign users to groups.

<details>
    <summary>Answer</summary>

    D. Create groups. Assign an IAM Predefined role to each group as required, including those who should have access to sensitive data. Assign users to groups.

</details>

## Question 3

`You are responsible for monitoring all changes in your Cloud Storage and Firestore instances. For each change, you need to invoke an action that will verify the compliance of the change in near real time. You want to accomplish this with minimal setup. What should you do?`

A. Use the trigger mechanism in each datastore to invoke the security script.

B. Use Cloud Function events, and call the security script from the Cloud Function triggers.

D. Use a Python script to get logs of the datastores, analyze them, and invoke the security script.

C. Redirect your data-changing queries to an App Engine application, and call the security script from the application.

<details>
    <summary>Answer</summary>

    B. Use Cloud Function events, and call the security script from the Cloud Function triggers.

</details>

## Question 4

`Your application needs to process a significant rate of transactions. The rate of transactions exceeds the processing capabilities of a single virtual machine (VM). You want to spread transactions across multiple servers in real time and in the most cost-effective manner. What should you do?`

A. Send transactions to BigQuery. On the VMs, poll for transactions that do not have the ‘processed’ key, and mark them ‘processed’ when done.

B. Set up Cloud SQL with a memory cache for speed. On your multiple servers, poll for transactions that do not have the ‘processed’ key, and mark them ‘processed’ when done.

C. Send transactions to Pub/Sub. Process them in VMs in a managed instance group.

D. Record transactions in Cloud Bigtable, and poll for new transactions from the VMs.

<details>
    <summary>Answer</summary>

    C. Send transactions to Pub/Sub. Process them in VMs in a managed instance group.

</details>

## Question 5

`Your team needs to directly connect your on-premises resources to several virtual machines inside a virtual private cloud (VPC). You want to provide your team with fast and secure access to the VMs with minimal maintenance and cost. What should you do?`

A. Set up Cloud Interconnect.

B. Use Cloud VPN to create a bridge between the VPC and your network.

C. Assign a public IP address to each VM, and assign a strong password to each one.

D. Start a Compute Engine VM, install a software router, and create a direct tunnel to each VM.

<details>
    <summary>Answer</summary>

    B. Use Cloud VPN to create a bridge between the VPC and your network.

</details>

## Question 6

`You are implementing Cloud Storage for your organization. You need to follow your organization’s regulations. They include: 1) Archive data older than one year. 2) Delete data older than 5 years. 3) Use standard storage for all other data. You want to implement these guidelines automatically and in the simplest manner available. What should you do?`

A. Set up Object Lifecycle management policies.

B. Run a script daily. Copy data that is older than one year to an archival bucket, and delete five-year-old data.

C. Run a script daily. Set storage class to ARCHIVE for data that is older than one year, and delete five-year-old data.

D. Set up default storage class for three buckets named: STANDARD, ARCHIVE, DELETED. Use a script to move the data in the appropriate bucket when its condition matches your company guidelines.

<details>
    <summary>Answer</summary>

    A. Set up Object Lifecycle management policies.

</details>

## Question 7

`You are creating a Cloud IOT application requiring data storage of up to 10 petabytes (PB). The application must support high-speed reads and writes of small pieces of data, but your data schema is simple. You want to use the most economical solution for data storage. What should you do?`

A. Store the data in Cloud Spanner, and add an in-memory cache for speed.

B. Store the data in Cloud Storage, and distribute the data through Cloud CDN for speed.

C. Store the data in Cloud Bigtable, and implement the business logic in the programming language of your choice.

D. Use BigQuery, and implement the business logic in SQL.

<details>
    <summary>Answer</summary>

    C. Store the data in Cloud Bigtable, and implement the business logic in the programming language of your choice.

</details>

## Question 8

`You have created a Kubernetes deployment on Google Kubernetes Engine (GKE) that has a backend service. You also have pods that run the frontend service. You want to ensure that there is no interruption in communication between your frontend and backend service pods if they are moved or restarted. What should you do?`

A. Create a service that groups your pods in the backend service, and tell your frontend pods to communicate through that service.

B. Create a DNS entry with a fixed IP address that the frontend service can use to reach the backend service.

C. Assign static internal IP addresses that the frontend service can use to reach the backend pods.

D. Assign static external IP addresses that the frontend service can use to reach the backend pods.

<details>
    <summary>Answer</summary>

    A. Create a service that groups your pods in the backend service, and tell your frontend pods to communicate through that service.

</details>

## Question 9

`You are responsible for the user-management service for your global company. The service will add, update, delete, and list addresses. Each of these operations is implemented by a Docker container microservice. The processing load can vary from low to very high. You want to deploy the service on Google Cloud for scalability and minimal administration. What should you do?`

A. Deploy your Docker containers into Cloud Run.

B. Start each Docker container as a managed instance group.

C. Deploy your Docker containers into Google Kubernetes Engine.

D. Combine the four microservices into one Docker image, and deploy it to the App Engine instance.

<details>
    <summary>Answer</summary>

    A. Deploy your Docker containers into Cloud Run.

</details>

## Question 10

`You provide a service that you need to open to everyone in your partner network.  You have a server and an IP address where the application is located. You do not want to have to change the IP address on your DNS server if your server crashes or is replaced. You also want to avoid downtime and deliver a solution for minimal cost and setup. What should you do?`

A. Create a script that updates the IP address for the domain when the server crashes or is replaced.

B. Reserve a static internal IP address, and assign it using Cloud DNS.

C. Reserve a static external IP address, and assign it using Cloud DNS.

D. Use the Bring Your Own IP (BYOIP) method to use your own IP address.

<details>
    <summary>Answer</summary>

    C. Reserve a static external IP address, and assign it using Cloud DNS.

</details>

## Question 11

`Your team is building the development, test, and production environments for your project deployment in Google Cloud. You need to efficiently deploy and manage these environments and ensure that they are consistent. You want to follow Google-recommended practices. What should you do?`

A. Create a Cloud Shell script that uses gcloud commands to deploy the environments.

B. Create one Terraform configuration for all environments. Parameterize the differences between environments.

C. For each environment, create a Terraform configuration. Use them for repeated deployment. Reconcile the templates periodically.

D. Use the Cloud Foundation Toolkit to create one deployment template that will work for all environments, and deploy with Terraform.

<details>
    <summary>Answer</summary>

    D. Use the Cloud Foundation Toolkit to create one deployment
    template that will work for all environments, and deploy with
    Terraform.
    
    > The Cloud Foundation Toolkit (CFT) provides ready-made templates that reflect Google Cloud recommended practices and can be used to automate creation of the environments.

</details>

## Question 12

`You receive an error message when you try to start a new VM: “You have exhausted the IP range in your subnet.” You want to resolve the error with the least amount of effort.  What should you do?`

A. Create a new subnet and start your VM there.

B. Expand the CIDR range in your subnet, and restart the VM that issued the error.

C. Create another subnet, and move several existing VMs into the new subnet.

D. Restart the VM using exponential backoff until the VM starts successfully

<details>
    <summary>Answer</summary>

    B. Expand the CIDR range in your subnet, and restart the VM that issued the error.

</details>

## Question 13

`You are running several related applications on Compute Engine virtual machine (VM) instances. You want to follow Google-recommended practices and expose each application through a DNS name. What should you do?`

A. Use the Compute Engine internal DNS service to assign DNS names to your VM instances, and make the names known to your users.

B. Assign each VM instance an alias IP address range, and then make the internal DNS names public.

C. Assign Google Cloud routes to your VM instances, assign DNS names to the routes, and make the DNS names public.

D. Use Cloud DNS to translate your domain names into your IP addresses.

<details>
    <summary>Answer</summary>

    A. Use the Compute Engine internal DNS service to assign DNS names to your VM instances, and make the names known to your users.

</details>

## Question 14

`You are charged with optimizing Google Cloud resource consumption. Specifically, you need to investigate the resource consumption charges and present a summary of your findings. You want to do it in the most efficient way possible. What should you do?`

A. Rename resources to reflect the owner and purpose. Write a Python script to analyze resource consumption.

B. Attach labels to resources to reflect the owner and purpose. Export Cloud Billing data into BigQuery, and analyze it with Data Studio.

C. Assign tags to resources to reflect the owner and purpose. Export Cloud Billing data into BigQuery, and analyze it with Data Studio.

D. Create a script to analyze resource usage based on the project to which the resources belong. In this script, use the IAM accounts and services accounts that control given resources.

<details>
    <summary>Answer</summary>

    B. Attach labels to resources to reflect the owner and purpose. Export Cloud Billing data into BigQuery, and analyze it with Data Studio.

</details>

## Question 15

`You are creating an environment for researchers to run ad hoc SQL queries. The researchers work with large quantities of data.  Although they will use the environment for an hour a day on average, the researchers need access to the functional environment at any time during the day. You need to deliver a cost-effective solution. What should you do?`

A. Store the data in Cloud Bigtable, and run SQL queries provided by Bigtable schema.

B. Store the data in BigQuery, and run SQL queries in BigQuery.

C. Create a Dataproc cluster, store the data in HDFS storage, and run SQL queries in Spark.

D. Create a Dataproc cluster, store the data in Cloud Storage, and run SQL queries in Spark.

<details>
    <summary>Answer</summary>

    B. Store the data in BigQuery, and run SQL queries in BigQuery.

</details>

## Question 16

`You are migrating your workload from on-premises deployment to Google Kubernetes Engine (GKE). You want to minimize costs and stay within budget. What should you do?`

A. Configure Autopilot in GKE to monitor node utilization and eliminate idle nodes.

B. Configure the needed capacity; the sustained use discount will make you stay within budget.

C. Scale individual nodes up and down with the Horizontal Pod Autoscaler.

D. Create several nodes using Compute Engine, add them to a managed instance group, and set the group to scale up and down depending on load.

<details>
    <summary>Answer</summary>

    A. Configure Autopilot in GKE to monitor node utilization and eliminate idle nodes.

</details>

## Question 17

`Your application allows users to upload pictures. You need to convert each picture to your internal optimized binary format and store it. You want to use the most efficient, cost-effective solution. What should you do?`

A. Store uploaded files in Cloud Bigtable, monitor Bigtable entries, and then run a Cloud Function to convert the files and store them in Bigtable.

B. Store uploaded files in Firestore, monitor Firestore entries, and then run a Cloud Function to convert the files and store them in Firestore.

C. Store uploaded files in Filestore, monitor Filestore entries, and then run a Cloud Function to convert the files and store them in Filestore.

D. Save uploaded files in a Cloud Storage bucket, and monitor the bucket for uploads. Run a Cloud Function to convert the files and to store them in a Cloud Storage bucket.

<details>
    <summary>Answer</summary>

    D. Save uploaded files in a Cloud Storage bucket, and monitor the bucket for uploads. Run a Cloud Function to convert the files and to store them in a Cloud Storage bucket.

</details>

## Question 18

`You are migrating your on-premises solution to Google Cloud. As a first step, the new cloud solution will need to ingest 100 TB of data. Your daily uploads will be within your current bandwidth limit of 100 Mbps. You want to follow Google-recommended practices for the most cost-effective way to implement the migration. What should you do?`

A. Set up Partner Interconnect for the duration of the first upload.

B. Obtain a Transfer Appliance, copy the data to it, and ship it to Google.

C. Set up Dedicated Interconnect for the duration of your first upload, and then drop back to regular bandwidth.

D. Divide your data between 100 computers, and upload each data portion to a bucket. Then run a script to merge the uploads together.

<details>
    <summary>Answer</summary>

    B. Obtain a Transfer Appliance, copy the data to it, and ship it to Google.

</details>

## Question 19

`You are setting up billing for your project. You want to prevent excessive consumption of resources due to an error or malicious attack and prevent billing spikes or surprises. What should you do?`

A. Set up budgets and alerts in your project.

B. Set up quotas for the resources that your project will be using.

C. Set up a spending limit on the credit card used in your billing account.

D. Label all resources according to best practices, regularly export the billing reports, and analyze them with BigQuery.

<details>
    <summary>Answer</summary>

    B. Set up quotas for the resources that your project will be using.

</details>

## Question 20

`Your project team needs to estimate the spending for your Google Cloud project for the next quarter. You know the project requirements. You want to produce your estimate as quickly as possible. What should you do?`

A. Build a simple machine learning model that will predict your next month’s spend.

B. Estimate the number of hours of compute time required, and then multiply by the VM per-hour pricing.

C. Use the Google Cloud Pricing Calculator to enter your predicted consumption for all groups of resources.

D. Use the Google Cloud Pricing Calculator to enter your consumption for all groups of resources, and then adjust for volume discounts.

<details>
    <summary>Answer</summary>

    C. Use the Google Cloud Pricing Calculator to enter your predicted consumption for all groups of resources.

</details>

## Question 21

`A company has built an application on Google Cloud that uses Cloud Spanner. The support team needs to monitor the environment but should not have access to table data.

They need a streamlined solution to grant the correct permissions to the support team. They want to follow Google-recommended practices.

What should be done?`

A. Add the support team group to the roles/spanner.databaseReader role

B. Add the support team group to the roles/monitoring.viewer role

C. Add the support team group to the roles/spanner.databaseUser role

D. Add the support team group to the roles/spanner.databaseUser role

<details>
    <summary>Answer</summary>

    B. Add the support team group to the roles/monitoring.viewer role

</details>

## Question 22

`A cloud engineering team has an inventory application with 2 backend API servers launched using Auto Scaling Groups. The team has been asked to load balance UDP, TCP, and SSL traffic on ports that are not supported by the TCP proxy and SSL proxy loader.

Which of the following Load Balancer is the best option?`

A. SSL Proxy Load Balancer

B. Network Load Balancer

C. HTTPS Load Balancer

D. TCP Proxy Load Balancer

<details>
    <summary>Answer</summary>

    B. Network Load Balancer

</details>

## Question 23

`You are a cloud engineer working for a digital media company. Your team has assigned you the task of choosing the best method for transferring 50TB of data from the on-premise network to the Google Cloud network. In addition, they need to choose the optimal storage solution as they need to access the videos weekly and image files roughly every 3 months.

What combination of services will satisfy the requirement?`

A. Storage Transfer Service and Standard Storage for videos, Coldline Storage for images files

B. Transfer Appliance and Standard Storage for videos, Coldline Storage for images files

C. Transfer Appliance and Coldline Storage for videos, Standard Storage for images files

D. Storage Transfer Service and Coldline Storage for videos, Standard Storage for images files

<details>
    <summary>Answer</summary>

    B. Transfer Appliance and Standard Storage for videos, Coldline Storage for images files

</details>

## Question 24

`A company's VMs are running in a subnet that has a subnet mask of 255.255.255.240. The current subnet has no more free IP addresses and you require an additional 10 IP addresses for new VMs. The existing and new VMs should all be able to reach each other without additional routes.`

A. Create a new subnet with the same starting IP but a wider range to overwrite the current subnet.

B. Use gcloud to expand the IP range of the current subnet.

C. Create a new project. Use Shared VPC to share the current network with the new project.

D. Delete the subnet, and recreate it using a wider range of IP addresses.

<details>
    <summary>Answer</summary>

    B. Use gcloud to expand the IP range of the current subnet.

</details>

## Question 25

`You have a single file with 32 GB of data to upload to a Nearline Storage bucket. The WAN (wide-area network) connection you are utilizing has a speed of 2 Gbps, and you are the only one on it. To transfer the file quickly, you want to use as much of the speed of 2 Gbps as possible. Cost is not a concern.

What method should you use to upload the file?`

A. Change the storage class of the bucket from Nearline to Multi-Regional.

B. Enable parallel composite uploads using gsutil on the file transfer.

C. Reduce the size of the TCP window on the system that is initiating the transfer.

D. Use a private connection to reduce traffic

<details>
    <summary>Answer</summary>

    B. Enable parallel composite uploads using gsutil on the file transfer.

</details>

## Question 26

`Your organization would like to obtain significant discounts on your VM instance deployments on Google Cloud. These VM instances need to be fully available. What pricing model would you want to consider?`

A.Committed Use Instances

B. On-Demand Instances

C. Preemptible instances

D.Spot instances

<details>
    <summary>Answer</summary>

    A. Committed Use Instances

</details>

## Question 27

`What does Google Cloud Marketplace provide?`

A. The ability to quickly deploy functional software packages that run on Google Cloud

B. Sets up Cloud VPN between the infrastructure on-premises and Google Cloud

C. A platform for trading VM instances

D. A centralized billing platform for all Google Cloud services and applications

<details>
    <summary>Answer</summary>

    A. The ability to quickly deploy functional software packages that run on Google Cloud

</details>

## Question 28

`You have been asked by your Manager to setup some Cloud Storage for some on-premises data that will migrate the cloud. You have been told that you need to have an archive for data over 6 months for DR purposes. What Storage Class would you choose?`

A. Coldline

B. Nearline

C. Standard

D. Archive

<details>
    <summary>Answer</summary>

    A. Coldline

</details>