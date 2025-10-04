# RIP-Dynamic-Routing-Lab-CCNA
CCNA RIP Dynamic Routing Lab using Cisco Packet Tracer. Includes step-by-step configuration, ping tests, and network topology

## Objective
- Learn and implement RIP dynamic routing across multiple routers.
- Verify connectivity using ping and troubleshooting techniques.

## Tools
- Cisco Packet Tracer
- Microsoft Word (documentation)
- Screenshots / Images for topology and ping tests

## Commands Used
- router rip
- network [ip address]
- show ip route
- ping

## Testing & Verification
- Ping tests between routers to confirm connectivity.
- Show ip route output confirms correct static routing.

## Files
- RIP Lab.pkt → Packet Tracer file
- RIP Documentation.pdf → Step-by-step guide
- Screenshots/ → Ping test results, router configurations

## Observations / Challenges
- All routers successfully exchanged routing tables automatically 
using RIP.
- The network achieved dynamic routing without manual route 
configuration.
- Missing connectivity (Ping failure): 
End devices couldn’t ping due to wrong IP addressing or 
subnet mismatch. 
   Fix: Checked interface IPs and subnet masks carefully.

## Documentation
- The complete step-by-step configuration and observations are available in the PDF below:
 [Static_Routing_Lab.pdf](https://github.com/user-attachments/files/22674493/Static_Routing_Lab.pdf)

## Topology Image
<img width="1365" height="713" alt="Image" src="https://github.com/user-attachments/assets/1e411593-1226-4e1c-8ae3-47afb309edc1" />
