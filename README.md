# **Modeling Epidemic Spread: A Simulation Approach Using NetLogo**

## **Overview**
This repository contains the code and methodology for simulating the spread of infectious diseases using an agent-based model in NetLogo. The simulation aims to explore the dynamics of disease propagation through a population categorized into three compartments: susceptible, infected, and recovered (SIR). It offers insights into how varying infection and recovery rates affect epidemic outcomes, with applications in public health and policy-making.

## **How to Run**
### **Prerequisites**
- Install NetLogo (version 6.4 or higher).

### **Steps**
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/epidemic-spread-netlogo.git
    ```
2. Open the NetLogo model file (`epidemic_spread.nlogo`) in the NetLogo application.
3. Adjust parameters using the sliders:
    - **Population Size**: Sets the total number of agents in the simulation.
    - **Infection Rate (\(\beta\))**: Adjusts the likelihood of disease transmission during contact.
    - **Recovery Rate (\(\gamma\))**: Modifies the speed at which infected agents recover.
4. Press **Setup** to initialize the population with the chosen parameters.
5. Press **Go** to start the simulation and observe the dynamics.
