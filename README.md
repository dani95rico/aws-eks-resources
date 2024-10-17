# AWS EKS Resources Repository

This repository contains examples of Kubernetes manifests to create AWS resources using Crossplane.
The services include:
- S3 Bucket
- RDS Database
- ELB LoadBalancer

## Instructions

1. Install Crossplane in your Kubernetes cluster.
2. Create AWS Provider and ProviderConfig secrets as shown in the manifests.
3. Deploy using Argo CD by connecting this repo to an Argo CD application.
