# University Campus Network Design

## Project Overview
This project involves designing a comprehensive network infrastructure for a small university campus. The network connects multiple faculties, labs, and a Scientific Computation Center, ensuring seamless access to internal and external networks.

## Project Objectives
- Provide reliable connectivity across all university facilities.
- Implement routing and VLAN to optimize traffic management and security.
- Ensure internet accessibility for all connected devices.

## Network Design Scope
1. **Faculties**:
   - 4 faculties, each consisting of 4 floors.
   - Each floor has 5 labs, with 10 PCs per lab.

2. **Scientific Computation Center**:
   - Equipped with several servers connected via a dedicated switch.

3. **Connections**:
   - Lab switches on each floor connect to a floor switch.
   - Floor switches connect to a main faculty switch.
   - Faculty switches and the Scientific Computation Center connect to a central university router.

4. **External Connectivity**:
   - The university router provides access to the World Wide Web.

## Technical Details
1. **IP Addressing**:
   - Classless IP addressing is employed to optimize public IP usage.

2. **Topologies**:
   - Star topology is used within labs for efficient connectivity.

3. **Routing and VLAN**:
   - RIP (Routing Information Protocol) manages inter-faculty and center data routing.
   - VLAN configurations segment and secure network traffic.

## Test Scenarios
1. **Scenario 1**:
   - Test data access from a PC in Lab 2 (1st floor of the Faculty of Computers & AI) to Server 0 in the Scientific Computation Center.
   - **Source IP**: PC 0 IP.
   - **Destination IP**: Server 0 IP.

2. **Scenario 2**:
   - Test VLAN communication between labs from different faculties.

3. **Scenario 3**:
   - Verify internet connectivity for a lab PC.

---
For more details, refer to the project documentation.

