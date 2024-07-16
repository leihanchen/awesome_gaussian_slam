# Awesome Gaussian SLAM Resources 

A curated list of papers and open-source resources focused on gaussian based slam system, focusing on slam systems with gaussian based mapping representation with any utilities. The ambition is keeping pace with the anticipated surge of research in the coming months. If you have any additions or suggestions, feel free to contribute. Additional resources like blog posts, videos, etc. are also welcome.

## Table of contents

- [Seminal Introduction Material](#introduction)
  * [Nerf](#nerf)
  * [3D Gaussian Splatting](#3d-gaussian-splatting)
<br>

- [Survey](#survey)
- [Theory](#gaussian-theory)
- [Gaussian SLAM](#gaussian-slam)
- [Navigation](#navigation)
- [Poses](#poses)
- [Large-Scale](#large-scale)

<br>

- [Data](#data)
- [Courses](#courses)

<br>

- [Open Source Implementations](#open-source-implementations)
  * [Unofficial Implementations](#unofficial-implementations)
  * [2D Gaussian Splatting](#2d-gaussian-splatting)
  * [Game Engines](#game-engines)
  * [Viewers](#viewers)
  * [Utilities](#utilities)
  * [Tutorial](#tutorial)
  * [Framework](#framework)
  * [Other](#other)
<br>

- [Blog Posts](#blog-posts)
- [Tutorial Videos](#tutorial-videos)
- [Credits](#credits)

<details span>
<summary><b>Update Log:</b></summary>
<br>
 **July 11, 2024**
 - Initial version
<br>
 **July 16, 2024**
 - Add survey and theory sections
</details>

<br>

## Introduction:

### Nerf:

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [📄 Paper](https://arxiv.org/abs/2003.08934.pdf) | [💻 Code](https://github.com/bmild/nerf)

### 3D Gaussian Splatting:

- [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/), Kerbl et al., SIGGRAPH 2023 | [📄 Paper](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [💻 Code](https://github.com/graphdeco-inria/gaussian-splatting) | [🎥 Short Presentation](https://youtu.be/T_kXY43VZnk?si=DrkbDFxQAv5scQNT) | [🎥 Explanation Video](https://www.youtube.com/live/xgwvU7S0K-k?si=edF8NkYtsRbgTbKi)

<br>

## Survey:
- **A Survey on 3D Gaussian Splatting**, Chen et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2401.03890.pdf)

- **3D Gaussian as a New Vision Era: A Survey**, Fei et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2402.07181.pdf)

- **Recent Advances in 3D Gaussian Splatting**, Wu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11134.pdf)

- **Gaussian Splatting: 3D Reconstruction and Novel View Synthesis, a Review**, Dalal et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2405.03417.pdf)

## Gaussian Theory:
- **[SIGGRAPH '24]2D Gaussian Splatting for Geometrically Accurate Radiance Fields**, Huang et al., SIGGRAPH 2024 | [📄 Paper](https://arxiv.org/pdf/2402.03246.pdf) | [🌐 Project Page](https://surfsplatting.github.io/) | [💻 Code](https://github.com/hbb1/2d-gaussian-splatting)

- **PGSR: Planar-based Gaussian Splatting for Efficient and High-Fidelity Surface Reconstruction**, Chen et al., arXiv 2024 | [📄 Paper](https://arxiv.org/abs/2406.06521.pdf) | [🌐 Project Page](https://zju3dv.github.io/pgsr/) | [💻 Code](https://github.com/zju3dv/PGSR)

- **[CVPR '24]4D Gaussian Splatting for
Real-Time Dynamic Scene Rendering**,
Wu et al., CVPR 2024 | [📄 Paper](https://arxiv.org/abs/2310.08528.pdf) | [🌐 Project Page](https://guanjunwu.github.io/4dgs/) | [💻 Code](https://github.com/hustvl/4DGaussians)


## Gaussian SLAM:
## 2024:
- **SGS-SLAM: Semantic Gaussian Splatting For Neural Dense SLAM**, Li et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2402.03246.pdf) | [🎥 Demo Video](https://www.youtube.com/watch?v=y83yw1E-oUo)

- **SemGauss-SLAM: Dense Semantic Gaussian Splatting SLAM**, Zhu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.07494.pdf)

- **Compact 3D Gaussian Splatting For Dense Visual SLAM**, Deng et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11247.pdf)

- **NEDS-SLAM: A Novel Neural Explicit Dense Semantic SLAM Framework using 3D Gaussian Splatting**, Ji et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11679.pdf)

- **High-Fidelity SLAM Using Gaussian Splatting with Rendering-Guided Densification and Regularized Optimization**, Sun et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.12535.pdf)

- **RGBD GS-ICP SLAM**, Ha et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.12550.pdf) | [💻 Code](https://github.com/Lab-of-AI-and-Robotics/GS_ICP_SLAM) | [🎥 Short Presentation](https://youtu.be/e-bHh_uMMxE?si=bU4_Su4J91WQ2MEX)

- **EndoGSLAM: Real-Time Dense Reconstruction and Tracking in Endoscopic Surgeries using Gaussian Splatting** Wang et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.15124.pdf) | [🌐 Project Page](https://endogslam.loping151.com/) | [💻 Code](https://github.com/Loping151/EndoGSLAM)

- **CG-SLAM: Efficient Dense RGB-D SLAM in a Consistent Uncertainty-aware 3D Gaussian Field**, Ren et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.16095.pdf) | [🌐 Project Page](https://zju3dv.github.io/cg-slam/) | [💻 Code](https://github.com/hjr37/CG-SLAM)

- **MM3DGS SLAM: Multi-modal 3D Gaussian Splatting for SLAM Using Vision, Depth, and Inertial Measurements** Sun et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2404.00923) | [🌐 Project Page](https://vita-group.github.io/MM3DGS-SLAM/) | [💻 Code (not yet)]()  

- **Gaussian-LIC: Photo-realistic LiDAR-Inertial-Camera SLAM with 3D Gaussian Splatting**, Lang et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2404.06926.pdf)    

- **RTG-SLAM: Real-time 3D Reconstruction at Scale using Gaussian Splatting**, Peng et al., arXiv 2024 | [📄 Paper](https://arxiv.org/abs/2404.19706.pdf) | [🌐 Project Page](https://gapszju.github.io/RTG-SLAM/) | [💻 Code](https://github.com/MisEty/RTG-SLAM)

## 2023:
- **[CVPR '24] GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting**, Yan et al., arXiv 2023 | [📄 Paper](https://arxiv.org/pdf/2311.11700.pdf) | [🌐 Project Page](https://gs-slam.github.io/)

- **[CVPR '24] SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM**, Keetha et al., arXiv 2023 | [📄 Paper](https://arxiv.org/pdf/2312.02126.pdf) | [🌐 Project Page](https://spla-tam.github.io/) | [💻 Code](https://github.com/spla-tam/SplaTAM) | [🎥 Explanation Video](https://www.youtube.com/watch?v=35SX8DTdQLs)

- **[CVPR '24] Gaussian Splatting SLAM**, Matsuki et al., arXiv 2023 |  [📄 Paper](https://www.imperial.ac.uk/media/imperial-college/research-centres-and-groups/dyson-robotics-lab/hide-et-al_GaussianSplattingSLAM_Dec2023.pdf) | [🌐 Project Page](https://rmurai.co.uk/projects/GaussianSplattingSLAM/) | [💻 Code](https://github.com/muskie82/MonoGS) | [🎥 Short Presentation](https://youtu.be/x604ghp9R_Q?si=fPtz4kgBKFfcnQf3) 




- **Gaussian-SLAM: Photo-realistic Dense SLAM with Gaussian Splatting**, Yugay et al., arXiv 2023 |  [📄 Paper](https://ivi.fnwi.uva.nl/cv/paper/GaussianSLAM.pdf) | [🌐 Project Page](https://vladimiryugay.github.io/gaussian_slam/) | [💻 Code](https://github.com/VladimirYugay/Gaussian-SLAM) | [🎥 Short Presentation](https://www.youtube.com/watch?v=RZK1o_ija7M)

- **[CVPR '24] Photo-SLAM: Real-time Simultaneous Localization and Photorealistic Mapping for Monocular, Stereo, and RGB-D Cameras**, Huang et al., arXiv 2023 | [📄 Paper](https://arxiv.org/pdf/2311.16728.pdf) | [🌐 Project Page](https://huajianup.github.io/research/Photo-SLAM/) | [💻 Code](https://github.com/HuajianUP/Photo-SLAM) 

<br>

## Navigation:
## 2024:
- **GaussNav: Gaussian Splatting for Visual Navigation**, Lei et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11625.pdf) | [🌐 Project Page](https://xiaohanlei.github.io/projects/GaussNav/) | [💻 Code](https://github.com/XiaohanLei/GaussNav)

- **3DGS-ReLoc: 3D Gaussian Splatting for Map Representation and Visual ReLocalization**, Jiang et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11367.pdf)

- **Beyond Uncertainty: Risk-Aware Active View Acquisition for Safe Robot Navigation and 3D Scene Understanding with FisherRF**, Liu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11396.pdf)

- **3DGS-Calib: 3D Gaussian Splatting for Multimodal SpatioTemporal Calibration**, Herau et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11577.pdf)

- **[CVPR '24] HUGS: Holistic Urban 3D Scene Understanding via Gaussian Splatting** Zhou et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.12722.pdf) | [🌐 Project Page](https://xdimlab.github.io/hugs_website/)| [💻 Code](https://github.com/hyzhou404/HUGS)

- **HO-Gaussian: Hybrid Optimization of 3D Gaussian Splatting for Urban Scenes**, Li et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.20032.pdf) 

- **SGD: Street View Synthesis with Gaussian Splatting and Diffusion Prior**, Yu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.20079.pdf)  

## Poses:
## 2024:
- **[ECCV '24]GGRt: Towards Generalizable 3D Gaussians without Pose Priors in Real-Time**, Li et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.10147) | [🌐 Project Page](https://3d-aigc.github.io/GGRt/)

- **GS-Pose: Cascaded Framework for Generalizable Segmentation-based 6D Object Pose Estimation**, Cai et al., arXiv 2024 |  [📄 Paper](https://arxiv.org/pdf/2403.10683) | [🌐 Project Page](https://dingdingcai.github.io/gs-pose/) | [💻 Code](https://github.com/dingdingcai/GS-pose) | [🎥 Short Presentation](https://youtu.be/SnJazusDLM8)

## Large-Scale:
## 2024:
- **[SIGGRAPH '24] A Hierarchical 3D Gaussian Representation for Real-Time Rendering of Very Large Datasets**, Kerbl et al., arXiv 2024 | [📄 Paper (Low Resolution)](https://repo-sam.inria.fr/fungraph/hierarchical-3d-gaussians/hierarchical-3d-gaussians_low.pdf) | [📄 Paper (High Resolution)](https://repo-sam.inria.fr/fungraph/hierarchical-3d-gaussians/hierarchical-3d-gaussians_high.pdf) | [🌐 Project Page](https://repo-sam.inria.fr/fungraph/hierarchical-3d-gaussians/)
  
- **Fed3DGS: Scalable 3D Gaussian Splatting with Federated Learning**, Suzuki et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11460) | [💻 Code](https://github.com/DensoITLab/Fed3DGS)

- **Creating Seamless 3D Maps Using Radiance Fields**, Sathyan et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.11364.pdf)

- **HGS-Mapping: Online Dense Mapping Using Hybrid Gaussian Representation in Urban Scenes**, Wu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2403.20159.pdf)

- **CityGaussian: Real-time High-quality Large-Scale Scene Rendering with Gaussians**, Liu et al., arXiv 2024 |[📄 Paper](https://arxiv.org/pdf/2403.20159.pdf) | [🌐 Project Page](https://dekuliutesla.github.io/citygs/) | [💻 Code](https://github.com/DekuLiuTesla/CityGaussian) 

- **MM-Gaussian: 3D Gaussian-based Multi-modal Fusion for Localization and Reconstruction in Unbounded Scenes**, Wu et al., arXiv 2024 | [📄 Paper](https://arxiv.org/pdf/2404.04026.pdf) 

- **On Scaling Up 3D Gaussian Splatting Training**, Zhao et al., arXiv 2024 | [📄 Paper](https://arxiv.org/abs/2406.18533)  | [🌐 Project Page](https://daohanlu.github.io/scaling-up-3dgs/) | [💻 Code](https://github.com/nyu-systems/Grendel-GS) 

<br>

## Data
- [NERDS 360 Multi-View dataset for Outdoor Scenes](https://zubair-irshad.github.io/projects/neo360.html)

<br>

## Courses
- [MIT Inverse Rendering Lectures (Module 2)](https://www.scenerepresentations.org/courses/inverse-graphics-23/)

<br>

## Open Source Implementations 

### Unofficial Implementations
|                                                                                             | Language       | License    |
|---------------------------------------------------------------------------------------------|----------------|------------|
| [Taichi 3D Gaussian Splatting](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting) | taichi         | Apache-2.0 |
| [Gaussian Splatting 3D](https://github.com/heheyas/gaussian_splatting_3d)                   | Python/CUDA    |            |
| [3D Gaussian Splatting](https://github.com/WangFeng18/3d-gaussian-splatting)                | Python/CUDA    | MIT        |
| [fast](https://github.com/MrNeRF/gaussian-splatting-cuda)                                   | C++/CUDA       | Inria/MPII |
| [nerfstudio](https://github.com/nerfstudio-project/gsplat)                                  | Python/CUDA    | Apache-2.0 |
| [taichi-splatting](https://github.com/uc-vision/taichi-splatting)                           | taichi/PyTorch | Apache-2.0 |
| [OpenSplat](https://github.com/pierotofy/OpenSplat)                                         | C++/CPU or GPU | AGPL-3.0   |
| [3D Gaussian Splatting](https://github.com/joeyan/gaussian_splatting)                       | Python/CUDA    | MIT        |
| [Grendel Distributed 3DGS](https://github.com/nyu-systems/Grendel-GS)                       | Python/CUDA    | Apache-2.0 |

### 2D Gaussian Splatting
- [jupyter notebook 2D GS splatting](https://github.com/OutofAi/2D-Gaussian-Splatting)

### Gaussian Style Transfer 
- [Direct Gaussian Style Optimization (DGSO): Stylizing 3D Gaussian Splats](https://github.com/An-u-rag/stylized-gaussian-splatting) - Applying style transfer during gaussian optimization to produce stylized gaussian splats of a scene.

### Game Engines 
- [Unity](https://github.com/aras-p/UnityGaussianSplatting)
- [PlayCanvas](https://github.com/playcanvas/engine/tree/main/extras/splat)
- [Unreal](https://github.com/xverse-engine/XV3DGS-UEPlugin)

### Viewers
- [WebGL Viewer 1](https://github.com/antimatter15/splat)
- [WebGL Viewer 2](https://github.com/kishimisu/Gaussian-Splatting-WebGL)
- [WebGL Viewer 3](https://github.com/BladeTransformerLLC/gauzilla)
- [WebGPU Viewer 1](https://github.com/cvlab-epfl/gaussian-splatting-web)
- [WebGPU Viewer 2](https://github.com/MarcusAndreasSvensson/gaussian-splatting-webgpu)
- [WebGPU Viewer 3](https://github.com/KeKsBoTer/web-splat)
- [Three.js](https://github.com/mkkellogg/GaussianSplats3D)
- [A-Frame](https://github.com/quadjr/aframe-gaussian-splatting)
- [Nerfstudio Unofficial](https://github.com/yzslab/nerfstudio/tree/gaussian_splatting)
- [Nerfstudio Viser](https://github.com/nerfstudio-project/viser)
- [Blender (Editor)](https://github.com/ReshotAI/gaussian-splatting-blender-addon/tree/master)
- [WebRTC viewer](https://github.com/dylanebert/gaussian-viewer)
- [iOS & Metal viewer](https://github.com/laanlabs/metal-splats)
- [jupyter notebook](https://github.com/shumash/gaussian-splatting/blob/mshugrina/interactive/interactive.ipynb)
- [PyOpenGL viewer (also with official CUDA backend)](https://github.com/limacv/GaussianSplattingViewer.git)
- [PlayCanvas Viewer](https://github.com/playcanvas/model-viewer)
- [gsplat.js](https://github.com/dylanebert/gsplat.js)
- [Splatapult](https://github.com/hyperlogic/splatapult) - 3d gaussian splatting renderer in C++ and OpenGL, works with OpenXR for tethered VR
- [3DGS.cpp](https://github.com/shg8/3DGS.cpp) - cross-platform, high performance 3DGS renderer in C++ and Vulkan Compute, supporting Windows, macOS, Linux, iOS, and visionOS
- [vkgs](https://github.com/jaesung-cs/vkgs) - cross-platform, high performance 3DGS renderer in C++ and Vulkan Compute/Graphics
- [Gaussian Viewer](https://github.com/Florian-Barthel/gaussian_viewer) - Loads also Compact3D plys.
- [spaTV](https://github.com/antimatter15/splaTV) - WebGL Viewer for 4D Gaussians (based on SpaceTime Gaussian) with demo [here](http://antimatter15.com/splaTV/)
- [Taichi Viewer](https://github.com/uc-vision/splat-viewer)
- [uc-vision-splat-viewer](https://github.com/uc-vision/splat-viewer)(3D gaussin splatting renderer with benchmarking capability)

### Utilities
- [Kapture](https://github.com/naver/kapture) - A unified data format to facilitate visual localization and structure from motion e.g. for bundler to colmap model conversion
- [Kapture image cropper script](https://gist.github.com/jo-chemla/258e6e40d3d6c2220b29518ff3c17c40) - Undistorted image cropper script to remove black borders with included conversion instructions
- [camorph](https://github.com/Fraunhofer-IIS/camorph) - A toolbox for conversion between camera parameter conventions e.g. Reality Capture to colmap model
- [3DGS Converter](https://github.com/francescofugazzi/3dgsconverter) - A tool for converting 3D Gaussian Splatting .ply files into a format suitable for Cloud Compare and vice-versa
- [SuperSplat](https://github.com/playcanvas/super-splat) - Open source browser-based tool to clean/filter, reorient and compress .ply/.splat files
- [SpectacularAI](https://github.com/SpectacularAI/point-cloud-tools) - Conversion scripts for different 3DGS conventions
- [GSOPs](https://github.com/david-rhodes/GSOPs) - GSOPs (Gaussian Splat Operators) for SideFX Houdini. Import, edit, and export models, or generate synthetic training data

### Tutorial
- [Tutorial from the authors of 3DGS](https://3dgstutorial.github.io/)

### Framework
- [msplat](https://github.com/pointrix-project/msplat) - A modular differential gaussian rasterization library.
- [GauStudio](https://github.com/GAP-LAB-CUHK-SZ/gaustudio) - Unified framework with different paper implementations
- [gaussian-splatting-lightning](https://github.com/yzslab/gaussian-splatting-lightning) - A 3D Gaussian Splatting framework with various derived algorithms and an interactive web viewer

### Other
- [My-exp-Gaussians](https://github.com/ingra14m/My-exp-Gaussians) - Enhancing the ability of 3D Gaussians to model complex scenes
- [360-gaussian-splatting](https://github.com/inuex35/360-gaussian-splatting) - Generate gaussian splatting directly from 360 images


## Blog Posts

1. [Gaussian Splatting is pretty cool](https://aras-p.info/blog/2023/09/05/Gaussian-Splatting-is-pretty-cool/)
2. [Making Gaussian Splats smaller](https://aras-p.info/blog/2023/09/13/Making-Gaussian-Splats-smaller/)
3. [Making Gaussian Splats more smaller](https://aras-p.info/blog/2023/09/27/Making-Gaussian-Splats-more-smaller/)
4. [Introduction to 3D Gaussian Splatting](https://huggingface.co/blog/gaussian-splatting)
5. [Very good (technical) intro to 3D Gaussian Splatting](https://medium.com/@AriaLeeNotAriel/numbynum-3d-gaussian-splatting-for-real-time-radiance-field-rendering-kerbl-et-al-60c0b25e5544)
6. [Write up on some mathematical details of the 3DGS implementation](https://github.com/kwea123/gaussian_splatting_notes)
7. [Discussion about gs universal format](https://github.com/mkkellogg/GaussianSplats3D/issues/47#issuecomment-1801360116)
8. [Math explanation to understand 3DGS](https://github.com/chiehwangs/3d-gaussian-theory)
9. [Compressing Gaussian Splats](https://blog.playcanvas.com/compressing-gaussian-splats/)
10. [Comprehensive overview of Gaussian Splatting](https://towardsdatascience.com/a-comprehensive-overview-of-gaussian-splatting-e7d570081362)
11. [Gaussian Head Avatars: A Summary](https://towardsdatascience.com/gaussian-head-avatars-a-summary-2bd17bd48500)
12. [NeRFs vs. 3DGS](https://edwardahn.me/writing/NeRFvs3DGS/)
13. [Howto capture images for 3DGS](https://medium.com/@heyulei/capture-images-for-gaussian-splatting-81d081bbc826)
14. [Mathematical details of forward and backward passes](https://github.com/joeyan/gaussian_splatting/blob/main/MATH.md)
15. [3D in Geospatial: NeRFs, Gaussian Splatting, and Spatial Computing](https://ckoziol.com/blog/2024/radiance_methods/)

## Tutorial Videos

1. [Getting Started with 3DGS for Windows](https://youtu.be/UXtuigy_wYc?si=j1vfORNspcocSH-b)
2. [How to view 3DGS Scenes in Unity](https://youtu.be/5_GaPYBHqOo?si=6u9j1HqXwF_5WSUL)
3. [Two-minute explanation of 3DGS](https://youtu.be/HVv_IQKlafQ?si=w5c9XKHfKIBuXDLW)
4. [Jupyter notebook tutorial](https://www.youtube.com/watch?v=OcvA7fmiZYM&t=2s)
5. [Intro to gaussian splatting (and Unity plugin)](https://www.xuanprada.com/blog/2023/10/22/intro-to-gaussian-splatting)
6. [Computerphile 3DGS explanation](https://youtu.be/VkIJbpdTujE?si=1GLjzBfF9LCuT22o)

## Credits
Most credits should be contributed to [Awesome 3D Gaussian Splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting?tab=readme-ov-file#slam), [3D Gaussian Splatting Papers](https://github.com/Awesome3DGS/3D-Gaussian-Splatting-Papers)