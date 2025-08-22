# 3D-Medical-Imaging-Review

## Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models

---

### About This Review
This repository serves as a companion resource to our review paper *"Voxels to Vision"*.  

The paper traces the **evolution of 3D medical image analysis**, highlighting the transformation from early deep learning architectures to modern foundation models. Specifically, it covers:  
- **Classic Deep Learning Models** – CNNs, RNNs, and early Transformers  
- **Generative Models** – VAEs, GANs, and diffusion models for synthesis, augmentation, and reconstruction  
- **Foundation Models** – multimodal architectures that integrate vision, language, and large-scale pre-training for universal medical imaging tasks  

Our review provides:  
- A **historical perspective** on how 3D medical imaging has advanced over the past decade  
- **Comparative insights** into strengths, limitations, and performance across tasks such as segmentation, detection, classification, reconstruction, and report generation  
- Discussion of **emerging research frontiers** including multimodal fusion, cross-institution generalization, and trustworthy AI for clinical adoption  
- A **curated resource hub** for datasets and open-source code  

---

## Available Resources

This repository collects practical resources to help researchers, students, and practitioners accelerate their work in 3D medical image analysis.

### Public 3D Medical Imaging Datasets
A curated list of openly available datasets covering MRI, CT, PET, and Ultrasound modalities.

| Dataset Name | Modality | Task(s) | No. of Subjects / Scans | Access Link |
|--------------|----------|---------|--------------------------|-------------|
| BraTS (Brain Tumor Segmentation Challenge) | MRI (T1, T1ce, T2, FLAIR) | Segmentation, Classification | ~2000+ cases | https://www.med.upenn.edu/cbica/brats/ |
| LUNA16 (LIDC-IDRI subset) | CT | Nodule Detection, Classification | 888 scans | Challenge: https://luna16.grand-challenge.org/ • Data: https://luna16.grand-challenge.org/Data/ |
| Medical Segmentation Decathlon (MSD) | CT, MRI | Multi-organ Segmentation (10 tasks) | 2,633 scans | https://medicaldecathlon.com/ |
| AMOS22 (Abdominal Multi-Organ Segmentation) | CT + MRI | Multi-organ Segmentation (15 organs) | 500 CT + 100 MRI | Challenge: https://amos22.grand-challenge.org/ • Data: https://zenodo.org/records/7262581 |
| The Cancer Imaging Archive (TCIA) – Portal | CT, MRI, PET | Multi-task (various collections) | Many collections | https://www.cancerimagingarchive.net/ |
| LIDC-IDRI (TCIA collection) | CT | Lung Nodule Detection/Analysis | 1,010 subjects | https://www.cancerimagingarchive.net/collection/lidc-idri/ |
| BraTS-AFRICA (TCIA collection) | MRI (T1, T1ce, T2, FLAIR) | Brain Tumor Segmentation | 146 cases | https://www.cancerimagingarchive.net/collection/brats-africa/ |
| MedMNIST v2 (3D subsets) | 3D biomedical (28×28×28) | Classification | 6 3D datasets (~10k total) | https://medmnist.com/v2 |
| MedShapeNet | 3D anatomical shapes | Segmentation, Classification, Reconstruction | 100,000+ shapes | https://medshapenet.ikim.nrw/ |
| OpenNeuro | MRI/fMRI/MEG/EEG/PET | Various neuroimaging tasks | 600+ datasets | https://openneuro.org |





---

### GitHub Codes for 3D Imaging AI Models
A collection of recent open-source implementations for 3D analysis — spanning medical imaging frameworks and general-purpose 3D computer vision libraries.

| Repository | Model / Framework | Task(s) | Domain | Link |
|------------|------------------|---------|--------|------|
| nnU-Net | Universal Segmentation Framework | 3D Segmentation | Medical Imaging | https://github.com/MIC-DKFZ/nnUNet |
| MONAI | PyTorch-based Medical Imaging AI | Classification, Segmentation, Detection | Medical Imaging | https://github.com/Project-MONAI/MONAI |
| TotalSegmentator | Segmentation of 100+ Anatomical Structures | Segmentation | Medical Imaging | https://github.com/wasserth/TotalSegmentator |
| TorchIO | Data Augmentation & Preprocessing | Augmentation, Preprocessing | Medical Imaging | https://github.com/fepegar/torchio |
| Kaolin (NVIDIA) | 3D Deep Learning Framework | Classification, Segmentation, Rendering | General 3D | https://github.com/NVIDIAGameWorks/kaolin |
| Minkowski Engine | Sparse Convolutional Networks | 3D Detection, Segmentation | General 3D | https://github.com/NVIDIA/MinkowskiEngine |
| PointNet/PointNet++ | Point Cloud Networks | Classification, Segmentation | General 3D | https://github.com/charlesq34/pointnet |
| 3D ResNets | 3D CNN Models | Classification, Action Recognition | General 3D | https://github.com/kenshohara/3D-ResNets-PyTorch |
| VoxelMorph | Learning-based Image Registration | Registration, Alignment | Medical Imaging | https://github.com/voxelmorph/voxelmorph |
| Med-DDPM | Diffusion-based Generative Models | Synthesis, Segmentation | Medical Imaging | https://github.com/mobaidoctor/Med-DDPM |


---

## Citation

If you use this repository or the resources, please cite our paper:

```bibtex
@article{owais2025voxels,
  title={Voxels to Vision: A Comprehensive Review Tracing the Evolution of 3D Medical Imaging Analysis from Classic CNNs to Emerging Foundation Models},
  author={Muhammad Owais, Muhammad Zubair, Daniya Najiha Abdul Kareem, Sana Akhtar Naseer, Mehbub Alam, Mubashir Ahmad, and Irfan Hussain},
  journal={Preprint},
  year={2025}
}
