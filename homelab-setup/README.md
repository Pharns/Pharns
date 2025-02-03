# Homelab Setup

This documentation showcases my Proxmox-based homelab environment—a crucial element of my personal portfolio demonstrating my capabilities in cybersecurity research and testing.


## Key Features
- **Advanced Virtualization with Proxmox VE:** Efficiently utilizes Proxmox VE to build and manage a diverse array of virtual machines. This platform enables the agile deployment necessary for running complex simulations and experiments.
- **Diverse Security Tool Deployment:** Features dedicated virtual machines configured with industry-standard tools like Security Onion and Kali Linux, designed to mimic real-world cybersecurity infrastructures and scenarios.
- **Robust Network Segmentation:** Uses VLANs for meticulous traffic isolation, allowing for safe and isolated testing environments. This practice ensures controlled conditions for penetration testing and network security trials.
- **Secure Intranet Configuration with Tailscale:** Implements Tailscale to establish an encrypted and secure communication channel within the lab, further reinforcing the isolated and protected status of the network against external threats.
- **Practical Network Topology Visualization:** The network diagram provides a comprehensive view of the homelab’s architecture, designed to highlight segmentation strategies and secure interconnections best suited for defense-in-depth practices.

## Home Lab Topology
Below is the network diagram representing my Proxmox Virtual Environment (PVE). This detailed architecture highlights my ability to design and implement secure and efficient network infrastructures—a critical skill set for cybersecurity roles.
![Home Lab Network Diagram](https://raw.githubusercontent.com/Pharns/Pharns/main/homelab-setup/screenshots/CNN%20Network%20Diagram-Github.jpg)

## Screenshots
#### Proxmox Virtual Environment (PVE)
Here is a screenshot of the Proxmox VE interface, illustrating the system's capacity to host and manage a diverse range of virtual machines effectively.
![Proxmox Environment](https://raw.githubusercontent.com/Pharns/Pharns/main/homelab-setup/screenshots/Proxmox-Environment.png)

## Equipment
- [**Beelink SER5 Mini PC**](https://amzn.to/42DGjVC)
  - **Processor:** AMD Ryzen 7 5700U with Radeon Graphics
    - **Architecture:** x86_64
    - **Cores/Threads:** 8 cores, 16 threads
    - **Base/Max Frequency:** 1.8GHz base, up to 4.372GHz max
    - **Cache:** L1: 256 KiB, L2: 4 MiB, L3: 8 MiB
    - **Sockets:** 1
  - **Memory:** Corsair Vengence LPX DDR4 RAM 64GB ([Upgraded](https://amzn.to/3Q0ZPEc))
  - **Storage:**
    - **NVME:** 500GB (Main Drive)
    - **External SSD:** 2TB
    - **External HDD:** 4TB
  - **Graphics Support:** Integrated Radeon Graphics, supports 4K FPS
  - **Connectivity:** WiFi 6, Bluetooth 5.2, USB 3.2
  - **Virtualization:** AMD-V
