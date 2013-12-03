OpenStack Scripts
=================

# introduction

## description
OpenStack multi-node installer and uninstaller scripts and guides

## contributors
* 2013.12 - justasabc

## licenses
GLP 2.0

------
# pre
## pre check

	vim ./pre/check_cpu

## nova-volume

	vim ./pre/check_nova_volume


------
# controller node
## install 

	vim ./same/interfaces
	source ./set_env
	./controller/install

## uninstall

	./controller/uninstall

## reinstall nova
	./controller/nova_uninstall
	./controller/nova_install


------
# compute node
## install 

	vim ./same/interfaces
	source ./set_env
	./node/install

## uninstall

	./node/uninstall
