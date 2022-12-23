# Ansible

Ansible is an open-source automation platform that can be used to configure and manage systems, deploy software, and perform complex tasks across a network of nodes. It uses a simple, human-readable language called YAML to describe the desired state of the infrastructure and the tasks that should be performed to achieve that state.
Ansible uses a push-based architecture, which means that it pushes configuration changes and tasks to the nodes in your infrastructure rather than requiring those nodes to pull instructions from a central server. This makes Ansible easy to use and allows it to scale to large infrastructure deployments.
Ansible is highly extensible and can be used to automate a wide range of tasks, including configuration management, application deployment, and cloud provisioning. It also has a large and active community of users, which means that there are many resources available for learning how to use ansible and getting help with it.

# VPC
A Virtual Private Cloud (VPC) is a virtual network that is isolated from the rest of the internet. It is used to securely host resources such as servers, databases, and applications in the cloud.
A VPC is a useful tool for organizations that want to have the flexibility and scalability of the cloud, but also need to maintain control over the security and networking of their resources.
In a VPC, you can create and configure network resources such as subnets, route tables, and security groups. You can also connect your VPC to your on-premises infrastructure using a VPN connection.
VPCs are offered by many cloud providers, including Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). Each provider has its own set of features and tools for managing and configuring VPCs.

# Components of VPC
Subnets: A subnet is a range of IP addresses within a VPC. You can create multiple subnets in a VPC, and each subnet can be associated with a different availability zone (AZ). This allows you to distribute your resources across multiple AZs for increased availability.
Internet Gateway: An Internet Gateway is a VPC component that allows resources in your VPC to communicate with the internet. It is a virtual router that connects your VPC to the internet.
NAT Gateway: A NAT (Network Address Translation) Gateway allows resources in a private subnet to communicate with the internet, but prevents incoming connections from the internet. This can be used to increase the security of your VPC.
VPN Connection: A VPN (Virtual Private Network) Connection allows you to securely connect your on-premises network to your VPC over the internet. This can be used to extend your on-premises network into the cloud.
Security Group: A Security Group is a virtual firewall that controls inbound and outbound traffic to resources in your VPC. You can create rules to allow or deny traffic based on IP address, port, and protocol.
Route Tables: A Route Table is a VPC component that determines how traffic is routed between subnets, the internet, and on-premises networks. You can create multiple Route Tables and associate them with different subnets to control the flow of traffic within your VPC.

# Bastion Host
A bastion host, also known as a jump host or jump server, is a secure server that is used to access other servers on a network. It is typically used as a secure gateway to access servers in a private network, such as a corporate network or a virtual private cloud (VPC).
A bastion host is typically configured with strong security measures, such as two-factor authentication and strict access controls, to prevent unauthorized access. It is also usually configured with a minimal operating system and a limited number of tools and applications to reduce the attack surface.
To access servers on the private network, users connect to the bastion host using a secure protocol such as SSH (Secure Shell) or RDP (Remote Desktop Protocol). From there, they can use the bastion host to connect to other servers on the private network.
Bastion hosts are commonly used in cloud computing environments to provide a secure way to access resources in a VPC. They can also be used in on-premises environments to provide secure access to internal networks.
