# Kubernetes in the clouds

Maintaining Kuberentes clusters on-premise can be hazzle. For testing
some of the recipes, I highly recommend using a cloud provider as it
is easier to follow the [_cattle not pets_ approach](http://cloudscaling.com/blog/cloud-computing/the-history-of-pets-vs-cattle/).

## Setting up Kubernetes

My tool of choice for setting up _volatile infrastructure_ (servers, clusters, domains, 
certificates) is [Terraform](https://terraform.io/). At [GitHub I collected some snippets](https://github.com/tboeghk/kubernetes-in-the-clouds/) 
and links how to set up a basic Kubernetes clusters with different cloud providers.

* [Digital Ocean](https://github.com/tboeghk/kubernetes-in-the-clouds/tree/master/digital-ocean)
* [Google GCP](https://github.com/tboeghk/kubernetes-in-the-clouds/tree/master/google)
* [Amazon EKS](https://github.com/tboeghk/kubernetes-in-the-clouds/tree/master/aws)
* Azure

> My personal favorite (by far) is [Digital Ocean](digitalocean.md) as the cluster
> is up and running in less than 3 minutes time and 20 lines of Terraform code!