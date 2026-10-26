# Cisco Routing & Switching Labs

**Author:** Sawed Kotawdekar
**Portfolio focus:** CCNA-level routing, switching, and network configuration practice  
**File format:** Cisco Packet Tracer (`.pkt`)

This repository collects Packet Tracer practice projects covering static routing, dynamic routing protocols, VLANs, and trunking.

> **Verification note:** The `.pkt` files are preserved from the supplied archive. The topologies, IP addressing, protocol settings, and end-to-end connectivity have not been independently verified in this preparation step. Add screenshots and command outputs after opening each lab in Cisco Packet Tracer.

## Projects

| Area | Project files | Topics to document and verify |
|---|---|---|
| Static routing | `01-static-routing/` | Interface addressing, next-hop/static routes, routing table, end-to-end ping |
| RIP | `02-rip/` | RIP version, advertised networks, learned routes, connectivity |
| OSPF | `03-ospf/` | Area configuration, neighbor adjacency, OSPF routes, connectivity |
| EIGRP | `04-eigrp/` | AS number, neighbor relationships, learned routes, connectivity |
| BGP | `05-bgp/` | AS numbers, peerings, advertised/received routes, connectivity |
| VLAN | `06-vlan/`, `08-vlan-practice/` | VLAN IDs/names, port assignments, inter-VLAN routing if configured |
| Trunking | `07-trunking/` | Trunk ports, allowed VLANs, native VLAN if configured |

## How to use the labs

1. Install or open Cisco Packet Tracer.
2. Open the relevant `.pkt` file.
3. Review the topology and interface labels.
4. Inspect the device configurations and complete the project README with the actual IP addressing and commands used.
5. Verify configuration using the relevant `show` commands and ping tests.
6. Capture clear screenshots of the topology and successful verification.

## Suggested verification commands

Use only the commands relevant to the lab:

- General: `show ip interface brief`, `show running-config`, `show ip route`
- Static routing: `show ip route static`
- RIP: `show ip protocols`
- OSPF: `show ip ospf neighbor`, `show ip ospf interface brief`
- EIGRP: `show ip eigrp neighbors`, `show ip protocols`
- BGP: `show ip bgp summary`, `show ip bgp`
- VLANs: `show vlan brief`
- Trunking: `show interfaces trunk`

Command availability can vary by device model and Packet Tracer version.

## Repository structure

```text
01-static-routing/
02-rip/
03-ospf/
04-eigrp/
05-bgp/
06-vlan/
07-trunking/
08-vlan-practice/
```

Each folder includes a project-specific README checklist. Replace any placeholders with details confirmed from the actual Packet Tracer lab.

## Skills demonstrated

- IPv4 addressing and subnetting
- Static and dynamic routing concepts
- Routing and switching configuration
- Network troubleshooting and connectivity validation
- Technical documentation

Only list a skill as demonstrated in a specific project after verifying the lab and documenting the evidence.

## Safety and sharing

These are lab files intended for learning. Do not add passwords, personal information, or configuration from networks you do not have permission to share.
