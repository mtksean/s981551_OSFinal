# s981551_report
OS Final report on markdown
                                        The Internet Protocol (IP)  
Student: s981551
Name: Sean
The Internet Protocol (IP) provides a service to the transport layer. IP is responsible for
Delivering the data to the required destination, from host to host. It deals with the routing
of packets through a network. One can only begin to imagine what an audacious task that
is, taking into consideration the size and global reach of the Internet, the number of hosts
and as a consequence the number of IP address prefixes.

IP provides a connection-less service and one that is not reliable. It does not guarantee the
delivery of data to the intended destination. Moreover, IP does not try to retransmit lost
data. IP packets often arrive at the destination out of sequence because they may have
been routed through the network via different paths or asymmetrically, i.e., using a
different path from source to destination and then back to the source. It leaves the task of
untangling these packets and placing them in some sort of comprehensible order, and
Re-transmission when required, to the layers above the network (IP) layer.

Each IP packet is an independent entity and IP maintains no state information on any IP
packets transmitted. The four-byte (32bit) IP address is used to identify the source and
destination of the IP datagram.
IP uses an 8-bit protocol identifier that identifies the upper layer the data belongs to, and
subsequently where to send the data.

Internet Protocol Version 6 (IPv6)
We are very quickly running out of IPv4 address space. No one can really blame the
engineers who originally thought that a 32-bit address space, equivalent to 4.3 billion
unique addresses - would be adequate. Considering that the world population at the time
was roughly 3.7 billion people (now 7.2b), it was perhaps a fair assumption to make. This
network after all was only required to support an Arpanet experiment. The original IP
network was never designed to support commercial use or global and ubiquitous
proliferation of the Internet we have today.

Nevertheless, IPv4 has being able to support extraordinary network growth over several
decades, adapting and scaling to support several previously unimaginable demands.
Initially, IP address management was not disciplined or that well-structured. In fact, to put
it politely, IP address requirements were not adequately defined or justified. During this
early period, the distribution and allocation of IP addresses was quite generous. By the
early to mid-nineties it was becoming quite clear that something had to be done to help
conserve IP address space as it was very quickly running out. The global Internet
addressing authority’s implemented very strict IP address allocations to service providers,
their customers and other Internet users. In parallel, IP addresses were designed in a way
that introduced the IP Classless Network – Please see the Classless IP Address
Assignment section in this e-book for more information. Other IPv4 features such as
Network Address Translation (NAT), which enables the mapping of private IP addresses
to public. And Port Address Translation (PAT), that enables the mapping of multiple IP
addresses, typically private, to one public facing IP address. The translation of return
traffic is achieved using UDP/TCP application ports and a translation table. However, all
these efforts were in vain as it became clear that over time and with the ever-increasing
popularity of the Internet, and the introduction over the years of mobile phone users, it
was only a matter of time before IPv4 addresses would eventually be completely
exhausted.

The solution to the problem of IP address exhaustion was IPv6, originally documented in
December 1995 in RFC1883. This RFC is now obsolete and has been superseded by RFC
2460 issued in December 1998. IPv6 was developed by the IETF.
IPv6 supports 3.4 x 10^38 IP addresses. Simply put, this number is vast. It is somewhat
difficult to put into perspective the size and magnitude of unique addresses IPv6 can
support. One way to think of it is - the number 3 followed by 38 zeros! Another way to
think about it is that there are enough addresses to allocate a few hundred to each known
star in our known Universe. Suffice it to say that we perhaps learnt from the original IPv4
limitation and were very determined to never be in a position of completely exhausting the
number of available IP addresses again.

Next Generation IP Networks
We often hear about Next Generation IP networks (IP NGN) and the use of this term is
now becoming a little overused. The best and most comprehensive definition is perhaps
The International Telecommunication Union (ITU) concept of IP NGN. The ITU has
specified the following as key characteristics of the IP NGN:
-Packet-based transfer
-Separation of control functions among bearer capabilities, call/session, and
application/service
-Support for a wide range of services, applications and mechanisms based on service
building blocks (including real time/streaming/non-real time services and multi-media)
-Broadband capabilities with end-to-end QoS and transparency
-Interworking with legacy networks via open interfaces
-Generalized mobility
-Unfettered access by users to different service providers
-Unified service characteristics for the same service as perceived by the user
-Converged services between Fixed and Mobile networks
-Independence of service-related functions from underlying transport technologies
-Support of multiple last mile technologies
-Compliant with all Regulatory requirements, for example concerning emergency
communications and security/privacy, etc.
-All kinds of services over all kinds of media
-Decoupling services from networks so that a service is neither defined by nor limited to
the type of network providing the service
-Interworking existing networks into a single network
-Open interfaces that offer flexibility to service providers
-Generalized mobility, enabling end users access to services wherever they may be
Summary
-Transmission Control Protocol and the User Datagram Protocol are transport layer
protocols responsible for the flow of data between end systems
-The Internet Protocol (IP) provides a service to the transport layer. IP is responsible for
delivering the data to the required destination, from host to host.
-The Internet Control Message Protocol (ICMP) sits directly on top of IP and provides
error and control messaging.
-The solution to the problem of IPv4 address exhaustion was IPv6, originally documented
in December 1995 in RFC1883. This RFC is now obsolete and has been superseded by
RFC 2460 issued in December 1998. IPv6 was developed by the IETF
