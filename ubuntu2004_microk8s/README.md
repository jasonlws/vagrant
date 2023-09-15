# Environment

Tools: Vagrant + Virtual Box
Vagrant Box: generic/ubuntu2004
OS: Ubuntu 20.04

1. Add Vagrant box image
```console
$ vagrant box add generic/ubuntu2004
```

2. Start Vagrant 
```console
$ vagrant up
```

3. Kubernetes Dashboard

Access [https://127.0.0.1:31625](https://127.0.0.1:31625) and copy the token from the last statement from `vagrant up`

3. Destroy Vagrant
```console
$ vagrant destroy jasonlws -f
```