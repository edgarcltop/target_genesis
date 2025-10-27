# What is Genesis?
Genesis is a physics platform designed for general purpose *Robotics/Embodied AI/Physical AI* applications. It is simultaneously multiple things:
1. A **universal physics engine** re-built from the ground up, capable of simulating a wide range of materials and physical phenomena.
2. A **lightweight**, **ultra-fast**, **pythonic**, and **user-friendly** robotics simulation platform.
3. A powerful and fast **photo-realistic rendering system**.
3. A **generative data engine** that transforms user-prompted natural language description into various modalities of data.

Powered by a universal physics engine re-designed and re-built from the ground up, Genesis integrates various physics solvers and their coupling into a unified framework. This core physics engine is further enhanced by a generative agent framework that operates at an upper level, aiming towards fully **automated data generation** for robotics and beyond. 

## Key Features
- **Speed**: Genesis delivers an unprecedented simulation speed -- over 43 million FPS when simulating a Frana robotic arm with a single RTX 4090 (430,000 faster than real-time).
- **Cross-platform**: Genesis runs natively across different systems (Linux, MacOS, Windows), and across different compute backend (CPU, Nvidia GPU, AMD GPU, Apple Metal).
- **Unification of various physics solvers**: Genesis develops a unified simulation framework that integrates various physics solvers: Rigid body, MPM, SPH, FEM, PBD, Stable Fluid.
- **Support a wide range of material models**:  Genesis supports simulation (and the coupling) of rigid and articulated bodies, various types of liquids, gaseous phenomenon, deformable objects, thin-shell objects and granular materials.

## Getting Started
### Quick Installation
Genesis is available via PyPI:
```bash
pip install genesis-world
```
## Contributing to Genesis

The goal of the Genesis project is to build a fully transparent, user-friendly ecosystem where contributors from both robotics and computer graphics can **come together to collaboratively create a high-efficiency, realistic (both physically and visually) virtual world for robotics research and beyond**.

We sincerely welcome *any forms of contributions* from the community to make the world a better place for robots. From **pull requests** for new features, **bug reports**, to even tiny **suggestions** that will make Genesis API more intuitive, all are wholeheartedly appreciated!

