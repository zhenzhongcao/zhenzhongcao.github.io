
# 📝 Publications 
## 👄 Main Paper
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RAL & IROS 2022</div><img src='images/ObjectAwareSLAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Object-Aware SLAM Based on Efficient Quadric Initialization and Joint Data Association**](https://ieeexplore.ieee.org/abstract/document/9829272), **Zhenzhong Cao**, Yunzhou Zhang, Rui Tian, Rong Ma, Xinggang Hu, Sonya Coleman, Dermot Kerr \| [**Project**](https://github.com/zhenzhongcao/Object-Aware-SLAM)

- Semantic simultaneous localization and mapping (SLAM) is a popular technology enabling indoor mobile robots to sufficiently perceive and interact with the environment. In this paper, we propose an object-aware semantic SLAM system, which consists of a quadric initialization method, an object-level data association method, and a multi-constraint optimization factor graph. To overcome the limitation of multi-view observations and the requirement of dense point clouds for objects, an efficient quadric initialization method based on object detection and surfel construction is proposed, which can efficiently initialize quadrics within fewer frames and with small viewing angles. The robust object-level joint data association method and the tightly coupled multi-constraint factor graph for quadrics optimization and joint bundle adjustment enable the accurate estimation of constructed quadrics and camera poses. Extensive experiments using public datasets show that the proposed system achieves competitive performance with respect to accuracy and robustness of object quadric estimation and camera localization compared with state-of-the-art methods.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/SemanticTopoLoop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SemanticTopoLoop: Semantic Loop Closure With 3D Topological Graph Based on Quadric-Level Object Map**](https://arxiv.org/abs/2311.02831), **Zhenzhong Cao** \| [**Project**](https://github.com/zhenzhongcao/SemanticToopLoop)

- Loop closure, as one of the crucial components in SLAM, plays an essential role in correcting the accumulated errors. Traditional appearance-based methods, such as bag-of-words models, are often limited by local 2D features and the volume of training data, making them less versatile and robust in real-world scenarios, leading to missed detections or false positives detections in loop closure. To address these issues, we first propose a semantic loop closure method based on quadric-level object map topology, which represents scenes through the topological graph of quadric-level objects and achieves accurate loop closure at a wide field of view by comparing differences in the topological graphs. Next, in order to solve the data association problem between frame and map in loop closure, we propose a object-level data association method based on multi-level verification, which can associate 2D semantic features of current frame with 3D objects landmarks of map. Finally, we integrate these two methods into a complete object-aware SLAM system. Qualitative experiments and ablation studies demonstrate the effectiveness and robustness of the proposed object-level data association algorithm. Quantitative experiments show that our semantic loop closure method outperforms existing state-of-the-art methods in terms of precision, recall and localization accuracy metrics.

</div>
</div>

## 📚 Co-Author Paper
- ``RAL & ICRA 2021`` [Accurate and Robust Object SLAM With 3D Quadric Landmark Reconstruction in Outdoors](https://ieeexplore.ieee.org/abstract/document/9662189), Rui Tian, Yunzhou Zhang, Yonghui Feng, Linghao Yang, **Zhenzhong Cao**, Sonya Coleman, Dermot Kerr
- `ICRA 2022` [SemLoc: Accurate and Robust Visual Localization with Semantic and Structural Constraints from Prior Maps](https://ieeexplore.ieee.org/abstract/document/9811925), Shiwen Liang, Yunzhou Zhang, Rui Tian, Delong Zhu, Linghao Yang, **Zhenzhong Cao**
- ``IROS 2022`` [CFP-SLAM: A Real-time Visual SLAM Based on Coarse-to-Fine Probability in Dynamic Environments](https://ieeexplore.ieee.org/abstract/document/9981826), Xinggang Hu, Yunzhou Zhang, **Zhenzhong Cao**, Rong Ma, Yanmin Wu, Zhiqiang Deng, Wenkai Sun 
- ``TITS 2023`` [Object SLAM With Robust Quadric Initialization and Mapping for Dynamic Outdoors](https://ieeexplore.ieee.org/abstract/document/10149129), Rui Tian, Yunzhou Zhang, **Zhenzhong Cao**, Jinpeng Zhang, Linghao Yang, Sonya Coleman, Dermot Kerr, Kun Li
