## UTP Cables
| Device Type | Transmit (Tx) Pins | Receive (Rx) Pins |
|-------------|--------------------|-------------------|
| Router      | 1 and 2            | 3 and 6           |
| Firewall    | 1 and 2            | 3 and 6           |
| PC          | 1 and 2            | 3 and 6           |
| Switch      | 3 and 6            | 1 and 2           |

## Eternet Standards (UTP Cables copper)
| Speed    | Common name      | IEEE Standard | Informal Name | Maximum Length |
|----------|------------------|---------------|---------------|----------------|
| 10 Mbps  | Ethernet         | 802.3i        | 10BASE-T      | 100m           |
| 100 Mbps | Fast Ethernet    | 802.3u        | 100BASE-T     | 100m           |
| 1 Gbps   | Gigabit Ethernet | 802.3ab       | 1000BASE-T    | 100m           |
| 10 Gbps  | 10 Gig Ethernet  | 802.3an       | 10GBASE-T     | 100m           |

## Fiber-Optic Cable Standards
| Informal Name | IEEE Standard | Speed   | Cable Type               | Maximum Length     |
|---------------|---------------|---------|--------------------------|--------------------|
| 1000BASE-LX   | 802.3z        | 1 Gbps  | Multimode or Single-Mode | 500m (MM) 5km (SM) |
| 100GBASE-SR   | 802-3ae       | 10 Gbps | Multimode                | 400m               |
| 10GBASE-LR    | 802.3ae       | 10 Gbps | Single-Mode              | 10km               |
| 10BASE-ER     | 802.3ae       | 10 Gbps | Single-Mode              | 30km               |

### UTP
- Lower cost than fiber-optic
- Shorter maximum distance than fiber-optic (100m)
- Can be vulnerable to EMI (Electromagnetic interference)
- RJ45 ports used with UTP are cheaper than SFP ports
- Emit (leak) a faint signal outside of the cable, whick can be copied (security risk)

### Fiber-optic
- Higher cost than UTP
- Longer maximum distance than UTP
- No vulnerability to EMI
- SFP ports are more expensibe than RJ45 ports (single-mode is more expensive than multimode)
- Does not emit any signal outside of the cable (=no security risk)