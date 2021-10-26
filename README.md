# EKS Cluster Using Terraform
This repository to show how Elastic Kubernetes Cluster(EKS) that is a managed services of AWS can be created using IaC terraform.

## Big Picture
 A picture is a graphical representation about creating EKS cluster in a virtual private cloud in AWS in a scure way.
 
 ![anton](https://user-images.githubusercontent.com/21228768/138806022-bac47082-fae3-44ea-be97-af25cc2b49f3.png)


## Included

1. Create VPC and Subnets
2. Create Internet and NAT Gatways
3. Create Route Tables and associations
4. Create IAM Role for EKS Cluster
5. Attach AmazonEKSClusterPolicy to EKS Role
6. Create AWS EKS Cluster
7. Create IAM Role for EKS Node Group
8. Attach AmazonEKSWorkerNodePolicy, AmazonEKS_CNI_Policy, and AmazonEC2ContainerRegistryReadOnly to EKS Node Group IAM Role
9. Create AWS EKS Node Group
10. Run Terraform Commands to Create AWS EKS Cluster
11. Connect to EKS Cluster

 Hope this will be good learning guide.






