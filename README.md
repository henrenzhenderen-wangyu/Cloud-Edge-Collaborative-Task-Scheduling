#  Cloud-Edge Collaborative Task Scheduling Dataset

##  Overview

This dataset is specifically developed for research on cloud-edge collaborative task scheduling. It references the Pakistan and Topo4MEC datasets by utilizing their network topologies, and employs a Poisson process to simulate task arrival times. Based on these settings, additional task attributes such as size, deadline, and computational demand are synthesized to construct two distinct task scheduling datasets.

---

## Dataset Description

Each task in this dataset is described with a rich set of attributes to support fine-grained simulation and analysis. The dataset is suitable for experiments in:

- Real-time task scheduling
- Task offloading strategies
- Success Rate optimization
- Energy efficiency optimization
- Latency efficiency optimization

### Task Attributes

Each task entry includes the following fields:

- **`task_id`** – Unique identifier for each task  
- **`size`** – Task size 
- **`source_node`** – Name of the node where the task was generated  
- **`generation_time`** – Timestamp of task generation  
- **`deadline`** – Time deadline for task completion  
- **`cpu_cycles_per_bit`** – Number of CPU computation cycles required per bit  
- **`transmission_rate`** – Data transmission bit rate  
- **`data_type`** – Task type 

---

## Referenced Datasets

This dataset is built upon and improves the following publicly available datasets:

- **Pakistan**  
  GitHub: [ https://github.com/saifulislamPhD/IoT-Compute-Dataset](https://github.com/saifulislamPhD/IoT-Compute-Dataset)

- **Topo4MEC**  
  GitHub: [https://github.com/bnxng/Topo4MEC](https://github.com/bnxng/Topo4MEC)

---

## Applications

This dataset supports a wide range of research scenarios, including but not limited to:

- Cloud-Edge collaborative scheduling  
- Computation offloading decision-making  
- Real-time systems and latency-aware scheduling  
- Multi-objective optimization (e.g., latency, energy consumption, task success rate)

---

