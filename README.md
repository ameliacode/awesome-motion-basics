<h2 align="center"> All about locomotions from A to Z </h2>
  
<p align="center">📓 From Basic to its Application 🛠</p>
  
---
## Content
- Computer Graphics Basics
- Locomotion Kinematic Basics
- Related Simulation Engines
- Character Animation
- Application State-of-the-Art

## Introduction

### 💻 Computer Graphics Basics
Books and website to recommend 
- 📚 **Introduction to Computer Graphics with OpenGL ES** written by JungHyun Han: Read Chapter11 to 14, Highly recommended
- 📚 **Computer Animation Algorithms and Techniques** written by Rick Patent
- 📚 [Optional] **Hands-On Reinforcement Learning with Python Master reinforcement and deep reinforcement learning using OpenAI Gym and TensorFlow** written by Sudharsan Ravichandiran

### 🦿 Locomotion Kinematics Basics 

#### Motion data
Its file extension vary: .bvh, .amc, .c3d, .mpg, .npz and so on. See [CMU dataset](http://mocap.cs.cmu.edu/) for more info.  
Overall, Skeleton consists a number of joints, starting from a root(mostly refer to hips, pelvis, etc.) to all joints expand as child joints. In a skeleton, joints form a hierarchical structure with parent-child relationship. So, it is recommended to have prior knowledge of rotation unit (unit quaternion, rotation matrix, rotation vector, euler angle and so on), some data structure (tree, list) and, difference between character space(local joint space) and world space(global joint space).

☑ For starter, start playing with mocap file: ⚠ Notify not all mocap files have same joint numbers, info or sequences.
- Mocap data parser: [Fairmotion](https://github.com/facebookresearch/fairmotion)
- Simplified bvh parser [NpyBvh](https://github.com/dabeschte/npybvh)


### Related Simulation Engines

#### Pybullet
As long it is not simulated, users can simply create kinematic environment.
- [Pybullet](https://github.com/bulletphysics/bullet3)
- [Pybullet RL Environments: Zoo](https://github.com/araffin/rl-baselines-zoo)
- [TUTORIAL: Teaching humanoid walk](https://www.codeproject.com/Articles/5280281/Teaching-a-Robot-to-Walk-with-AI-Introduction-to-C)

#### Pydart
#### Gazebo
#### Ogre
#### Mujoco

### 🦾 Character Animation
Some papers to checkout:
(If you are new, it is strongly recommended to checkout review papers)

#### Motion Stitching

#### Motion Warping
- [Motion Warping | Siggraph 1995](https://homes.cs.washington.edu/~zoran/warpage/warpage.pdf)

#### Motion Blending
- [Flexible Automatic Motion Blending with Registration Curves Lucas | Eurographics 2003](https://research.cs.wisc.edu/graphics/Gallery/kovar.vol/RegistrationCurves/regCurves.pdf)
- [Motion Blending Krisine Slot 2007](http://image.diku.dk/projects/media/kristine.slot.07.pdf)

#### Motion Denoise

#### Motion Control
- [Chracter MVAE control | Siggraph 2020](https://arxiv.org/pdf/2103.14274.pdf)
- [Learning Symmetric and Low-energy Locomotion](https://arxiv.org/pdf/1801.08093.pdf)

#### Motion Estimation

#### Motion Synthesis



### 🛠 Implementation or State-of-the-art

Some papers might intrigue you :)


### Siggraph, Eurographics etc.
Mostly, unlike other computer science field, graphics engineers or researchers publish their paper in these conferences: . Compared to other conferences, its registration fees are slightly expensive 🙄.


### 😎 Cool Graphics developer/researchers out there:


