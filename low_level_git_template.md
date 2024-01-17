# Awesome Diffusion Models In Low-level Vision

A curated list of awesome **Diffusion Models(DMs)** in low-level vision. 

**<Last updated at 2024/01/17>**

---

## Contributing

Please feel free to send us pull requests or email us to add links.

## Contents

* [Papers](##Papers)
  * [Diffusion Models For Natural Image Restoration](###1. Diffusion Models For Natural Image Restoration)
    <details>
        <summary>
    * [General-purpose Image Restoration(IR)](####1.1 General-purpose Image Restoration)
        </summary>
    	* [Zero-shot DM-based IR](#####1.1.1 Zero-shot DM-based IR)
        * [Supervised DM-based IR](#####1.1.2 Supervised DM-based IR)
    </details>
    
    * [Super Resolution](####1.2 Super Resolution (SR))
    * [Inpainting](####1.3 Inpainting)
    * [Deblur](####1.4 Deblur)
    * [Dehaze](####1.5 Dehaze)
    * [Low-light Enhancement](####1.6 Low-light Enhancement)
  * [Extended Diffusion Models In Low-level Vision](###2. Extended Diffusion Models In Low-level Vision)
    * [Diffusion Models In Low-level Medical Image Analysis](####2.1 Diffusion Models In Low-level Medical Image Analysis)
      * [MRI](#####2.1.1 MRI)
      * [X-ray-based](#####2.1.2 X-ray-based)
      * [Multi-modal](#####2.1.3 Multi-modal)
      * [Other Modalities](#####2.1.4 Other Modalities)
    * [Diffusion Models In Remote Sensing For Low-level Vision Tasks](####2.2 Diffusion Models In Remote Sensing For Low-level Vision Tasks)
      * [Visible-light Remote Sensing Image](#####2.2.1 Visible-light Remote Sensing Image)
      * [Hyperspectral Imaging (HSI)](#####2.2.2 HSI)
      * [Synthetic Aperture Radar (SAR)](#####2.2.3 SAR)
      * [Multi-modal](#####2.2.4 Multi-modal)
    * [Varied Low-level Vision Tasks In Video Through Diffusion Models](####2.3 Varied Low-level Vision Tasks In Video Through Diffusion Models)
      * [Video Frame Prediction and Interpolation](#####2.3.1 Video Frame Prediction and Interpolation)
      * [Super Resolution Module For Text-to-Video Generation](#####2.3.2 Super Resolution Module For Text-to-Video Generation)
* [Related Surveys Recommended](##Related Surveys Recommended)
* [Reference](##Reference)

## Papers

### 1. Diffusion Models For Natural Image Restoration

#### 1.1 General-purpose Image Restoration

##### 1.1.1 Zero-shot DM-based IR

|  when   |    what    | title                                                        |       pub.        |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2023/12 | **GenSAM** | Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects<br/><font size=1>*Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong*</font> |   AAAI<br/>2024   | [Paper](https://arxiv.org/abs/2311.07374)/[Code](https://github.com/jyLin8100/GenSAM)/[Demo](https://lwpyh.github.io/GenSAM/) |
| 2023/08 | **FPNet**  | Frequency Perception Network for Camouflaged Object Detection<br/><font size=1>*Runmin Cong, Mengyao Sun, Sanyi Zhang, Xiaofei Zhou, Wei Zhang, Yao Zhao*</font> | ACM MM<br />2023  | [Paper](https://arxiv.org/abs/2308.08924)/[Code](https://github.com/rmcong/FPNet_ACMMM23) |
| 2023/05 |     -      | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping<br/><font size=1>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</font> | NeurIPS<br />2023 | [Paper](https://arxiv.org/abs/2305.11003)/[Code](https://github.com/ChunmingHe/WS-SAM) |

##### 1.1.2 Supervised DM-based IR

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |



#### 1.2 Super Resolution (SR)

|  when   |    what    | title                                                        |           pub.           |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :----------------------: | :----------------------------------------------------------: |
| 2021/04 | **SRDiff** | **SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models** <br/><font size=1>*H. Li, Y. Yang, M. Chang, S. Chen, H. Feng, Z. Xu, Q. Li, and Y. Chen.*</font> | Neurocomputing<br />2022 | [Paper]([[2104.14951\] SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models (arxiv.org)](https://arxiv.org/abs/2104.14951))/[Code](https://github.com/LeiaLi/SRDiff) |
| 2021/04 |  **SR3**   | **Image Super-Resolution via Iterative Refinement**<br /><font size=1>*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi.*</font> |     TPAMI<br />2022      | [Paper](https://arxiv.org/abs/2104.07636)/[Code](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) |
| 2021/05 |  **CDM**   | **Cascaded Diffusion Models for High Fidelity Image Generation**<br /><font size=1>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans.*</font> |      JMLR<br />2022      | [Paper](https://arxiv.org/abs/2106.15282)/[Code](https://github.com/Theodore-PKU/paper-notes/blob/master/cascaded-di%EF%AC%80usion-models-for-high-fidelity-image-generation-210803.md) |
| 2023/03 |  **IDM**   | **Implicit Diffusion Models for Continuous Super-Resolution**<br /><font size=1>*Sicheng Gao, Xuhui Liu, Bohan Zeng, Sheng Xu, Yanjing Li, Xiaoyan Luo, Jianzhuang Liu, Xiantong Zhen, Baochang Zhang*</font> |      CVPR<br />2023      | [Paper](https://arxiv.org/abs/2303.16491)/[Code](https://github.com/IP-SuperResolution/IDM/blob/main/README.md) |

#### 1.3 Inpainting

|  when   |    what     | title                                                        |       pub.        |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2022/01 | **RePaint** | **Repaint: Inpainting using denoising diffusion probabilistic models**<br/><font size=1>*A. Lugmayr, M. Danelljan, A. Romero, F. Yu, R. Timofte, and L. Van Gool.*</font> |  CVPR<br />2022   | [Paper](https://arxiv.org/abs/2201.09865)/[Code](https://github.com/Yidan-Zhang/RePaint-Inpainting-using-Denoising-Diffusion-Probabilistic-Models) |
| 2022/05 | **Palette** | **Palette: Image-to-image diffusion models**<br/><font size=1>C. Saharia, W. Chan, H. Chang, C. Lee, J. Ho, T. Salimans, D. Fleet, and M. Norouzi.</font> | SIGGRAPH<br/>2022 | [Paper](https://arxiv.org/abs/2111.05826)/[Code](https://github.com/Janspiry/Palette-Image-to-Image-Diffusion-Models) |

#### 1.4 Deblur

|  when   |    what     | title                                                        |      pub.       |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2021/12 |  **DVSR**   | **Deblurring via Stochastic Refinement**<br /><font size=1>Jay Whang, Mauricio Delbracio, Hossein Talebi, Chitwan Saharia, Alexandros G. Dimakis, Peyman Milanfar</font> |  CVPR<br/>2022  | [Paper](https://arxiv.org/abs/2112.02475)/[Code](https://github.com/nothonfz/Debluring-via-Stochastic-Refinement) |
| 2022/12 |      -      | **Multiscale Structure Guided Diffusion for Image Deblurring**<br /><font size=1>*M. Ren, M. Delbracio, H. Talebi, G. Gerig, and P. Milanfar.*</font> | ICCV<br />2023  |          [Paper](https://arxiv.org/abs/2212.01789)/          |
| 2023/05 | **HI-Diff** | **Hierarchical Integration Diffusion Model for Realistic Image Deblurring**<br /><font size=1>Zheng Chen, Yulun Zhang, Ding Liu, Bin Xia, Jinjin Gu, Linghe Kong, Xin Yuan</font> | arXiv<br />2023 | [Paper]([[2212.01789\] Multiscale Structure Guided Diffusion for Image Deblurring (arxiv.org)](https://arxiv.org/abs/2212.01789))/ |

#### 1.5 Dehaze

|  when   |      what       | title                                                        |      pub.       |                             link                             |
| :-----: | :-------------: | :----------------------------------------------------------- | :-------------: | :----------------------------------------------------------: |
| 2022/11 | **WeatherDiff** | **Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models**<br /><font size=1>Ozan Özdenizci, Robert Legenstein</font> | TPAMI<br />2023 | [Paper](https://arxiv.org/abs/2207.14626)/[Code](https://github.com/IGITUGraz/WeatherDiffusion) |

#### 1.6 Low-light Enhancement

|  when   |   what   | title                                                        |     pub.      |                             link                             |
| :-----: | :------: | ------------------------------------------------------------ | :-----------: | :----------------------------------------------------------: |
| 2023/01 | **WCDM** | **Low-Light Image Enhancement with Wavelet-based Diffusion Models**<br /><font size=1>*Hai Jiang, Ao Luo, Songchen Han, Haoqiang Fan, Shuaicheng Liu*</font> | TOG<br />2023 | [Paper](https://arxiv.org/abs/2306.00306)/[Code](https://github.com/JianghaiSCU/Diffusion-Low-Light) |

### 2. Extended Diffusion Models In Low-level Vision

#### 2.1 Diffusion Models In Low-level Medical Image Analysis

##### 2.1.1 MRI

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.1.2 X-ray-based

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.1.3 Multi-modal

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.1.4 Other Modalities

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

#### 2.2 Diffusion Models In Remote Sensing For Low-level Vision Tasks

##### 2.2.1 Visible-light Remote Sensing Image

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.2.2 HSI

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.2.3 SAR

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.2.4 Multi-modal

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

#### 2.3 Varied Low-level Vision Tasks In Video Through Diffusion Models

##### 2.3.1 Video Frame Prediction and Interpolation

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

##### 2.3.2 Super Resolution Module For Text-to-Video Generation

| when | what | title | pub. | link |
| :--: | :--: | ----- | :--: | :--: |
|      |      |       |      |      |
|      |      |       |      |      |
|      |      |       |      |      |

## Related Surveys Recommended

**Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping**. 
*Chunming He†, Kai Li†, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*
NeurIPS 2023. [[Paper](https://arxiv.org/abs/2305.11003)] [[Code](https://github.com/ChunmingHe/WS-SAM)]
May 2023



**Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction**
*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*
CVPR 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/Papers/He_Camouflaged_Object_Detection_With_Feature_Decomposition_and_Edge_Reconstruction_CVPR_2023_Paper.pdf)] [[Code](https://github.com/ChunmingHe/FEDER)]
Feb 2023

## Reference

[Awesome-diffusion-low-level-vision-by-yulunzhang](https://github.com/yulunzhang/awesome-diffusion-low-level-vision)

[Awesome-low-level-vision-resources](https://github.com/sunny2109/Awesome-low-level-vision-resources)

