## Ethernet



The most common type of LAN **hardware** is known as Ethernet. In its simplest form, it consists of a single cable with hosts attached to it through connectors, taps, or transceivers. Simple Ethernets are relatively inexpensive to install, which together with a net transfer rate of 10, 100, or even 1,000 Megabits per second,accounts for much of its popularity.

Ethernets come in three flavors: thick, thin, and twisted pair.

Ethernet works like a bus system, where a host may send packets (or frames) of up to 1,500 bytes to
another host on the same Ethernet. A host is addressed by a six−byte address hardcoded into the firmware of
its Ethernet network interface card (NIC). These addresses are usually written as a sequence of two−digit hex numbers separated by colons, as in aa:bb:cc:dd:ee:ff.

 A frame sent by one station is seen by all attached stations, but only the destination host actually picks it up and processes it. If two stations try to send at the same time, a collision occurs. Collisions on an Ethernet are detected very quickly by the electronics of the interface cards and are resolved by the two stations aborting the send, each waiting a random interval and re−attempting the transmission.
