# Futuristic Connectivity

*All power to the leafs!*

fc00 is an effort to a redistribution of power in computer networking.
We build an encrypted IPv6 network using public-key cryptography for
address allocation, and a distributed hash table for routing. This provides
near-zero-configuration networking, and prevents many of the security and
scalability issues that plague existing networks.

fc00 is named after the `fc00::/8` IPv6 address space which it inhabits.

To get a better idea of fc00, read the following documents.
Although they are slightly outdated, they capture the essence of fc00 very well.

- [Project goals of cjdns][goals]
- [Cjdns whitepaper][whitepaper]
- [The Edge of Dystopia][dystopia], cjd @ 30c3

[goals]: https://github.com/cjdelisle/cjdns/blob/master/doc/projectGoals.md
[whitepaper]: https://github.com/cjdelisle/cjdns/blob/master/doc/Whitepaper.md
[dystopia]: https://cdn.media.ccc.de/congress/2013/workshops/30c3-WS-en-YBTI_Routing-Caleb_James_Delisle-Edge_of_Dystopia.webm

## Preliminary Roadmap

- [ ] Specification of FCP, the *Futuristic Connectivity Protocol*,
      derived from the reference implementation [cjdns][cjdns].
  - [ ] CryptoAuth
  - [ ] Peering
  - [ ] Switch
  - [ ] Router
  - [ ] IPv6
  - [ ] IPTunnel
- [ ] Go implementation of FCP CryptoAuth and Switch
- [ ] Integration with [libp2p][libp2p]

[cjdns]: https://github.com/cjdelisle/cjdns
[libp2p]: https://github.com/ipfs/libp2p
