# Drybox

Drybox is a preconfigured vagrant box. It comes with Docker, Kubernetes, Git, Jenkins, and Ansible.

Ubuntu 16.04


### Install

Before you can use the box you need to have Virtualbox and Vagrant installed on your system.

##### Download Vagrant [here](https://www.vagrantup.com/).

##### Download Virtualbox [here](https://www.virtualbox.org/wiki/Downloads).


## Drybox Install

1. Make a new directory:
   `mkdir drybox`
   ![](images/drybox1.png)

2. In the new directory run this command:
   `vagrant init johnxeast/drybox`. This will create a file called '**Vagrantfile**' which is your vagrant config file. You can edit it as you wish.
   ![](images/drybox2.png)

3. You can validate the '**Vagrantfile**' with `vagrant validate`
   ![](images/drybox3.png)

