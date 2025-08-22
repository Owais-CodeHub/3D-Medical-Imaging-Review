# 🌐 3D-Medical-Imaging-Review

## Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models

---

### 📖 About This Review
This repository serves as a companion resource to our review paper *"Voxels to Vision"*.  

The paper traces the **evolution of 3D medical image analysis**, highlighting the transformation from early deep learning architectures to modern foundation models. Specifically, it covers:  
- 🏛️ **Classic Deep Learning Models** – CNNs, RNNs, and early Transformers  
- 🧪 **Generative Models** – VAEs, GANs, and diffusion models for synthesis, augmentation, and reconstruction  
- 🌍 **Foundation Models** – multimodal architectures that integrate vision, language, and large-scale pre-training for universal medical imaging tasks  

Our review provides:  
- A **historical perspective** on how 3D medical imaging has advanced over the past decade  
- **Comparative insights** into strengths, limitations, and performance across tasks such as segmentation, detection, classification, reconstruction, and report generation  
- Discussion of **emerging research frontiers** including multimodal fusion, cross-institution generalization, and trustworthy AI for clinical adoption  
- A **curated resource hub** for datasets and open-source code  

---

## 📚 Available Resources

This repository collects practical resources to help researchers, students, and practitioners accelerate their work in 3D medical image analysis.

### 📊 Public 3D Medical Imaging Datasets
A curated list of openly available datasets covering MRI, CT, PET, and Ultrasound modalities.

| Dataset Name | Modality | Task(s) | No. of Subjects / Scans | Access Link |
|--------------|----------|---------|--------------------------|-------------|
| BraTS (Brain Tumor Segmentation Challenge) | MRI (T1, T1Gd, T2, FLAIR) | Segmentation, Classification | ~2000+ cases | [BraTS](https://www.med.upenn.edu/cbica/brats/) |
| LUNA16 | CT | Nodule Detection, Classification | 888 low-dose CT scans | [LUNA16] (https://luna16.grand-challenge.org/Data/) |
| LiTS (Liver Tumor Segmentation Challenge) | CT | Liver & Tumor Segmentation | 131 CT scans | [LiTS](https://www.kaggle.com/datasets/andrewmvd/lits-png) |
| KiTS (Kidney Tumor Segmentation Challenge) | CT | Kidney & Tumor Segmentation | 300+ CT scans | [KiTS](https://kits21.kits-challenge.org/) |
| AMOS22 | CT + MRI | Multi-Organ Segmentation | 500+ CT/MRI scans, 15 organs | [AMOS22](https://amos22.grand-challenge.org/) |
| MSD (Medical Segmentation Decathlon) | CT, MRI | Multi-organ Segmentation | 10 tasks, 2,633 scans | [MSD](http://medicaldecathlon.com/) |
| TCIA Collections | CT, MRI, PET | Multi-task | 50+ curated datasets | [TCIA](https://www.cancerimagingarchive.net/) |
| ADNI | MRI, PET | Alzheimer’s Progression | 3000+ scans | [ADNI](http://adni.loni.usc.edu/) |
| UK Biobank Imaging | MRI, CT, Ultrasound | Population Study | 100,000+ participants | [UK Biobank](https://www.ukbiobank.ac.uk/) |

---

### 🤖 GitHub Codes for 3D Imaging AI Models
A collection of recent open-source implementations for 3D analysis — spanning medical imaging frameworks and general-purpose 3D computer vision libraries.

| Repository | Model / Framework | Task(s) | Domain | Link |
|------------|------------------|---------|--------|------|
| nnUNet | Universal Segmentation Framework | 3D Segmentation | Medical Imaging | [nnUNet](https://github.com/MIC-DKFZ/nnUNet) |
| MONAI | PyTorch-based Medical Imaging AI | Classification, Segmentation, Detection | Medical Imaging | [MONAI](https://github.com/Project-MONAI/MONAI) |
| TotalSegmentator | Segmentation of 100+ Anatomical Structures | Segmentation | Medical Imaging | [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) |
| TorchIO | Data Augmentation & Preprocessing | Augmentation, Preprocessing | Medical Imaging | [TorchIO](https://github.com/fepegar/torchio) |
| Kaolin (NVIDIA) | 3D Deep Learning Framework | Classification, Segmentation, Rendering | General 3D | [Kaolin](https://github.com/NVIDIAGameWorks/kaolin) |
| Minkowski Engine | Sparse Convolutional Networks | 3D Detection, Segmentation | General 3D | [MinkowskiEngine](https://github.com/NVIDIA/MinkowskiEngine) |
| PointNet/PointNet++ | Point Cloud Networks | Classification, Segmentation | General 3D | [PointNet](https://github.com/charlesq34/pointnet) |
| 3D ResNets | 3D CNN Models | Classification, Action Recognition | General 3D | [3D ResNets](https://github.com/kenshohara/3D-ResNets-PyTorch) |
| VoxelMorph | Learning-based Image Registration | Registration, Alignment | Medical Imaging | [VoxelMorph](https://github.com/voxelmorph/voxelmorph) |
| Med-DDPM | Diffusion-based Generative Models | Synthesis, Segmentation | Medical Imaging | [Med-DDPM](https://github.com/mobaidoctor/med-ddpm) |

---

## 📑 Citation

If you use this repository or the resources, please cite our paper:

```bibtex
@article{owais2025voxels,
  title={Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models},
  author={Muhammad Owais, Muhammad Zubair, Daniya Najiha Abdul Kareem, Sana Akhtar Naseer, Mehbub Alam, Mubashir Ahmad, and Irfan Hussain},
  journal={Preprint},
  year={2025}
}
