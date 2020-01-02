# Kubernetes Observability Patterns

This is a collection of recipes I commonly use when building a production ready
Kubernetes clusters. This repo aims at filling the gap between a vanilla and a 
production ready Kubernetes. But remember: your milage may vary!

## Recipes covered

* [Log Management](log-management/)
* Monitoring
* Cluster & Application Scaling

## Kubernetes test bed

Before copy & pasting some YAML into your production cluster, I highly suggest testing
things in a dedicated test cluster. I maintain some basic 
[_Terraform_ cloud provider setups over at GitHub](https://github.com/tboeghk/kubernetes-in-the-clouds).
