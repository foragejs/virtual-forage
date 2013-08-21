Virtual-norch
=============

Virtual-norch is a virtualisation package for [Norch](http://www.norch.net), allowing a host machine to run Norch on a guest OS.
This can be useful for testing Norch on another operating system, and also for investigating clustering strategies.

##Downloading

Like all things on GitHub, virtual-norch is best git cloned onto your machine. Since virtual-norch contains submodules a
couple of extra git commands must be invoked in order to obtain a working copy.

`git clone https://github.com/fergiemcdowall/virtual-norch.git`

##Installation

[VirtualBox](https://www.virtualbox.org/) is the virtualisation software that allows a 'host' operating system to run a 'guest' operation system.
[Vagrant](http://www.vagrantup.com/) is used to install and configure the guest OS.

Set up virtualisation by following these steps:

1. Install [VirtualBox](https://www.virtualbox.org/)
2. Install [Vagrant](http://www.vagrantup.com/)

##Operation

`vagrant up` - gets your virtual box up and running. May take a long time to download stuff the first time
you run it (Ubuntu is the standard OS). This script will clone, install and startup a norch in your virtual machine.

Your Norch should be available on `http://localhost:3000/`

##Shutdown

`vagrant destroy`

##Contributers

Niels Henrik Hagen [@nhhagen](https://github.com/nhhagen) - concept and prototype


