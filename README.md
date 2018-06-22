## Docker Enterprise Edition on AWS
This Quick Start to automatically set up the following Docker Enterprise Edition (EE) environment on AWS:
* A virtual private cloud (VPC) that spans three Availability Zones and includes three public subnets.
* Three Swarm controller nodes that run the DTR and UCP services.
* A cluster of Swarm nodes in an Auto Scaling group, so the cluster can grow dynamically as the load on the instances increases.
* Three Elastic Load Balancing (ELB) load balancers. Two of these load balancers provide inbound access to the management consoles for UCP and DTR, and the third provides inbound access to customer applications running on the Swarm nodes.
* Amazon Simple Storage Service (Amazon S3) for backing up the root certificate authorities (CAs).

### Architecture
![quickstart-doocker](/images/docker.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/98RWP).
