
# OmniDrive: LLM-Agent for Autonomous Driving with 3D Perception, Reasoning and Planning

<!-- ## Introduction -->


We utilize OmniDrive and the initial version of OAT-MTDS, an integrated LLM-Agent framework designed for end-to-end autonomous driving. Our key contributions span both the model (OmniDrive-Agent) and the benchmark (OmniDrive-nuScenes). The OmniDrive-Agent introduces an innovative 3D multimodal LLM architecture, employing sparse queries to elevate and compress visual representations into 3D space. OmniDrive-nuScenes serves as a comprehensive benchmark, incorporating a range of VQA tasks for reasoning and planning. These tasks cover areas such as scene description, traffic regulation interpretation, 3D grounding, counterfactual reasoning, decision-making, and strategic planning.


## Getting Started

Please follow our documentation step by step. If you like our work, please recommend it to your colleagues and friends.

1. [**Environment Setup.**](./docs/setup.md)

## Currently Supported Features
- [x] OmnDrive Training Framework
- [x] OmnDrive Dataset
- [ ] OmnDrive Checkpoint
- [x] Evaluation
- [x] Data Generation
- [ ] TensorRT Inference
- [ ] DeepSpeed
- [ ] Tiny LLM

## Visual Results

Joint End-to-end Planning and Reasoning

<div align="center">
<img src="https://github.com/NVlabs/OmniDrive/releases/download/v1.0/demo1.gif" width="1000">

<img src="https://github.com/NVlabs/OmniDrive/releases/download/v1.0/demo2.gif" width="1000">
</div>
<br>

Interactive Conversation with Ego Vehicle

<div align="center">
<img src="https://github.com/NVlabs/OmniDrive/releases/download/v1.0/demo3.gif" width="1000">
</div>
<br>

Counterfactual Reasoning of Planning Behaviors

<div align="center">
<img src="https://github.com/NVlabs/OmniDrive/releases/download/v1.0/demo4.png" width="1000">

<img src="https://github.com/NVlabs/OmniDrive/releases/download/v1.0/demo5.png" width="1000">
</div>
