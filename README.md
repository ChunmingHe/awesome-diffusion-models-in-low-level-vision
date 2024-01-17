# Awesome Diffusion Models In Low-level Vision

A curated list of awesome **Diffusion Models(DMs)** in low-level vision. 

**<Last updated at 2024/01/18>**

---

## Contributing

Please feel free to send us pull requests or email us to add links.

## Contents

* [Papers](#Papers) 
	* [Diffusion Models For Natural Image Restoration](#1.)<details><summary>
	    [General-purpose Image Restoration (IR)](#1.1)</summary>
	     * [Zero-shot DM-based IR](#1.1.1)
	     * [Supervised DM-based IR](#1.1.2)</details>
           * [Super Resolution](#1.2)
           * [Inpainting](#1.3)
           * [Deblur](#1.4)
           * [Dehaze](#1.5)
           * [Low-light Enhancement](#1.6)
        * [Extended Diffusion Models In Low-level Vision](#2.)<details><summary>
	          [Diffusion Models In Low-level Medical Image Analysis](#2.1)</summary>
            * [MRI](#2.1.1)
            * [X-ray-based](#2.1.2)
            * [Multi-modal](#2.1.3)
            * [Other Modalities](#2.1.4)</details><details> <summary>
                   [Diffusion Models In Remote Sensing For Low-level Vision Tasks](#2.2) </summary>
               	* [Visible-light Remote Sensing Image](#2.2.1)
               	* [Hyperspectral Imaging (HSI)](#2.2.2)
               	* [Synthetic Aperture Radar (SAR)](#2.2.3)
               	* [Multi-modal](#2.2.4)</details><details><summary>
                   [Varied Low-level Vision Tasks In Video Through Diffusion Models](#2.3)</summary>
                       	* [Video Frame Prediction and Interpolation](#2.3.1)
                       	* [Super Resolution Module For Text-to-Video Generation](#2.3.2)</details>
* [Related Surveys Recommended](#Related_Surveys_Recommended)
* [Reference](#Reference)

## <a id="Papers">Papers</a>

### <a id="1.">1. Diffusion Models For Natural Image Restoration</a>

#### <a id="1.1">1.1 General-purpose Image Restoration</a>

##### <a id="1.1.1">1.1.1 Zero-shot DM-based IR</a>

|  when   |        what        | title                                                        |      pub.       |                             link                             |
| :-----: | :----------------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2021.05 |     **SNIPS**      | **SNIPS: Solving Noisy Inverse Problems Stochastically**<br /><sup><sub>*Bahjat Kawar, Gregory Vaksman, Michael Elad*</sup></sub> | NIPS<br />2021  | [Paper](https://arxiv.org/abs/2105.14951)/[Code](https://github.com/bahjat-kawar/snips_torch) |
| 2021.08 |      **ILVR**      | **ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models**<br /><sup><sub>*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon*</sup></sub> | ICCV<br />2021  | [Paper](https://arxiv.org/abs/2108.02938)/[Code](https://github.com/jychoi118/ilvr_adm) |
| 2021.12 |      **CCDF**      | **Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction**<br /><sup><sub>*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye*</sup></sub> | CVPR<br />2022  |          [Paper](https://arxiv.org/abs/2112.05146)/          |
| 2022.01 |      **DDRM**      | **Denoising Diffusion Restoration Models**<br /><sup><sub>*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song*</sup></sub> | NIPS<br />2022  | [Paper](https://arxiv.org/abs/2201.11793)/[Code](https://github.com/bahjat-kawar/ddrm) |
| 2022.01 |      **MCG**       | **Improving diffusion models for inverse problems using manifold constraints**<br /><sup><sub>*Hyungjin Chung, Byeongsu Sim, Dohoon Ryu, Jong Chul Ye*</sup></sub> | NIPS<br />2022  | [Paper](https://arxiv.org/abs/2206.00941)/[Code](https://github.com/HJ-harry/MCG_diffusion) |
| 2022.09 |      **DPS**       | **Diffusion Posterior Sampling for General Noisy Inverse Problems**<br /><sup><sub>*Hyungjin Chung, Jeongsol Kim, Michael T. Mccann, Marc L. Klasky, Jong Chul Ye*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2209.14687)/[Code](https://github.com/DPS2022/diffusion-posterior-sampling) |
| 2022.12 |      **DDNM**      | **Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model**<br /><sup><sub>*Yinhuai Wang, Jiwen Yu, Jian Zhang*</sup></sub> | ICLR<br />2023  | [Paper](https://arxiv.org/abs/2212.00490)/[Code](https://github.com/wyhuai/DDNM) |
| 2023.02 |      **πGDM**      | **Pseudoinverse-Guided Diffusion Models for Inverse Problems**<br /><sup><sub>*Jiaming Song, Arash Vahdat, Morteza Mardani, Jan Kautz*</sup></sub> | ICLR<br />2023  |    [Paper](https://openreview.net/forum?id=9_gsMA8MRKQ)/     |
| 2023.03 | **DiracDiffusion** | **DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency**<br /><sup><sub>*Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2303.14353)/          |
| 2023.04 |      **GDP**       | **Generative Diffusion Prior for Unified Image Restoration and Enhancement**<br /><sup><sub>*Ben Fei, Zhaoyang Lyu, Liang Pan, Junzhe Zhang, Weidong Yang, Tianyue Luo, Bo Zhang, Bo Dai*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2304.01247)/[Code](https://github.com/Fayeben/GenerativeDiffusionPrior) |
| 2023.04 |         -          | **Score-Based Diffusion Models as Principled Priors for Inverse Imaging**<br /><sup><sub>*Berthy T. Feng, Jamie Smith, Michael Rubinstein, Huiwen Chang, Katherine L. Bouman, William T. Freeman*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2304.11751)/          |
| 2023.05 |    **DiffPIR**     | **Denoising diffusion models for plug-and-play image restoration**<br /><sup><sub>*Yuanzhi Zhu, Kai Zhang, Jingyun Liang, Jiezhang Cao, Bihan Wen, Radu Timofte, Luc Van Gool*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2305.08995)/[Code](https://github.com/yuanzhi-zhu/DiffPIR) |
| 2023.05 |    **RED-Diff**    | **A Variational Perspective on Solving Inverse Problems with Diffusion Models**<br /><sup><sub>*Morteza Mardani, Jiaming Song, Jan Kautz, Arash Vahdat*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2305.04391)/          |
| 2022.12 |      **ADIR**      | **ADIR: Adaptive Diffusion for Image Reconstruction**<br /><sup><sub>*Shady Abu-Hussein, Tom Tirer, Raja Giryes*</sup></sub> | arXiv<br />2022 |          [Paper](https://arxiv.org/abs/2212.03221)/          |

##### <a id="1.1.2">1.1.2 Supervised DM-based IR</a>

|  when   |     what     | title                                                        |      pub.       |                             link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2021.12 |   **LDM**    | **High-resolution image synthesis with latent diffusion models**<br /><sup><sub>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer*</sup></sub> | CVPR<br />2022  | [Paper](https://arxiv.org/abs/2112.10752)/[Code](https://github.com/CompVis/latent-diffusion) |
| 2023.01 |  **IR-SDE**  | **Image Restoration with Mean-Reverting Stochastic Differential Equations**<br /><sup><sub>*Ziwei Luo, Fredrik K. Gustafsson, Zheng Zhao, Jens Sjölund, Thomas B. Schön*</sup></sub> | ICML<br />2023  | [Paper](https://arxiv.org/abs/2301.11699)/[Code](https://github.com/Algolzw/image-restoration-sde) |
| 2023.04 | **Refusion** | **Refusion: Enabling Large-Size Realistic Image Restoration with Latent-Space Diffusion Models**<br /><sup><sub>*Ziwei Luo, Fredrik K. Gustafsson, Zheng Zhao, Jens Sjölund, Thomas B. Schön*</sup></sub> | CVPRW<br />2023 | [Paper](https://arxiv.org/abs/2304.08291)/[Code](https://github.com/Algolzw/image-restoration-sde?tab=readme-ov-file) |
| 2023.05 |   **InDI**   | **Inversion by Direct Iteration: An Alternative to Denoising Diffusion for Image Restoration**<br/><sup><sub>*Mauricio Delbracio, Peyman Milanfar*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2303.11435)/[Code](https://github.com/fpramunno/InDI-implementation?tab=readme-ov-file) |

#### <a id="1.2">1.2 Super Resolution (SR)</a>

|  when   |    what     | title                                                        |           pub.           |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :----------------------: | :----------------------------------------------------------: |
| 2021/04 | **SRDiff**  | **SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models** <br/><sup><sub>*H. Li, Y. Yang, M. Chang, S. Chen, H. Feng, Z. Xu, Q. Li, and Y. Chen.*</sup></sub> | Neurocomputing<br />2022 | [Paper](https://arxiv.org/abs/2104.14951)/[Code](https://github.com/LeiaLi/SRDiff) |
| 2021/04 |   **SR3**   | **Image Super-Resolution via Iterative Refinement**<br /><sup><sub>*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi.*</sup></sub> |     TPAMI<br />2022      | [Paper](https://arxiv.org/abs/2104.07636)/[Code](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) |
| 2021/05 |   **CDM**   | **Cascaded Diffusion Models for High Fidelity Image Generation**<br /><sup><sub>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans.*</sup></sub> |      JMLR<br />2022      | [Paper](https://arxiv.org/abs/2106.15282)/[Code](https://github.com/Theodore-PKU/paper-notes/blob/master/cascaded-di%EF%AC%80usion-models-for-high-fidelity-image-generation-210803.md) |
| 2023.02 | **CDPMSR**  | **CDPMSR: Conditional Diffusion Probabilistic Models for Single Image Super-Resolution**<br /><sup><sub>*Axi Niu, Kang Zhang, Trung X. Pham, Jinqiu Sun, Yu Zhu, In So Kweon, Yanning Zhang*</sup></sub> |     arXiv<br />2023      |          [Paper](https://arxiv.org/abs/2302.12831)/          |
| 2022/09 | **SUE-SR**  | **Face Super-Resolution Using Stochastic Differential Equations**<br /><sup><sub>*Marcelo dos Santos, Rayson Laroca, Rafael O. Ribeiro, João Neves, Hugo Proença, David Menotti*</sup></sub> |    SIGGRAPH<br />2022    | [Paper](https://arxiv.org/abs/2209.12064)/[Code](https://github.com/marcelowds/sr-sde) |
| 2023/03 |   **IDM**   | **Implicit Diffusion Models for Continuous Super-Resolution**<br /><sup><sub>*Sicheng Gao, Xuhui Liu, Bohan Zeng, Sheng Xu, Yanjing Li, Xiaoyan Luo, Jianzhuang Liu, Xiantong Zhen, Baochang Zhang*</sup></sub> |      CVPR<br />2023      | [Paper](https://arxiv.org/abs/2303.16491)/[Code](https://github.com/IP-SuperResolution/IDM/blob/main/README.md) |
| 2023/03 | **ResDiff** | **ResDiff: Combining CNN and Diffusion Model for Image Super-Resolution**<br /><sup><sub>*Shuyao Shang, Zhengyang Shan, Guangxing Liu, Jinglin Zhang*</sup></sub> |     arXiv<br />2023      | [Paper](https://arxiv.org/abs/2303.08714)/[Code](https://github.com/WalkingCat/ResDiff) |

#### <a id="1.3">1.3 Inpainting</a>

|  when   |    what     | title                                                        |       pub.        |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2022/01 | **RePaint** | **Repaint: Inpainting using denoising diffusion probabilistic models**<br/><sup><sub>*A. Lugmayr, M. Danelljan, A. Romero, F. Yu, R. Timofte, and L. Van Gool.*</sup></sub> |  CVPR<br />2022   | [Paper](https://arxiv.org/abs/2201.09865)/[Code](https://github.com/Yidan-Zhang/RePaint-Inpainting-using-Denoising-Diffusion-Probabilistic-Models) |
| 2022/05 | **Palette** | **Palette: Image-to-image diffusion models**<br/><sup><sub>*C. Saharia, W. Chan, H. Chang, C. Lee, J. Ho, T. Salimans, D. Fleet, and M. Norouzi.</sup></sub> | SIGGRAPH<br/>2022 | [Paper](https://arxiv.org/abs/2111.05826)/[Code](https://github.com/Janspiry/Palette-Image-to-Image-Diffusion-Models) |

#### <a id="1.4">1.4 Deblur</a>

|  when   |    what     | title                                                        |      pub.       |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2021/12 |  **DVSR**   | **Deblurring via Stochastic Refinement**<br /><sup><sub>*Jay Whang, Mauricio Delbracio, Hossein Talebi, Chitwan Saharia, Alexandros G. Dimakis, Peyman Milanfar*</sup></sub> |  CVPR<br/>2022  | [Paper](https://arxiv.org/abs/2112.02475)/[Code](https://github.com/nothonfz/Debluring-via-Stochastic-Refinement) |
| 2022/12 |      -      | **Multiscale Structure Guided Diffusion for Image Deblurring**<br /><sup><sub>*M. Ren, M. Delbracio, H. Talebi, G. Gerig, and P. Milanfar.*</sup></sub> | ICCV<br />2023  |          [Paper](https://arxiv.org/abs/2212.01789)/          |
| 2023/05 | **HI-Diff** | **Hierarchical Integration Diffusion Model for Realistic Image Deblurring**<br /><sup><sub>*Zheng Chen, Yulun Zhang, Ding Liu, Bin Xia, Jinjin Gu, Linghe Kong, Xin Yuan*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2212.01789)/          |

#### <a id="1.5">1.5 Dehaze</a>

|  when   |      what       | title                                                        |      pub.       |                             link                             |
| :-----: | :-------------: | :----------------------------------------------------------- | :-------------: | :----------------------------------------------------------: |
| 2022/11 | **WeatherDiff** | **Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models**<br /><sup><sub>*Ozan Özdenizci, Robert Legenstein*</sup></sub> | TPAMI<br />2023 | [Paper](https://arxiv.org/abs/2207.14626)/[Code](https://github.com/IGITUGraz/WeatherDiffusion) |

#### <a id="1.6">1.6 Low-light Enhancement</a>

|  when   |     what      | title                                                        |      pub.       |                             link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/01 |   **WCDM**    | **Low-Light Image Enhancement with Wavelet-based Diffusion Models**<br /><sup><sub>*Hai Jiang, Ao Luo, Songchen Han, Haoqiang Fan, Shuaicheng Liu*</sup></sub> |  TOG<br />2023  | [Paper](https://arxiv.org/abs/2306.00306)/[Code](https://github.com/JianghaiSCU/Diffusion-Low-Light) |
| 2023/05 |  **PyDiff**   | **Pyramid Diffusion Models For Low-light Image Enhancement**<br /><sup><sub>*Dewei Zhou, Zongxin Yang, Yi Yang*</sup></sub> | IJCAI<br />2023 | [Paper](https://arxiv.org/abs/2305.10028)/[Code](https://github.com/limuloo/PyDIff) |
| 2023/11 | **Reti-Diff** | **Reti-Diff: Illumination Degradation Image Restoration with Retinex-based Latent Diffusion Model**<br /><sup><sub>*Chunming He, Chengyu Fang, Yulun Zhang, Kai Li, Longxiang Tang, Chenyu You, Fengyang Xiao, Zhenhua Guo, Xiu Li*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2311.11638)/[Code](https://github.com/ChunmingHe/Reti-Diff) |

### <a id="2.">2. Extended Diffusion Models In Low-level Vision</a>

#### <a id="2.1">2.1 Diffusion Models In Low-level Medical Image Analysis</a>

##### <a id="2.1.1">2.1.1 MRI</a>

|  when   |     what      | title                                                        |      pub.       |                             link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2021/08 |   **CSGM**    | **Robust Compressed Sensing MRI with Deep Generative Priors**<br /><sup><sub>*Alper Güngör, Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Tolga Çukur*</sup></sub> | NIPS<br />2021  | [Paper](https://arxiv.org/abs/2108.01368)/[Code](https://github.com/utcsilab/csgm-mri-langevin) |
| 2021/10 | **Score-MRI** | **Score-based diffusion models for accelerated MRI**<br /><sup><sub>*Hyungjin Chung, Jong Chul Ye*</sup></sub> | MedIA<br />2022 | [Paper](https://arxiv.org/abs/2110.05243)/[Code](https://github.com/HJ-harry/score-MRI) |
| 2022/07 |  **AdaDiff**  | **Adaptive Diffusion Priors for Accelerated MRI Reconstruction**<br /><sup><sub>*Alper Güngör, Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Tolga Çukur*</sup></sub> | MedIA<br />2023 | [Paper](https://arxiv.org/abs/2207.05876)/[Code](https://github.com/icon-lab/AdaDiff) |

##### <a id="2.1.2">2.1.2 X-ray-based</a>

|  when   |   what    | title                                                        |      pub.      |                             link                             |
| :-----: | :-------: | ------------------------------------------------------------ | :------------: | :----------------------------------------------------------: |
| 2022/11 | **DOLCE** | **DOLCE: A Model-Based Probabilistic Diffusion Framework for Limited-Angle CT Reconstruction**<br /><sup><sub>*Jiaming Liu, Rushil Anirudh, Jayaraman J. Thiagarajan, Stewart He, K. Aditya Mohan, Ulugbek S. Kamilov, Hyojin Kim*</sup></sub> | ICCV<br />2023 | [Paper](https://arxiv.org/abs/2211.12340)/[Code](https://github.com/wustl-cig/DOLCE) |

##### <a id="2.1.3">2.1.3 Multi-modal</a>

|  when   |     what     | title                                                        |      pub.       |                    link                    |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------: |
| 2022/09 |      -       | **Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models**<br /><sup><sub>*Qing Lyu, Ge Wang*</sup></sub> | arXiv<br />2022 | [Paper](https://arxiv.org/abs/2209.12104)/ |
| 2022/07 | **UMM-CSGM** | **A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion**<br /><sup><sub>*Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen*</sup></sub> | arXiv<br />2022 | [Paper](https://arxiv.org/abs/2207.03430)/ |
| 2023/04 |   **FGDM**   | **Zero-shot Medical Image Translation via Frequency-Guided Diffusion Models**<br /><sup><sub>*Yunxiang Li, Hua-Chieh Shao, Xiao Liang, Liyuan Chen, Ruiqi Li, Steve Jiang, Jing Wang, You Zhang*</sup></sub> |  TMI<br />2023  | [Paper](https://arxiv.org/abs/2304.02742)/ |

##### <a id="2.1.4">2.1.4 Other Modalities</a>

|  when   |       what       | title                                                        |                   pub.                    |                             link                             |
| :-----: | :--------------: | ------------------------------------------------------------ | :---------------------------------------: | :----------------------------------------------------------: |
| 2022/01 | **DenoOCT-DDPM** | **Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model**<br /><sup><sub>*Dewei Hu, Yuankai K. Tao, Ipek Oguz*</sup></sub> |              SPIE<br />2022               | [Paper](https://arxiv.org/abs/2201.11760)/[Code](https://github.com/deweihu/oct_ddpm) |
| 2022/09 |   **PET-DDM**    | **PET image denoising based on denoising diffusion probabilistic models**<br /><sup><sub>*Kuang Gong, Keith A. Johnson, Georges El Fakhri, Quanzheng Li, Tinsu Pan*</sup></sub> | Eur. J. Nucl. Med. Mol. Imaging<br />2023 |          [Paper](https://arxiv.org/abs/2209.06167)/          |

#### <a id="2.2">2.2 Diffusion Models In Remote Sensing For Low-level Vision Tasks</a>

##### <a id="2.2.1">2.2.1 Visible-light Remote Sensing Image</a>

|  when   |     what     | title                                                        |           pub.           |                             link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :----------------------: | :----------------------------------------------------------: |
| 2022/09 |   **PSSR**   | **Diffusion Model with Detail Complement for Super-Resolution of Remote Sensing**<br /><sup><sub>*Liu, Jinzhe and Yuan, Zhiqiang and Pan, Zhaoying and Fu, Yiqun and Liu, Li and Lu, Bin*</sup></sub> | Remote Sensing<br />2022 |     [Paper](https://www.mdpi.com/2072-4292/14/19/4834)/      |
| 2023/08 | **ARDD-Net** | **Remote Sensing Image Dehazing Using Adaptive Region-Based Diffusion Models**<br /><sup><sub>*Y Huang, S Xiong*</sup></sub> |      LGRS<br />2023      | [Paper](https://ieeexplore.ieee.org/abstract/document/10233893)/ |
| 2023/09 |  **RSDiff**  | **RSDiff: Remote Sensing Image Generation from Text Using Diffusion Model**<br /><sup><sub>*Ahmad Sebaq, Mohamed ElHelw*</sup></sub> |     arXiv<br />2023      |          [Paper](https://arxiv.org/abs/2309.02455)/          |
| 2023/10 | **EDiffSR**  | **EDiffSR: An Efficient Diffusion Probabilistic Model for Remote Sensing Image Super-Resolution**<br /><sup><sub>*Yi Xiao, Qiangqiang Yuan, Kui Jiang, Jiang He, Xianyu Jin, Liangpei Zhang*</sup></sub> |      TGRS<br />2024      | [Paper](https://arxiv.org/abs/2310.19288)/[Code](https://github.com/XY-boy/EDiffSR) |

##### <a id="2.2.2">2.2.2 HSI</a>

|  when   |     what     | title                                                        |      pub.       |                             link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/01 | **HSR-Diff** | **HSR-Diff:Hyperspectral Image Super-Resolution via Conditional Diffusion Models**<br /><sup><sub>*Chanyue Wu, Dong Wang, Hanyu Mao, Ying Li*</sup></sub> | ICCV<br />2023  |          [Paper](https://arxiv.org/abs/2306.12085)/          |
| 2023/03 |  **DDS2M**   | **DDS2M: Self-Supervised Denoising Diffusion Spatio-Spectral Model for Hyperspectral Image Restoration**<br /><sup><sub>*Yuchun Miao, Lefei Zhang, Liangpei Zhang, Dacheng Tao*</sup></sub> | ICCV<br />2023  | [Paper](https://arxiv.org/abs/2303.06682)/[Code](https://github.com/Meow-YC/DDS2M/tree/master) |
| 2023/07 | **R2H-CCD**  | **R2H-CCD: Hyperspectral Imagery Generation from RGB Images Based on Conditional Cascade Diffusion Probabilistic Models**<br /><sup><sub>*Zhang, Lei and Luo, Xiaoyan and Li, Sen and Shi, Xiaofeng*</sup></sub> | IGASS<br />2023 |   [Paper](https://ieeexplore.ieee.org/document/10281589)/    |
| 2023/07 |      -       | **A Noise-Model-Free Hyperspectral Image Denoising Method Based on Diffusion Model**<br /><sup><sub>*Deng, Keli and Jiang, Zhongshun and Qian, Qipeng and Qiu, Yi and Qian, Yuntao*</sup></sub> | IGASS<br />2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10281546)/ |
| 2023/07 | **DDPM-Fus** | **Hyperspectral and Multispectral Image Fusion Using the Conditional Denoising Diffusion Probabilistic Model**<br /><sup><sub>*Shuaikai Shi, Lijun Zhang, Jie Chen*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2307.03423)/[Code](https://github.com/shuaikaishi/DDPMFus) |

##### <a id="2.2.3">2.2.3 SAR</a>

|  when   | what | title                                                        |      pub.       |                             link                             |
| :-----: | :--: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/06 |  -   | **SAR Despeckling using a Denoising Diffusion Probabilistic Model**<br /><sup><sub>*Malsha V. Perera, Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel*</sup></sub> | LGRS<br />2023  | [Paper](https://arxiv.org/abs/2206.04514)/[Code](https://github.com/malshaV/SAR_DDPM) |
| 2023/08 |  -   | **Diffusion Models for Interferometric Satellite Aperture Radar**<br /><sup><sub>*Alexandre Tuel, Thomas Kerdreux, Claudia Hulbert, Bertrand Rouet-Leduc*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2308.16847)/[Code](https://github.com/thomaskerdreux/PDM_SAR_InSAR_generation) |
| 2023/07 |  -   | **Unsupervised SAR Despeckling Based on Diffusion Model**<br /><sup><sub>*Xiao, Siyao and Huang, Libing and Zhang, Shunsheng*</sup></sub> | IGASS<br />2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10282914)/ |

##### <a id="2.2.4">2.2.4 Multi-modal</a>

|  when   |    what     | title                                                        |           pub.           |                        link                         |
| :-----: | :---------: | ------------------------------------------------------------ | :----------------------: | :-------------------------------------------------: |
| 2023/03 | **DDPM-CR** | **Denoising Diffusion Probabilistic Feature-Based Network for Cloud Removal in Sentinel-2 Imagery**<br /><sup><sub>*Jing, Ran and Duan, Fuzhou and Lu, Fengxian and Zhang, Miao and Zhao, Wenji*</sup></sub> | Remote Sensing<br />2023 | [Paper](https://www.mdpi.com/2072-4292/15/9/2217)/  |
| 2023/04 |  **DDRF**   | **DDRF: Denoising Diffusion Model for Remote Sensing Image Fusion**<br /><sup><sub>*ZiHan Cao, ShiQi Cao, Xiao Wu, JunMing Hou, Ran Ran, Liang-Jian Deng*</sup></sub> |     arXiv<br />2023      |     [Paper](https://arxiv.org/abs/2304.04774)/      |
| 2023/04 |      -      | **Cloud Removal in Remote Sensing Using Sequential-Based Diffusion Models**<br /><sup><sub>*Zhao, Xiaohu and Jia, Kebin*</sup></sub> | Remote Sensing<br />2023 | [Paper](https://www.mdpi.com/2072-4292/15/11/2861)/ |
| 2023/07 |      -      | **Improved Flood Insights: Diffusion-Based SAR to EO Image Translation**<br /><sup><sub>*Minseok Seo, Youngtack Oh, Doyi Kim, Dongmin Kang, Yeji Choi*</sup></sub> |     arXiv<br />2023      |     [Paper](https://arxiv.org/abs/2307.07123)/      |

#### <a id="2.3">2.3 Varied Low-level Vision Tasks In Video Through Diffusion Models</a>

##### <a id="2.3.1">2.3.1 Video Frame Prediction and Interpolation</a>

|  when   |    what    | title                                                        |       pub.        |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2022/03 |  **RVD**   | **Diffusion Probabilistic Modeling for Video Generation**<br /><sup><sub>*Ruihan Yang, Prakhar Srivastava, Stephan Mandt*</sup></sub> | Entropy<br />2023 | [Paper](https://arxiv.org/abs/2203.09481)/[Code](https://github.com/buggyyang/RVD) |
| 2022/05 |  **MCVD**  | **MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation**<br /><sup><sub>*Vikram Voleti, Alexia Jolicoeur-Martineau, Christopher Pal*</sup></sub> |  NIPS<br />2022   | [Paper](https://arxiv.org/abs/2205.09853)/[Code](https://github.com/voletiv/mcvd-pytorch) |
| 2022/06 | **RaMViD** | **Diffusion Models for Video Prediction and Infilling**<br /><sup><sub>*Tobias Höppe, Arash Mehrjou, Stefan Bauer, Didrik Nielsen, Andrea Dittadi*</sup></sub> |  TMLR<br />2022   |          [Paper](https://arxiv.org/abs/2206.07696)/          |
| 2023/03 | **LDMVFI** | **LDMVFI: Video Frame Interpolation with Latent Diffusion Models**<br /><sup><sub>*Duolikun Danier, Fan Zhang, David Bull*</sup></sub> |  arXiv<br />2023  | [Paper](https://arxiv.org/abs/2303.09508)/[Code](https://github.com/danier97/LDMVFI) |

##### <a id="2.3.2">2.3.2 Super Resolution Module For Text-to-Video Generation</a>

|  when   |   what    | title                                                        |      pub.       |                             link                             |
| :-----: | :-------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/04 |     -     | **Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models**<br /><sup><sub>*Andreas Blattmann, Robin Rombach, Huan Ling, Tim Dockhorn, Seung Wook Kim, Sanja Fidler, Karsten Kreis*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2304.08818)/[Demo](https://research.nvidia.com/labs/toronto-ai/VideoLDM/) |
| 2023/05 | **PYoCo** | **Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models**<br /><sup><sub>*Songwei Ge, Seungjun Nah, Guilin Liu, Tyler Poon, Andrew Tao, Bryan Catanzaro, David Jacobs, Jia-Bin Huang, Ming-Yu Liu, Yogesh Balaji*</sup></sub> | ICCV<br />2023  | [Paper](https://arxiv.org/abs/2305.10474)/[Demo](https://research.nvidia.com/labs/dir/pyoco/) |
| 2023/09 | **LAVIE** | **LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models**<br /><sup><sub>*Yaohui Wang, Xinyuan Chen, Xin Ma, Shangchen Zhou, Ziqi Huang, Yi Wang, Ceyuan Yang, Yinan He, Jiashuo Yu, Peiqing Yang, Yuwei Guo, Tianxing Wu, Chenyang Si, Yuming Jiang, Cunjian Chen, Chen Change Loy, Bo Dai, Dahua Lin, Yu Qiao, Ziwei Liu*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2309.15103)/[Code](https://vchitect.github.io/LaVie-project/) |

## <a id="Related_Surveys_Recommended">Related Surveys Recommended</a>
**Diffusion Models for Image Restoration and Enhancement -- A Comprehensive Survey.**<br />
arXiv 2023. [[Paper](https://arxiv.org/abs/2308.09388)] <br />
Aug. 2023

## <a id="Reference">Reference</a>

[Awesome-diffusion-low-level-vision-by-yulunzhang](https://github.com/yulunzhang/awesome-diffusion-low-level-vision)

[Awesome-low-level-vision-resources](https://github.com/sunny2109/Awesome-low-level-vision-resources)

[Awesome-Diffusion-Models-in-Medical-Imaging: Diffusion Models in Medical Imaging](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging)

