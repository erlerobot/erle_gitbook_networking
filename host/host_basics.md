# Host basics
---

A network host is a computer or other device connected to a computer network. A network host may offer information resources, services, and applications to users or other nodes on the network. A network host is a network node that is assigned a network layer host address.

The  /etc /hostname file contains the computer name
adopted when the operating system starts.
If you use the command `hostname`you can see the name of your host computer.
```
root@erlerobot:~# hostname
erlerobot
root@erlerobot:~#
```
The names of the machines can be with
complete or qualification relating to the local domain.

The /etc/host.conf tells the older Linux standard library resolver functions which services to use, and
in what order.In other words, host.conf indicates the order of the sources will use the address of operating system to obtain DNS resolutions requiring computer applications. There are two options:

- Look for them inside: /etc/hosts
- Search them outside: /etc/resolv.conf


Options in host.conf must appear on separate lines. Fields may be separated by white space (spaces or
tabs). A hash sign (#) introduces a comment that extends to the next newline. For example typing the option `order` etermines the order in which the resolving services are tried

The /etc/hosts is a simple mechanism of
name resolution. Contains one record per line, consisting of a IP address, hostname and optionally
a list of aliases for the hostname. The fields are separated by tabs or spaces and field with the @ IP should begin in the first column.The command `host` is a simple utility for performing DNS lookups. It is normally used to convert names to IP addresses and vice versa. When no arguments or options are given, host prints a short summary of its command line arguments and options.

The file /etc/resolv.conf contains the IP addresses of machines that can provide DNS services to
our host. The statement points to DNS nameserver have the function that the host can use them to make their decisions.

Moreover, just as with IP addresses, sometimes
You can also use a symbolic name for
network numbers. For this purpose, the file /etc/hosts has a companion called /etc /networks, that associates names network with corresponding numbers and vice versa.
