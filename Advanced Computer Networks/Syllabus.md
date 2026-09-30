# Advanced Computer Networks

**Backbone:** Stanford CS144 (build a TCP stack); *Computer Networks: A Systems Approach* by Peterson & Davie (free online); Stanford CS244 or Princeton COS 561 reading lists for advanced papers.

**Topics**

1. TCP internals: congestion control (Reno, CUBIC, BBR), flow control, retransmission
2. QUIC and HTTP/3; TLS 1.3 handshake
3. Datacenter topologies: Clos/fat-tree, ECMP, oversubscription
4. SDN: control/data plane separation, OpenFlow history, P4
5. Network measurement and telemetry: sFlow, INT, gNMI streaming
6. Congestion in datacenters: ECN, DCTCP, incast
7. Routing at scale: BGP in the datacenter (RFC 7938), EVPN-VXLAN

**Projects**

- Complete the CS144 TCP implementation labs.
- **Congestion-control lab:** in Mininet or ns-3, compare CUBIC, BBR, and DCTCP under incast and report the results with graphs.
- **EVPN-VXLAN fabric in containerlab:** build a 2-spine/4-leaf fabric with FRRouting, then break links and measure convergence.
