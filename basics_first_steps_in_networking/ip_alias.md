## IP alias

New kernels support a feature that can completely replace the dummy interface and serve other useful
functions. **IP Alias allows you to configure multiple IP addresses onto a physical device**. In the simplest case,you could replicate the function of the dummy interface by configuring the host address(or the host ID portion of an IP address), as an alias onto the [loopback interface, represented as *lo*](../linux_network_devices/linux_interfaces.md) and completely avoid using the dummy interface. In more complex uses, you couldconfigure your host to look like many different hosts, each with its own IP address. This configuration is
sometimes called *Virtual Hosting*.

To configure an alias for an interface, you must first ensure that your kernel has been compiled with support
for IP Alias (check that you have a /proc/net/ip_alias file; if not, you will have to recompile your
kernel). Configuration of an IP alias is virtually identical to configuring a real network device; you use a special name to indicate it's an alias that you want. For example:

```
 ifconfig lo:0 172.16.1.1
```

This command would produce an alias for the loopback interface with the address 172.16.1.1. IP aliases
are referred to by appending :n to the actual network device, in which n is an integer. In our example, the
network device we are creating the alias on is lo, and we are creating an alias numbered zero for it. This
way, a single physical device may support a number of aliases.
Each alias may be treated as though it is a separate device, and as far as the kernel IP software is concerned, it will be; however, it will be sharing its hardware with another interface.

