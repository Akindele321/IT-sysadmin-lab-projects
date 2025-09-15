# Hyper-VLAN Lab
Set up two TinyCore Linux VMs on Hyper-V, place their virtual NICs on VLANs, and test
basic connectivity. 

** You will see **

- Creating Generation 1 VMs on Hyper-V
- Attaching a bootable ISO
- Setting a Port VLAN ID on a Hyper-V virtual NIC
- Assigning static IPs in TinyCore Linux
- Verifying connectivity with 'ping'

## Topology

- **Host:** Windows with Hyper-V enabled
- **Virtual Switch:** 'Mod9Switch' (External or Internal)
- **VMs:** 'VM1' and 'VM2' (1 vCPU, 1024 MB)
- **Guest OS:** TinyCore Linux (Core-current.iso_
- **IP Plan (example):**
- 'VM1' - '10.0.0.10/24'
- 'VM2' - '10.0.0.20/24'

## Screenshots
![Hypervlan-1](./Hypervlanmanag-1.png)
![Hypervlan-2](./Hypervlanmanag-2.png)
![Hypervlan-3](./Hypervlanmanag-3.png)
![Hypervlan-4](./Hypervlanmanag-4.png)
![Hypervlan-5](./Hypervlanmanag-5.png)
![Hypervlan-6](./Hypervlanmanag-6.png)
![Hypervlan-7](./Hypervlanmanag-7.png)
![Hypervlan-8](./Hypervlanmanag-8.png)
![Hypervlan-9](./Hypervlanmanag-9.png)
![Hypervlan-10](./Hypervlanmanag-10.png)
