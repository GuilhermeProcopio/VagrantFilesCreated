# Vagrant 
Vagrant it`s a tool created by Hashicorp (insert link here) in (year)

Vagrant help to create and manage virtual machines, using operational system automated installation using infrastructure as code.

- Tool to developed to create and manage virtual machines
- Automated Operational System Installation
- Have CLI to create workflows
- Easy to use, focus on automation
- In DevOps culture: testing your IaC scripts

Vagrant Lifecycle

Lifecycle management of the machine:

- SSH for the VM - Vagrant SSH
- Halt/Shutdown for server
- Destroy machines and delete disks and metadata
- Package the machine and distribute

Vagrant File

- VagrantFile is the VM creation file

Share the host infrastructure

Text file - easy to versions

create in the current directory (using vagrant init)

Obs: VagrantFile for directory

More than one box in VagrantFile

Vagrant Boxes

- Box: OS Images
- You can clone an image
- Share with box file
- Multi-machines using the same Box

---

Vagrant Functionality

Forward ports

Share Directory

IaC

---

Obs:

Configure the .gitignore to ignore the .vagrant

vagrant destroy the machine, not the box

after edit the script, execute the destroy command

Install the vbguest modules

Forward in the mandatory ports (acima) of 1024

After all edit in the Vagrantfile execute the vagrant reload

Installing a plugin in vagrant

`vagrant plugin install vagrant-vbguest --plugin-version 0.21`
