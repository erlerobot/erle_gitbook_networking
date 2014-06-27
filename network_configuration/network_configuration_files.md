## Network configuration files

In Linux we are able to configure the network by editing the configuration files.We can find this files in the etc directory and edit them using, for example *vi* text editor.(If they don't exist, you can create them and they will update their content automatically).

![filesetc](img6/etc.jpg)

#### /etc/network/interfaces

Contains information required to configure the interfaces of host network at boot time. It also allows you to set static routes to other networks.

What you find if you go to networks directory and open interfaces, by typing:
```
vi interfaces
```
Is text editable file like this:

![interfaces](img6/interfaces.jpg)


####/etc/hostname
Here is specified the name of the machine.

![hostname](img6/hostname.jpg)

####/etc/hosts

As we have seen in [*5.1 Host Basics*](../host/host_basics.md), in the file /etc/hosts specify the IP along with the name of each machine you want to access by name.
The /etc/hosts file always contains the localhost IP address, 127.0.0.1, which is used for interprocess communication(never remove this line).Sometimes contains addresses of additional hosts, which can be contacted without using an external naming service such as DNS (the Domain Name Server).

![hosts](img6/hosts.jpg)

####/etc/resolv.conf

In the file / etc / resolv.conf specify what servers use to resolve domain names.

![conf](img6/netconf.jpg)

####/etc/nsswitch.conf

Defines the order in which to contact different name services.

![switch](img6/switch.jpg)
