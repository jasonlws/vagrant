# Environment

Environment: Kali Linux install with OWASP mutillidae II

### Install a Box

This will download the box named `kalilinux/rolling` and `generic/ubuntu2004` from HashiCorp's Vagrant Cloud box catalog, where you can find and host boxes.

```
vagrant box add kalilinux/rolling

vagrant box add generic/ubuntu2004
```

### Bring up a virtual machine

Run the following from your terminal:

```
vagrant up
```

### Destroy a virtual machine

Run the following from your terminal:

```
vagrant destroy jasonlws-kali jasonlws-docker -f
```

### Kali Linux

Login: root
Password: P@ssw0rd

### OWASP mutillidae II

For first time access:

- Setup the database - Click [http://192.168.56.111/set-up-database.php](http://192.168.56.111/set-up-database.php)
- Setup LDAP - Login phpLDAPAdmin [http://192.168.56.111:82](http://192.168.56.111:82)
  1. Login as cn=admin,dc=mutillidae,dc=localhost (Password: mutillidae)
  2. Click [import] 
  3. Copy content from [/root/jasonlws-kali/mutillidae/mutillidae.Idif](./shared/jasonlws-kali/mutillidae.Idif)
  4. Paste to textbox
  5. Click [Proceed>>] button

Access Links:

- [OWASP mutillidae II - https://192.168.56.111](https://192.168.56.111)
- [phpMyAdmin - http://192.168.56.111:81](http://192.168.56.111:81)
- [phpLDAPAdmin - http://192.168.56.111:82](http://192.168.56.111:82)

### References

- GitHub [webpwnized/mutillidae-dockerhub](https://github.com/webpwnized/mutillidae-dockerhub)
- YouTube: [How to Run Mutillidae from DockerHub Images](https://www.youtube.com/watch?v=c1nOSp3nagw)

## License

MIT - a permissive free software license originating at the Massachusetts Institute of Technology (MIT), it puts only very limited restriction on reuse and has, therefore, an excellent license compatibility. It permits reuse within proprietary software provided that all copies of the licensed software include a copy of the MIT License terms and the copyright notice.

Check the [LICENSE file](../LICENSE) for more details.