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