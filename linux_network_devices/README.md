## Linux Network Devices

The Linux kernel supports a number of hardware drivers for various types of equipment. This section gives a
short overview of the driver families available and the interface names they use.
There is a number of standard names for interfaces in Linux, which are listed here. Most drivers support more than one interface, in which case the interfaces are numbered, as in `eth0` and `eth1`:

####Lo

This is the local loopback interface. It is used for testing purposes, as well as a couple of network
applications. It works like a closed circuit in that any datagram written to it will immediately be
returned to the host's networking layer. There's always one loopback device present in the kernel, and
there's little sense in having more.

####eth0, eth1, &

These are the Ethernet card interfaces. They are used for most Ethernet cards, including many of the
parallel port Ethernet cards.

####tr0, tr1, &
These are the Token Ring card interfaces. They are used for most Token Ring cards, including
non−IBM manufactured cards.

####sl0, sl1, &
These are the SLIP interfaces. SLIP interfaces are associated with serial lines in the order in which
they are allocated for SLIP.

####ppp0, ppp1, &
These are the PPP interfaces. Just like SLIP interfaces, a PPP interface is associated with a serial line
once it is converted to PPP mode.

####plip0, plip1, &

These are the PLIP interfaces. PLIP transports IP datagrams over parallel lines. The interfaces are
allocated by the PLIP driver at system boot time and are mapped onto parallel ports. In the
2.0.x kernels there is a direct relationship between the device name and the I/O port of the parallel
port, but in later kernels the device names are allocated sequentially, just as for SLIP and PPP devices.

####ax0, ax1, &

These are the AX.25 interfaces. AX.25 is the primary protocol used by amateur radio operators.
AX.25 interfaces are allocated and mapped in a similar fashion to SLIP devices.
There are many other types of interfaces available for other network drivers. We've listed only the most
common ones.
