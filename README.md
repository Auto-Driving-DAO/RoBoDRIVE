# OpenAutoDriving (OAD) Framework

Welcome to the official repository of **OpenAutoDriving (OAD)**, an open-source end-to-end autonomous driving system developed by AutoDriving DAO. This framework aims to empower the community by offering a modular, flexible, and highly scalable solution for autonomous driving, while embracing the latest advancements in multimodal perception, AI, and decision-making.

## Table of Contents
- [Overview](#overview)
- [System Components](#system-components)
  - [OAD-MTDS (Multi-task Driving System)](#oad-mtds-multi-task-driving-system)
  - [OAD-QFormer (Visual Language Alignment System)](#oad-qformer-visual-language-alignment-system)
  - [OAD-RDS (Reasoning and Decision System)](#oad-rds-reasoning-and-decision-system)
  - [OAD-VIT (Multimodal Perception System)](#oad-vit-multimodal-perception-system)
- [Future Development](#future-development)
- [How to Contribute](#how-to-contribute)
- [License](#license)

## Overview

The **OpenAutoDriving (OAD)** project is a fully open-source initiative that addresses the pressing need for an accessible, community-driven autonomous driving solution. Unlike closed systems like Tesla's FSD or Waymo, OAD is designed to provide an open and modular architecture, allowing developers to implement, test, and innovate upon its core functionalities.

The framework is structured into four key components:
1. **OAD-MTDS (Multi-task Driving System)**
2. **OAD-QFormer (Visual Language Alignment System)**
3. **OAD-RDS (Reasoning and Decision System)**
4. **OAD-VIT (Multimodal Perception System)**

Each of these components is built with flexibility and scalability in mind, enabling seamless integration with various hardware setups and use cases.

## System Components

### OAD-MTDS (Multi-task Driving System)
The **OAD-MTDS** is a modular system designed to handle multiple driving tasks such as object detection, lane detection, and motion planning. It uses perception queries from the OAD-QFormer to generate task-specific outputs, allowing for accurate predictions across various tasks.

- **Key Features:**
  - Task-specific transformer heads for tasks like object detection, lane detection, and depth estimation.
  - Scalable architecture, enabling the addition of new task heads.
  - Built-in support for popular models like ViLD for object detection, GroupViT for image segmentation, and DepthCLIP for depth estimation.



### OAD-QFormer (Visual Language Alignment System)
The **OAD-QFormer** bridges the gap between visual and language data by aligning perception queries with language tokens. This module plays a crucial role in understanding scenes and enabling reasoning within the autonomous driving context.

- **Key Features:**
- Efficient pre-training strategy using frozen visual encoders.
- Cross-attention mechanism for robust visual-language alignment.
- Enhanced understanding of complex driving environments through multimodal input.


### OAD-RDS (Reasoning and Decision System)
The **OAD-RDS** integrates a large language model (LLM) to enable reasoning and decision-making based on 3D perception data. This system allows for high-level decision-making in complex driving environments by leveraging LLMs' reasoning capabilities.

- **Key Features:**
- Pre-trained on large datasets and fine-tuned for autonomous driving tasks.
- Path planning, counterfactual reasoning, and control generation for real-time decision-making.
- Explainable decision-making process, enhancing transparency and safety in autonomous driving.


### OAD-VIT (Multimodal Perception System)
The **OAD-VIT** is a multimodal vision transformer designed to process high-resolution multi-view inputs from cameras, LiDAR, and RiDAR. It extracts spatial and semantic information, enabling robust perception in dynamic driving environments.

- **Key Features:**
- Integration with multiple sensor types (Vision, LiDAR, RiDAR).
- Use of Vision Transformers for efficient feature extraction and query generation.
- Highly scalable architecture, adaptable to different hardware configurations.


## Future Development

The OAD framework is built for continuous improvement and evolution, with key areas of future development including:
1. **Massive Data Collection**: Leveraging real-world and simulated datasets to enhance model accuracy and edge-case handling.
2. **Model Fine-tuning and Upgrading**: Continuous model updates to incorporate cutting-edge AI advancements.
3. **Fully End-to-End Training**: Progressing towards full end-to-end learning from raw sensor inputs to decision-making, reducing reliance on human design.

## How to Contribute

We welcome contributions from the open-source community! You can contribute by:
- Adding new task-specific heads to the **OAD-MTDS**.
- Improving the efficiency of **OAD-QFormer** for better visual-language alignment.
- Enhancing the decision-making algorithms in **OAD-RDS**.
- Optimizing **OAD-VIT** for different sensor configurations.

Please refer to our [Contribution Guide](CONTRIBUTING.md) for detailed instructions on how to get involved.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

