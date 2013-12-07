OpenStack Essex Installer Scripts
=================

# 1. introduction

## 1.1 description
OpenStack essex multi-node installer and uninstaller scripts and guides for Ubuntu 12.04 Server 64-bit x86. Feel free to get copy of this repository.

`git clone https://github.com/justasabc/openstack_scripts.git`

## 1.2 contributors
* 2013.12 - [justasabc](http://github.com/justasabc)

## 1.3 licenses
Apache 2.0

## 1.4 version
* OS: Ubuntu 12.04 Server 64-bit x86
* OpenStack: Essex

# 2. pre-check

## 2.1 check cpu

	vim ./pre/check_cpu

## 2.2 check nova-volume

	vim ./pre/check_nova_volume

# 3. controller node
## 3.1 set env 

	vim ./same/interfaces
	source ./set_env

## 3.2 install 

	cd ./controller/
	./install

## 3.3 uninstall

	cd ./controller/
	./uninstall

## 3.4 reinstall nova

	cd ./controller/
	./nova_uninstall
	./nova_install

# 4. compute node
## 4.1 set env 

	vim ./same/interfaces
	source ./set_env

## 4.2 install 

	cd ./node/
	./install

## 4.2 uninstall

	cd ./node/
	./uninstall
