# University Campus WAN – Cisco Packet Tracer

## Project Overview

This repository contains one Cisco Packet Tracer project developed for CS360 Computer Networks and submitted in two reporting periods: Phase 1 and Phase 2.

The project models a university with a Main Campus and a Branch Campus connected through a serial WAN link. The completed topology contains:

- 12 end devices
- 4 Cisco Catalyst 2960 switches
- 2 Cisco 2911 routers
- 4 LANs
- 1 serial WAN connection between the campuses

The objective is to provide successful end-to-end communication between devices located in different LANs across WAN 1 and WAN 2.

## Submission Phases

### Phase 1 – Mid-Project Progress Report

Phase 1 documented the initial project work, including:

- Cisco Packet Tracer installation and study
- Device selection and node creation
- Study of copper straight-through, copper cross-over, and serial DCE/DTE links
- IP addressing planning
- Initial topology preparation
- Selection of static routing as the intended routing method
- Identification and resolution of the Cisco 2911 serial-interface module issue

### Phase 2 – Final Project Report

Phase 2 documented completion and verification of the same Packet Tracer project, including:

- Complete topology with all required nodes
- LAN cabling and router connections
- End-device IPv4 addressing, subnet masks, and default gateways
- Router LAN interface configuration
- Serial WAN configuration between Router 1 and Router 2
- Static routing between the two campus networks
- Successful end-to-end ping testing in both directions
- Final written reflection and project artifacts

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

- `CS360_Project.pkt` — the single Cisco Packet Tracer project used across both Phase 1 and Phase 2 submissions
- `documentation/ip-addressing-plan.md` — project IP addressing reference
- `documentation/phase1-submission-checklist.md` — Phase 1 submission checklist
- `documentation/phase2-repository-checklist.md` — Phase 2 repository/submission checklist

## Project Structure

This course project used one continuously developed Packet Tracer file rather than separate project files for each phase. Phase 1 and Phase 2 are reporting milestones for the same network project.

## Version-Control Note

The Packet Tracer project was initially created locally and then added to this repository for submission and ongoing documentation. Repository commits reflect the actual dates when files and documentation were added, renamed, organized, or updated. No historical timestamps were reconstructed or backdated.
