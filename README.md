# University Campus WAN – Cisco Packet Tracer

## Project Overview

This repository contains the Cisco Packet Tracer project for CS360 Computer Networks. The project models a university network with a Main Campus and a Branch Campus connected through a serial WAN link.

The completed topology contains:

- 12 end devices
- 4 Cisco Catalyst 2960 switches
- 2 Cisco 2911 routers
- 4 LANs
- 1 serial WAN connection between the campuses

The objective is to provide successful end-to-end communication between devices located in different LANs across WAN 1 and WAN 2.

## Project Phases

### Phase 1 – Mid-Project Progress

Phase 1 covered the initial project setup and preparation, including Packet Tracer installation, device and cable studies, IP addressing planning, and the initial Packet Tracer project file.

### Phase 2 – Final Project

Phase 2 completes the network implementation and verification. The final work covers:

- Complete network topology
- LAN connections using appropriate Ethernet cabling
- End-device IP addressing and default gateways
- Router LAN interface configuration
- Serial WAN configuration between Router 1 and Router 2
- Routing between the two campus networks
- Connectivity testing using ping in both directions
- Final report evidence and reflection

## Network Addressing Plan

| Network | Purpose | Subnet | Default Gateway |
|---|---|---|---|
| LAN 1 | Computer Lab | `172.16.10.0/24` | `172.16.10.1` |
| LAN 2 | Admin Office | `172.16.20.0/24` | `172.16.20.1` |
| LAN 3 | Library | `172.16.30.0/24` | `172.16.30.1` |
| LAN 4 | Faculty Office | `172.16.40.0/24` | `172.16.40.1` |
| WAN Link | Router 1 ↔ Router 2 | `10.10.10.0/30` | N/A |

WAN serial interface addresses:

- Router 1: `10.10.10.1/30`
- Router 2: `10.10.10.2/30`

## Repository Contents

- `CS360_Project-Phase 1.pkt` — Packet Tracer project file currently stored in the repository
- `documentation/ip-addressing-plan.md` — IP addressing reference
- `documentation/phase1-submission-checklist.md` — Phase 1 submission checklist
- `documentation/phase2-repository-checklist.md` — Phase 2 repository/submission checklist

Additional final artifacts, such as the completed Phase 2 Packet Tracer file and final report, should be added as separate files so the Phase 1 artifact remains preserved.

## Academic Work and Repository Maintenance

The network design, Packet Tracer implementation, configuration, testing, and academic report content were completed by the student project team. Repository organization and presentation may be maintained separately from the underlying networking work.

## Version-Control Note

The initial Packet Tracer work was completed locally before this repository was used for structured version control. Repository commits reflect the actual dates on which files and documentation were added or reorganized; no historical timestamps are reconstructed or backdated.
