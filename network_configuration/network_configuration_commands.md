## Network configuration commands



There are many more parameters to `ifconfig` than we have described so far. Its normal invocation is this:
```
ifconfig interface [address [parameters]]
```
interface is the interface name, and address is the IP address to be assigned to the interface. This may
be either an IP address in dotted quad notation or a name that `ifconfig` will look up in /etc/hosts.

```
ifconfig
```
As we have seen this command displays the configuration information for all network interfaces of the system.

![ifconf](img6/ifconf.jpg)

```
ifconfig eth0 down
```
Disables the network interface eth0.

```
ifconfig eth0
```
Check the status of the eth0 interface.

![ifcon2](img6/iconf1.jpg)

```
ifconfig interfase dirección-ip
```

Interfacing basic configuration.Asign IP address and activates it. The other parameters take values assigned by default.For example, the subnet mask takes the value corresponding to the type of network the Ip address belong to.Like that we have  255.255.0.0 for a vlass B address.

```
ifconfig eth0 100.200.26.1 netmask 255.255.255.0 broadcast 100.200.26.255
```
Sets the network interface from scratch.
