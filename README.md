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

### 🤖 GitHub Codes for 3D Imaging AI Models
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
| 3D-UNet | CNN-based Models |  Segmentation | Medical Imaging | https://github.com/wolny/pytorch-3dunet |
| Brain-MRI-Classification | CNN-based Models |  Segmentation | Medical Imaging | https://github.com/strikersps/Brain-MRI-Image-Classification-Using-Deep-Learning |
| Residual CNN | CNN-based Models |  Classification | Medical Imaging | https://github.com/neuro-ml/resnet_cnn_mri_adni |
| 2.5D CNN | CNN-based Models |  Classification | Medical Imaging | https://github.com/shabanian2018/Age_MRI-Classification |
| 3D-UXNet | CNN-based Models |  Segmentation | Medical Imaging | https://github.com/MASILab/3DUX-Net |
| MedNeXT | CNN-based Models |  Segmentation | Medical Imaging | https://github.com/MIC-DKFZ/MedNeXt |
| VoxelMorph | CNN-based Models | Registration, Alignment | Medical Imaging | https://github.com/voxelmorph/voxelmorph |
| Recurrent 3D DenseUNet | RNN-based Models |  Segmentation | Medical Imaging | https://github.com/muntakimrafi/TIA2020-Recurrent-3D-DenseUNet |
| Bi-directional RNN | RNN-based Models |  Segmentation | Medical Imaging | https://github.com/oopil/3D_medical_image_FSS |
| RNN-NAD | RNN-based Models | Prediction | Medical Imaging | https://github.com/ThomasYeoLab/Standalone_Nguyen2020_RNNAD |
| Brain-on-Cloud | RNN-based Models | Classification | Medical Imaging | https://github.com/airtlab/Brain-on-Cloud |
| UNet-CRF-RNN | RNN-based Models | Segmentation | Medical Imaging | https://github.com/EsmeYi/UNet-CRF-RNN |
| U-VixLSTM | RNN-based Models | Segmentation | Medical Imaging | https://github.com/duttapallabi2907/U-VixLSTM |
| UNETR | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV |
| Swin-Unet | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/HuCaoFighting/Swin-Unet |
| TransUNet | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Beckschen/TransUNet |
| Swin-UNETR | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Project-MONAI/research-contributions/tree/main/SwinUNETR |
| DwinFormer | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Daniyanaj/DWINFORMER |
| nnFormer | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/282857341/nnformer |
| VT-UNet | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/himashi92/vt-unet |
| TransFuse | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Rayicer/TransFuse |
| MedViT | Transformer-based Models | Classification | Medical Imaging | https://github.com/Rayicer/TransFuse |
| UNETR++ | Transformer-based Models | Segmentation | Medical Imaging | https://github.com/Amshaker/unetr_plus_plus |
| seGAN | GAN-based Models | Segmentation | Medical Imaging | https://github.com/YuanXue1993/SegAN |
| GAN-Unet 3D| GAN-based Models | Segmentation | Medical Imaging | https://github.com/arnab39/FewShot_GAN-Unet3D |
| f-Anogan | GAN-based Generative Models | Synthesis, Detection | Medical Imaging | https://github.com/tSchlegl/f-AnoGAN |
| ResTransGAN | GAN-based Generative Models | Synthesis, Segmentation | Medical Imaging | https://github.com/bithuanglq/ResTransGAN  |
| DiffMIC | Diffussion-based Generative Models | Classification | Medical Imaging | https://github.com/tSchlegl/f-AnoGAN |
| MedsSegDiff | Diffussion-based Generative Models | Synthesis, Segmentation | Medical Imaging | https://github.com/SuperMedIntel/MedSegDiff |
| Med-DDPM | Diffusion-based Generative Models | Synthesis, Segmentation | Medical Imaging | https://github.com/mobaidoctor/Med-DDPM |
| 3D- MedDiffusion | Diffussion-based Generative Models | Synthesis | Medical Imaging | https://github.com/ShanghaiTech-IMPACT/3D-MedDiffusion?tab=readme-ov-file |
| Diff-UNet | Diffussion-based Generative Models | Segmentation | Medical Imaging | https://github.com/ge-xing/Diff-UNet |
| VAE-Seg | VAE-based Generative Models | Segmentation | Medical Imaging | https://github.com/IAmSuyogJadhav/3d-mri-brain-tumor-segmentation-using-autoencoder-regularization |
| BiomedCLIP | Textually Prompted Foundation Models | Image retrieval, Image classification, Visual question-answering | Medical Imaging | https://github.com/microsoft/BiomedCLIP_data_pipeline |
| MedBLIP | Textually Prompted Foundation Models | Zero-shot prediction tasks, Zero-shot Visual question-answering| Medical Imaging | https://github.com/Qybc/MedBLIP |
| Med-Flamingo | Textually Prompted Foundation Models |  Visual question-answering | Medical Imaging | https://github.com/snap-stanford/med-flamingo |
| LLaVa-Med | Textually Prompted Foundation Models |  Assisting Multi-modal Conversations, Biomedical Visual Question Answering | Medical Imaging |https://github.com/microsoft/LLaVA-Med |
| UniMedCLIP | Textually Prompted Foundation Models |  Zero-shot Prediction Tasks | Medical Imaging |https://github.com/mbzuai-oryx/UniMed-CLIP |
| Med3DVLM | Textually Prompted Foundation Models |  Visual question-answering | Medical Imaging |https://github.com/mirthAI/Med3DVLM |
| MedSAM | Visually Prompted Foundation Models |  Zero-shot segmentation | Medical Imaging | https://github.com/bowang-lab/MedSAM |
| SAM-Med3D | Visually Prompted Foundation Models |  Zero-shot segmentation | Medical Imaging | https://github.com/uni-medical/SAM-Med3D |
| Med-SAM2 | Visually Prompted Foundation Models |  Zero-shot segmentation | Medical Imaging | https://github.com/bowang-lab/MedSAM2 |
| MedPaLM | Visually Prompted Foundation Models |  Image classification, report summarization, report generation, visual question answering| Medical Imaging | https://github.com/kyegomez/Med-PaLM |


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
