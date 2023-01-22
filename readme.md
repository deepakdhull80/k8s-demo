# Kubernetes demo

## prerequisites

```bash
    #1. install kubectl
    
    #2. install minikube
    # if os linux, arch is x86-64
    curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
    sudo install minikube-linux-amd64 /usr/local/bin/minikube

    #Start kubernetes cluster
    minikube start

    # load docker image in minikube
    minikube load image {docker-image-name}

```

## kubernetes commands

```bash

    # start anything in kubernetes 
    kubectl apply -f ./kubernetes/{file-name}.yaml

    #remove service
    kubectl delete svc {service-name}
    #remove deployment
    kubectl delete deploy {pod-name}

```