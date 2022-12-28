# 👏Review of Deep Face Spoofing and Deep Face Anti-Spoofing🎭 #

![dfs_dfas](./pictures/DFS%20and%20DFAS.png)
This is the accompanying webpage for "Deep Facial Spoofing and Deep Face Anti-Spoofing: a Systematic Literature Review", a critical review of recent progress in deep learning methods for face spoofing and anti-spoofing.

## Introduction
We present taxonomies and provide an up-to-date and critical review of recent deep-face spoofing (DFS) and deep face anti-spoofing (DFAS) models. We identify three main groups of DFS mechanisms: template and model inversion, adversarial examples, and identity-agnostic faces. Likewise, DFAS mechanisms could be divided into three categories: DFAS as deep discriminative learning, DFAS as generative learning, and DFAS as joint or hybrid learning.

🔔This web page will be continuously updated with new studies🔥
_____________

## Contents ##
* [Deep Face Spoofing](#DFS)
    * [DFS1: Template and Model Inversion](#DFS1)
    * [DFS2: Adversarial Examples](#DFS2)
    * [DFS3: Identity-Agnostic Faces](#DFS3)
* [Deep Face-Anti Spoofing](#DFAS)
    * [DFAS1: DFAS as Deep Discriminative Learning](#DFAS1)
    * [DFAS2: DFAS as Deep Generative Learning](#DFAS2)
    * [DFAS3: DFAS as Joint/Hybrid Learning](#DFAS3)
        * [Joint Traditional and Deep Architectures](#Joint1)
        * [Joint Multiple Deep Architectures](#Joint2)
        
_____________

<a name="DFS"></a>
### Deep Face Spoofing ####
<img src="./pictures/taxonomy_dfs.png" width="720">

<a name="DFS1"></a>
#### 1️⃣DFS1: Template and Model Inversion

<p align="center">
   <img src="./pictures/Deep%20Template%20Reconstruction.png" style="width:300pt"><br />
   <strong>Deep Template Inversion<br /><br />
   <img src="./pictures/Model%20Inversion.png" style="width:300pt"><br />
   <strong>Deep Model Inversion<br /><br />
<p\>
    
| Method            | Year | Category                    | Backbone                                   | White/Grey/Black Box   | Static/Dynamic |
| ----------------- | ---- | --------------------------- | ------------------------------------------ | ---------------------- | -------------- |
| NbNet             | 2019 | Deep template inversion     | De-CNN                                     | Black                  | S              |
| GHDFI-StyleGAN2   | 2021 | Deep template inversion     | StyleGAN2                                  | Black                  | S              |
| BiohashGAN        | 2022 | Inverting binarizations     | GAN+SimHashNet                             | Black                  | S              |
| Binary Inversion  | 2021 | Inverting binarizations     | De-CNN+FCN                                 | White                  | S              |
| Deep MIA          | 2022 | Model inversion             | α\-GAN+Face Seed Initialization            | White                  | S              |
| Deep MIA-blackbox | 2021 | Model inversion             | VAE                                        | Black                  | S              |
| GMIA              | 2020 | Model inversion             | GAN                                        | White                  | S              |
| AMI               | 2019 | Model inversion             | Transposed CNN                             | Black                  | S              |

<a name="DFS2"></a>
#### 2️⃣DFS2: Adversarial Examples
<p align="center">
   <img src="./pictures/Imperceptible%20Perturbations.png" width="360"><br />
   <strong>Deep Template Inversion<br /><br />
   <img src="./pictures/Adversarial%20Landmarks.png" width="360"><br />
   <strong>Adversarial Landmarks<br /><br />
   <img src="./pictures/Adversarial%20Makeup%20Effects.png" width="360"><br />
   <strong>Adversarial Makeup Effects<br /><br />
 <p\>
    
| Method            | Year | Category                    | Backbone                                   | White/Grey/Black Box   | Static/Dynamic |
| ----------------- | ---- | --------------------------- | ------------------------------------------ | ---------------------- | -------------- |
| DFANet            | 2021 | Imperceptible perturbations | Deep Face Model+Dropout                    | Black                  | S              |
| PQP               | 2021 | Imperceptible perturbations | Deep Face Model+SSIM Gradient              | Black                  | S              |
| EDBAA             | 2019 | Imperceptible perturbations | Deep Face Model+(1+1)-CMA-ES               | Black                  | S              |
| FaceAdv           | 2021 | Adversarial landmarks       | GAN+RSO                                    | White and Black        | S              |
| AGN               | 2019 | Adversarial landmarks       | Deep Convolutional GAN                     | White                  | S              |
| PPAE              | 2022 | Adversarial landmarks       | Smoothness Loss                            | White and Black        | S              |
| AdvStickers       | 2022 | Adversarial landmarks       | Deep Face Model+RHDE                       | Black                  | S              |
| GAEMA             | 2019 | Adversarial makeup effects  | GANs                                       | White                  | S              |
| Adv-makeup        | 2021 | Adversarial makeup effects  | GANs                                       | Black                  | S              |
| RWAM              | 2022 | Adversarial makeup effects  | Cycle-GAN                                  | White                  | D              |
| DACNM             | 2021 | Adversarial makeup effects  | Facenet                                    | Black                  | D              |

<a name="DFS3"></a>
#### 3️⃣DFS3: Identity-Agnostic Faces
<p align="center">
   <img src="./pictures/Morph%20Face.png" width="360"><br />
   <strong>Deep Template Inversion<br /><br />
   <img src="./pictures/Master%20Face.png" width="360"><br />
   <strong>Adversarial Landmarks<br /><br />
 <p\>
    
| Method            | Year | Category                    | Backbone                                   | White/Grey/Black Box   | Static/Dynamic |
| ----------------- | ---- | --------------------------- | ------------------------------------------ | ---------------------- | -------------- |
| NbNet             | 2019 | Deep template inversion     | De-CNN                                     | Black                  | S              |
| GHDFI-StyleGAN2   | 2021 | Deep template inversion     | StyleGAN2                                  | Black                  | S              |
| BiohashGAN        | 2022 | Inverting binarizations     | GAN+SimHashNet                             | Black                  | S              |
| Binary Inversion  | 2021 | Inverting binarizations     | De-CNN+FCN                                 | White                  | S              |
| Deep MIA          | 2022 | Model inversion             | α\-GAN+Face Seed Initialization            | White                  | S              |
| Deep MIA-blackbox | 2021 | Model inversion             | VAE                                        | Black                  | S              |
| GMIA              | 2020 | Model inversion             | GAN                                        | White                  | S              |
| AMI               | 2019 | Model inversion             | Transposed CNN                             | Black                  | S              |
| DFANet            | 2021 | Imperceptible perturbations | Deep Face Model+Dropout                    | Black                  | S              |
| PQP               | 2021 | Imperceptible perturbations | Deep Face Model+SSIM Gradient              | Black                  | S              |
| EDBAA             | 2019 | Imperceptible perturbations | Deep Face Model+(1+1)-CMA-ES               | Black                  | S              |
| FaceAdv           | 2021 | Adversarial landmarks       | GAN+RSO                                    | White and Black        | S              |
| AGN               | 2019 | Adversarial landmarks       | Deep Convolutional GAN                     | White                  | S              |
| PPAE              | 2022 | Adversarial landmarks       | Smoothness Loss                            | White and Black        | S              |
| AdvStickers       | 2022 | Adversarial landmarks       | Deep Face Model+RHDE                       | Black                  | S              |
| GAEMA             | 2019 | Adversarial makeup          | GANs                                       | White                  | S              |
| Adv-makeup        | 2021 | Adversarial makeup          | GANs                                       | Black                  | S              |
| RWAM              | 2022 | Adversarial makeup          | Cycle-GAN                                  | White                  | D              |
| DACNM             | 2021 | Adversarial makeup          | Facenet                                    | Black                  | D              |
| Amora             | 2020 | Morphing face               | GAN                                        | Black                  | S              |
| Mipgan            | 2021 | Morphing face               | GANs                                       | Unknown                | S              |
| Regenmorph        | 2021 | Morphing face               | GAN                                        | Unknown                | S              |
| Master Face-LVE   | 2022 | Master face                 | StyleGAN+LVE                               | White, Grey, and Black | S              |
| UAXs              | 2021 | Master face                 | Deep Face Model+mini-batch L2 optimization | White and Black        | S              |
| TAA               | 2020 | Master face                 | Deep Face Model+brute force attack         | Black                  | S              |

_____________
<a name="DFAS"></a>
### Deep Face-Anti Spoofing ####
![tax_dfas](https://github.com/dhimasarief/DFS_DFAS/blob/main/taxonomy_dfas.png)

<a name="DFAS1"></a>
#### 1️⃣DFAS1: DFAS asDeep Discriminative Learning


<a name="DFAS2"></a>
#### 2️⃣DFAS2: DFAS as Deep Generative Learning


<a name="DFAS3"></a>
#### 3️⃣DFAS3: DFAS as Joint/Hybrid Learning

<a name="Joint1"></a>
##### Joint Traditional and Deep Architectures

<a name="Joint2"></a>
##### Joint Multiple Deep Architectures
