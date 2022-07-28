# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-eks-cluster), containing
Terraform configuration files to provision an EKS cluster on AWS.

########################################################################

follow the link bellow for Prerequisites and instructions.

https://learn.hashicorp.com/tutorials/terraform/eks


aws eks update-kubeconfig --region [REGION WHERE THE CLUSTER WAS DEPLOYED ] --name [CLUSTER NAME]

to the cluster na,e run the command 

cat ~/.kube/config
