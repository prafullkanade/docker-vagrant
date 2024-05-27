# docker Server Using Vagrant

docker Server using vagrant, virtual box and ubuntu 22.04

## Create Ubuntu, Install docker using Vagrant & VirtualBox


### Checkout the Repo
Clone the repo locally by running below command 
  
```sh 
git clone the repo https://github.com/prafullkanade/docker-vagrant.git
cd docker-server
```

### Bootstrapping k8s cluster using shell script
Run below command to provision new docker server

```sh
./bootstrap.sh
```

#### Stop docker server

```sh
vagrant halt
```

#### Cleanup k8s cluster
```sh
vagrant destroy -f
```
