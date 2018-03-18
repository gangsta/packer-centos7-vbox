# Packer Configs

* To build Centos Image using Packer be sure that you have installed [packer](https://www.packer.io/downloads.html)

## How to start

* Clone Repository
* Install packer and run following

```bash
packer validate centos-vbox.json
packer build centos-vbox.json
```
* Or use packer binary from this repository(not recommended)

```
./packer validate centos-vbox.json
./packer build centos-vbox.json
```

* In case of success get some beer en enjoy life!
