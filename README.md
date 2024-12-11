
# AI-BC: AI and Blockchain Integration for Power System Security  

## Overview  
This repository hosts MATLAB-based code and resources for integrating Artificial Intelligence (AI) and Blockchain (BC) to enhance the security and resilience of power systems. The project includes:  
- A machine learning (ML) agent trained using the IEEE 57-node system dataset.  
- Simulation data representing both normal and cyber-attack scenarios.  
- Branch data to model system behavior.  
- Blockchain mechanisms for data integrity and secure event logging.  

## Contents  

### 1. **Machine Learning Agent**  
- MATLAB implementation of an ML agent trained with normal and hacked data from the IEEE 57-node system.  
- Detects anomalies and abnormal behavior, contributing to enhanced system security.  

### 2. **Active Training Sources**  
- **Normal Data**: Represents standard operational behavior.  
- **Hacked Data**: Simulates cyber-attacks or other disruptions, enabling the ML agent to recognize and classify anomalies.  

### 3. **Branch Data**  
- Includes system branch parameters such as resistance, reactance, and line limits used to model the IEEE 57-node system.  
- Essential for power flow calculations and network simulations.  

### 4. **Blockchain Framework**  
To accommodate multiple AI-BC nodes, our approach integrates key technologies to ensure scalability, flexibility, and security. Windows PowerShell, combined with open Ethereum-windows-v3.1.0 (we uploaded all node settings and ethkeys to GitHub), enables decentralized and collaborative node operations. Nodes are deployed in isolated environments using Docker 4.36, which facilitates dynamic scaling, conflict-free operation, and resource adjustments via a visualized interface. Additionally, Postman 10.5.2 is utilized for API-based communication, ensuring standardized, secure, and efficient data exchange and task distribution. 

## Getting Started  

### 1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Yang325600/AI-BC
   cd AI-BC
   ```  

### 2. **Requirements**  
- MATLAB R2021b (or later) with the following toolboxes:  
  - Machine Learning Toolbox  
  - Optimization Toolbox  
  - Power System Toolbox (optional)  
- Install any additional dependencies mentioned in the repository.
- Windows PowerShell
- Open Ethereum-windows-v3.1.0
- Docker 4.36
- Postman 10.5.2 

### 3. **Run the ML Agent**  
- Open `ml_agent.m` in MATLAB.  
- Run the script to train or test the machine learning model on provided datasets.  

### 4. **Blockchain Simulation**  
- Execute `blockchain_simulation.m` to run simulations for block generation, mining, and verification.  

## Applications  
- **Power System Cybersecurity**: Detects and mitigates cyber-attacks on power system networks.  
- **Operational Resilience**: Improves response and recovery during abnormal conditions.  
- **Data Security**: Blockchain ensures tamper-proof and reliable event recording.  

## Contributing  
Contributions are welcome!  
- Fork the repository and submit a pull request with your enhancements.  
- Ensure compatibility with MATLAB workflows and include documentation for new features.  

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  

## Contact  
For questions or collaboration opportunities, please visit the [repository](https://github.com/Yang325600/AI-BC) or reach out to the contributors.  
