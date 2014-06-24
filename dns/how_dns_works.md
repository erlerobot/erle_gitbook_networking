## How *DNS* works


How a DNS works in an image:

![DNS](img4/dns-rev-1.gif)

Note: In networking, when talking about caché we refer to data temporarily stored in anticipation of using them again and thus save computation time, search or download from the network.



As we have seen, DNS organizes hostnames in a domain hierarchy. A domain is a collection of sites that are related in some sense because they form a proper network (e.g., all machines on a campus, or all hosts on BITNET), because they all belong to a certain organization (e.g., the U.S. government), or because they're simply geographicallyclose. For instance, universities are commonly grouped in the edu domain, with each university or college using a separate subdomain, below which their hosts are subsumed.

>Groucho Marx University have the
groucho.edu domain, while the LAN of the Mathematics department is assigned maths.groucho.edu. Hosts on
the departmental network would have this domain name tacked onto their hostname, so erdos would be
known as erdos.maths.groucho.edu. This is called the fully qualified domain name (FQDN), which uniquely
identifies this host worldwide.

Organizing the namespace in a hierarchy of domain names nicely solves the problem of name uniqueness;
with DNS, a hostname has to be unique only within its domain to give it a name different from all other hosts worldwide. Furthermore, fully qualified names are easy to remember. Taken by themselves, these are already very good reasons to split up a large domain into several subdomains.

DNS does even more for you than this. It also allows you to delegate authority over a subdomain to its
administrators.

>For example, the maintainers at the Groucho Computing Center might create a subdomain for
each department; we already encountered the math and physics subdomains above. When they find the
network at the Physics department too large and chaotic to manage from outside (after all, physicists are known to be an unruly bunch of people), they may simply pass control of the physics.groucho.edu domain to the administrators of this network. These administrators are free to use whatever hostnames they like and assign them IP addresses from their network in whatever fashion they desire, without outside interference.

To this end, the namespace is split up into zones, each rooted at a domain. Note the subtle difference between a *zone* and a *domain*:

>The domain groucho.edu encompasses all hosts at Groucho Marx University, while the zone groucho.edu includes only the hosts that are managed by the Computing Center directly; those at the Mathematics department, for example. The hosts at the Physics department belong to a different zone,namely physics.groucho.edu.


