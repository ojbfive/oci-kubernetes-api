![](basic/logo.png)
# Connecting to OKE Private API with NetFoundry Networking.
![](basic/nfkubbiker.jpg)


Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes (OKE) reduces the operational burden of setting up and managing enterprise-grade Kubernetes clusters. NetFoundry and Oracle recognize that connecting to your Kubernetes cluster and its ecosystem is complex, so NetFoundry allows you to connect while also following Oracle best practice design principles:

* Secure by default: OKE hardens Kubernetes clusters following Enterprise Security best practices.

* Simplified Kubernetes operations: Oracle manages your cluster resources and automates recurrent Kubernetes administration and scaling tasks.

* High performance: Containerized applications run on high-performance Compute resources through OCI's non-blocking network.

Earlier in the year Oracle announced general availability of fully private Kubernetes clusters for Oracle Container Enginer for Kubernetes (OKE). This allows you to create fully private OKE clusters without having to expose public IP's. The standard method to connect is with FastConnect or VPN/Bastion connectivity.

What's New?

Oracle and technology partner NetFoundry have designed an alternative solution using SDN technology. NetFoundry provides Zero Trust Network connectivity for Edge, Multicloud, IOT and on premise infrastructure. [Here is more information on the NetFoundry Zero Trust Networking platform.](https://blogs.oracle.com/cloud-infrastructure/zero-trust-network-access-with-netfoundry)
The solution is 100% software and can be instantiated directly from the Oracle Cloud console and OCI CLI using HELM Charts to deploy NetFoundry software.





