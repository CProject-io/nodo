# C-Project Nodes

## 1. Introduction

In traditional blockchains, block generation required enormous energy consumption, leading to high costs and significant environmental impact. In C-Project, we have redefined this paradigm: our nodes not only validate transactions but also act as renewable energy generators. By using low-power devices (such as Raspberry Pi or NVIDIA Jetson) directly connected to self-managed energy generators (solar panels, wind turbines, or hydroelectric systems), our nodes are autonomous and actively contribute to the network’s self-sustainability. Moreover, the network creates its own internal economy to finance the maintenance, development, and future expansion of the entire ecosystem.

## 2. Node Architecture

The architecture of our nodes is built upon two fundamental pillars: hardware (energy autonomy) and software (features and consensus mechanisms).

### 2.1. Hardware and Energy Autonomy

- **Low-Power Devices:**
  - **Raspberry Pi 4:** Compact and efficient devices, ideal for basic node operations.
  - **NVIDIA Jetson Nano:** Devices with higher processing capabilities for advanced tasks such as data analysis and intensive computation.

- **Renewable Energy Sources:**
  - **Photovoltaic Solar Panels:** Capture solar energy to power the nodes.
  - **Wind Turbines:** Complement solar energy in conditions of low sunlight.
  - **Hydroelectric Systems:** An alternative in areas with sufficient water resources.

- **Energy Storage and Management Systems:**
  - **High-Capacity Batteries:** Ensure continuous operation during periods of low energy generation.
  - **Charge Controllers and Monitoring Systems:** Optimize charging efficiency and provide real-time monitoring of energy production and consumption.

- **Physical Integration:**
  - Nodes must be directly connected to the energy generators, ensuring that the produced energy is used to power the node and sustain network operations.

### 2.2. Software and Functionalities

- **Substrate-Based Node Client:**
  - Our software is a fork of Substrate, customized to incorporate the **Proof of Generation (PoG)** consensus mechanism.
  - Specific modules (pallets) are developed for energy auditing, reward distribution, and governance.

- **Consensus and Validation Mechanism:**
  - **Transaction Aggregation:** A node or a set of nodes can collect and validate transactions, integrating them into proposed blocks.
  - **Automatic Block Generation:** Blocks are automatically generated at discrete time intervals, ensuring a steady and predictable flow of blocks, independent of the transaction validation process.
  - **Reward Distribution:**  
    - Rewards for nodes that aggregate transactions are determined by the amount of renewable energy they generate to keep their nodes operational.  
    - This model directly links remuneration to renewable energy production and node sustainability.

## 3. Services and Scalability

- **Storage and Computation:**  
  Nodes are designed to scale by offering low-cost data storage services and the capability to perform computational tasks directly on the blockchain.

- **Secure Interconnection:**  
  Secure communication between nodes is ensured through protocols based on libp2p and other security standards.

- **Network Interconnection Layer & Free Access Infrastructure:**  
  In addition to the above services, we envision the development of a network interconnection layer that enables the blockchain to provide its own free-access communication infrastructure. This layer would be implemented using mesh networking and long-range communication technologies (e.g., LoRa and extended Wi-Fi), integrated into each node.
  - **Objectives:**  
    - Facilitate direct, secure communication between nodes even in areas with limited connectivity.  
    - Provide decentralized and free access to the network, allowing any user to connect and consume services without relying on centralized providers.  
    - Enhance additional services, such as distributed storage and computation, through a robust infrastructure similar to a WAN or an open-access Internet.
  - **Benefits:**  
    - Increases the autonomy and resilience of the ecosystem.  
    - Facilitates expansion and adoption as the network itself becomes a decentralized communication medium.  
    - Reinforces the vision of a sustainable and self-sufficient ecosystem.

## 4. Conclusion

The architecture of the nodes in C-Project represents a paradigm shift in blockchain design. By integrating renewable energy generation with transaction validation and automatic block creation, our nodes ensure network operability, security, and sustainability. This model not only generates an internal economy to finance maintenance and development but also paves the way for future expansions in storage, computation, and interconnection, establishing C-Project as a comprehensive and eco-friendly alternative to traditional blockchains.

---

With this architecture, C-Project is positioned as a 100% self-sustaining network that incentivizes clean energy generation, offers scalable infrastructure, and promotes decentralization at multiple levels.
