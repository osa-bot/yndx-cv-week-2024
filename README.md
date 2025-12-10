# yndx-cv-week-2024

[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

## Overview

This project is an educational resource focused on computer vision. It provides an intensive learning experience, exploring techniques to create efficient image generation models. The aim is to distill the power of complex models into smaller, faster ones for practical applications.

## Table of Contents

- [Core features](#core-features)
- [Installation](#installation)
- [Contributing](#contributing)
- [Citation](#citation)

## Core features

1. **Stable Diffusion Integration**: The project leverages the Stable Diffusion 1.5 model as a teacher for knowledge distillation, utilizing its capabilities for image generation and providing a foundation for the consistency model.
2. **Consistency Distillation**: The core of the project focuses on consistency distillation, a technique to train a smaller, faster model by aligning its predictions with those of a larger, pre-trained diffusion model (Stable Diffusion).
3. **DDIM Solver Implementation**: The project implements the DDIM (Denoising Diffusion Implicit Models) solver, a crucial component for generating samples and for the distillation process, enabling efficient and controlled image generation.
4. **LoRA Adapter Training**: The project utilizes LoRA (Low-Rank Adaptation) to efficiently fine-tune the Stable Diffusion model, reducing the number of trainable parameters and enabling training on limited hardware.
5. **Classifier-Free Guidance**: The project incorporates classifier-free guidance (CFG) to control the generation process, allowing for more targeted and coherent image generation based on text prompts.

## Installation

Install yndx-cv-week-2024 using one of the following methods:

**Build from source:**

1. Clone the yndx-cv-week-2024 repository:
```sh
git clone https://github.com/DRMPN/yndx-cv-week-2024
```

2. Navigate to the project directory:
```sh
cd yndx-cv-week-2024
```

## Contributing

- **[Report Issues](https://github.com/DRMPN/yndx-cv-week-2024/issues)**: Submit bugs found or log feature requests for the project.

## Citation

If you use this software, please cite it as below.

### APA format:

    DRMPN (2024). yndx-cv-week-2024 repository [Computer software]. https://github.com/DRMPN/yndx-cv-week-2024

### BibTeX format:

    @misc{yndx-cv-week-2024,

        author = {DRMPN},
