## ControlGrid

ControlGrid is a simulation and analysis platform designed to model liquidity behavior in financial networks such as Central Bank Digital Currency (CBDC) payment systems.

The system represents payment infrastructures as graphs and analyzes how liquidity flows between participants. By simulating transaction flows and network conditions, ControlGrid helps identify bottlenecks and potential congestion points before they escalate into large-scale payment delays.

## Problem Statement

Modern digital payment networks process a massive volume of transactions in real time. In complex systems such as CBDC networks, hidden liquidity shortages can create cascading delays across multiple participants.

Traditional monitoring tools detect issues only after they occur, making it difficult to prevent systemic disruptions.

ControlGrid addresses this challenge by modeling the network structure and simulating liquidity movement to proactively detect congestion risks.


## Solution

ControlGrid builds a graph-based representation of a payment network where:

* Nodes represent participants such as banks or institutions.
* Edges represent payment channels between participants.
* Liquidity values represent available transaction capacity.

The system runs simulations on this network to observe how liquidity moves through the system and how congestion propagates when liquidity becomes constrained.


## Key Features

* Graph-based financial network modeling
* Liquidity flow simulation
* Detection of congestion and bottlenecks
* Visualization of payment interactions
* Flexible architecture for experimenting with different network configurations


## Tech Stack

* Python
* NetworkX (Graph modeling)
* Simulation-based analysis


## Project Structure

```
ControlGrid
│
├── network
│   ├── network.py
│   └── config.py
│
├── simulation
│   └── simulator.py
│
├── utils
│   └── helpers.py
│
└── main.py
```


## Future Improvements

* AI-based congestion prediction
* Real-time network visualization dashboard
* Integration with live transaction datasets
* Advanced liquidity optimization strategies


## Team

* Sneha Jain
* Mrunmayee Kulat
* Sharvari Mahurkar


## Repository

https://github.com/snehajain-01/ControlGrid
