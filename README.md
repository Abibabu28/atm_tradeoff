# Adaptive Trade-off Model (ATM)

## Overview
The Adaptive Trade-off Model (ATM) is a distributed system that dynamically balances computation between local and distributed processing based on real-time performance metrics. Using reinforcement learning techniques, ATM optimizes resource utilization across federated nodes.

## Features
- Federated architecture with coordinator and worker nodes
- Real-time performance metrics collection and analysis
- Q-learning based adaptive strategy selection
- Kafka-based communication infrastructure
- Configurable trade-off between local computation and distributed processing

## Execution
Run the system in federated mode with:
```
python start_atm.py --mode federated --nodes 5
```

## Performance
The system continuously monitors CPU, memory, network, and disk utilization across all nodes, adjusting its computation strategy to optimize overall system performance. Initial results show successful adaptation between balanced and distribution-heavy approaches.
