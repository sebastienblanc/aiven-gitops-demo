# Aiven k8s Operator + ArgoCD Demo

This repo contains just a simple `Aiven CR` that represents a PostgreSQL DB resource. If applied on a Kubernetes Cluster with the Aiven Operator installed on it, the resource will be created on your Aiven platform. 
Applying the resource doesn't happen manually but is using the GitOps approach where you basically commit/push a resource to a repo and ArgoCD will apply it for you on the cluster.

## Pre-requisites

First you need a Kubernetes CLuster, something like Minikube should be enough.

Then you need to install ArgoCD , it's pretty easy, just follow those intructions : https://argo-cd.readthedocs.io/en/stable/operator-manual/installation/

You need an Aiven account, you can start a free trial : https://console.aiven.io/signup

And finally you need to install the Aiven Kubernetes Operator : https://docs.aiven.io/docs/tools/kubernetes.html


## Running

Fork this repo ! 

Create a new application in ArgoCD pointing to your fork.

Commit, Push & Enjoy ! 