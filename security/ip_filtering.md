## IP Filtering

IP filtering is simply a mechanism that decides which types of IP datagrams will be processed normally and
which will be discarded. By discarded we mean that the datagram is deleted and completely ignored, as if it
had never been received. You can apply many different sorts of criteria to determine which datagrams you
wish to filter; some examples of these are:

- Protocol type: TCP, UDP, ICMP, etc.
- Socket number (for TCP/UPD).
- Datagram type: SYN/ACK, data, ICMP Echo Request, etc.
- Datagram source address: where it came from.
- Datagram destination address: where it is going to.

It is important to understand at this point that IP filtering is a network layer facility. This means it doesn't understand anything about the application using the network connections, only about the connections themselves. For example, you may deny users access to your internal network on the default telnet port, but if you rely on IP filtering alone, you can't stop them from using the telnet program with a port that you do allow to pass trhough your firewall. You can prevent this sort of problem by using proxy servers for each service that you allow across your firewall. The proxy servers understand the application they were designed to proxy and can therefore prevent abuses, such as using the telnet program to get past a firewall by using the World
Wide Web port.

 If you want to read more visit the chapter about IP filtering [here](http://www.tldp.org/LDP/nag2/nag2.pdf).



