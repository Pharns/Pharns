# Homelab Setup

This documentation showcases my Proxmox-based homelab environment—a crucial element of my personal portfolio demonstrating my capabilities in cybersecurity research and testing.


## Key Features
- **Advanced Virtualization with Proxmox VE:** Efficiently utilizes Proxmox VE to build and manage a diverse array of virtual machines. This platform enables the agile deployment necessary for running complex simulations and experiments.
- **Diverse Security Tool Deployment:** Features dedicated virtual machines configured with industry-standard tools like Security Onion and Kali Linux, designed to mimic real-world cybersecurity infrastructures and scenarios.
- **Robust Network Segmentation:** Uses VLANs for meticulous traffic isolation, allowing for safe and isolated testing environments. This practice ensures controlled conditions for penetration testing and network security trials.
- **Secure Intranet Configuration with Tailscale:** Implements Tailscale to establish an encrypted and secure communication channel within the lab, further reinforcing the isolated and protected status of the network against external threats.
- **Practical Network Topology Visualization:** The network diagram provides a comprehensive view of the homelab’s architecture, designed to highlight segmentation strategies and secure interconnections best suited for defense-in-depth practices.

## Home Lab Topology

The network diagram below represents my Proxmox Virtual Environment (PVE). This detailed architecture highlights my ability to design and implement secure and efficient network infrastructures—a critical skill set for cybersecurity roles.


![Home Lab Network Diagram](https://raw.githubusercontent.com/Pharns/Pharns/main/homelab-setup/screenshots/CNN%20Network%20Diagram-Github.jpg)

## Screenshots
#### Proxmox Virtual Environment (PVE)
Screenshot of the Proxmox VE interface, illustrating the system's capacity to host and manage a diverse range of virtual machines effectively.


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
 
## Installing Proxmox on the Beelink

Let me share how I set up Proxmox on my Beelink SER5 Mini PC—a straightforward and fun process!

### Step 1: Preparing the USB Stick
First, I grabbed a USB stick with at least 2GB of space. I visited the [Proxmox website](https://www.proxmox.com/en/downloads) to download the Proxmox VE ISO image. Using a handy tool like Rufus, I created a bootable USB drive from the downloaded ISO.

### Step 2: Booting from the USB
Once my USB was ready, I plugged it into the Beelink. I restarted the PC and hit `Del` to enter the BIOS settings. Here, I switched the boot order to prioritize the USB stick and saved the changes.

### Step 3: Installing Proxmox
As the PC booted up, the Proxmox installer appeared. I selected "Install Proxmox VE" and agreed to the usual license agreement. I chose the NVMe drive for installation and set up my country, time zone, and keyboard layout.

### Step 4: Configuring the Network
Next, I configured the network settings. I went with the default DHCP option, which was easy. I also set a strong password and entered my email for any necessary notifications.

### Step 5: Completing the Installation
With everything set, I clicked “Install” and let Proxmox do its thing. Once the installation finished, I removed the USB stick and rebooted the system.

### Step 6: Accessing Proxmox
Finally, on another device, I opened a web browser and navigated to `https://<my-proxmox-ip>:8006`. I logged in using the credentials I had set, and just like that, my Beelink was a fully functioning Proxmox powerhouse!

This setup opened up a world of virtual machine possibilities, and I'm excited to explore more. If you're considering this setup, I hope my experience gives you the confidence to dive in!
