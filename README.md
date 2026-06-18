# Overview & Project Information
Designed and simulated a scalable 5G wireless network infrastructure for urban and suburban environments using OMNeT++. The project focused on RF planning, network topology design, QoS optimization, and wireless performance evaluation. 

This project was developed as part of a university group project focused on 5G wireless network design and simulation. My contribution included simulation configuration and performance analysis.

## Authors
- Hasan Bahzad (Me)
- Salman Mohamed
- Husain Mohamedi
- Husain Ali

# Objectives
- Design 5G network topologies for different propagation environments
- Simulate urban and suburban deployment scenarios
- Evaluate QoS and network performance
- Analyze throughput, latency and packet loss

# Technologies Used
- OMNeT++
- 5G Networking
- RF Planning
- MIMO
- QoS Analysis
- VoIP / CBR / VoD Traffic Simulation

# Features
- Urban and suburban 5G deployment simulations
- gNodeB placement and cell coverage planning
- Traffic modeling with different load conditions

# Simulation Scenarios

The project implemented and evaluated two 5G deployment scenarios within the OMNeT++ simulation environment:

- **Urban Scenario:**  
  Dense propagation environment utilizing micro-cell deployment to improve network capacity, QoS performance, and user coverage in high-traffic areas.

- **Suburban Scenario:**  
  Large-area macro-cell deployment designed to provide scalable wireless coverage with optimized infrastructure distribution and reduced propagation challenges.

Both scenarios included traffic modeling using VoIP, Constant Bit Rate (CBR), and Video-on-Demand (VoD) services under different load conditions to evaluate throughput, latency, and packet loss performance.

# Screenshots
The following screenshots demonstrate the implemented 5G network topologies and deployment scenarios within the OMNeT++ simulation environment.

## Macro Cell Topology
Large-area macro-cell topology designed to improve wireless coverage and scalability in suburban environments.

![Macro Topology](screenshots/topologies/macro-topology.png)

## Micro Cell Topology
Simulation topology demonstrating dense urban 5G deployment using micro cells for higher capacity and QoS optimization.

![Micro Topology](screenshots/topologies/micro-topology.png)

# Project Structure
```
configs/       -> Configuration files
docs/          -> Project documentation
screenshots/   -> Network topology and result images
```
