# Packer Configs

* to build Centos Image using Packer be sure that you have installed [packer](https://www.packer.io/downloads.html)

## How to start

* Clone Repository
* install packer and run following

```bash
packer validate centos-vbox.json
packer build centos-vbox.json
```
* Or use packer binary from this repositroy(not recomended)

```
./packer validate centos-vbox.json
./packer build centos-vbox.json
```

* In case of Succes Get some beer en enjoy life!
