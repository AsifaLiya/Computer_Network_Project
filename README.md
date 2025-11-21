# Computer_Network_Project
This is my First project in GitHub.
<br>
Author - Asifa Akter Liya & Benazir Meem.
<br>
# EWUX University Multi-Campus Network Project

**Description**  
This project presents the design, implementation, and analysis of a multi-campus enterprise network for **EWUX University**, modeled after a large-scale university network. The project simulates a real-world university networking environment, including wired and wireless connectivity, critical services, and inter-campus communication.

---

## What We Did

### 1. Network Design
- Developed a multi-campus network topology with **seven campuses**, each having wired and wireless devices.  
- Designed **subnets** for classrooms, labs, administrative units, and libraries, ensuring at least **three devices per subnet**.  
- Interlinked **seven routers nonlinearly** to efficiently manage inter-campus traffic.  
- Prepared a complete **static IP addressing plan** for all devices.

### 2. Implementation (Cisco Packet Tracer)
- Configured routers, switches, and end devices based on the design.  
- Implemented **three separate network configurations** using **RIP, OSPF, and EIGRP** routing protocols.  
- Verified connectivity across all campuses using **ping**, **tracert**, and routing table commands.

### 3. Testing & Diagnosis
- Conducted **ping tests** between campuses to verify connectivity.  
- Used **tracert** to confirm OSPF path selection.  
- Examined router behavior with:  
  - `show ip route`  
  - `show ip protocols`

### 4. Protocol Comparison & Analysis
- Compared **RIP, OSPF, and EIGRP** in terms of:  
  - Route propagation  
  - Convergence speed  
  - Routing table structure  
- Documented observations, challenges, and troubleshooting steps for each protocol.

### 5. Optional Enhancements (Simulation)
- Configured **DHCP** for a single LAN.  
- Set up a **DNS server** for the university web address.  
- Created **VLAN segmentation** for students, staff, and administrative units.  
- Applied **ACLs** to control traffic.  
- Simulated **link failures** to observe OSPF convergence.

---

## Tools Used
- **Cisco Packet Tracer** for network simulation and implementation  
- Handwritten/network design diagrams for topology planning  

---

## Outcome
The project successfully demonstrated a fully functional, multi-campus network, highlighting the differences between routing protocols, and provided hands-on experience in **designing, implementing, and troubleshooting large-scale enterprise networks**.
