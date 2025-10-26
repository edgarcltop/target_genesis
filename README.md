<div align="center">
  <img src="imgs/big_text.png" alt="Genesis" width="85%">
  
</div>

---

<!-- <div align="center">
  <img src="imgs/teaser.png" width="100%">
</div> -->


# What is Genesis?
Genesis is a physics platform designed for general purpose *Robotics/Embodied AI/Physical AI* applications. It is simultaneously multiple things:
1. A **universal physics engine** re-built from the ground up, capable of simulating a wide range of materials and physical phenomena.
2. A **lightweight**, **ultra-fast**, **pythonic**, and **user-friendly** robotics simulation platform.
3. A powerful and fast **photo-realistic rendering system**.
3. A **generative data engine** that transforms user-prompted natural language description into various modalities of data.

Powered by a universal physics engine re-designed and re-built from the ground up, Genesis integrates various physics solvers and their coupling into a unified framework. This core physics engine is further enhanced by a generative agent framework that operates at an upper level, aiming towards fully **automated data generation** for robotics and beyond. 

Currently, we are open-sourcing the **underlying physics engine and the simulation platform**. Our generative framework is a modular system that incorporates many different generative modules, each handling a certain range of data modalities, routed by a high level agent. Some of the modules integrated existing papers and some are still under submission. Access to our generative feature will be gradually rolled out in the near future. If you are interested, feel free to explore more the [paper list](#papers-behind-genesis) below.

Genesis is built and will continuously evolve with the following ***long-term missions***:
2. **Unifying a wide spectrum of state-of-the-art physics solvers** into a single framework, allowing re-creating the whole physical world in a virtual realm with the highest possible physical, visual and sensory fidelity, using the most advanced simulation techniques.
3. **Minimizing human effort** in collecting and generating data for robotics and other domains, letting the data flywheel spin on its own.

Project Page: https://genesis-embodied-ai.github.io/

## Key Features
- **Speed**: Genesis delivers an unprecedented simulation speed -- over 43 million FPS when simulating a Frana robotic arm with a single RTX 4090 (430,000 faster than real-time).
- **Cross-platform**: Genesis runs natively across different systems (Linux, MacOS, Windows), and across different compute backend (CPU, Nvidia GPU, AMD GPU, Apple Metal).
- **Unification of various physics solvers**: Genesis develops a unified simulation framework that integrates various physics solvers: Rigid body, MPM, SPH, FEM, PBD, Stable Fluid.
- **Support a wide range of material models**:  Genesis supports simulation (and the coupling) of rigid and articulated bodies, various types of liquids, gaseous phenomenon, deformable objects, thin-shell objects and granular materials.
- **Support for a wide range of robots**: Robot arm, legged robot, drone, _soft robot_, etc., and extensive support for loading different file types: `MJCF (.xml)`, `URDF`, `.obj`, `.glb`, `.ply`, `.stl`, etc.
- **Photorealistic and high-performance ray-tracer**: Genesis supports native ray-tracing based rendering.
- **Differentiability**: Genesis is designed to be fully compatible with differentiable simulation. Currently, our MPM solver and Tool Solver are differentiable, and differentiability for other solvers will be added soon (starting with rigid-body simulation).
- **Physics-based Tactile Sensor**: Genesis involves a physics-based and differentiable [tactile sensor simulation module. This will be integrated to the public version soon (expected in verion 0.2.0).
- **User-friendliness**: Genesis is designed in a way to make using simulation as simple as possible. From installation to API design, if there's anything you found counter-intuitive or difficult to use, please [let us know]
- 
## Getting Started
### Quick Installation
Genesis is available via PyPI:
```bash
pip install genesis-world
```
You also need to install **PyTorch** following the [official instructions](https://pytorch.org/get-started/locally/).

### Documentation
Please refer to our [documentation site](https://genesis-world.readthedocs.io/en/latest/user_guide/index.html) to for detailed installation steps, tutorials and API references.

## Contributing to Genesis

The goal of the Genesis project is to build a fully transparent, user-friendly ecosystem where contributors from both robotics and computer graphics can **come together to collaboratively create a high-efficiency, realistic (both physically and visually) virtual world for robotics research and beyond**.

We sincerely welcome *any forms of contributions* from the community to make the world a better place for robots. From **pull requests** for new features, **bug reports**, to even tiny **suggestions** that will make Genesis API more intuitive, all are wholeheartedly appreciated!

## Support
* Please use Github [Issues](https://github.com/Genesis-Embodied-AI/Genesis/issues) for bug reports and feature requests.
* Please use GitHub [Discussions](https://github.com/Genesis-Embodied-AI/Genesis/discussions) for discussing ideas, and asking questions.

## License and Acknowledgment
The Genesis source code is licensed under Apache 2.0.
The development of Genesis won't be possible without these amazing open-source projects:
- [Taichi](https://github.com/taichi-dev/taichi): for providing a high-performance cross-platform compute backend. Kudos to all the members providing technical support from taichi!
- [FluidLab](https://github.com/zhouxian/FluidLab) for providing a reference MPM solver implementation
- [SPH_Taichi](https://github.com/erizmr/SPH_Taichi) for providing a reference SPH solver implementation
- [MuJoCo](https://github.com/google-deepmind/mujoco) and [Brax](https://github.com/google/brax) for providing reference for rigid body dynamics
- [libccd](https://github.com/danfis/libccd) for providing reference for collision detection

}
```

