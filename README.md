# University Campus WAN – Cisco Packet Tracer

## Project Overview

This repository contains the Cisco Packet Tracer work for a university network project connecting a Main Campus and a Branch Campus across a WAN serial link.

The design includes four LANs, two routers, four switches, and twelve end devices. Each campus contains two LANs, and communication between campuses is provided through routing between Router 1 and Router 2.

## Phase 1 Scope

Phase 1 focuses on project preparation and progress documentation, including:

- Installing and studying Cisco Packet Tracer
- Creating and connecting network devices
- Studying copper straight-through, copper cross-over, and serial DCE/DTE links
- Planning the IP addressing scheme
- Preparing the initial Packet Tracer project file
- Identifying the routing approach to be completed/tested in the next phase

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

## Repository Files

- `CS360_Project-Phase 1.pkt` — Cisco Packet Tracer Phase 1 project file
- `documentation/ip-addressing-plan.md` — detailed IP addressing reference
- `documentation/phase1-submission-checklist.md` — Phase 1 submission checklist

## Project Objective

The final project objective is to configure and test successful packet transmission between devices in any LAN in WAN 1 (Main Campus) and devices in any LAN in WAN 2 (Branch Campus).

## Version-Control Note

The initial Phase 1 Packet Tracer work was completed locally before this repository was used for structured version control. Subsequent documentation and repository improvements are tracked through the repository commit history using their actual timestamps.
