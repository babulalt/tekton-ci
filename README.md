# Tekton-CICD : Cloud Native CICD

## ***Installing Tekton Pipelines on Kubernetes***
### *To install Tekton Pipelines on a Kubernetes cluster:*

    Run the following command to install Tekton Pipelines and its dependencies:

    kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml

##  ***Install Tekton dashboard***

## Install from here

    kubectl apply --filename https://storage.googleapis.com/tekton-releases/dashboard/latest/tekton-dashboard-release.yaml

## *Enter the Dashboard via:*
 
    kubectl proxy

    http://localhost:8001/api/v1/namespaces/tekton-pipelines/services/tekton-dashboard:http/proxy/

    