## What is *Networking*?



A *network* consists of multiple machines (computers) that are connected together and share each other all kinds of information. This connection between the network can be developed through waves and signals or wires, depending on which is most convenient for work and the type of information that needs to be shared.

In the *network* multiple machines (host) are connected to the comunication sub-net that allows the dialog between them. They can comunicate in two basic ways:

- Through channels point to point (PPP)
- Through broadcast channels

For communicating machines that aren't able to comunicate by themselves, **routers** (intermediate machines) are used.

Moreoever, the **protocols** are a set of rules (interfaces, algorithms, formats messages...) known by the entities exchanging data through the communications network.


The protocols used by the machines are organised in different **layers or levels**, in such a way that:

- Each layer offers services to a higher level
- Each layer is supported by services offered by a lower level

Each level in a machine "talks with" his twin
in another. The rules governing this "conversation" form the protocol of that level.

Here you can find some example of protocols and his corresponding level:

|**Layer name**|	** Protocols**|
|--------------------|-----------------------|
|Application layer|	HTTP, DNS, SMTP, POP, ...|
|Transport layer|	TCP, UDP|
|Network layer|	IP, IPv6|
|Network access layer|	PPP, PPPoE, Ethernet|

When we talk about **Network Architecture**, we are talking about the set of levels and protocols of a computers network.




