## The default Docker networks 
* The bridge network connects the default docker virtual network through a NAT firewall to the physical network that the host VM is connected to. 
* The host network is a special network that skips the virtual networking of Docker and attaches the container directly to the host interface.
* The none network is not attached to anything.