# Elastic Google Cloud Infrastructure: Scaling and Automation

## Table of Contents

- [Elastic Google Cloud Infrastructure: Scaling and Automation](#elastic-google-cloud-infrastructure-scaling-and-automation)
  - [Table of Contents](#table-of-contents)
  - [Interconnecting Networks](#interconnecting-networks)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
    - [Question 4](#question-4)
  - [Load Balancing and Autoscaling](#load-balancing-and-autoscaling)
    - [Question 1](#question-1-1)
    - [Question 2](#question-2-1)
    - [Question 3](#question-3-1)
  - [Infrastructure Automation](#infrastructure-automation)
    - [Question 1](#question-1-2)
    - [Question 2](#question-2-2)
  - [Managed Services](#managed-services)
    - [Question 1](#question-1-3)
    - [Question 2](#question-2-3)


## Interconnecting Networks

### Question 1

`Which of the following approaches to multi-project networking, uses a centralized network administration model?`

- VPC Network Peering

- Cloud VPN

- Shared VPC

<details>
    <summary>Answer</summary>

    - Shared VPC

    > Shared VPC is a centralized network administration model. It allows you to create a single VPC network that can be shared across multiple projects. This allows you to
    create a single network that spans multiple projects. This is useful if you have multiple projects that need to communicate with each other. For example, you might
    have a project that contains your production environment and a project that contains your development environment. You might want to create a Shared VPC network
    that spans both projects so that your development environment can communicate with your production environment.

</details>

### Question 2

`If you cannot meet Google’s peering requirements, which network connection service should you choose to connect to Google Workspace and YouTube?`

- Dedicated Interconnect

- Direct Peering

- Carrier Peering

- Partner Interconnect

<details>
    <summary>Answer</summary>

    - Carrier Peering

    > Carrier Peering allows you to connect to Google Workspace and YouTube without meeting Google’s peering requirements.

</details>

### Question 3

`Which Google Cloud Interconnect service requires a connection in a Google Cloud colocation facility and provides 10 Gbps per link?`

- Cloud VPN

- Partner Interconnect

- Carrier Peering

- Direct Peering

- Dedicated Interconnect

<details>
    <summary>Answer</summary>

    - Dedicated Interconnect

    > Dedicated Interconnect requires a connection in a Google Cloud colocation facility and provides 10 Gbps per link.

</details>

### Question 4

`What is the purpose of Virtual Private Networking (VPN)?`

- It is a method to detect intruders at the edge of a network boundary.

- To enable a secure communication method (a tunnel) to connect two trusted environments through an untrusted environment, such as the Internet.

- The main purpose is to encrypt data so that it can be stored in an encrypted format.

- VPNs are also called access control lists, or ACLs, and they limit network access

<details>
    <summary>Answer</summary>

    - To enable a secure communication method (a tunnel) to connect two trusted environments through an untrusted environment, such as the Internet.

    > VPNs are a method to enable a secure communication method (a tunnel) to connect two trusted environments through an untrusted environment, such as the Internet. VPNs
    are also called access control lists, or ACLs, and they limit network access.

</details>

## Load Balancing and Autoscaling

### Question 1

`Which of the following are applicable autoscaling policies for managed instance groups?`

- Monitoring metrics

- Load balancing capacity

- Queue-based workload

- CPU utilization

<details>
    <summary>Answer</summary>

    - Monitoring metrics

    - Load balancing capacity

    - Queue-based workload

    - CPU utilization

    > Autoscaling policies are used to scale the number of instances in a managed instance group based on the current workload. You can use autoscaling policies to
    scale based on monitoring metrics, load balancing capacity, queue-based workload, and CPU utilization.

</details>

### Question 2

`Which three Google Cloud load balancing services support IPv6 clients?`

- Internal load balancing

- TCP proxy load balancing

- SSL proxy load balancing

- Network load balancing

- HTTP(S) load balancing

<details>
    <summary>Answer</summary>

    - HTTP(S) load balancing

    - TCP proxy load balancing

    - SSL proxy load balancing

    > HTTP(S) load balancing, TCP proxy load balancing, and SSL proxy load balancing support IPv6 clients.

</details>

### Question 3

`Which of the following is not a Google Cloud load balancing service?`

- Network load balancing

- TCP proxy load balancing

- SSL proxy load balancing

- Internal load balancing

- Hardware-defined load balancing

- HTTP(S) load balancing

<details>
    <summary>Answer</summary>

    - Hardware-defined load balancing

    > Hardware-defined load balancing is not a Google Cloud load balancing service.

</details>

## Infrastructure Automation

### Question 1

`What’s the benefit of writing templates for your Terraform configuration?`

- Allows you to run configuration management software.

- Allows you to hardcode properties for your resources

- Allows you to abstract part of your configuration into individual building blocks that you can reuse

<details>
    <summary>Answer</summary>

    - Allows you to abstract part of your configuration into individual building blocks that you can reuse

    > Writing templates for your Terraform configuration allows you to abstract part of your configuration into individual building blocks that you can reuse. This
    allows you to write more concise and readable configuration files.

</details>

### Question 2

`What does Google Cloud Marketplace offer?`

- A centralized billing platform for all Google Cloud services and applications

- Production-grade solutions from third-party vendors who have already created their own deployment configurations based on Terraform

- A platform for trading VM instance

<details>
    <summary>Answer</summary>

    - Production-grade solutions from third-party vendors who have already created their own deployment configurations based on Terraform

    > Google Cloud Marketplace offers production-grade solutions from third-party vendors who have already created their own deployment configurations based on
    Terraform.

</details>

## Managed Services

### Question 1

`How are Managed Services useful?`

- Managed Services are more customizable than infrastructure solutions.

- Managed Services are pay services offered by 3rd party vendors.

- Managed Services may be an alternative to creating and managing infrastructure solutions.

- If you have an existing infrastructure service, Google will manage it for you if you purchase a Managed Services contract.

<details>
    <summary>Answer</summary>

    - Managed Services may be an alternative to creating and managing infrastructure solutions.

    > Managed Services may be an alternative to creating and managing infrastructure solutions. Managed Services are not customizable, and they are not pay services
    offered by 3rd party vendors.

</details>

### Question 2

`Which of the following is a feature of Dataproc?`

- It doesn't integrate with Cloud Monitoring, but it has its own monitoring system.

- It typically takes less than 90 seconds to start a cluster.

- Dataproc allows full control over HDFS advanced settings.

- Dataproc billing occurs in 10-hour intervals.

<details>
    <summary>Answer</summary>

    - It typically takes less than 90 seconds to start a cluster.

    > Dataproc typically takes less than 90 seconds to start a cluster. Dataproc integrates with Cloud Monitoring, and it allows full control over HDFS advanced
    settings. Dataproc billing occurs in 10-minute intervals.

</details>

