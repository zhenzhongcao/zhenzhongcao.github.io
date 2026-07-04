# 📝 Publications 
## 👄 Main Paper

<audio src="../../audios/OurSong.mp3" autoplay loop>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RAL and IROS 2022</div><img src='images/ObjectAwareSLAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[**Object-Aware SLAM Based on Efficient Quadric Initialization and Joint Data Association**](https://ieeexplore.ieee.org/abstract/document/9829272), **Zhenzhong Cao**, Yunzhou Zhang, Rui Tian, Rong Ma, Xinggang Hu, Sonya Coleman, Dermot Kerr \| [**Project**](https://github.com/zhenzhongcao/Object-Aware-SLAM)

- We propose an efficient quadric initialization (EQI) method based on object detection and surfel construction which initializes quadrics using fewer frames with small viewing angles.
- We propose a robust object-level joint data association (JDA) method combining multi-dimensional information and statistic distributions. 
- We propose a multi-constraint optimization factor graph for quadrics optimization and joint bundle adjustment.
- We implement a complete visual semantic SLAM system, aiming to build a novel object-oriented and semanticallyenhanced map for indoor robot interaction.

</div>

</div>



<div class="divcss5"><img src="images/paperGif.gif" /></div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/SemanticTopoLoop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SemanticTopoLoop: Semantic Loop Closure With 3D Topological Graph Based on Quadric-Level Object Map**](https://arxiv.org/abs/2311.02831), **Zhenzhong Cao** \| [**Project**](https://github.com/zhenzhongcao/SemanticToopLoop)

- MLV-ODA method is introduced to reduce the time and space complexity of data association, indirectly promoting the accuracy and completeness of object construction in the scene.
- QLT-SLC method is presented to improve the precision and recall rate of loop closure, as well as enhance the system's localization accuracy.
- The proposed MLV-ODA method and QLT-SLC method are embed into the Object-Aware SLAM system, which jointly maintain the PPO-MD.
- Qualitative experiments, quantitative experiments, and ablation studies are designed to demonstrate the effectiveness and robustness of the proposed MLV-ODA and QLT-SLC method.

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/RGBDS-SLAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RGBDS-SLAM: A RGB-D Semantic Dense SLAM Based on 3D Multi Level Pyramid Gaussian Splatting**](https://github.com/zhenzhongcao/RGBDS-SLAM), **Zhenzhong Cao**, Chenyang Zhao, Qianyi Zhang, Jinzheng Guang, Yinuo Song, Jingtai Liu \| [**Project**](https://github.com/zhenzhongcao/RGBDS-SLAM)

- We propose a 3D Multi-Level Pyramid Gaussian Splatting (MLP-GS) module, which builds multi-resolution image pyramids for progressive training to restore scene fine-grained details and ensure cross-view reconstruction consistency.
- We design a Tightly Coupled Multi-Features Reconstruction Optimization (TCMF-RO) mechanism, enabling mutual promotion of RGB, depth and semantic reconstruction accuracy in joint rendering optimization.
- We build a full RGB-D semantic dense SLAM system extended from ORB-SLAM3, realizing real-time high-fidelity joint reconstruction of color, geometry and semantic information.
- Extensive experiments on Replica and ScanNet datasets show our method outperforms SOTA methods, with 11.13% PSNR gain and 68.57% LPIPS improvement; ablation studies verify the validity of MLP-GS and TCMF-RO modules.

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal 2026</div><img src='images/LLF-GS-SLAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LLF-GS SLAM: Real-Time 3D Gaussian Semantic SLAM via Compact Label-Language Features**](https://github.com/zhenzhongcao/LLF-GS-SLAM), **Zhenzhong Cao**, Chenyang Zhao, Yinuo Song, Jingtai Liu \| [**Project**](https://github.com/zhenzhongcao/LLF-GS SLAM)

- We propose a label-language dual-branch semantic Gaussian representation: global consistent explicit labels serve as object segmentation anchors, while each object maintains compact multi-view language feature banks for open-vocabulary interaction.
- A global label consistency alignment mechanism is proposed to match frame-wise SAM segmentation masks with rendered global semantic maps, eliminating cross-view label fragmentation.
- We compress 512-dim CLIP features into 16-dim compact embeddings via offline autoencoder, and design quality-aware multi-view feature bank update strategy to balance storage overhead and retrieval performance.
- The system supports real-time online mapping, open-vocabulary text query and object-level 3D editing; experiments on Replica and TUM RGB-D datasets achieve superior semantic segmentation and object retrieval efficiency under limited GPU memory.

</div>

</div>

## 📚 Co-Author Paper
- ``RAL and ICRA 2021`` [Accurate and Robust Object SLAM With 3D Quadric Landmark Reconstruction in Outdoors](https://ieeexplore.ieee.org/abstract/document/9662189), Rui Tian, Yunzhou Zhang, Yonghui Feng, Linghao Yang, **Zhenzhong Cao**, Sonya Coleman, Dermot Kerr
- `ICRA 2022` [SemLoc: Accurate and Robust Visual Localization with Semantic and Structural Constraints from Prior Maps](https://ieeexplore.ieee.org/abstract/document/9811925), Shiwen Liang, Yunzhou Zhang, Rui Tian, Delong Zhu, Linghao Yang, **Zhenzhong Cao**
- ``IROS 2022`` [CFP-SLAM: A Real-time Visual SLAM Based on Coarse-to-Fine Probability in Dynamic Environments](https://ieeexplore.ieee.org/abstract/document/9981826), Xinggang Hu, Yunzhou Zhang, **Zhenzhong Cao**, Rong Ma, Yanmin Wu, Zhiqiang Deng, Wenkai Sun 
- ``TITS 2023`` [Object SLAM With Robust Quadric Initialization and Mapping for Dynamic Outdoors](https://ieeexplore.ieee.org/abstract/document/10149129), Rui Tian, Yunzhou Zhang, **Zhenzhong Cao**, Jinpeng Zhang, Linghao Yang, Sonya Coleman, Dermot Kerr, Kun Li