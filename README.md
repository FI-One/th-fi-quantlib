# th-fi-quantlib

## Getting Started

1. Install [Vagrant](https://www.vagrantup.com/downloads)

	If you are using virtualbox, you may need to run this command to install the guest additions:
	```shell
	$ vagrant plugin install vagrant-vbguest
	```

2. Start Vagrant
	```shell
	$ vagrant up
	```

3. Installing Quantlib

4. Creating Python Bindings

```shell
$ export PATH=$PATH:<location of quantlib configure>
$ ./configure CXXFLAGS='-O1 -I<quantlib include directory>'
$ make -C Python
```
