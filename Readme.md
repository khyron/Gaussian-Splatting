# Gaussian Splatting Models

This repository hosts **Gaussian Splatting models** for real-time 3D rendering and visualization. These models are generated using the [Gaussian Splatting](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) technique, which represents a scene as a set of anisotropic 3D Gaussians instead of traditional meshes or point clouds.

---

## 📦 Releases

Precompiled **Gaussian Splatting model files** (`.ply`) are available under the [Releases](https://github.com/khyron/Gaussian-Splatting/releases) section.
Download them to test directly in supported viewers, pipelines, or convert them into alternative formats for your workflow.

---

## 📂 File Format

All models are stored in the **`.ply` (Polygon File Format / Stanford PLY)** format.

### PLY Format Description

* **Type**: ASCII or Binary
* **Usage**: Commonly used to store 3D data such as vertices, normals, colors, and in the case of Gaussian Splatting, additional attributes like scale and opacity.
* **Structure**:

  * A **header** that describes the properties of each element (vertex, face, Gaussian attributes).
  * A **body** that contains the actual data values.

For Gaussian Splatting models, the PLY file typically contains:

* `x, y, z` → 3D position
* `nx, ny, nz` → Normal direction
* `r, g, b` → Color information
* `scale_x, scale_y, scale_z` → Ellipsoid radii for splats
* `opacity` → Transparency value

📖 **PLY File Format Reference**:

* [Stanford PLY Format Documentation](http://paulbourke.net/dataformats/ply/)
* [Wikipedia: Polygon File Format](https://en.wikipedia.org/wiki/PLY_%28file_format%29)

---

## 🛠 Tools for Editing & Converting `.ply` Files

You can use the following tools to **edit, convert, or visualize** PLY files:

* **[Supersplat](https://github.com/antimatter15/supersplat)** – Tool for viewing and editing Gaussian Splatting models in the browser.
* **[Splat-Transform](https://github.com/playcanvas/splat-transform)** – Utility for converting Gaussian Splat models into different formats.
* **[MeshLab](https://www.meshlab.net/)** – Open-source system for processing and editing 3D triangular meshes.
* **[CloudCompare](https://www.danielgm.net/cc/)** – 3D point cloud and mesh processing software.
* **[Blender](https://www.blender.org/)** – Free and open-source 3D creation suite (supports `.ply` import/export).
* **[Assimp (Open Asset Import Library)](https://www.assimp.org/)** – Library and tools to convert between different 3D formats.
* **[Online 3D Viewer](https://3dviewer.net/)** – Browser-based tool to preview `.ply` and other 3D files without installing software.

---

## 🎨 Plugins & Integrations

Gaussian Splatting models can be integrated into common creative pipelines using plugins or add-ons:

* **Blender**:

  * [Blender Kiri Engine Add-on](https://github.com/Kiri-Innovation/3dgs-render-blender-addon)
* **After Effects / Davinci Reolve **:

  * [irrealix - Plugin](https://aescripts.com/authors/f-l/irrealix/) – Gaussian Splat/NeRF integration for motion graphics and compositing.
* **Other 3D & VFX Tools**:

  * [Unreal Engine Plugin (3DGS)](https://github.com/graphdeco-inria/gaussian-splatting/tree/main/unreal)
  * [Unity Gaussian Splatting Viewer](https://github.com/aras-p/UnityGaussianSplatting)

---

## 📚 Related Resources

* Original paper: [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)
* Codebase: [3DGS GitHub Repository](https://github.com/graphdeco-inria/gaussian-splatting)
* Dataset examples: [Official 3DGS Datasets](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/datasets/)

---

## 🚀 Usage

1. Clone this repository

   ```bash
   git clone https://github.com/yourusername/gaussian-splatting-models.git
   ```
2. Download `.ply` models from the **Releases** page.
3. Open the models in your preferred 3D viewer or Gaussian Splatting renderer.
4. Convert or edit using MeshLab, Blender, CloudCompare, Supersplat, or Splat-Transform.

---

## 📄 License  

This repository is licensed under the [Creative Commons Attribution 4.0 International License (CC-BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  

You are free to:  
- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material for any purpose, even commercially  

Under the following terms:  
- **Attribution** — You must give appropriate credit, provide a link to this repository, and indicate if changes were made.  

