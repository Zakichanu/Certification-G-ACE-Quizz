# Essential Google Cloud Infrastructure: Core Services

## Table of Contents

- [Essential Google Cloud Infrastructure: Core Services](#essential-google-cloud-infrastructure-core-services)
  - [Table of Contents](#table-of-contents)
  - [Identity and Access Management](#identity-and-access-management)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
  - [Storage and Database Services](#storage-and-database-services)
    - [Question 1](#question-1-1)
    - [Question 2](#question-2-1)
    - [Question 3](#question-3-1)
  - [Resource Management](#resource-management)
    - [Question 1](#question-1-2)
    - [Question 2](#question-2-2)
    - [Question 3](#question-3-2)
  - [Resource Monitoring](#resource-monitoring)
    - [Question 1](#question-1-3)
    - [Question 2](#question-2-3)
    - [Question 3](#question-3-3)

## Identity and Access Management

### Question 1

`What abstraction is primarily used to administer user access in IAM ?`

- Leases, an abstraction of periodic entitlements.

- Credentials, an abstraction of an authorization token.

- Roles, an abstraction of job roles.

- Privileges, an abstraction of access rights.

<details>
    <summary>Answer</summary>

    - Roles, an abstraction of job roles.

    > IAM administration uses pre-defined roles for administration of user access. The roles are defined by more granular permissions. But permissions are not applied to users directly, only through the roles that are assigned to them.

</details>

### Question 2

`Which of the following is not a type of IAM member?`

- Google Account

- Google Group

- Service Account

- Cloud Identity domain

- Organization Account

- Google Workspace domain

<details>
    <summary>Answer</summary>

    - Organization Account

    > There are five different types of members: Google Accounts, Service Accounts, Google Groups, Google Workspace domain, and Cloud Identity domains. There are no "Organization Accounts" in IAM.

</details>

### Question 3

`Which of the following is not a type of IAM role?`

- Basic

- Custom

- Predefined

- Advanced

<details>
    <summary>Answer</summary>

    - Advanced

    > There are three types of roles in IAM: basic roles, predefined roles, and custom roles. There are no "advanced" roles in IAM.

</details>

## Storage and Database Services

### Question 1

`Which data storage service provides data warehouse services for storing data but also offers an interactive SQL interface for querying the data?`

- Cloud SQL

- BigQuery

- Datalab

- Dataproc

<details>
    <summary>Answer</summary>

    - BigQuery

    > BigQuery is a data warehouse service that provides interactive SQL access to data stored in Google Cloud Storage. Cloud SQL is a relational database service. Datalab is a data analysis service. Dataproc is a data processing service.

</details>

### Question 2

`Which Google Cloud data storage service offers ACID transactions and can scale globally?`

- Cloud SQL

- Cloud Storage

- Cloud Spanner

- Cloud CDN

<details>
    <summary>Answer</summary>

    - Cloud Spanner

    > Cloud Spanner is a globally scalable, relational database service that offers ACID transactions. Cloud SQL is a relational database service. Cloud Storage is a general-purpose object storage service. Cloud CDN is a content delivery network service.

</details>

### Question 3

`What data storage service might you select if you just needed to migrate a standard relational database running on a single machine in a datacenter to the cloud?`

- BigQuery

- Cloud SQL

- Cloud Storage

- Persistent Disk

<details>
    <summary>Answer</summary>

    - Cloud SQL

    > Cloud SQL is a relational database service that can be used to migrate a standard relational database running on a single machine in a datacenter to the cloud. BigQuery is a data warehouse service. Cloud Storage is a general-purpose object storage service. Persistent Disk is a block storage service.

</details>

## Resource Management

### Question 1

`A budget is set at $500 and an alert is set at 100%. What happens when the full amount is used?`

- Everything in the associated project will be suspended because there is no more budget to spend.

- Nothing. There is no point in sending a notification when there is no budget remaining.

- A notification email is sent to the Billing Administrator.

- You have a 4-hour courtesy period before Google shuts down all resources.


<details>
    <summary>Answer</summary>

    - A notification email is sent to the Billing Administrator.

    > When the budget is set at 100%, a notification email is sent to the Billing Administrator. Everything in the associated project will be suspended because there is no more budget to spend. There is no point in sending a notification when there is no budget remaining. You have a 4-hour courtesy period before Google shuts down all resources.

</details>

### Question 2

`How do quotas protect Google Cloud customers?`

- By preventing resource use in too many zones in a region.

- By preventing uncontrolled consumption of resources.

- By preventing resource use by unknown users.

- By preventing resource use of too many different Google Cloud services.

<details>
    <summary>Answer</summary>

    - By preventing uncontrolled consumption of resources.

    > Quotas protect Google Cloud customers by preventing uncontrolled consumption of resources. Quotas do not prevent resource use in too many zones in a region, resource use by unknown users, or resource use of too many different Google Cloud services.

</details>

### Question 3

`No resources in Google Cloud can be used without being associated with...`

- A user.

- A project.

- A virtual machine.

- A bucket.

<details>
    <summary>Answer</summary>

    - A project.

    > No resources in Google Cloud can be used without being associated with a project. A user can be associated with a project. A virtual machine can be associated with a project. A bucket can be associated with a project.

</details>

## Resource Monitoring

### Question 1

`What is the foundational process at the base of Google's Site Reliability Engineering (SRE) ?`

- Root cause analysis.

- Testing and release procedures.

- Monitoring.

- Capacity planning.

<details>
    <summary>Answer</summary>

    - Monitoring.

    > Monitoring is the foundational process at the base of Google's Site Reliability Engineering (SRE). Root cause analysis, testing and release procedures, and capacity planning are all important parts of SRE, but monitoring is the foundation.

</details>

### Question 2

`Google Cloud’s operations suite integrates several technologies, including monitoring, logging, error reporting, and debugging that are commonly implemented in other environments as separate solutions using separate products. What are key benefits of integration of these services?`

- Better for Google Cloud only so long as you don't need to monitor other applications or clouds

- Ability to replace one tool with another from a different vendor

- Detailed control over the connections between the technologies

- Reduces overhead, reduces noise, streamlines use, and fixes problems faster

<details>
    <summary>Answer</summary>

    - Reduces overhead, reduces noise, streamlines use, and fixes problems faster

    > Google Cloud’s operations suite integrates several technologies, including monitoring, logging, error reporting, and debugging that are commonly implemented in other environments as separate solutions using separate products. The key benefits of integration of these services are that it reduces overhead, reduces noise, streamlines use, and fixes problems faster.

</details>

### Question 3

`What is the purpose of the Cloud Trace service?`

- Reporting on Google Cloud resource consumption as part of managing performance.

- Reporting on Google Cloud system errors.

- Reporting on application errors.

- Reporting on latency as part of managing performance.

<details>
    <summary>Answer</summary>

    - Reporting on latency as part of managing performance.

    > Cloud Trace is a latency reporting service that is part of Google Cloud's operations suite. Cloud Trace is used to report on latency as part of managing performance. Cloud Trace is not used to report on Google Cloud resource consumption, Google Cloud system errors, or application errors.

</details>

