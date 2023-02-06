# Google Cloud Fundamentals : Core Infrastructure

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