# Hacking Setup
## Description
This is my personal setup for my pentest missions. I'm using Vagrant and shell scripting to automate the creation of new pentest VMs. This setup is widely inspired by @danymat, thank you (see https://github.com/danymat/pentest-lab)

## Prerequisites
- Vagrant (https://www.vagrantup.com)
- VMWare Fusion 13 Player (https://www.vmware.com/fr/products/fusion.html)

As I am running a M1 Pro chip, this gist have been usefull to install both Vagrant & VMWare Fusion 13 Player (https://gist.github.com/sbailliez/2305d831ebcf56094fd432a8717bed93)

Furthermore, as no trustable kali linux is available on Vagrant Cloud (https://app.vagrantup.com/boxes/search?utf8=%E2%9C%93&sort=downloads&provider=&q=kali+arm), it's also needed to have a manually created vagrant box (more on that later)

## Run
- `vagrant up`
- `vagrant ssh`
