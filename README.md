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
   <img src="./pictures/Deep%20Template%20Reconstruction.png" width="360"><br />
   <strong>Deep Template Inversion<br /><br />
   <img src="./pictures/Model%20Inversion.png" width="360"><br />
   <strong>Deep Model Inversion
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


<a name="DFS3"></a>
#### 3️⃣DFS3: Identity-Agnostic Faces


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
