# VLSM — Variable Length Subnet Masking

## Overview

This project demonstrates **Variable Length Subnet Masking (VLSM)** for IPv4 network planning. VLSM allows a network to be divided into subnets of different sizes according to the number of hosts required in each subnet.

## Objectives

- Understand the purpose of VLSM.
- Plan IPv4 subnets according to host requirements.
- Select suitable subnet masks for different subnet sizes.
- Use address space efficiently.
- Represent the network design in Cisco Packet Tracer.

## Project Files

- `VLSM.pkt` — Cisco Packet Tracer project file.
- `VLSM-Topology.png` — Network topology image.

## Method

VLSM network planning generally involves identifying the host requirements, arranging subnet requirements from largest to smallest, selecting suitable subnet masks, allocating non-overlapping address ranges, and assigning the resulting addresses to the relevant interfaces.

## Useful Verification Commands

```text
show ip interface brief
show running-config
```

These commands help inspect interface addressing and review device configuration in the Packet Tracer topology.

## Expected Learning Outcome

Understand how VLSM supports efficient IPv4 address allocation by assigning subnet sizes according to host requirements.

## Author

Ibrahim Baghareeb
