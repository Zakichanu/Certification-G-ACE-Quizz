# Essential Cloud Infrastructure

## Interacting with Google Cloud

### Question 1

`Which of the following does not allow you to interact with Google Cloud?`

- Google Cloud Console

- Cloud Shell

- Cloud Explorer

- REST-based API

<details>
    <summary>Answer</summary>

    - Cloud Explorer

    > There are four ways you can interact with Google Cloud: There’s the Cloud Console, Cloud Shell and the Cloud SDK, the APIs, and the Cloud Mobile App. The
    Cloud Explorer is not a Google Cloud tool.

</details>

### Question 2

`What is the difference between the Google Cloud Console and Cloud Shell?`

- The Cloud Console is a command-line tool, while Cloud Shell is a graphical user interface

- Cloud Shell is a command-line tool, while the Cloud Console is a graphical user interface

- There is no difference as these tools are 100% identical.

- Cloud Shell is a locally installed tool, while the Cloud Console is a temporary virtual machine.

<details>
    <summary>Answer</summary>

    - Cloud Shell is a command-line tool, while the Cloud Console is a graphical user interface

    > The Cloud Console is a graphical user interface and Cloud Shell is a command-line tool. Both tools allow you to interact with Google Cloud. Even though the
    Cloud Console can do things Cloud Shell can't do and vice-versa, don’t think of them as alternatives, but think of them as one extremely flexible and powerful
    interface.
</details>

## Virtual Networks

### Question 1

`What are the three types of networks offered in Google Cloud?`

- Default network, auto network, and custom network.

- IPv4 unicast network, IPv4 multicast network, IPv6 network

- Zonal, regional, and global

- Gigabit network, 10 gigabit network, and 100 gigabit network

<details>
    <summary>Answer</summary>

    - Default network, auto network, and custom network.

    > The three network types offered by Google Cloud are: default, auto and custom. Each project starts with a default network. The auto-type network uses the same subnet IP ranges as the default-type, with a network name other than default. A custom-type allows you to specify the IP ranges of subnets.

</details>

### Question 2

`In Google Cloud, what is the minimum number of IP addresses that a VM instance needs?`

- Three: One internal, one external and one alias IP address

- One: Only an internal IP address

- Two: One internal and one external IP address

<details>
    <summary>Answer</summary>

    - One: Only an internal IP address

    > In Google Cloud, each virtual machine needs to have an internal IP address. The external IP address is optional; therefore, a VM instance only needs one IP 
    address.
</details>

### Question 3

`What is one benefit of applying firewall rules by tag rather than by address?`

- Tags on firewall rules control which ephemeral IP addresses VMs will receive.

- When a VM is created with a matching tag, the firewall rules apply irrespective of the IP address it is assigned.

- Tags help organizations track firewall billing.

- Tags in network traffic help with network sniffing.


<details>
    <summary>Answer</summary>

    - When a VM is created with a matching tag, the firewall rules apply irrespective of the IP address it is assigned.

    > When a VM is created the ephemeral external IP address is assigned from a pool. There is no way to predict which address will be assigned, so there is no way to write a rule that will match that VM's IP address before it is assigned. Tags allow a symbolic assignment that does not depend on order in the IP addresses. It makes for simpler, more general, and easier to maintain, firewall rules.

</details>

## Virutal Machines

### Question 1

`What are sustained use discounts?`

- Purchase commitments for specific resources you know you will use

- Per-second billing that starts after a 1 minute minimum

- Automatic discounts that you get for running specific Compute Engine resources for a significant portion of the billing month

- Discounts you receive by using preemptible VM instances

<details>
    <summary>Answer</summary>

    - Automatic discounts that you get for running specific Compute Engine resources for a significant portion of the billing month

    > That's correct! Sustained use discounts are automatic discounts that you get for running specific Compute Engine resources (vCPUs, memory, GPU devices) for 
    a significant portion of the billing month. To take advantage of the full 30% discount, create your VM instances on the first day of the month, 
    because discounts reset at the beginning of each month.

</details>

### Question 2

`Which statement is true of Virtual Machine Instances in Compute Engine?`

- Compute Engine uses VMware to create Virtual Machine Instances.

- All Compute Engine VMs are single tenancy and do not share CPU hardware.

- A VM in Compute Engine always maps to a single hardware computer in a rack.

- In Compute Engine, a VM is a networked service that simulates the features of a computer.

<details>
    <summary>Answer</summary>

    - In Compute Engine, a VM is a networked service that simulates the features of a computer.

    > VMs in Compute Engine are a collection of networked services which includes persistent disks that are network-attached. In some cases the Google Cloud VM
    behaves unlike hardware or other kinds of virtual machines, for example, when a multi-tenant virtual CPU "bursts", using excess capacity beyond the VM spec.

</details>

### Question 3

`Which statement is true of persistent disks?`

- ersistent disks are physical hardware devices connected directly to VMs.

- Once created, a persistent disk cannot be resized.

- Persistent disks are encrypted by default.

- Persistent disks are always HDDs (magnetic spinning disks).

<details>
    <summary>Answer</summary>

    - Persistent disks are encrypted by default.

    > Persistent Disks are not physical disks, they are a virtual-networked service. Each persistent disk remains encrypted either with system-defined keys 
    or with customer-supplied keys.

</details>