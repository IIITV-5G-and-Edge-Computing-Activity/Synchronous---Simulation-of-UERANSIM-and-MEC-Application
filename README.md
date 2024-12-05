# Use of Open5GS for 5G Simulation and ETSI MEC API Testing

## Overview

This project demonstrates the simulation of 5G networks using **Open5GS** and **UERANSIM**, alongside testing of MEC (Multi-access Edge Computing) APIs within the ETSI MEC Sandbox. By integrating Open5GS as the 5G Core Network and UERANSIM for User Equipment (UE) and Radio Access Network (RAN) emulation, this work provides insights into 5G connectivity, protocol exchanges, and edge computing.

Explore how cutting-edge open-source tools and platforms enable the development, simulation, and evaluation of 5G systems and MEC services.

---

## Key Features

- **5G Core Network Simulation**: Open5GS implementation for core functionalities like AMF, SMF, and SGW.
- **UERANSIM Integration**: Simulating UE and gNodeB for detailed network testing.
- **ETSI MEC Sandbox Testing**: Experimentation with APIs like RNIS, AMS, MEC011, and more in realistic network scenarios.
- **Comprehensive Analysis**: Results showcasing network communication, latency reduction, and dynamic resource allocation.
- **Edge Computing Exploration**: Assessing low-latency service delivery for real-time applications.

---

## Tools & Technologies

### 1. **Open5GS**
[**Open5GS**](https://open5gs.org/open5gs/docs/guide/01-quickstart/) is an open-source implementation of the core network for 4G and 5G systems. It supports both EPC for LTE and 5GC for standalone 5G. Key modules include AMF, SMF, and SGW, allowing seamless simulation and research.  
Repository: [Open5GS GitHub](https://github.com/open5gs/open5gs)

### 2. **UERANSIM**
[**UERANSIM**](https://github.com/aligungr/UERANSIM) is a 5G UE and RAN simulator. It facilitates the simulation of gNodeB and UE for realistic 5G network behavior, including protocol exchanges and session management.

### 3. **ETSI MEC Sandbox**
The ETSI MEC Sandbox provides a controlled environment to test MEC applications and APIs under diverse network scenarios such as:
- 4G Macro Network
- 4G-WiFi Macro Network
- 4G-5G-WiFi Macro Network
- 4G-5G Macro V2X Network

APIs tested include:
- **MEC011**: Edge Platform Application Enablement
- **RNIS**: Radio Network Information Service
- **AMS**: Application Mobility Service
- **WAIS**: WLAN Access Information Service
- **V2X**: Vehicle-to-Everything Information Service  

---

## System Design and Implementation

### Open5GS and UERANSIM Configuration
- **AMF Setup**: Configured to handle UE registration and signaling through the NGAP protocol.
- **gNodeB and UE Setup**: Simulated using UERANSIM with packet exchanges analyzed via Wireshark.  
  ![Guide to Open5GS Setup](https://open5gs.org/open5gs/docs/guide/01-quickstart/)

### MEC API Experimentation
- MEC services like RNIS and MEC011 were integrated to evaluate their real-world impact on application responsiveness and edge computing.

[Learn More About UERANSIM Setup](https://github.com/aligungr/UERANSIM)

---

## Results and Analysis

### **Simulation Outcomes**
- Successful simulation of UE registration, gNodeB communication, and core network interaction using Open5GS and UERANSIM.  
  ![Protocol Exchanges Example](https://github.com/open5gs/open5gs)

### **MEC API Performance**
- Optimized application responsiveness and reduced latency, leveraging APIs like MEC011 and RNIS.

---

## Contributions

1. **Open5GS and UERANSIM Setup**:  
   - _Dipean Dasgupta, Archit Verma_  
2. **ETSI MEC Testing**:  
   - _Shobhit Gupta, Rahul Rathore_

Acknowledgment to **Dr. Bhupendra Kumar** for his guidance.

---

## Links and Resources

- **Project Report**: [Read on Overleaf](https://www.overleaf.com/read/mfnvpmcdqnvp#a594c5)  
- **Project Video**: [Watch the Demo](https://drive.google.com/file/d/1TgFO4EMQSMUNWVxf-oNElm0d4KsxsjK_/view?usp=sharing)  
- **GitHub Repository**: [Visit Repo](https://github.com/open5gs/open5gs)  

---

### Future Work

- Expanding the network simulation to include AI-based optimizations.
- Exploring additional MEC APIs for diverse applications.


