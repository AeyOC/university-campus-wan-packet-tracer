# IP Addressing Plan

This document records the addressing scheme defined for the university campus WAN project.

## Main Campus – WAN 1

### LAN 1 – Computer Lab

- Network: `172.16.10.0/24`
- Subnet mask: `255.255.255.0`
- Default gateway: `172.16.10.1`
- Router interface: `172.16.10.1/24`

### LAN 2 – Admin Office

- Network: `172.16.20.0/24`
- Subnet mask: `255.255.255.0`
- Default gateway: `172.16.20.1`
- Router interface: `172.16.20.1/24`

## Branch Campus – WAN 2

### LAN 3 – Library

- Network: `172.16.30.0/24`
- Subnet mask: `255.255.255.0`
- Default gateway: `172.16.30.1`
- Router interface: `172.16.30.1/24`

### LAN 4 – Faculty Office

- Network: `172.16.40.0/24`
- Subnet mask: `255.255.255.0`
- Default gateway: `172.16.40.1`
- Router interface: `172.16.40.1/24`

## WAN Serial Link

- Network: `10.10.10.0/30`
- Subnet mask: `255.255.255.252`
- Router 1 serial interface: `10.10.10.1/30`
- Router 2 serial interface: `10.10.10.2/30`

## Routing

The project requirements allow either static routing or a dynamic routing protocol such as RIP. The selected routing configuration should be documented and tested during the final implementation phase.
