
# <p align=center>Awesome Diffusion Models In Low-level Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ChunmingHe/awesome-diffusion-models-in-low-level-vision) </p>




<p align=center>🔥A curated list of awesome <b>Diffusion Models(DMs)</b> in low-level vision.🔥</p>

<p align=center>Please feel free to offer your suggestions in the Issues and pull requests to add links.</p>

<p align=center><b>[ Last updated at 2024/07/18 ]</b></p>



## Contents
* [Latest Works Recommended](#3.)
* [Papers](#Papers) 
	* [Diffusion Models For Natural Image Restoration](#1.)<details><summary>
	    [General-purpose Image Restoration (IR)](#1.1)</summary>
	     * [Zero-shot DM-based IR](#1.1.1)
	     * [Supervised DM-based IR](#1.1.2)</details><details><summary>
            [Task-specific Image Restoration (IR)](#1.2)</summary>
           * [Super Resolution](#1.2.1)
           * [Inpainting](#1.2.2)
           * [Deblur](#1.2.3)
           * [Dehaze](#1.2.4)
           * [Low-light Enhancement](#1.2.5)
           * [Image Fusion](#1.2.6)</details>
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
                     * [Super Resolution For Video Generation](#2.3.2)
                     * [Video Restoration](#2.3.3)</details>
* [Related Surveys Recommended](#4.)
* [Datasets for low-level vision tasks](#5.)
* [Reference](#Reference)

## <a id="3.">Latest Works Recommended</a>

**Reti-Diff: Illumination Degradation Image Restoration with Retinex-based Latent Diffusion Model**<br />*Chunming He, Chengyu Fang, Yulun Zhang, Kai Li, Longxiang Tang, Chenyu You, Fengyang Xiao, Zhenhua Guo, Xiu Li*<br />
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.11638)] [[Code](https://github.com/ChunmingHe/Reti-Diff)]<br />
Nov. 2023<br />

## <a id="Papers">Papers</a>

### <a id="1.">1. Diffusion Models For Natural Image Restoration</a>

#### <a id="1.1">1.1 General-purpose Image Restoration</a>

##### <a id="1.1.1">1.1.1 Zero-shot DM-based IR</a>

|  Release   |        Method        | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :----------------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/05 |    **DiffPIR**     | **Denoising diffusion models for plug-and-play image restoration**<br /><sup><sub>*Yuanzhi Zhu, Kai Zhang, Jingyun Liang, Jiezhang Cao, Bihan Wen, Radu Timofte, Luc Van Gool*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2305.08995)/[Code](https://github.com/yuanzhi-zhu/DiffPIR) |
| 2023/05 |    **RED-Diff**    | **A Variational Perspective on Solving Inverse Problems with Diffusion Models**<br /><sup><sub>*Morteza Mardani, Jiaming Song, Jan Kautz, Arash Vahdat*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2305.04391)/          |
| 2023/04 |      **GDP**       | **Generative Diffusion Prior for Unified Image Restoration and Enhancement**<br /><sup><sub>*Ben Fei, Zhaoyang Lyu, Liang Pan, Junzhe Zhang, Weidong Yang, Tianyue Luo, Bo Zhang, Bo Dai*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2304.01247)/[Code](https://github.com/Fayeben/GenerativeDiffusionPrior) |
| 2023/04 |         -          | **Score-Based Diffusion Models as Principled Priors for Inverse Imaging**<br /><sup><sub>*Berthy T. Feng, Jamie Smith, Michael Rubinstein, Huiwen Chang, Katherine L. Bouman, William T. Freeman*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2304.11751)/          |
| 2023/02 |      **πGDM**      | **Pseudoinverse-Guided Diffusion Models for Inverse Problems**<br /><sup><sub>*Jiaming Song, Arash Vahdat, Morteza Mardani, Jan Kautz*</sup></sub> | ICLR<br />2023  |    [Paper](https://openreview.net/forum?id=9_gsMA8MRKQ)/     |
| 2022/12 |      **ADIR**      | **ADIR: Adaptive Diffusion for Image Reconstruction**<br /><sup><sub>*Shady Abu-Hussein, Tom Tirer, Raja Giryes*</sup></sub> | arXiv<br />2022 |          [Paper](https://arxiv.org/abs/2212.03221)/          |
| 2022/12 |      **DDNM**      | **Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model**<br /><sup><sub>*Yinhuai Wang, Jiwen Yu, Jian Zhang*</sup></sub> | ICLR<br />2023  | [Paper](https://arxiv.org/abs/2212.00490)/[Code](https://github.com/wyhuai/DDNM) |
| 2022/09 |      **DPS**       | **Diffusion Posterior Sampling for General Noisy Inverse Problems**<br /><sup><sub>*Hyungjin Chung, Jeongsol Kim, Michael T. Mccann, Marc L. Klasky, Jong Chul Ye*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2209.14687)/[Code](https://github.com/DPS2022/diffusion-posterior-sampling) |
| 2022/01 |      **MCG**       | **Improving diffusion models for inverse problems using manifold constraints**<br /><sup><sub>*Hyungjin Chung, Byeongsu Sim, Dohoon Ryu, Jong Chul Ye*</sup></sub> | NIPS<br />2022  | [Paper](https://arxiv.org/abs/2206.00941)/[Code](https://github.com/HJ-harry/MCG_diffusion) |
| 2022/01 |      **DDRM**      | **Denoising Diffusion Restoration Models**<br /><sup><sub>*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song*</sup></sub> | NIPS<br />2022  | [Paper](https://arxiv.org/abs/2201.11793)/[Code](https://github.com/bahjat-kawar/ddrm) |
| 2021/12 |      **CCDF**      | **Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction**<br /><sup><sub>*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye*</sup></sub> | CVPR<br />2022  |          [Paper](https://arxiv.org/abs/2112.05146)/          |
| 2021/08 |      **ILVR**      | **ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models**<br /><sup><sub>*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon*</sup></sub> | ICCV<br />2021  | [Paper](https://arxiv.org/abs/2108.02938)/[Code](https://github.com/jychoi118/ilvr_adm) |
| 2021/05 |     **SNIPS**      | **SNIPS: Solving Noisy Inverse Problems Stochastically**<br /><sup><sub>*Bahjat Kawar, Gregory Vaksman, Michael Elad*</sup></sub> | NIPS<br />2021  | [Paper](https://arxiv.org/abs/2105.14951)/[Code](https://github.com/bahjat-kawar/snips_torch) |

##### <a id="1.1.2">1.1.2 Supervised DM-based IR</a>

|  Release   |     Method     | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2024/03 | **DiffUIR** | **Selective Hourglass Mapping for Universal Image Restoration Based on Diffusion Model**<br /><sup><sub>*Dian Zheng, Xiao-Ming Wu, Shuzhou Yang, Jian Zhang, Jian-Fang Hu, Wei-Shi Zheng*</sup></sub> | CVPR<br />2024 | [Paper](https://arxiv.org/abs/2403.11157)/[Code](https://github.com/iSEE-Laboratory/DiffUIR) |
| 2024/03 | - | **Efficient Diffusion Model for Image Restoration by Residual Shifting**<br /><sup><sub>*Yuanzhi Zhu, Kai Zhang, Jingyun Liang, Jiezhang Cao, Bihan Wen, Radu Timofte, Luc Van Gool*</sup></sub> | arXiv<br />2024 | [Paper](https://arxiv.org/abs/2403.07319)/[Code](https://github.com/zsyOAOA/ResShift) |
| 2023/08 | **RDDM** | **Residual Denoising Diffusion Models**<br /><sup><sub>*Jiawei Liu, Qiang Wang, Huijie Fan, Yinong Wang, Yandong Tang, Liangqiong Qu*</sup></sub> | CVPR<br />2024 | [Paper](https://arxiv.org/abs/2308.13712)/[Code](https://github.com/nachifur/RDDM) |
| 2023/08 | **DiffBIR** | **DiffBIR: Towards Blind Image Restoration with Generative Diffusion Prior**<br /><sup><sub>*Xinqi Lin, Jingwen He, Ziyan Chen, Zhaoyang Lyu, Bo Dai, Fanghua Yu, Wanli Ouyang, Yu Qiao, Chao Dong*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2308.15070)/[Code](https://github.com/XPixelGroup/DiffBIR) |
| 2023/05 |   **InDI**   | **Inversion by Direct Iteration: An Alternative to Denoising Diffusion for Image Restoration**<br/><sup><sub>*Mauricio Delbracio, Peyman Milanfar*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2303.11435)/[Code](https://github.com/fpramunno/InDI-implementation?tab=readme-ov-file) |
| 2023/03 | **DiracDiffusion** | **DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency**<br /><sup><sub>*Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2303.14353)/          |
| 2023/04 | **Refusion** | **Refusion: Enabling Large-Size Realistic Image Restoration with Latent-Space Diffusion Models**<br /><sup><sub>*Ziwei Luo, Fredrik K. Gustafsson, Zheng Zhao, Jens Sjölund, Thomas B. Schön*</sup></sub> | CVPRW<br />2023 | [Paper](https://arxiv.org/abs/2304.08291)/[Code](https://github.com/Algolzw/image-restoration-sde?tab=readme-ov-file) |
| 2023/01 |  **IR-SDE**  | **Image Restoration with Mean-Reverting Stochastic Differential Equations**<br /><sup><sub>*Ziwei Luo, Fredrik K. Gustafsson, Zheng Zhao, Jens Sjölund, Thomas B. Schön*</sup></sub> | ICML<br />2023  | [Paper](https://arxiv.org/abs/2301.11699)/[Code](https://github.com/Algolzw/image-restoration-sde) |
| 2021/12 |   **LDM**    | **High-resolution image synthesis with latent diffusion models**<br /><sup><sub>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer*</sup></sub> | CVPR<br />2022  | [Paper](https://arxiv.org/abs/2112.10752)/[Code](https://github.com/CompVis/latent-diffusion) |

#### <a id="1.2">1.2 Task-specific Image Restoration</a>
##### <a id="1.2.1">1.2.1 Super Resolution (SR)</a>

|  Release   |    Method     | Title                                                        |           Pub.           |                             Link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :----------------------: | :----------------------------------------------------------: |
| 2023/11 | **CoSeR** | **CoSeR: Bridging Image and Language for Cognitive Super-Resolution**<br /><sup><sub>*Haoze Sun, Wenbo Li, Jianzhuang Liu, Haoyu Chen, Renjing Pei, Xueyi Zou, Youliang Yan, Yujiu Yang*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2311.16512)/[Code](https://github.com/VINHYU/CoSeR) |
| 2023/09 | - | **License Plate Super-Resolution Using Diffusion Models**<br /><sup><sub>*Sawsan AlHalawani, Bilel Benjdira, Adel Ammar, Anis Koubaa, Anas M. Ali*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2309.12506)/ |
| 2023/08 | **PASD** | **Pixel-Aware Stable Diffusion for Realistic Image Super-resolution and Personalized Stylization**<br /><sup><sub>*Tao Yang, Rongyuan Wu, Peiran Ren, Xuansong Xie, Lei Zhang*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2308.14469)/[Code](https://github.com/yangxy/PASD/) |
| 2023/07 | **ResShift** | **ResShift: Efficient Diffusion Model for Image Super-resolution by Residual Shifting**<br /><sup><sub>*Zongsheng Yue, Jianyi Wang, Chen Change Loy*</sup></sub> | NIPS<br />2023 | [Paper](https://arxiv.org/abs/2307.12348)/[Code](https://github.com/zsyOAOA/ResShift) |
| 2023/07 | **PartDiff** | **PartDiff: Image Super-resolution with Partial Diffusion Models**<br /><sup><sub>*Axi Niu, Pham Xuan Trung, Kang Zhang, Jinqiu Sun, Yu Zhu, In So Kweon, Yanning Zhang*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2307.11926)/ |
| 2023/07 | **ACDMSR** | **ACDMSR: Accelerated Conditional Diffusion Models for Single Image Super-Resolution**<br /><sup><sub>*Axi Niu, Pham Xuan Trung, Kang Zhang, Jinqiu Sun, Yu Zhu, In So Kweon, Yanning Zhang*</sup></sub> | IEEE Trans. Broadcast.<br />2024 | [Paper](https://arxiv.org/abs/2307.00781)/ |
| 2023/05 | **StableSR** | **Exploiting Diffusion Prior for Real-World Image Super-Resolution**<br /><sup><sub>*Jianyi Wang, Zongsheng Yue, Shangchen Zhou, Kelvin C.K. Chan, Chen Change Loy*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2305.07015)/[Code](https://github.com/IceClear/StableSR) |
| 2023/03 | **DR2** | **DR2: Diffusion-Based Robust Degradation Remover for Blind Face Restoration**<br /><sup><sub>*Zhixin Wang, Xiaoyun Zhang, Ziying Zhang, Huangjie Zheng, Mingyuan Zhou, Ya Zhang, Yanfeng Wang*</sup></sub> | CVPR<br />2023 | [Paper](https://arxiv.org/abs/2303.06885)/[Code](https://github.com/Kaldwin0106/DR2_Drgradation_Remover) |
| 2023/03 | **ResDiff** | **ResDiff: Combining CNN and Diffusion Model for Image Super-Resolution**<br /><sup><sub>*Shuyao Shang, Zhengyang Shan, Guangxing Liu, Jinglin Zhang*</sup></sub> |   AAAI<br />2024  | [Paper](https://arxiv.org/abs/2303.08714)/[Code](https://github.com/WalkingCat/ResDiff) |
| 2023/03 |   **IDM**   | **Implicit Diffusion Models for Continuous Super-Resolution**<br /><sup><sub>*Sicheng Gao, Xuhui Liu, Bohan Zeng, Sheng Xu, Yanjing Li, Xiaoyan Luo, Jianzhuang Liu, Xiantong Zhen, Baochang Zhang*</sup></sub> |      CVPR<br />2023      | [Paper](https://arxiv.org/abs/2303.16491)/[Code](https://github.com/IP-SuperResolution/IDM/blob/main/README.md) |
| 2023/02 | - | **Denoising Diffusion Probabilistic Models for Robust Image Super-Resolution in the Wild**<br /><sup><sub>*Hshmat Sahak, Daniel Watson, Chitwan Saharia, David Fleet*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2302.07864)/ |
| 2023/02 | **CDPMSR**  | **CDPMSR: Conditional Diffusion Probabilistic Models for Single Image Super-Resolution**<br /><sup><sub>*Axi Niu, Kang Zhang, Trung X. Pham, Jinqiu Sun, Yu Zhu, In So Kweon, Yanning Zhang*</sup></sub> |     arXiv<br />2023      |          [Paper](https://arxiv.org/abs/2302.12831)/          |
| 2022/09 | **SUE-SR**  | **Face Super-Resolution Using Stochastic Differential Equations**<br /><sup><sub>*Marcelo dos Santos, Rayson Laroca, Rafael O. Ribeiro, João Neves, Hugo Proença, David Menotti*</sup></sub> |    SIGGRAPH<br />2022    | [Paper](https://arxiv.org/abs/2209.12064)/[Code](https://github.com/marcelowds/sr-sde) |
| 2021/05 |   **CDM**   | **Cascaded Diffusion Models for High Fidelity Image Generation**<br /><sup><sub>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans.*</sup></sub> |      JMLR<br />2022      | [Paper](https://arxiv.org/abs/2106.15282)/[Code](https://github.com/Theodore-PKU/paper-notes/blob/master/cascaded-di%EF%AC%80usion-models-for-high-fidelity-image-generation-210803.md) |
| 2021/04 |   **SR3**   | **Image Super-Resolution via Iterative Refinement**<br /><sup><sub>*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi.*</sup></sub> |     TPAMI<br />2022      | [Paper](https://arxiv.org/abs/2104.07636)/[Code](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) |
| 2021/04 | **SRDiff**  | **SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models** <br/><sup><sub>*H. Li, Y. Yang, M. Chang, S. Chen, H. Feng, Z. Xu, Q. Li, and Y. Chen.*</sup></sub> | Neurocomputing<br />2022 | [Paper](https://arxiv.org/abs/2104.14951)/[Code](https://github.com/LeiaLi/SRDiff) |

##### <a id="1.2.2">1.2.2 Inpainting</a>

|  Release   |    Method     | Title                                                        |       Pub.        |                             Link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2024/03 | **MMGInpainting** | **MMGInpainting: Multi-Modality Guided Image Inpainting Based On Diffusion Models**<br/><sup><sub>*Cong Zhang, Wenxia Yang, Xin Li, Huan Han*</sup></sub> | IEEE Trans Multimedia<br />2024 | [Paper](https://ieeexplore.ieee.org/document/10480591)/[Code](https://github.com/skipper-zc/MMGInpainting/) |
| 2024/03 | **BrushNet** | **BrushNet: A Plug-and-Play Image Inpainting Model with Decomposed Dual-Branch Diffusion**<br/><sup><sub>*Xuan Ju, Xian Liu, Xintao Wang, Yuxuan Bian, Ying Shan, Qiang Xu*</sup></sub> | arXiv<br />2024 | [Paper](https://arxiv.org/abs/2403.06976)/[Code](https://github.com/TencentARC/BrushNet) |
| 2024/03 | - | **Fill in the ____ (a Diffusion-based Image Inpainting Pipeline)**<br/><sup><sub>*Eyoel Gebre, Krishna Saxena, Timothy Tran*</sup></sub> | arXiv<br />2024 | [Paper](https://arxiv.org/abs/2403.16016)/ |
| 2023/09 | **Gradpaint** | **Gradpaint: Gradient-Guided Inpainting with Diffusion Models**<br/><sup><sub>*Asya Grechka, Guillaume Couairon, Matthieu Cord*</sup></sub> | CVIU<br />2024 | [Paper](https://arxiv.org/abs/2309.09614)/ |
| 2022/05 | **Palette** | **Palette: Image-to-image diffusion models**<br/><sup><sub>*C. Saharia, W. Chan, H. Chang, C. Lee, J. Ho, T. Salimans, D. Fleet, and M. Norouzi.*</sup></sub> | SIGGRAPH<br/>2022 | [Paper](https://arxiv.org/abs/2111.05826)/[Code](https://github.com/Janspiry/Palette-Image-to-Image-Diffusion-Models) |
| 2022/01 | **RePaint** | **Repaint: Inpainting using denoising diffusion probabilistic models**<br/><sup><sub>*A. Lugmayr, M. Danelljan, A. Romero, F. Yu, R. Timofte, and L. Van Gool.*</sup></sub> |  CVPR<br />2022   | [Paper](https://arxiv.org/abs/2201.09865)/[Code](https://github.com/Yidan-Zhang/RePaint-Inpainting-using-Denoising-Diffusion-Probabilistic-Models) |

##### <a id="1.2.3">1.2.3 Deblur</a>

|  Release   |    Method     | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2024/04 | **Diffevent** | **Diffevent: Event Residual Diffusion for Image Deblurring**<br /><sup><sub>*Pei Wang, Jiumei He, Qingsen Yan, Yu Zhu, Jinqiu Sun, Yanning Zhang*</sup></sub> | ICASSP<br />2024 | [Paper](https://ieeexplore.ieee.org/abstract/document/10446822)/[Code](https://github.com/Pei233/DIFFEVENT) |
| 2024/01 | **FastDiffusionEM** | **Fast Diffusion EM: a diffusion model for blind inverse problems with application to deconvolution**<br /><sup><sub>*Charles Laroche, Andrés Almansa, Eva Coupete*</sup></sub> | WACV<br />2024 | [Paper](https://ieeexplore.ieee.org/document/10483663)/[Code](https://github.com/claroche-r/fastdiffusionem) |
| 2024/01 | **SI-DDPM-FMO** | **Single-Image Deblurring, Trajectory and Shape Recovery of Fast Moving Objects With Denoising Diffusion Probabilistic Models**<br /><sup><sub>*Radim Spetlik, Denys Rozumnyi, Jiří Matas*</sup></sub> | WACV<br />2024 | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Spetlik_Single-Image_Deblurring_Trajectory_and_Shape_Recovery_of_Fast_Moving_Objects_WACV_2024_paper.html)/[Code](https://github.com/radimspetlik/SI-DDPM-FMO) |
| 2023/05 | **HI-Diff** | **Hierarchical Integration Diffusion Model for Realistic Image Deblurring**<br /><sup><sub>*Zheng Chen, Yulun Zhang, Ding Liu, Bin Xia, Jinjin Gu, Linghe Kong, Xin Yuan*</sup></sub> | arXiv<br />2023 |          [Paper](https://arxiv.org/abs/2212.01789)/          |
| 2022/12 |      -      | **Multiscale Structure Guided Diffusion for Image Deblurring**<br /><sup><sub>*M. Ren, M. Delbracio, H. Talebi, G. Gerig, and P. Milanfar.*</sup></sub> | ICCV<br />2023  |          [Paper](https://arxiv.org/abs/2212.01789)/          |
| 2021/12 |  **DVSR**   | **Deblurring via Stochastic Refinement**<br /><sup><sub>*Jay Whang, Mauricio Delbracio, Hossein Talebi, Chitwan Saharia, Alexandros G. Dimakis, Peyman Milanfar*</sup></sub> |  CVPR<br/>2022  | [Paper](https://arxiv.org/abs/2112.02475)/[Code](https://github.com/nothonfz/Debluring-via-Stochastic-Refinement) |

##### <a id="1.2.4">1.2.4 Dehaze</a>

|  Release   |      Method       | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :-------------: | :----------------------------------------------------------- | :-------------: | :----------------------------------------------------------: |
| 2023/08 | **HazeAug** | **Frequency Compensated Diffusion Model for Real-scene Dehazing**<br /><sup><sub>*Jing Wang, Songtao Wu, Kuanhong Xu, Zhiqiang Yuan*</sup></sub> | Neural Networks<br />2024 | [Paper](https://arxiv.org/abs/2308.10510)/[Code](https://github.com/W-Jilly/frequency-compensated-diffusion-model-pytorch) |
| 2022/11 | **WeatherDiff** | **Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models**<br /><sup><sub>*Ozan Özdenizci, Robert Legenstein*</sup></sub> | TPAMI<br />2023 | [Paper](https://arxiv.org/abs/2207.14626)/[Code](https://github.com/IGITUGraz/WeatherDiffusion) |

##### <a id="1.2.5">1.2.5 Low-light Enhancement</a>

|  Release   |     Method      | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2024/01 | **CFWD** | **Low-light Image Enhancement via CLIP-Fourier Guided Wavelet Diffusion**<br /><sup><sub>*Minglong Xue, Jinhong He, Yanyi He, Zhipu Liu, Wenhai Wang, Mingliang Zhou*</sup></sub> | arXiv<br />2024 | [Paper](https://arxiv.org/abs/2401.03788)/[Code](https://github.com/He-Jinhong/CFWD) |
| 2023/12 | **L<sup>2</sup>DM** | **L<sup>2</sup>DM: A Diffusion Model for Low-Light Image Enhancement**<br /><sup><sub>*Lv, Xingguo and Dong, Xingbo and Jin, Zhe and Zhang, Hui and Song, Siyi and Li, Xuejun*</sup></sub> | PRCV<br />2023 | [Paper](https://link.springer.com/chapter/10.1007/978-981-99-8552-4_11)/[Code](https://github.com/01cv/L2DM) |
| 2023/11 | **Reti-Diff** | **Reti-Diff: Illumination Degradation Image Restoration with Retinex-based Latent Diffusion Model**<br /><sup><sub>*Chunming He, Chengyu Fang, Yulun Zhang, Kai Li, Longxiang Tang, Chenyu You, Fengyang Xiao, Zhenhua Guo, Xiu Li*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2311.11638)/[Code](https://github.com/ChunmingHe/Reti-Diff) |
| 2023/10 | **GASD** | **Global Structure-Aware Diffusion Process for Low-Light Image Enhancement**<br /><sup><sub>*Jinhui Hou, Zhiyu Zhu, Junhui Hou, Hui Liu, Huanqiang Zeng, Hui Yuan*</sup></sub> | NIPS<br />2023 | [Paper](https://arxiv.org/abs/2310.17577)/[Code](https://github.com/jinnh/GSAD) |
| 2023/10 | **LLDE** | **LLDE: Enhancing Low-Light Images with Diffusion Model**<br /><sup><sub>*Xin Peng Oo, Chee Seng Chan*</sup></sub> | ICIP<br />2023 | [Paper](https://ieeexplore.ieee.org/document/10222446)/[Code](https://github.com/OoiXinPeng/LLDE) |
| 2023/09 | - | **Bootstrap Diffusion Model Curve Estimation for High Resolution Low-Light Image Enhancement**<br /><sup><sub>*Jiancheng Huang, Yifan Liu, Shifeng Chen*</sup></sub> | PRICAI<br /> 2023 | [Paper](https://arxiv.org/abs/2309.14709)/ |
| 2023/08 | **ExposureDiffusion** | **ExposureDiffusion: Learning to Expose for Low-light Image Enhancement**<br /><sup><sub>*Yufei Wang, Yi Yu, Wenhan Yang, Lanqing Guo, Lap-Pui Chau, Alex C. Kot, Bihan Wen*</sup></sub> | ICCV<br />2023 | [Paper](https://arxiv.org/pdf/2307.07710.pdf)/[Code](https://github.com/IP-Enhancement/ExposureDiffusion/tree/main) |
| 2023/08 | **Diff-Retinex** | **Diff-Retinex: Rethinking Low-light Image Enhancement with A Generative Diffusion Model**<br /><sup><sub>*Xunpeng Yi, Han Xu, Hao Zhang, Linfeng Tang, Jiayi Ma*</sup></sub> | ICCV<br />2023 | [Paper](https://ieeexplore.ieee.org/document/10377645)/ |
| 2023/08 | **CLE Diffusion** | **CLE Diffusion: Controllable Light Enhancement Diffusion Model**<br /><sup><sub>*Yuyang Yin, Dejia Xu, Chuangchuang Tan, Ping Liu, Yao Zhao, Yunchao Wei*</sup></sub> | MM<br />23 | [Paper](https://arxiv.org/abs/2308.06725)/[Code](https://github.com/YuyangYin/CLEDiffusion) |
| 2023/07 | **LLDiffusion** | **LLDiffusion: Learning Degradation Representations in Diffusion Models for Low-Light Image Enhancement**<br /><sup><sub>*Tao Wang, Kaihao Zhang, Ziqian Shao, Wenhan Luo, Bjorn Stenger, Tae-Kyun Kim, Wei Liu, Hongdong Li*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2307.14659)/[Code](https://github.com/TaoWangzj/LLDiffusion) |
| 2023/07 | **DiffLIE** | **DiffLIE: Low-Light Image Enhancment based on Deep Diffusion Model**<br /><sup><sub>*Guanyu Wu; Cheng. Jin*</sup></sub> | ISCTIS<br />2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10213153)/ |
| 2023/06 | - | **Diffusion Model Based Low-Light Image Enhancement for Space Satellite**<br /><sup><sub>*Yiman Zhu, Lu Wang, Jingyi Yuan, Yu Guo*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2306.14227)/ |
| 2023/05 |  **PyDiff**   | **Pyramid Diffusion Models For Low-light Image Enhancement**<br /><sup><sub>*Dewei Zhou, Zongxin Yang, Yi Yang*</sup></sub> | IJCAI<br />2023 | [Paper](https://arxiv.org/abs/2305.10028)/[Code](https://github.com/limuloo/PyDIff) |
| 2023/03 | **LPDM** | **Denoising Diffusion Post-Processing for Low-Light Image Enhancement**<br /><sup><sub>*Savvas Panagiotou, Anna S. Bosman*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2303.09627)/[Code](https://github.com/savvaki/LPDM) |
| 2023/03 | **DiD** | **Diffusion in the Dark: A Diffusion Model for Low-Light Text Recognition**<br /><sup><sub>*Cindy M. Nguyen, Eric R. Chan, Alexander W. Bergman, Gordon Wetzstein*</sup></sub> | WACV<br />2024 | [Paper](https://arxiv.org/abs/2303.04291)/[Code](https://github.com/ccnguyen/diffusion-in-the-dark/tree/master) |
| 2023/01 |   **DiffLL**    | **Low-Light Image Enhancement with Wavelet-based Diffusion Models**<br /><sup><sub>*Hai Jiang, Ao Luo, Songchen Han, Haoqiang Fan, Shuaicheng Liu*</sup></sub> |  TOG<br />2023  | [Paper](https://arxiv.org/abs/2306.00306)/[Code](https://github.com/JianghaiSCU/Diffusion-Low-Light) |
##### <a id="1.2.6">1.2.6 Image Fusion</a>

| Release |     Method     | Title                                                        |      Pub.      |                             Link                             |
| :-----: | :------------: | :----------------------------------------------------------- | :------------: | :----------------------------------------------------------: |
| 2023/06 | **FusionDiff** | **FusionDiff: Multi-focus image fusion using denoising diffusion probabilistic models**<br /><sup><sub>*Mining Li, Ronghao Pei, Tianyou Zheng, Yang Zhang, Weiwei Fu*</sup></sub> | ESWA<br />2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417423021668)/[Code](https://github.com/lmn-ning/ImageFusion) |
| 2023/03 |    **DDFM**    | **DDFM: Denoising Diffusion Model for Multi-Modality Image Fusion**<br /><sup><sub>*Zixiang Zhao, Haowen Bai, Yuanzhi Zhu, Jiangshe Zhang, Shuang Xu, Yulun Zhang, Kai Zhang, Deyu Meng, Radu Timofte, Luc Van Gool*</sup></sub> | ICCV<br />2023 | [Paper](https://arxiv.org/abs/2303.06840)/[Code](https://github.com/Zhaozixiang1228/MMIF-DDFM) |
| 2023/01 | **Dif-Fusion** | **Dif-Fusion: Towards High Color Fidelity in Infrared and Visible Image Fusion with Diffusion Models**<br /><sup><sub>*Jun Yue, Leyuan Fang, Shaobo Xia, Yue Deng, Jiayi Ma*</sup></sub> | TIP<br />2023  | [Paper](https://arxiv.org/abs/2301.08072)/[Code](https://github.com/GeoVectorMatrix/Dif-Fusion) |

### <a id="2.">2. Extended Diffusion Models In Low-level Vision</a>

#### <a id="2.1">2.1 Diffusion Models In Low-level Medical Image Analysis</a>

##### <a id="2.1.1">2.1.1 MRI</a>

|  Release   |     Method      | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2022/07 |  **AdaDiff**  | **Adaptive Diffusion Priors for Accelerated MRI Reconstruction**<br /><sup><sub>*Alper Güngör, Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Tolga Çukur*</sup></sub> | MedIA<br />2023 | [Paper](https://arxiv.org/abs/2207.05876)/[Code](https://github.com/icon-lab/AdaDiff) |
| 2021/10 | **Score-MRI** | **Score-based diffusion models for accelerated MRI**<br /><sup><sub>*Hyungjin Chung, Jong Chul Ye*</sup></sub> | MedIA<br />2022 | [Paper](https://arxiv.org/abs/2110.05243)/[Code](https://github.com/HJ-harry/score-MRI) |
| 2021/08 |   **CSGM**    | **Robust Compressed Sensing MRI with Deep Generative Priors**<br /><sup><sub>*Alper Güngör, Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Tolga Çukur*</sup></sub> | NIPS<br />2021  | [Paper](https://arxiv.org/abs/2108.01368)/[Code](https://github.com/utcsilab/csgm-mri-langevin) |

##### <a id="2.1.2">2.1.2 X-ray-based</a>

|  Release   |   Method    | Title                                                        |      Pub.      |                             Link                             |
| :-----: | :-------: | ------------------------------------------------------------ | :------------: | :----------------------------------------------------------: |
| 2022/11 | **DOLCE** | **DOLCE: A Model-Based Probabilistic Diffusion Framework for Limited-Angle CT Reconstruction**<br /><sup><sub>*Jiaming Liu, Rushil Anirudh, Jayaraman J. Thiagarajan, Stewart He, K. Aditya Mohan, Ulugbek S. Kamilov, Hyojin Kim*</sup></sub> | ICCV<br />2023 | [Paper](https://arxiv.org/abs/2211.12340)/[Code](https://github.com/wustl-cig/DOLCE) |

##### <a id="2.1.3">2.1.3 Multi-modal</a>

|  Release   |     Method     | Title                                                        |      Pub.       |                    Link                    |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------: |
| 2023/04 |   **FGDM**   | **Zero-shot Medical Image Translation via Frequency-Guided Diffusion Models**<br /><sup><sub>*Yunxiang Li, Hua-Chieh Shao, Xiao Liang, Liyuan Chen, Ruiqi Li, Steve Jiang, Jing Wang, You Zhang*</sup></sub> |  TMI<br />2023  | [Paper](https://arxiv.org/abs/2304.02742)/ |
| 2022/09 |      -       | **Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models**<br /><sup><sub>*Qing Lyu, Ge Wang*</sup></sub> | arXiv<br />2022 | [Paper](https://arxiv.org/abs/2209.12104)/ |
| 2022/07 | **UMM-CSGM** | **A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion**<br /><sup><sub>*Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen*</sup></sub> | arXiv<br />2022 | [Paper](https://arxiv.org/abs/2207.03430)/ |

##### <a id="2.1.4">2.1.4 Other Modalities</a>

|  Release   |       Method       | Title                                                        |                   Pub.                    |                             Link                             |
| :-----: | :--------------: | ------------------------------------------------------------ | :---------------------------------------: | :----------------------------------------------------------: |
| 2024/02 | - | **Dehazing Ultrasound using Diffusion Models**<br /><sup><sub>*Tristan S.W. Stevens, Faik C. Meral, Jason Yu, Iason Z. Apostolakis, Jean-Luc Robert, Ruud J.G. Van Sloun*</sup></sub> | TMI<br />2024 | [Paper](https://ieeexplore.ieee.org/abstract/document/10423849)/ |
| 2022/09 |   **PET-DDM**    | **PET image denoising based on denoising diffusion probabilistic models**<br /><sup><sub>*Kuang Gong, Keith A. Johnson, Georges El Fakhri, Quanzheng Li, Tinsu Pan*</sup></sub> | Eur. J. Nucl. Med. Mol. Imaging<br />2023 |          [Paper](https://arxiv.org/abs/2209.06167)/          |
| 2022/01 | **DenoOCT-DDPM** | **Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model**<br /><sup><sub>*Dewei Hu, Yuankai K. Tao, Ipek Oguz*</sup></sub> |              SPIE<br />2022               | [Paper](https://arxiv.org/abs/2201.11760)/[Code](https://github.com/deweihu/oct_ddpm) |

#### <a id="2.2">2.2 Diffusion Models In Remote Sensing For Low-level Vision Tasks</a>

##### <a id="2.2.1">2.2.1 Visible-light Remote Sensing Image</a>

|  Release   |     Method     | Title                                                        |           Pub.           |                             Link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :----------------------: | :----------------------------------------------------------: |
| 2023/10 | **EDiffSR**  | **EDiffSR: An Efficient Diffusion Probabilistic Model for Remote Sensing Image Super-Resolution**<br /><sup><sub>*Yi Xiao, Qiangqiang Yuan, Kui Jiang, Jiang He, Xianyu Jin, Liangpei Zhang*</sup></sub> |      TGRS<br />2024      | [Paper](https://arxiv.org/abs/2310.19288)/[Code](https://github.com/XY-boy/EDiffSR) |
| 2023/09 |  **RSDiff**  | **RSDiff: Remote Sensing Image Generation from Text Using Diffusion Model**<br /><sup><sub>*Ahmad Sebaq, Mohamed ElHelw*</sup></sub> |     arXiv<br />2023      |          [Paper](https://arxiv.org/abs/2309.02455)/          |
| 2023/08 | **ARDD-Net** | **Remote Sensing Image Dehazing Using Adaptive Region-Based Diffusion Models**<br /><sup><sub>*Y Huang, S Xiong*</sup></sub> |      LGRS<br />2023      | [Paper](https://ieeexplore.ieee.org/abstract/document/10233893)/ |
| 2022/09 |   **PSSR**   | **Diffusion Model with Detail Complement for Super-Resolution of Remote Sensing**<br /><sup><sub>*Liu, Jinzhe and Yuan, Zhiqiang and Pan, Zhaoying and Fu, Yiqun and Liu, Li and Lu, Bin*</sup></sub> | Remote Sensing<br />2022 |     [Paper](https://www.mdpi.com/2072-4292/14/19/4834)/      |

##### <a id="2.2.2">2.2.2 HSI</a>

|  Release   |     Method     | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/07 | **DDPM-Fus** | **Hyperspectral and Multispectral Image Fusion Using the Conditional Denoising Diffusion Probabilistic Model**<br /><sup><sub>*Shuaikai Shi, Lijun Zhang, Jie Chen*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2307.03423)/[Code](https://github.com/shuaikaishi/DDPMFus) |
| 2023/07 |      -       | **A Noise-Model-Free Hyperspectral Image Denoising Method Based on Diffusion Model**<br /><sup><sub>*Deng, Keli and Jiang, Zhongshun and Qian, Qipeng and Qiu, Yi and Qian, Yuntao*</sup></sub> | IGASS<br />2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10281546)/ |
| 2023/07 | **R2H-CCD**  | **R2H-CCD: Hyperspectral Imagery Generation from RGB Images Based on Conditional Cascade Diffusion Probabilistic Models**<br /><sup><sub>*Zhang, Lei and Luo, Xiaoyan and Li, Sen and Shi, Xiaofeng*</sup></sub> | IGASS<br />2023 |   [Paper](https://ieeexplore.ieee.org/document/10281589)/    |
| 2023/03 |  **DDS2M**   | **DDS2M: Self-Supervised Denoising Diffusion Spatio-Spectral Model for Hyperspectral Image Restoration**<br /><sup><sub>*Yuchun Miao, Lefei Zhang, Liangpei Zhang, Dacheng Tao*</sup></sub> | ICCV<br />2023  | [Paper](https://arxiv.org/abs/2303.06682)/[Code](https://github.com/Meow-YC/DDS2M/tree/master) |
| 2023/01 | **HSR-Diff** | **HSR-Diff:Hyperspectral Image Super-Resolution via Conditional Diffusion Models**<br /><sup><sub>*Chanyue Wu, Dong Wang, Hanyu Mao, Ying Li*</sup></sub> | ICCV<br />2023  |          [Paper](https://arxiv.org/abs/2306.12085)/          |

##### <a id="2.2.3">2.2.3 SAR</a>

|  Release   | Method | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :--: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2023/07 |  -   | **Unsupervised SAR Despeckling Based on Diffusion Model**<br /><sup><sub>*Xiao, Siyao and Huang, Libing and Zhang, Shunsheng*</sup></sub> | IGASS<br />2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10282914)/ |
| 2023/08 |  -   | **Diffusion Models for Interferometric Satellite Aperture Radar**<br /><sup><sub>*Alexandre Tuel, Thomas Kerdreux, Claudia Hulbert, Bertrand Rouet-Leduc*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2308.16847)/[Code](https://github.com/thomaskerdreux/PDM_SAR_InSAR_generation) |
| 2023/06 |  -   | **SAR Despeckling using a Denoising Diffusion Probabilistic Model**<br /><sup><sub>*Malsha V. Perera, Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel*</sup></sub> | LGRS<br />2023  | [Paper](https://arxiv.org/abs/2206.04514)/[Code](https://github.com/malshaV/SAR_DDPM) |

##### <a id="2.2.4">2.2.4 Multi-modal</a>

|  Release   |    Method     | Title                                                        |           Pub.           |                        Link                         |
| :-----: | :---------: | ------------------------------------------------------------ | :----------------------: | :-------------------------------------------------: |
| 2023/07 |      -      | **Improved Flood Insights: Diffusion-Based SAR to EO Image Translation**<br /><sup><sub>*Minseok Seo, Youngtack Oh, Doyi Kim, Dongmin Kang, Yeji Choi*</sup></sub> |     arXiv<br />2023      |     [Paper](https://arxiv.org/abs/2307.07123)/      |
| 2023/04 |      -      | **Cloud Removal in Remote Sensing Using Sequential-Based Diffusion Models**<br /><sup><sub>*Zhao, Xiaohu and Jia, Kebin*</sup></sub> | Remote Sensing<br />2023 | [Paper](https://www.mdpi.com/2072-4292/15/11/2861)/ |
| 2023/04 |  **DDRF**   | **DDRF: Denoising Diffusion Model for Remote Sensing Image Fusion**<br /><sup><sub>*ZiHan Cao, ShiQi Cao, Xiao Wu, JunMing Hou, Ran Ran, Liang-Jian Deng*</sup></sub> |     arXiv<br />2023      |     [Paper](https://arxiv.org/abs/2304.04774)/      |
| 2023/03 | **DDPM-CR** | **Denoising Diffusion Probabilistic Feature-Based Network for Cloud Removal in Sentinel-2 Imagery**<br /><sup><sub>*Jing, Ran and Duan, Fuzhou and Lu, Fengxian and Zhang, Miao and Zhao, Wenji*</sup></sub> | Remote Sensing<br />2023 | [Paper](https://www.mdpi.com/2072-4292/15/9/2217)/  |

#### <a id="2.3">2.3 Varied Low-level Vision Tasks In Video Through Diffusion Models</a>

##### <a id="2.3.1">2.3.1 Video Frame Prediction and Interpolation</a>

|  Release   |    Method    | Title                                                        |       Pub.        |                             Link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2023/03 | **LDMVFI** | **LDMVFI: Video Frame Interpolation with Latent Diffusion Models**<br /><sup><sub>*Duolikun Danier, Fan Zhang, David Bull*</sup></sub> |  arXiv<br />2023  | [Paper](https://arxiv.org/abs/2303.09508)/[Code](https://github.com/danier97/LDMVFI) |
| 2022/06 | **RaMViD** | **Diffusion Models for Video Prediction and Infilling**<br /><sup><sub>*Tobias Höppe, Arash Mehrjou, Stefan Bauer, Didrik Nielsen, Andrea Dittadi*</sup></sub> |  TMLR<br />2022   |          [Paper](https://arxiv.org/abs/2206.07696)/          |
| 2022/05 |  **MCVD**  | **MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation**<br /><sup><sub>*Vikram Voleti, Alexia Jolicoeur-Martineau, Christopher Pal*</sup></sub> |  NIPS<br />2022   | [Paper](https://arxiv.org/abs/2205.09853)/[Code](https://github.com/voletiv/mcvd-pytorch) |
| 2022/03 |  **RVD**   | **Diffusion Probabilistic Modeling for Video Generation**<br /><sup><sub>*Ruihan Yang, Prakhar Srivastava, Stephan Mandt*</sup></sub> | Entropy<br />2023 | [Paper](https://arxiv.org/abs/2203.09481)/[Code](https://github.com/buggyyang/RVD) |

##### <a id="2.3.2">2.3.2 Super Resolution For Video Generation</a>

|  Release   |   Method    | Title                                                        |      Pub.       |                             Link                             |
| :-----: | :-------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2024/03 | **SATeCo** | **Learning Spatial Adaptation and Temporal Coherence in Diffusion Models for Video Super-Resolution**<br /><sup><sub>*Zhikai Chen, Fuchen Long, Zhaofan Qiu, Ting Yao, Wengang Zhou, Jiebo Luo, Tao Mei*</sup></sub> | CVPR<br />2024 | [Paper](https://arxiv.org/abs/2403.17000)/ |
| 2024/01 | - | **Inflation with Diffusion: Efficient Temporal Adaptation for Text-to-Video Super-Resolution**<br /><sup><sub>*Xin Yuan, Jinoo Baek, Keyang Xu, Omer Tov, Hongliang Fei*</sup></sub> | WACV<br />2024 | [Paper](https://arxiv.org/abs/2401.10404)/ |
| 2023/09 | **LAVIE** | **LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models**<br /><sup><sub>*Yaohui Wang, Xinyuan Chen, Xin Ma, Shangchen Zhou, Ziqi Huang, Yi Wang, Ceyuan Yang, Yinan He, Jiashuo Yu, Peiqing Yang, Yuwei Guo, Tianxing Wu, Chenyang Si, Yuming Jiang, Cunjian Chen, Chen Change Loy, Bo Dai, Dahua Lin, Yu Qiao, Ziwei Liu*</sup></sub> | arXiv<br />2023 | [Paper](https://arxiv.org/abs/2309.15103)/[Code](https://vchitect.github.io/LaVie-project/) |
| 2023/05 | **PYoCo** | **Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models**<br /><sup><sub>*Songwei Ge, Seungjun Nah, Guilin Liu, Tyler Poon, Andrew Tao, Bryan Catanzaro, David Jacobs, Jia-Bin Huang, Ming-Yu Liu, Yogesh Balaji*</sup></sub> | ICCV<br />2023  | [Paper](https://arxiv.org/abs/2305.10474)/[Demo](https://research.nvidia.com/labs/dir/pyoco/) |
| 2023/04 |     -     | **Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models**<br /><sup><sub>*Andreas Blattmann, Robin Rombach, Huan Ling, Tim Dockhorn, Seung Wook Kim, Sanja Fidler, Karsten Kreis*</sup></sub> | CVPR<br />2023  | [Paper](https://arxiv.org/abs/2304.08818)/[Demo](https://research.nvidia.com/labs/toronto-ai/VideoLDM/) |

##### <a id="2.3.3">2.3.3 Video Restoration</a>

| Release |   Method    | Title                                                        |      Pub.      |                             Link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :------------: | :----------------------------------------------------------: |
| 2024/03 | **DiffTTA** | **Genuine Knowledge from Practice: Diffusion Test-Time Adaptation for Video Adverse Weather Removal**<br /><sup><sub>*Yijun Yang, Hongtao Wu, Angelica I. Aviles-Rivero, Yulun Zhang, Jing Qin, Lei Zhu*</sup></sub> | CVPR<br />2024 | [Paper](https://arxiv.org/abs/2403.07684)/[Code](https://github.com/scott-yjyang/DiffTTA) |

## <a id="4.">Related Surveys Recommended</a>

**Diffusion Models in Low-Level Vision: A Survey**<br />
arXiv 2024. [[Paper](https://arxiv.org/abs/2406.11138)] <br />Jun. 2024<br />

**Diffusion Models Meet Remote Sensing: Principles, Methods, and Perspectives**<br />
arXiv 2024. [[Paper](https://arxiv.org/abs/2404.08926)] <br />Apr. 2024<br />

**Diffusion Models, Image Super-Resolution And Everything: A Survey**<br />
arXiv 2024. [[Paper](https://arxiv.org/abs/2401.00736)] <br />
Jan. 2024<br />

**State of the Art on Diffusion Models for Visual Computing**<br />
arXiv 2023.  [[Paper](https://arxiv.org/abs/2310.07204)]<br />
Oct. 2023<br />

**Diffusion Models for Image Restoration and Enhancement -- A Comprehensive Survey.**<br />
arXiv 2023. [[Paper](https://arxiv.org/abs/2308.09388)] <br />
Aug. 2023<br />

**Survey on Diverse Image Inpainting using Diffusion Models**<br />
PCEMS 2023. [[Paper](https://ieeexplore.ieee.org/abstract/document/10136091)]<br />
Jun. 2023<br />

**Diffusion Models for Medical Image Analysis: A Comprehensive Survey**<br />
Medical Image Analysis 2023. [[Paper](https://www.sciencedirect.com/journal/medical-image-analysis)]<br />
Nov. 2022<br />

**Diffusion Models in Vision: A Survey**<br />
TPAMI 2023. [[Paper](https://arxiv.org/abs/2209.04747)]<br />
Sep. 2022<br />

**Diffusion Models: A Comprehensive Survey of Methods and Applications**<br />
ACM Computing Surveys 2023. [[Paper](https://arxiv.org/abs/2209.00796)]<br />
Sep. 2022<br />

## <a id="5.">Datasets for low-level vision tasks</a>
    Due to space limitations, we provide a summary of commonly used datasets for several classical natural low-level vision tasks here, including their scales, sources, modalities, and remarks. Clicking on the dataset will redirect you to its download link.

| Tasks      | Datasets                                                     | Scales      | Sources    | Modalities | Remarks                                                      |
| ---------- | ------------------------------------------------------------ | ----------- | ---------- | ---------- | ------------------------------------------------------------ |
| **SR**     | [*BSD500*](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) | 500         | TPAMI 2010 | Syn        | A synthetic benchmark that is initially designed for object contour detection. |
| **SR**     | [*Set14*](https://sites.google.com/site/romanzeyde/research-interests) | 14          | TPAMI 2015 | Syn        | Commonly utilized for testing performance of super-resolution algorithms. |
| **SR**     | [*Manga109*](http://www.manga109.org/en/)                    | 109         | MTAP 2015  | Syn        | Compiled mainly for academic research on Japanese manga media processing. |
| **SR**     | [*General100*](https://www.kaggle.com/datasets/msahebi/super-resolution) | 100         | ECCV 2016  | Syn        | Synthesized images in uncompressed BMP format covering various scales. |
| **SR**     | [*DIV2K*](https://data.vision.ee.ethz.ch/cvl/ntire17//)      | 900/100     | NTIRE 2018 | Real       | A commonly-used dataset with diverse scenarios and realistic degradations. |
| **SR**     | [*Flickr1024*](https://github.com/YingqianWang/Flickr1024)   | 1024        | ICCVW 2019 | Syn        | A large-scale stereo image dataset with high-quality pairs and diverse scenarios. |
| **SR**     | [*Urban100*](https://github.com/jbhuang0604/SelfExSR)        | 100         | CVPR 2019  | Syn        | Sourced from urban environments: city streets, buildings, and urban landscapes. |
| **SR**     | [*DRealSR*](https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution) | 31970       | ECCV 2020  | Real       | Benchmarks captured by DSLR cameras, circumventing simulated degradation. |
| **Deblur** | [*GoPro*](https://seungjunnah.github.io/Datasets/gopro)      | 2103/1111   | CVPR 2017  | Syn        | Acquired by high-speed cameras for video quality assessment and restoration. |
| **Deblur** | [*HIDE*](https://github.com/joanshen0508/HA_deblur)          | 8422        | ICCV 2019  | Syn        | Cover long-distance and short-distance scenarios degraded by motion blur. |
| **Deblur** | [*REDS*](https://seungjunnah.github.io/Datasets/reds)        | 270/30      | NTIRE 2019 | Real       | Contain 300 video sequences with dynamic duration and varied resolutions. |
| **Deblur** | [*BSD*](https://seungjunnah.github.io/Datasets/reds)         | 80/20       | ECCV 2020  | Real       | Comprise more scenes and use the proposed beam-splitter acquisition system. |
| **Deblur** | [*RealBlur*](https://github.com/rimchang/RealBlur)           | 3758/980    | ECCV 2020  | Real       | Cover common instances of motion blur, captured in raw and JPEG formats. |
| **Dehaze** | [*I-Haze*](https://data.vision.ee.ethz.ch/cvl/ntire18//i-haze/) | 35          | NTIRE 2018 | Real       | Indoor dataset with real haze for objective image dehazing and evaluation. |
| **Dehaze** | [*O-Haze*](https://data.vision.ee.ethz.ch/cvl/ntire18//o-haze/) | 45          | NTIRE 2018 | Real       | Outdoor dataset with real haze for objective image dehazing and evaluation. |
| **Dehaze** | [*Dense-Haze*](https://data.vision.ee.ethz.ch/cvl/ntire19//dense-haze/) | 33          | ICIP 2019  | Real       | Real-world dataset with dense haze for robust single image dehazing methods. |
| **Dehaze** | [*RESIDE*](https://github.com/Boyiliee/RESIDE-dataset-link)  | 13000/990   | TIP 2019   | Syn+Real   | Divided into five subsets to highlight diverse sources and heterogeneous contents. |
| **Dehaze** | [*NH-Haze*](https://data.vision.ee.ethz.ch/cvl/ntire20/nh-haze/) | 55          | CVRPW 2020 | Real       | The first non-homogeneous dehazing dataset with realistic haze distribution. |
| **Dehaze** | [*Haze-4K*](https://github.com/liuye123321/DMT-Net)          | 4000        | MM 2021    | Syn        | A large-scale synthetic dataset for image dehazing with varing distributions. |
| **LLIE**   | [*MIT-Fivek*](https://data.csail.mit.edu/graphics/fivek/)    | 4500/500    | CVPR 2011  | Syn        | A curated dataset of RAW photos adjusted by skilled retouchers for visual appeal. |
| **LLIE**   | [*LOLv1*](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset) | 485/15      | BMVC 2018  | Real       | The first dataset with image pairs from real scenarios for low-light enhancement. |
| **LLIE**   | [*SID*](https://github.com/cchen156/Learning-to-See-in-the-Dark) | 5094        | CVPR 2018  | Real       | A dataset of raw short-exposure images with their long-exposure reference images. |
| **LLIE**   | [*SICE*](https://github.com/csjcai/SICE)                     | 589         | TIP 2018   | Syn        | A large-scale multi-exposure image dataset with complex illumination conditions. |
| **LLIE**   | [*ExDark*](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset) | 7363        | CVIU 2019  | Real       | Collected in low-light scenarios with 12 classes and instance-level annotations. |
| **LLIE**   | [*LOLv2-Real*](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset) | 689/100     | TIP 2021   | Real       | A three-step shooting strategy is used to eliminate intra-pair image misalignments. |
| **LLIE**   | [*LOLv2-Syn*](https://github.com/flyywh/SGM-Low-Light)       | 900/100     | TIP 2021   | Syn        | Synthetic dark images mimic real low-light photography via histogram analysis. |
| **LLIE**   | [*SDSD-Indoor*](https://github.com/dvlab-research/SDSD)      | 62/6        | ICCV 2021  | Real       | Indoor dataset collected from dynamic scenes under varying lighting conditions. |
| **LLIE**   | [*SDSD-Outdoor*](https://github.com/dvlab-research/SDSD)     | 116/10      | ICCV 2021  | Real       | Outdoor dataset collected from dynamic scenes under varying lighting conditions. |
| **Derain** | [*Rain100H*](https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html) | 1800/100    | CVPR 2017  | Syn        | Comprise synthetic datasets with five types of rain streaks for rain removal. |
| **Derain** | [*RainDrop*](https://github.com/rui1996/DeRaindrop)          | 861/239     | CVPR 2018  | Syn        | Image pairs with raindrop degradation, captured using the setup of dual glasses.|
| **Derain** | [*SPA-Data*](https://github.com/stevewongv/SPANet)           | 638492/1000 | CVPR 2019  | Real       | Design a semi-automatic method to generate clean images from real rain streaks. |
| **Derain** | [*MPID*](https://github.com/panda-lab/Single-Image-Deraining) | 3961/419    | CVPR 2019  | Syn+Real   | A large-scale benchmark that focuses on driving and surveillance scenarios. |
| **Derain** | [*RainCityscapes*](https://github.com/xw-hu/DAF-Net)         | 9432/1188   | CVPR 2019  | Syn        | A famous rain removal dataset with paired depth maps for outdoor scenarios. |
| **Derain** | [*RainDS*](https://github.com/Songforrr/RainDS_CCN)          | 3450/900    | CVPR 2021  | Syn+Real   | A hybrid dataset with both real and synthesized data under diverse scenarios. |
| **Derain** | [*RainDirection*](https://github.com/Yueziyu/RainDirection-and-Real3000-Dataset) | 2920/430    | ICCV 2021  | Syn        | A large-scale synthetic rainy dataset with directional labels in the training phase. |
| **Derain** | [*GT-RAIN*](https://github.com/UCLA-VMG/GT-RAIN)             | 28217/2100  | ECCV 2022  | Real       | The first paired derain dataset with real data by controlling non-rain variations. |
| **Desnow** | [*Snow100k*](https://sites.google.com/view/yunfuliu/desnownet) | 100000      | TIP 2018   | Syn+Real   | A large-scale dataset with over 1k real-world images degraded by heavy snow. |
| **Desnow** | [*SRRS*](https://github.com/weitingchen83/JSTASR-DesnowNet-ECCV-2020) | 16000       | ECCV 2020  | Syn+Real   | A hybrid snow dataset with 15k synthesized images and 1k real-world images. |
| **Desnow** | [*CSD*](https://github.com/weitingchen83/ICCV2021-Single-Image-Desnowing-HDCWNet) | 10000       | ICCV 2021  | Syn        | A large-scale desnowing dataset to comprehensively simulate snow scenarios. |

## <a id="Reference">Reference</a>

[Awesome-diffusion-low-level-vision-by-yulunzhang](https://github.com/yulunzhang/awesome-diffusion-low-level-vision)

[Awesome-low-level-vision-resources](https://github.com/sunny2109/Awesome-low-level-vision-resources)

[Awesome-Diffusion-Models-in-Medical-Imaging: Diffusion Models in Medical Imaging](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging)

