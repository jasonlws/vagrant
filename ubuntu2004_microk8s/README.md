# Environment

Tools: Vagrant + Virtual Box
Vagrant Box: generic/ubuntu2004
OS: Ubuntu 20.04

1. Add Vagrant box image
```console
vagrant box add generic/ubuntu2004
```

2. Start Vagrant 
```console
vagrant up
```

3. Kubernetes Dashboard

Access [https://127.0.0.1:31625](https://127.0.0.1:31625) and copy the token from the last statement from `vagrant up`

3. Destroy Vagrant
```console
vagrant destroy jasonlws -f
```

## License

MIT - a permissive free software license originating at the Massachusetts Institute of Technology (MIT), it puts only very limited restriction on reuse and has, therefore, an excellent license compatibility. It permits reuse within proprietary software provided that all copies of the licensed software include a copy of the MIT License terms and the copyright notice.

Check the [LICENSE file](../LICENSE) for more details.