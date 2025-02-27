# 🏠 HomeLab Setup

This documentation showcases my Proxmox-based homelab environment—a crucial element of my personal portfolio demonstrating my capabilities in cybersecurity research and testing.


## 💡 Key Features
- **Advanced Virtualization with Proxmox VE:** Efficiently utilizes Proxmox VE to build and manage a diverse array of virtual machines. This platform enables the agile deployment necessary for running complex simulations and experiments.

  
- **Diverse Security Tool Deployment:** Features dedicated virtual machines configured with industry-standard tools like Security Onion and Kali Linux, designed to mimic real-world cybersecurity infrastructures and scenarios.

- **Robust Network Segmentation:** Uses VLANs for meticulous traffic isolation, allowing for safe and isolated testing environments. This practice ensures controlled conditions for penetration testing and network security trials.
  
- **Secure Intranet Configuration with Tailscale:** Implements Tailscale to establish an encrypted and secure communication channel within the lab, further reinforcing the isolated and protected status of the network against external threats.
  
- **Practical Network Topology Visualization:** The network diagram provides a comprehensive view of the homelab’s architecture, designed to highlight segmentation strategies and secure interconnections best suited for defense-in-depth practices.

## 🌐 Home Lab Topology

The network diagram below illustrates the architecture of my homelab's Proxmox Virtual Environment (PVE). This setup serves as a practical learning environment where I'm developing and refining skills in network design, security implementation, and infrastructure management.


![Home Lab Network Diagram](https://raw.githubusercontent.com/Pharns/Pharns/main/homelab-setup/screenshots/CNN%20Network%20Diagram-Github.jpg)


## 🛠️ **Homelab Setup**
- **Objective:** Build a comprehensive virtualized security lab using Proxmox VE for research, testing, and skill development.
- **Infrastructure:**
  - pfSense Firewall with segmented VLANs for security isolation
  - Zero Trust Network implementation using numerous tools (Tailscale, Twingate, Netbird)
  - Self-hosted services (VLAN 100) including Whonix, n8n, Nextcloud, and Kasm Workspaces
  - Dedicated Attack/Security Tools subnet featuring:
    - Security Onion for network monitoring
    - The Hive + Cortex for incident response
    - Nessus for vulnerability scanning
    - Wazuh for SIEM capabilities
    - Caldera for adversary emulation

- **Network Segmentation:**
  - VLAN 10: Metasploit & DVWA testing environment
  - VLAN 20: Windows environment with Active Directory
  - VLAN 30: Ubuntu with Docker, Portainer, and bWAPP
  - VLAN 100: Self-hosted services
  
- **Key Features:**
  - Multi-layered security architecture
  - Isolated testing environments
  - Enterprise-grade security tools
  - Automated workflow capabilities


## 💻 Proxmox Virtual Environment (PVE)
Screenshot of the Proxmox VE interface, illustrating the system's capacity to host and manage a diverse range of virtual machines effectively.


![Proxmox Environment](https://raw.githubusercontent.com/Pharns/Pharns/main/homelab-setup/screenshots/Proxmox-Environment.png)

## ⚙️ Equipment
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



## 🚀 My Journey: Building a Virtual Security Lab with Proxmox

I'd love to share one of my favorite projects: setting up a home cybersecurity lab using Proxmox on a Beelink SER5 Mini PC. This project combines my passion for hands-on learning with practical cybersecurity skills—and I've learned a **TON** along the way!

### 🎯 Why This Matters
Before diving into the technical details, let me explain why this project excites me. This lab serves as my personal testing ground where I can safely:
- Experiment with security tools and configurations
- Practice incident response scenarios
- Learn new cybersecurity techniques
- Test security solutions before implementing them

### 🔄 The Setup Journey: Making It Happen

#### 📋 Planning Phase
Just like in a professional environment, I started with careful planning:
- Researched the best hardware for my needs (the Beelink SER5 proved perfect!)
- Created a detailed checklist to ensure nothing was missed
- Kept security in mind from the very beginning
- Documented everything (a habit I learned in my nursing days)

#### 📝 Step-by-Step Implementation
1. **Getting Started**
   - Downloaded Proxmox VE from the official source
   - Verified SHA256 hash to ensure file integrity
   - Validated GPG signatures for authenticity
   - Created installation media using Balena Etcher

2. **BIOS Setup**
   - To access BIOS: 
     - Power on the Beelink
     - Repeatedly press either Delete, F2, or F10 during startup
   - Once in BIOS:
     - Enabled critical security features
     - Modified boot sequence for installation
     - Saved configuration changes

3. **Installation and Security**
   - Installed Proxmox VE with security in mind
   - Set up strong passwords and authentication
   - Made sure everything was properly configured

4. **Network Setup**
   - Configured the network securely
   - Set up protective firewall rules
   - Ensured safe remote access
   - Added monitoring to keep an eye on things

5. **Making It Secure**
   - Updated everything to the latest versions
   - Added extra security measures
   - Set up regular backups (better safe than sorry!)

## 📈 Project Impact & Growth

### 🧠 Key Learning Outcomes
- **Infrastructure Management**
  - Secure virtual environment administration
  - Resource optimization and monitoring
  - System hardening and security controls

- **Security Implementation**
  - Industry best practices deployment
  - Risk assessment and mitigation
  - Security tool integration and testing

- **Professional Development**
  - Technical problem-solving
  - Process documentation
  - Project management skills

### ⭐ Ongoing Improvements
- **Laboratory Enhancement**
  - Integration of advanced security tools
  - Robust backup solution implementation
  - Performance optimization and monitoring
  - Enhanced security controls

- **Infrastructure Expansion**
  - Self-hosted service deployment
  - Ansible automation implementation
  - Continuous integration/deployment practices

### 💼 Professional Applications
This hands-on project demonstrates practical experience in:
- Building secure, scalable environments
- Implementing enterprise-level security controls
- Developing automated solutions
- Managing complex technical infrastructures

What began as a personal learning initiative has evolved into a comprehensive platform for practical cybersecurity experience. I'm enthusiastic about applying these skills in a professional setting, where I can contribute to security initiatives while continuing to grow alongside industry experts.

### 🤝 Moving Forward
I remain committed to:
- Expanding technical capabilities
- Staying current with security trends
- Contributing to team success
- Sharing knowledge and experiences

What began as a personal homelab has matured into an extensive learning environment that reflects real-world security operations. Through this experience, I've developed practical skills that align directly with industry needs. I'm excited about the opportunity to apply this knowledge in a professional role, where I can contribute to strengthening security infrastructure while collaborating with and learning from experienced team members.
