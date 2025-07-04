# Awesome 3D Gaussian Splatting

<div align="center">
  A curated collection of resources focused on 3D Gaussian Splatting (3DGS) and related technologies.

  [**Browse the Paper List**](https://mrnerf.github.io/awesome-3D-gaussian-splatting/) | [**Contribute**](CONTRIBUTING.md) | [**MrNeRF**](https://www.mrnerf.com)

</div>

## Contents

- [Papers &amp; Documentation](#papers--documentation)
- [Implementations](#implementations)
- [Viewers &amp; Game Engine Support](#viewers--game-engine-support)
- [Tools &amp; Utilities](#tools--utilities)
- [Learning Resources](#learning-resources)
- [Sponsors](#sponsors)

## Papers & Documentation

### Papers Database

Visit our comprehensive, searchable database of 3D Gaussian Splatting papers:
[Papers Database](https://mrnerf.github.io/awesome-3D-gaussian-splatting/)

### Courses

- [MIT Inverse Rendering Lectures (Module 2)](https://www.scenerepresentations.org/courses/inverse-graphics-23/) - Academic deep dive into inverse rendering

### Datasets

- [NERDS 360 Multi-View dataset](https://zubair-irshad.github.io/projects/neo360.html) - High-quality outdoor scene dataset

## Implementations

### Official Reference

- [Original Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) - The reference implementation by the original authors

### Community Implementations

| Implementation                                                           | Language    | License    | Description                     |
| ------------------------------------------------------------------------ | ----------- | ---------- | ------------------------------- |
| [Taichi 3D GS](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting) | Taichi      | Apache-2.0 | Taichi-based implementation     |
| [Nerfstudio gsplat](https://github.com/nerfstudio-project/gsplat)           | Python/CUDA | Apache-2.0 | Integration with Nerfstudio     |
| [fast](https://github.com/MrNeRF/gaussian-splatting-cuda)                   | C++/CUDA    | Inria/MPII | High-performance implementation |
| [OpenSplat](https://github.com/pierotofy/OpenSplat)                         | C++/CPU/GPU | AGPL-3.0   | Cross-platform solution         |
| [Grendel](https://github.com/nyu-systems/Grendel-GS)                        | Python/CUDA | Apache-2.0 | Distributed computing focus     |
| [Warp 3DGS](https://github.com/guoriyue/3dgs-warp-scratch)                  | Warp/Python | AGPL-3.0   | Warp-based implementation       |

### Frameworks

- [Pointrix](https://github.com/pointrix-project/pointrix) - Differentiable point-based rendering
- [GauStudio](https://github.com/GAP-LAB-CUHK-SZ/gaustudio) - Unified framework with multiple implementations
- [DriveStudio](https://github.com/ziyc/drivestudio) - Urban scene reconstruction framework
- [GSCodecStudio](https://github.com/JasonLSC/GSCodec_Studio) - Compression and Dynamic splattings

## Viewers & Game Engine Support

### Game Engines

- [Unity Plugin](https://github.com/aras-p/UnityGaussianSplatting)
- [Unreal Plugin](https://github.com/xverse-engine/XV3DGS-UEPlugin)
- [PlayCanvas Integration](https://github.com/playcanvas/engine/tree/main/src/scene/gsplat)

### Web Viewers

**WebGL**

- [Splat Viewer](https://github.com/antimatter15/splat)
- [Gauzilla](https://github.com/BladeTransformerLLC/gauzilla)
- [Interactive Viewer](https://github.com/kishimisu/Gaussian-Splatting-WebGL)
- [GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D)

**WebGPU**

- [EPFL Viewer](https://github.com/cvlab-epfl/gaussian-splatting-web)
- [WebGPU Splat](https://github.com/KeKsBoTer/web-splat)

### Desktop Viewers

**Linux**

- [DearGaussianGUI](https://github.com/leviome/DearGaussianGUI)
- [LiteViz-GS](https://github.com/panxkun/liteviz-gs)

### Native Applications

- [Blender Add-on](https://github.com/ReshotAI/gaussian-splatting-blender-addon)
- [Blender Add-on (KIRI)](https://github.com/Kiri-Innovation/3dgs-render-blender-addon)
- [Blender Add-on (404—GEN)](https://github.com/404-Repo/three-gen-blender-plugin)
- [iOS Metal Viewer](https://github.com/laanlabs/metal-splats)
- [OpenGL Viewer](https://github.com/limacv/GaussianSplattingViewer)
- [VR Support (OpenXR)](https://github.com/hyperlogic/splatapult)
- [ROS2 Support](https://github.com/shadygm/ROSplat)

## Tools & Utilities

### Data Processing

- [Kapture](https://github.com/naver/kapture) - Unified data format for visual localization
- [3DGS Converter](https://github.com/francescofugazzi/3dgsconverter) - Format conversion tool
- [SuperSplat](https://github.com/playcanvas/super-splat) - Browser-based cleanup tool
- [Point Cloud Editor](https://github.com/JohannesKrueger/pointcloudeditor) - Web-based point cloud editing
- [SPZ Converter](https://github.com/stytim/spz) - SPZ conversion tool
- [gsbox Converter](https://github.com/gotoeasy/gsbox) - PLY SPLAT SPZ SPX conversion tool

### Development Tools

- [GSOPs for Houdini](https://github.com/david-rhodes/GSOPs) - Houdini integration tools
- [camorph](https://github.com/Fraunhofer-IIS/camorph) - Camera parameter conversion

## Learning Resources

### Blog Posts

- [3DGS Introduction](https://huggingface.co/blog/gaussian-splatting) - HuggingFace guide
- [Implementation Details](https://github.com/kwea123/gaussian_splatting_notes) - Technical deep dive
- [Mathematical Foundation](https://github.com/chiehwangs/3d-gaussian-theory) - Theory explanation
- [Capture Guide](https://medium.com/@heyulei/capture-images-for-gaussian-splatting-81d081bbc826) - Image capture tutorial

### Talks

- [Gaussian Splats: Ready for Standardization?](https://www.youtube.com/watch?v=0xdPpKSkO3I) - Metaverse Standards Forum 1/28/2025
- [Unity Integration Guide](https://www.youtube.com/watch?v=pM_HV2TU4rU&t=5298s) - Metaverse Standards Forum 5/6/2025

### Video Tutorials

- [Getting Started (Windows)](https://youtu.be/UXtuigy_wYc)
- [Gaussian Splats Town Hall - Part 2](https://youtu.be/5_GaPYBHqOo)
- [Two-Minute Explanation](https://youtu.be/HVv_IQKlafQ)
- [Jupyter Tutorial](https://www.youtube.com/watch?v=OcvA7fmiZYM)

## Sponsors

A big thank you to our sponsors for their generous support:

- [Yehe Liu](https://x.com/YeheLiu)
