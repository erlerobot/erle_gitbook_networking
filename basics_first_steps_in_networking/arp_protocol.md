## ARP protocol

The ARP protocol allows to find out the Ethernet address of a machine knowing its IP address.

The `arp` utility displays and modifies the Internet-to-Ethernet address translation tables used by the address resolution protocol (arp(4)).
With no flags, the program displays the current ARP entry for hostname.The host may be specified by name or by number, using Internet dot notation.

One of the most useful commands is:
```
arp -a
```

With this the program displays or deletes all of the current ARP entries.
