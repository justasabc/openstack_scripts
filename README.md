OpenStack Scripts
=================

# 1. introduction

## 1.1 description
OpenStack multi-node installer and uninstaller scripts and guides

## 1.2 contributors
* 2013.12 - justasabc

## 1.3 licenses
GLP 2.0

# 2. pre
## 2.1 check cpu

	vim ./pre/check_cpu

## 2.2 check nova-volume

	vim ./pre/check_nova_volume

# 3. controller node
## 3.1 install 

	vim ./same/interfaces
	source ./set_env
	./controller/install

## 3.2 uninstall

	./controller/uninstall

## 3.3 reinstall nova
	./controller/nova_uninstall
	./controller/nova_install


# 4. compute node
## 4.1 install 

	vim ./same/interfaces
	source ./set_env
	./node/install

## 4.2 uninstall

	./node/uninstall
