# Microservice Kubernates Scale
Project for study of container orchestration and automation of scale.
This project used OS Ubuntu 19.04

## Install Kubernates and Minikube to local uso (do not use in production)

### Dependency
```
$ sudo apt-get update && sudo apt-get install -y apt-transport-https curl
```

# Virtual Box
```
$ sudo apt-get install -y virtualbox virtualbox-ext-pack
```

# Kubernates
```
$ sudo curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
$ sudo touch /etc/apt/sources.list.d/kubernetes.list 
$ echo "deb http://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee -a /etc/apt/sources.list.d/kubernetes.list
$ sudo apt-get update
$ sudo apt-get install -y kubectl
```

# Minikube
```
$ curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.28.2/minikube-linux-amd64
$ chmod +x minikube && sudo mv minikube /usr/local/bin/

```

## Arquitecture

![Drag Racing](https://cdn-images-1.medium.com/max/800/1*KIVa4hUVZxg-8Ncabo8pdg.png)

Fonte: https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0

