# pre

## pre check
vim ./pre/check_cpu

## nova-volume
vim ./pre/check_nova_volume


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


# compute node

## install 
vim ./same/interfaces
source ./set_env
./node/install

## uninstall
./node/uninstall
