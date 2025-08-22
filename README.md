# 3D-Medical-Imaging-Review

## Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models

This repository serves as a companion resource to our review paper *"Voxels to Vision"*.  
The review traces the evolution of **3D medical image analysis**, highlighting how the field has progressed from early deep learning architectures such as CNNs and RNNs, to generative models (VAEs, GANs, diffusion models), and more recently to large-scale **foundation models** that integrate vision, language, and multimodal pre-training.  

Our work provides:
- A **historical perspective** on how 3D medical imaging analysis has evolved over the last decade.  
- A **comparative discussion** of strengths, limitations, and applications of each paradigm across core tasks such as segmentation, detection, classification, reconstruction, and report generation.  
- Insights into **emerging research frontiers** including multimodal fusion, generalization across institutions, and the integration of trustworthy AI in clinical practice.  
- A curated collection of **resources** to support researchers and practitioners in the field.  

---

## 📚 Available Resources in This Repository

- 📊 **3D Medical Imaging Datasets**  
  A curated list of publicly available datasets (MRI, CT, PET, Ultrasound) for tasks such as tumor segmentation, organ delineation, disease classification, and population-level studies. Each entry includes dataset description, modality, tasks, and official access links.  

- 🤖 **AI Models and GitHub Repositories**  
  A selection of open-source projects related to **3D deep learning**, covering medical-specific frameworks (e.g., nnUNet, MONAI, VoxelMorph) as well as general-purpose 3D computer vision models (e.g., PointNet, Minkowski Engine, Kaolin). These repositories provide code for segmentation, classification, detection, augmentation, and generative modeling.  

- 📑 **Citation Information**  
  BibTeX entry for citing our review paper if you use this repository or the resources listed here in your own research.  

---

By bringing these resources together, this repository aims to act as a **practical guide** for researchers, students, and practitioners who want to explore or build upon the rapidly evolving landscape of **3D medical image analysis**.  


## 1. Public 3D Medical Imaging Datasets

| Dataset Name | Modality | Task(s) | No. of Subjects / Scans | Access Link |
|--------------|----------|---------|--------------------------|-------------|
| BraTS (Brain Tumor Segmentation Challenge) | MRI (T1, T1Gd, T2, FLAIR) | Segmentation, Classification | ~2000+ cases | [BraTS](https://www.med.upenn.edu/cbica/brats2023/data.html) |
| LUNA16 | CT | Nodule Detection, Classification | 888 low-dose CT scans | [LUNA16](https://luna16.grand-challenge.org/) |
| LiTS (Liver Tumor Segmentation Challenge) | CT | Liver & Tumor Segmentation | 131 CT scans | [LiTS](https://competitions.codalab.org/competitions/17094) |
| KiTS (Kidney Tumor Segmentation Challenge) | CT | Kidney & Tumor Segmentation | 300+ CT scans | [KiTS](https://kits21.kits-challenge.org/) |
| AMOS22 | CT + MRI | Multi-Organ Segmentation | 500+ CT/MRI scans, 15 organs | [AMOS22](https://amos22.grand-challenge.org/) |
| MSD (Medical Segmentation Decathlon) | CT, MRI | Multi-organ Segmentation | 10 tasks, 2,633 scans | [MSD](http://medicaldecathlon.com/) |
| TCIA Collections | CT, MRI, PET | Multi-task | 50+ curated datasets | [TCIA](https://www.cancerimagingarchive.net/) |
| ADNI | MRI, PET | Alzheimer’s Progression | 3000+ scans | [ADNI](http://adni.loni.usc.edu/) |
| UK Biobank Imaging | MRI, CT, Ultrasound | Population Study | 100,000+ participants | [UK Biobank](https://www.ukbiobank.ac.uk/) |

---

## 2. GitHub Codes for 3D Imaging AI Models

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
| Med-DDPM | Diffusion-based Generative Models | Synthesis, Segmentation | Medical Imaging | [Med-DDPM](https://github.com/voxelmorph/med-ddpm) |

---

## 3. Citation

If you use this repository, please cite:

```bibtex
@article{owais2025voxels,
  title={Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models},
  author={Owais, Muhammad and Zubair, Muhammad and Abdul Kareem, Daniya Najiha and Naseer, Sana Akhtar and Alam, Mehbub and Ahmad, Mubashir and Hussain, Irfan},
  journal={},
  year={2025}
}
