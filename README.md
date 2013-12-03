OpenStack Scripts
=================

# 1. introduction

## 1.1 description
OpenStack multi-node installer and uninstaller scripts and guides.Feel free to get copy of repository.(https://github.com/justasabc/openstack_scripts.git)

## 1.2 contributors
* 2013.12 - [justasabc](http://github.com/justasabc)

## 1.3 licenses
GPL 2.0

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

	./controller/install

## 3.3 uninstall

	./controller/uninstall

## 3.4 reinstall nova

	./controller/nova_uninstall
	./controller/nova_install

# 4. compute node
## 4.1 set env 

	vim ./same/interfaces
	source ./set_env

## 4.2 install 

	./node/install

## 4.2 uninstall

	./node/uninstall
