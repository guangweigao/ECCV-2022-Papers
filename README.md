# ECCV-2022-Papers
![9361c19ba6cbc5ae7be1fba8d82759b](https://user-images.githubusercontent.com/62801906/150054267-d54c28a4-f2de-4171-88df-d9820222a392.jpg)

官网链接：https://eccv2022.ecva.net/

截稿日期：2022年3月7日(9:59PM CET, 11:59AM PST)

会议日期：2022年10月24日-2022年10月28日

## 历年综述论文分类汇总戳这里↘️[CV-Surveys](https://github.com/52CV/CV-Surveys)施工中~~~~~~~~~~

## 2022 年论文分类汇总戳这里
↘️[CVPR-2022-Papers](https://github.com/52CV/CVPR-2022-Papers)
↘️[WACV-2022-Papers](https://github.com/52CV/WACV-2022-Papers)

## 2021年论文分类汇总戳这里
↘️[ICCV-2021-Papers](https://github.com/52CV/ICCV-2021-Papers)
↘️[CVPR-2021-Papers](https://github.com/52CV/CVPR-2021-Papers)

## 2020 年论文分类汇总戳这里
↘️[CVPR-2020-Papers](https://github.com/52CV/CVPR-2020-Papers)
↘️[ECCV-2020-Papers](https://github.com/52CV/ECCV-2020-Papers)

## ❣❣❣另外打包下载ECCV 2022论文，可在【我爱计算机视觉】微信公众号后台回复“paper”。截止 7 月 15 日，已整理 96 篇。

|:cat:|:dog:|:tiger:|:wolf:|
|------|------|------|------|
|[1.其它](#1)|[2.Image Segmentation(图像分割)](#2)|[3.Image Progress(图像处理)](#3)|[4.Image Captioning(图像字幕)](#4)|
|[5.Image/Video Retrieval(图像/视频检索)](#5)|[6.Object Detection(目标检测)](#6)|[7.Object Tracking(目标跟踪)](#7)|[8.3D(三维视觉)](#8)|
|[9.Human Pose Estimation(人体姿态估计)](#9)|[10.Pose Estimation(物体姿势估计)](#10)|[11.Video](#11)|[12.Action Detection(人体动作检测与识别)](#12)|
|[13.Human-Object Interaction(人物交互)](#13)|[14.Visual Answer Questions(视觉问答)](#14)|[15.Vision-Language(视觉语言)](#15)|[16.Transformer](#16)|
|[17.GAN](#17)|[18.Image-to-Image Translation(图像到图像翻译)](#18)|[19.Image Synthesis/Generation(图像合成)](#19)|[20.Face(人脸)](#20)|
|[21.Semi/self-supervised learning(半/自监督)](#21)|[22.OCR](#22)|[23.Medical Image(医学影像)](#23)|[24.UAV/Remote Sensing/Satellite Image(无人机/遥感/卫星图像)](#24)|

## 7月18日更新 39 篇。

* VQA
  * [Rethinking Data Augmentation for Robust Visual Question Answering](https://arxiv.org/abs/2207.08739)<br>:star:[code](https://github.com/ItemZheng/KDDAug)
* 奇异值检测(Novelty Detection)
  * [Semantic Novelty Detection via Relational Reasoning](https://arxiv.org/abs/2207.08699)<br>:star:[code](https://github.com/FrancescoCappio/ReSeND)
* Multi-attribute Learning
  * [Label2Label: A Language Modeling Framework for Multi-Attribute Learning](https://arxiv.org/abs/2207.08677)<br>:star:[code](https://github.com/Li-Wanhua/Label2Label)
* 轨迹预测
  * [Action-based Contrastive Learning for Trajectory Prediction](https://arxiv.org/abs/2207.08664)
* 3D
  * [Towards High-Fidelity Single-view Holistic Reconstruction of Indoor Scenes](https://arxiv.org/abs/2207.08656)<br>:star:[code](https://github.com/UncleMEDM/InstPIFu)
  * [Self-calibrating Photometric Stereo by Neural Inverse Rendering](https://arxiv.org/abs/2207.07815)<br>:star:[code](https://github.com/junxuan-li/SCPS-NIR)
* GAN
  * [FakeCLR: Exploring Contrastive Learning for Solving Latent Discontinuity in Data-Efficient GANs](https://arxiv.org/abs/2207.08630)<br>:star:[code](https://github.com/iceli1007/FakeCLR)
* 类增量
  * [Class-incremental Novel Class Discovery](https://arxiv.org/abs/2207.08605)<br>:star:[code](https://github.com/OatmealLiu/class-iNCD)
* 小样本分割
  * [Dense Cross-Query-and-Support Attention Weighted Mask Aggregation for Few-Shot Segmentation](https://arxiv.org/abs/2207.08549)<br>:star:[code](https://github.com/pawn-sxy/DCAMA)
* 目标检测
  * [DID-M3D: Decoupling Instance Depth for Monocular 3D Object Detection](https://arxiv.org/abs/2207.08531)<br>:star:[code](https://github.com/SPengLiang/DID-M3D)
  * [SPSN: Superpixel Prototype Sampling Network for RGB-D Salient Object Detection](https://arxiv.org/abs/2207.07898)<br>:star:[code](https://github.com/Hydragon516/SPSN)
  * [You Should Look at All Objects](https://arxiv.org/abs/2207.07889)<br>:star:[code](https://github.com/CharlesPikachu/YSLAO)
* VOS
  * [Hierarchical Feature Alignment Network for Unsupervised Video Object Segmentation](https://arxiv.org/abs/2207.08485)<br>:star:[code](https://github.com/NUST-Machine-Intelligence-Laboratory/HFAN)
  * [Learning Quality-aware Dynamic Memory for Video Object Segmentation](https://arxiv.org/abs/2207.07922)<br>:star:[code](https://github.com/workforai/QDMN)
* 分割
  * [Open-world Semantic Segmentation via Contrasting and Clustering Vision-Language Embedding](https://arxiv.org/abs/2207.08455)
* OCR
  * [Real-time End-to-End Video Text Spotter with Contrastive Representation Learning](https://arxiv.org/abs/2207.08417)<br>:star:[code](https://github.com/weijiawu/CoText)
* 数据增强
  * [TokenMix: Rethinking Image Mixing for Data Augmentation in Vision Transformers](https://arxiv.org/abs/2207.08409)<br>:star:[code](https://github.com/Sense-X/TokenMix)
* 渲染
  * [MPIB: An MPI-Based Bokeh Rendering Framework for Realistic Partial Occlusion Effects](https://arxiv.org/abs/2207.08403)<br>:star:[code](https://github.com/JuewenPeng/MPIB):house:[project](https://juewenpeng.github.io/MPIB/)
* 对比学习
  * [Adversarial Contrastive Learning via Asymmetric InfoNCE](https://arxiv.org/abs/2207.08374)<br>:star:[code](https://github.com/yqy2001/A-InfoNCE)
  * [Fast-MoCo: Boost Momentum-based Contrastive Learning with Combinatorial Patches](https://arxiv.org/abs/2207.08220)<br>:star:[code](https://github.com/orashi/Fast-MoCo)
* 图像增强
  * [SepLUT: Separable Image-adaptive Lookup Tables for Real-time Image Enhancement](https://arxiv.org/abs/2207.08351)
* 增量学习
  * [Learning with Recoverable Forgetting](https://arxiv.org/abs/2207.08224)
* 时序动作检测
  * [Zero-Shot Temporal Action Detection via Vision-Language Prompting](https://arxiv.org/abs/2207.08184)<br>:star:[code](https://github.com/sauradip/STALE)
* 对抗攻击
  * [Watermark Vaccine: Adversarial Attacks to Prevent Watermark Removal](https://arxiv.org/abs/2207.08178)<br>:star:[code](https://github.com/thinwayliu/Watermark-Vaccine)
* VL
  * [FashionViL: Fashion-Focused Vision-and-Language Representation Learning](https://arxiv.org/abs/2207.08150)<br>:star:[code](https://github.com/BrandonHanx/mmf)
* 视频表征
  * [E-NeRV: Expedite Neural Video Representation with Disentangled Spatial-Temporal Context](https://arxiv.org/abs/2207.08132)<br>:star:[code](https://github.com/kyleleey/E-NeRV)
* 9D
  * [CATRE: Iterative Point Clouds Alignment for Category-level Object Pose Refinement](https://arxiv.org/abs/2207.08082)<br>:star:[code](https://github.com/THU-DA-6D-Pose-Group/CATRE)
* image retouching
  * [Neural Color Operators for Sequential Image Retouching](https://arxiv.org/abs/2207.08080)<br>:star:[code](https://github.com/amberwangyili/neurop)
* retinal image matching(视网膜图像匹配)
  * [Semi-Supervised Keypoint Detector and Descriptor for Retinal Image Matching](https://arxiv.org/abs/2207.07932)<br>:star:[code](https://github.com/ruc-aimc-lab/SuperRetina)
* 深度估计
  * [JPerceiver: Joint Perception Network for Depth, Pose and Layout Estimation in Driving Scenes](https://arxiv.org/abs/2207.07895)<br>:star:[code](https://github.com/sunnyHelen/JPerceiver)
* NAS
  * [CLOSE: Curriculum Learning On the Sharing Extent Towards Better One-shot NAS](https://arxiv.org/abs/2207.07868)<br>:star:[code](https://github.com/walkerning/aw_nas)
* 文本-视频检索
  * [TS2-Net: Token Shift and Selection Transformer for Text-Video Retrieval](https://arxiv.org/abs/2207.07852)<br>:star:[code](https://github.com/yuqi657/ts2_net)
* 小样本
  * [Cross-Domain Cross-Set Few-Shot Learning via Learning Compact and Aligned Representations](https://arxiv.org/abs/2207.07826)<br>:star:[code](https://github.com/WentaoChen0813/CDCS-FSL)
* 目标定位
  * [Bagging Regional Classification Activation Maps for Weakly Supervised Object Localization](https://arxiv.org/abs/2207.07818)<br>:star:[code](https://github.com/zh460045050/BagCAMs)
* 有源扬声器检测(视频会议)
  * [Learning Long-Term Spatial-Temporal Graphs for Active Speaker Detection](https://arxiv.org/abs/2207.07783)<br>:star:[code](https://github.com/SRA2/SPELL)
* 物体姿势估计
  * [TransGrasp: Grasp Pose Estimation of a Category of Objects by Transferring Grasps from Only One Labeled Instance](https://arxiv.org/abs/2207.07861)<br>:star:[code](https://github.com/yanjh97/TransGrasp)
* 其它
  * [NeFSAC: Neurally Filtered Minimal Samples](https://arxiv.org/abs/2207.07872)<br>:star:[code](https://github.com/cavalli1234/NeFSAC)
  * [Towards Understanding The Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search](https://arxiv.org/abs/2207.08350)
  * [Latency-Aware Collaborative Perception](https://arxiv.org/abs/2207.08560)<br>:star:[code](https://github.com/MediaBrain-SJTU/SyncNet)



* human relighting
  * [Geometry-aware Single-image Full-body Human Relighting](https://arxiv.org/abs/2207.04750)
* 奇异值检测(Novelty Detection)
  * [Semantic Novelty Detection via Relational Reasoning](https://arxiv.org/abs/2207.08699)<br>:star:[code](https://github.com/FrancescoCappio/ReSeND)
* Multi-attribute Learning
  * [Label2Label: A Language Modeling Framework for Multi-Attribute Learning](https://arxiv.org/abs/2207.08677)<br>:star:[code](https://github.com/Li-Wanhua/Label2Label)
## 光学、几何、光场成像
* 相机姿势
  * [Camera Pose Auto-Encoders for Improving Pose Regression](https://arxiv.org/abs/2207.05530)<br>:star:[code](https://github.com/yolish/camera-pose-auto-encoders)

## Data Augmentation(数据增强)
* [TokenMix: Rethinking Image Mixing for Data Augmentation in Vision Transformers](https://arxiv.org/abs/2207.08409)<br>:star:[code](https://github.com/Sense-X/TokenMix)

## Sound
* 视听分割
  * [Audio-Visual Segmentation](https://arxiv.org/abs/2207.05042)<br>:star:[code](https://github.com/OpenNLPLab/AVSBench)
* 语音合成
  * [VisageSynTalk: Unseen Speaker Video-to-Speech Synthesis via Speech-Visage Feature Selection](https://arxiv.org/abs/2206.07458)

## Style Transfer(风格迁移)
* [CCPL: Contrastive Coherence Preserving Loss for Versatile Style Transfer](https://arxiv.org/abs/2207.04808)<br>:open_mouth:oral:star:[code](https://github.com/JarrentWu1031/CCPL)


## Dataset(数据集)
* [COO: Comic Onomatopoeia Dataset for Recognizing Arbitrary or Truncated Texts](https://arxiv.org/abs/2207.04675)<br>:star:[code](https://github.com/ku21fan/COO-Comic-Onomatopoeia)<br>用于识别任意或截断文本的漫画拟声词数据集



## Scene Flow Estimation(场景流估计)
* [Bi-PointFlowNet: Bidirectional Learning for Point Cloud Based Scene Flow Estimation](https://arxiv.org/abs/2207.07522)<br>:star:[code](https://github.com/cwc1260/BiFlow)
 
## Anomaly Detection(异常检测)
* [Registration based Few-Shot Anomaly Detection](https://arxiv.org/abs/2207.07361)<br>:open_mouth:oral:star:[code](https://github.com/MediaBrain-SJTU/RegAD)
## 渲染
* [Relighting4D: Neural Relightable Human from Videos](https://arxiv.org/abs/2207.07104)<br>:star:[code](https://github.com/FrozenBurning/Relighting4D):house:[project](https://frozenburning.github.io/projects/relighting4d/):tv:[video](https://www.youtube.com/watch?v=NayAw89qtsY)
* [MPIB: An MPI-Based Bokeh Rendering Framework for Realistic Partial Occlusion Effects](https://arxiv.org/abs/2207.08403)<br>:star:[code](https://github.com/JuewenPeng/MPIB):house:[project](https://juewenpeng.github.io/MPIB/) 

## Few/Zero-Shot Learning/Domain Generalization/Adaptation(小/零样本/域泛化/适应)
* 小样本
  * [Cross-Domain Cross-Set Few-Shot Learning via Learning Compact and Aligned Representations](https://arxiv.org/abs/2207.07826)<br>:star:[code](https://github.com/WentaoChen0813/CDCS-FSL)


## Semantic Correspondence(语义对应)
* [Demystifying Unsupervised Semantic Correspondence Estimation](https://arxiv.org/abs/2207.05054)<br>:star:[code](https://github.com/MehmetAygun/demistfy_correspondence):house:[project](https://mehmetaygun.github.io/demistfy.html)

## Incremental Learning(增量学习)
* [Learning with Recoverable Forgetting](https://arxiv.org/abs/2207.08224)
* 类增量
  * [Class-incremental Novel Class Discovery](https://arxiv.org/abs/2207.08605)<br>:star:[code](https://github.com/OatmealLiu/class-iNCD) 


## Adversarial  Learning(对抗学习)
* 对抗攻击
  * [Frequency Domain Model Augmentation for Adversarial Attack](https://arxiv.org/abs/2207.05382)<br>:star:[code](https://github.com/yuyang-long/SSA)
  * [Watermark Vaccine: Adversarial Attacks to Prevent Watermark Removal](https://arxiv.org/abs/2207.08178)<br>:star:[code](https://github.com/thinwayliu/Watermark-Vaccine)

## Transfer Learning(迁移学习)
* [Factorizing Knowledge in Neural Networks](https://arxiv.org/abs/2207.03337)<br>:star:[code](https://github.com/Adamdad/KnowledgeFactor)

## Contrastive Learning(对比学习)
* [Network Binarization via Contrastive Learning](https://arxiv.org/abs/2207.02970)
* [Adversarial Contrastive Learning via Asymmetric InfoNCE](https://arxiv.org/abs/2207.08374)<br>:star:[code](https://github.com/yqy2001/A-InfoNCE)
* [Fast-MoCo: Boost Momentum-based Contrastive Learning with Combinatorial Patches](https://arxiv.org/abs/2207.08220)<br>:star:[code](https://github.com/orashi/Fast-MoCo)

## Open-set Recognition(开集识别)
* [DenseHybrid: Hybrid Anomaly Detection for Dense Open-set Recognition](https://arxiv.org/abs/2207.02606)

## Machine Learning(机器学习)
* [Predicting is not Understanding: Recognizing and Addressing Underspecification in Machine Learning](https://arxiv.org/abs/2207.02598)


## Feature Learning(联邦学习)
* [Image Coding for Machines with Omnipotent Feature Learning](https://arxiv.org/abs/2207.01932)


## Model Compression/Knowledge Distillation/Pruning(模型压缩/知识蒸馏/剪枝)
* 知识蒸馏
  * [Knowledge Condensation Distillation](https://arxiv.org/abs/2207.05409)<br>:star:[code](https://github.com/dzy3/KCD)
* 量化
  * [Synergistic Self-supervised and Quantization Learning](https://arxiv.org/abs/2207.05432)<br>:open_mouth:oral:star:[code](https://github.com/megvii-research/SSQL-ECCV2022)

## Point Cloud(点云)
* [Few 'Zero Level Set'-Shot Learning of Shape Signed Distance Functions in Feature Space](https://arxiv.org/abs/2207.04161)
* 点云定位
  * [CPO: Change Robust Panorama to Point Cloud Localization](https://arxiv.org/abs/2207.05317)


## SLAM/Augmented Reality/Virtual Reality/Robotics(增强/虚拟现实/机器人)
* VR
  * human volumetric capture(容积捕获)
    * [AvatarCap: Animatable Avatar Conditioned Monocular Human Volumetric Capture](https://arxiv.org/abs/2207.02031)<br>:star:[code](https://github.com/lizhe00/AvatarCap):house:[project](http://www.liuyebin.com/avatarcap/avatarcap.html)

## Neural Architecture Search(神经架构搜索)
* [SuperTickets: Drawing Task-Agnostic Lottery Tickets from Supernets via Jointly Architecture Searching and Parameter Pruning](https://arxiv.org/abs/2207.03677)<br>:star:[code](https://github.com/RICE-EIC/SuperTickets)
* [UniNet: Unified Architecture Search with Convolution, Transformer, and MLP](https://arxiv.org/abs/2207.05420)<br>:star:[code](https://github.com/Sense-X/UniNet)
* [ScaleNet: Searching for the Model to Scale](https://arxiv.org/abs/2207.07267)<br>:star:[code](https://github.com/luminolx/ScaleNet)
* [CLOSE: Curriculum Learning On the Sharing Extent Towards Better One-shot NAS](https://arxiv.org/abs/2207.07868)<br>:star:[code](https://github.com/walkerning/aw_nas)

## Image Classification(图像分类)
* 小样本图像分类
  * [Tree Structure-Aware Few-Shot Image Classification via Hierarchical Aggregation](https://arxiv.org/abs/2207.06989)<br>:star:[code](https://github.com/remiMZ/HTS-ECCV22) 


## 25.Autonomous vehicles(自动驾驶)
* 车辆轨迹预测
  * [Hierarchical Latent Structure for Multi-Modal Vehicle Trajectory Forecasting](https://arxiv.org/abs/2207.04624)<br>:star:[code](https://github.com/d1024choi/HLSTrajForecast)
  * [Action-based Contrastive Learning for Trajectory Prediction](https://arxiv.org/abs/2207.08664)
* 自动驾驶
  * [ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning](https://arxiv.org/abs/2207.07601)<br>:star:[code](https://github.com/OpenPerceptionX/ST-P3)

<a name="24"/>

## 24.UAV/Remote Sensing/Satellite Image(无人机/遥感/卫星图像)

<a name="23"/>

## 23.Medical Image(医学影像)
* 医学图像分割
  * [Personalizing Federated Medical Image Segmentation via Local Calibration](https://arxiv.org/abs/2207.04655)<br>:star:[code](https://github.com/jcwang123/FedLC)
* 放射科报告生成
  * [Cross-modal Prototype Driven Network for Radiology Report Generation](https://arxiv.org/abs/2207.04818)<br>:star:[code](https://github.com/Markin-Wang/XProNet)
* 密集预测
  * [ConCL: Concept Contrastive Learning for Dense Prediction Pre-training in Pathology Images](https://arxiv.org/abs/2207.06733)<br>:star:[code](https://github.com/TencentAILabHealthcare/ConCL)
* retinal image matching(视网膜图像匹配)
  * [Semi-Supervised Keypoint Detector and Descriptor for Retinal Image Matching](https://arxiv.org/abs/2207.07932)<br>:star:[code](https://github.com/ruc-aimc-lab/SuperRetina)


<a name="22"/>

## 22.OCR
* 文本识别
  * [Text-DIAE: Degradation Invariant Autoencoders for Text Recognition and Document Enhancement](https://arxiv.org/abs/2203.04814)
* 手写数学表达式识别
  * [CoMER: Modeling Coverage for Transformer-based Handwritten Mathematical Expression Recognition](https://arxiv.org/abs/2207.04410)<br>:star:[code](https://github.com/Green-Wood/CoMER)
* 场景文本检测
  * [Scene Text Recognition with Permuted Autoregressive Sequence Models](https://arxiv.org/abs/2207.06966)<br>:star:[code](https://github.com/baudm/parseq)
  * [Dynamic Low-Resolution Distillation for Cost-Efficient End-to-End Text Spotting](https://arxiv.org/abs/2207.06694)<br>:star:[code](https://github.com/hikopensource/DAVAR-Lab-OCR/)
* 视频文本检测
  * [Real-time End-to-End Video Text Spotter with Contrastive Representation Learning](https://arxiv.org/abs/2207.08417)<br>:star:[code](https://github.com/weijiawu/CoText)

<a name="21"/>

## 21.Semi/self-supervised learning(半/自监督)
* 半监督
  * [Towards Realistic Semi-Supervised Learning](https://arxiv.org/abs/2207.02269)
  * [OpenLDN: Learning to Discover Novel Classes for Open-World Semi-Supervised Learning](https://arxiv.org/abs/2207.02261)
* 监督学习
  * [Supervised Attribute Information Removal and Reconstruction for Image Manipulation](https://arxiv.org/abs/2207.06555)<br>:star:[code](https://github.com/NannanLi999/AIRR)


<a name="20"/>

## 20.Face(人脸)
* deepfake检测
  * [Detecting and Recovering Sequential DeepFake Manipulation](https://arxiv.org/abs/2207.02204)<br>:star:[code](https://github.com/rshaojimmy/SeqDeepFake):house:[project](https://rshaojimmy.github.io/Projects/SeqDeepFake)

<a name="19"/>

## 19.Image Synthesis/Generation(图像合成)
* 样本引导下的图像生成
  * [DynaST: Dynamic Sparse Transformer for Exemplar-Guided Image Generation](https://arxiv.org/abs/2207.06124)<br>:star:[code](https://github.com/Huage001/DynaST)

<a name="18"/>

## 18.Image-to-Image Translation(图像到图像翻译)
* [VecGAN: Image-to-Image Translation with Interpretable Latent Directions](https://arxiv.org/abs/2207.03411)
* 图像翻译
  * [BayesCap: Bayesian Identity Cap for Calibrated Uncertainty in Frozen Neural Networks](https://arxiv.org/abs/2207.06873)<br>:star:[code](https://github.com/ExplainableML/BayesCap)


<a name="17"/>

## 17.GAN
* [RepMix: Representation Mixing for Robust Attribution of Synthesized Images](https://arxiv.org/abs/2207.02063)<br>:star:[code](https://github.com/TuBui/image_attribution)
* [FakeCLR: Exploring Contrastive Learning for Solving Latent Discontinuity in Data-Efficient GANs](https://arxiv.org/abs/2207.08630)<br>:star:[code](https://github.com/iceli1007/FakeCLR)
* 线稿上色
  * [Eliminating Gradient Conflict in Reference-based Line-Art Colorization](https://arxiv.org/abs/2207.06095)<br>:star:[code](https://github.com/kunkun0w0/SGA)
* 图像生成
  * [WaveGAN: Frequency-aware GAN for High-Fidelity Few-shot Image Generation](https://arxiv.org/abs/2207.07288)<br>:star:[code](https://github.com/kobeshegu/ECCV2022_WaveGAN)

<a name="16"/>

## 16.Transformer
* [k-means Mask Transformer](https://arxiv.org/abs/2207.04044)<br>:star:[code](https://github.com/google-research/deeplab2)
* [Outpainting by Queries](https://arxiv.org/abs/2207.05312)<br>:star:[code](https://github.com/Kaiseem/QueryOTR)

<a name="15"/>

## 15.Vision-Language(视觉语言)
* [FashionViL: Fashion-Focused Vision-and-Language Representation Learning](https://arxiv.org/abs/2207.08150)<br>:star:[code](https://github.com/BrandonHanx/mmf)
* 视觉表征学习
  * [Wave-ViT: Unifying Wavelet and Transformers for Visual Representation Learning](https://arxiv.org/abs/2207.04978)<br>:star:[code](https://github.com/YehLi/ImageNetModel)
  * [Unsupervised Visual Representation Learning by Synchronous Momentum Grouping](https://arxiv.org/abs/2207.06167)


<a name="14"/>

## 14.Visual Answer Questions(视觉问答)
* [Weakly Supervised Grounding for VQA in Vision-Language Transformers](https://arxiv.org/abs/2207.02334)<br>:star:[code](https://github.com/aurooj/WSG-VQA-VLTransformers)
* [Rethinking Data Augmentation for Robust Visual Question Answering](https://arxiv.org/abs/2207.08739)<br>:star:[code](https://github.com/ItemZheng/KDDAug)
* Video-QA
  * [Video Graph Transformer for Video Question Answering](https://arxiv.org/abs/2207.05342)<br>:star:[code](https://github.com/sail-sg/VGT)

<a name="13"/>

## 13.Human-Object Interaction(人物交互)
* [Towards Hard-Positive Query Mining for DETR-based Human-Object Interaction Detection](https://arxiv.org/abs/2207.05293)<br>:star:[code](https://github.com/MuchHair/HQM)


<a name="12"/>

## 12.Action Detection(人体动作检测与识别)
* 动作识别
  * 基于骨架动作识别
    * [Global-local Motion Transformer for Unsupervised Skeleton-based Action Learning](https://arxiv.org/abs/2207.06101)<br>:star:[code](https://github.com/Boeun-Kim/GL-Transformer)
  * 小样本动作识别
    * [Compound Prototype Matching for Few-shot Action Recognition](https://arxiv.org/abs/2207.05515)
* 社会群体活动识别
  * [Hunting Group Clues with Transformers for Social Group Activity Recognition](https://arxiv.org/abs/2207.05254)
  * [Entry-Flipped Transformer for Inference and Prediction of Participant Behavior](https://arxiv.org/abs/2207.06235)
* 时序动作检测
  * [Semi-Supervised Temporal Action Detection with Proposal-Free Masking](https://arxiv.org/abs/2207.07059)<br>:star:[code](https://github.com/sauradip/SPOT)
  * [Temporal Action Detection with Global Segmentation Mask Learning](https://arxiv.org/abs/2207.06580)<br>:star:[code](https://github.com/sauradip/TAGS)
  * [ReAct: Temporal Action Detection with Relational Queries](https://arxiv.org/abs/2207.07097)<br>:star:[code](https://github.com/sssste/React)
  * [Zero-Shot Temporal Action Detection via Vision-Language Prompting](https://arxiv.org/abs/2207.08184)<br>:star:[code](https://github.com/sauradip/STALE)

<a name="11"/>

## 11.Video
* 视频语义分割
  * [Domain Adaptive Video Segmentation via Temporal Pseudo Supervision](https://arxiv.org/abs/2207.02372)<br>:star:[code](https://github.com/xing0047/TPS)
* 视频-视频合成
  * [Fast-Vid2Vid: Spatial-Temporal Compression for Video-to-Video Synthesis](https://arxiv.org/abs/2207.05049)<br>:star:[code](https://github.com/fast-vid2vid/fast-vid2vid):house:[project](https://fast-vid2vid.github.io/)
* 视频质量评估
  * [FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling](https://arxiv.org/abs/2207.02595)<br>:star:[code](https://github.com/timothyhtimothy/FAST-VQA)
* 视频对话
  * [Video Dialog as Conversation about Objects Living in Space-Time](https://arxiv.org/abs/2207.03656)<br>:star:[code](https://github.com/hoanganhpham1006/COST)
* 有源扬声器检测(视频会议)
  * [Learning Long-Term Spatial-Temporal Graphs for Active Speaker Detection](https://arxiv.org/abs/2207.07783)<br>:star:[code](https://github.com/SRA2/SPELL)
* VOS
  * [XMem: Long-Term Video Object Segmentation with an Atkinson-Shiffrin Memory Model](https://arxiv.org/abs/2207.07115)<br>:star:[code](https://github.com/hkchengrex/XMem):house:[project](https://hkchengrex.github.io/XMem/):tv:[video](https://youtu.be/mwOP8l3zVNw)
  * [Tackling Background Distraction in Video Object Segmentation](https://arxiv.org/abs/2207.06953)<br>:star:[code](https://github.com/suhwan-cho/TBD)
  * [Hierarchical Feature Alignment Network for Unsupervised Video Object Segmentation](https://arxiv.org/abs/2207.08485)<br>:star:[code](https://github.com/NUST-Machine-Intelligence-Laboratory/HFAN)
  * [Learning Quality-aware Dynamic Memory for Video Object Segmentation](https://arxiv.org/abs/2207.07922)<br>:star:[code](https://github.com/workforai/QDMN)
* 视频表征
  * [E-NeRV: Expedite Neural Video Representation with Disentangled Spatial-Temporal Context](https://arxiv.org/abs/2207.08132)<br>:star:[code](https://github.com/kyleleey/E-NeRV) 


<a name="10"/>

## 10.Pose Estimation(物体姿势估计)
* 抓取物体姿势估计
  * [TransGrasp: Grasp Pose Estimation of a Category of Objects by Transferring Grasps from Only One Labeled Instance](https://arxiv.org/abs/2207.07861)<br>:star:[code](https://github.com/yanjh97/TransGrasp)
* 6D
  * [Category-Level 6D Object Pose and Size Estimation using Self-Supervised Deep Prior Deformation Networks](https://arxiv.org/abs/2207.05444)<br>:star:[code](https://github.com/JiehongLin/Self-DPDN)
* 9D
  * [CATRE: Iterative Point Clouds Alignment for Category-level Object Pose Refinement](https://arxiv.org/abs/2207.08082)<br>:star:[code](https://github.com/THU-DA-6D-Pose-Group/CATRE)

<a name="9"/>

## 9.Human Pose Estimation(人体姿态估计)
* [Self-Constrained Inference Optimization on Structural Groups for Human Pose Estimation](https://arxiv.org/abs/2207.02425)
* 运动捕捉
  * [TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts](https://arxiv.org/abs/2207.01696)<br>:star:[code](https://github.com/EricGuo5513/TM2T):house:[project](https://ericguo5513.github.io/TM2T/)
* 基于点的衣着人体建模
  * [Learning Implicit Templates for Point-Based Clothed Human Modeling](https://arxiv.org/abs/2207.06955)<br>:star:[code](https://github.com/jsnln/fite):house:[project](https://jsnln.github.io/fite/)

<a name="8"/>

## 8.3D(三维视觉)
* [DeepPS2: Revisiting Photometric Stereo Using Two Differently Illuminated Images](https://arxiv.org/abs/2207.02025)
* [Towards High-Fidelity Single-view Holistic Reconstruction of Indoor Scenes](https://arxiv.org/abs/2207.08656)<br>:star:[code](https://github.com/UncleMEDM/InstPIFu)
* [Self-calibrating Photometric Stereo by Neural Inverse Rendering](https://arxiv.org/abs/2207.07815)<br>:star:[code](https://github.com/junxuan-li/SCPS-NIR)
* 3D场景合成
  * [Simple and Effective Synthesis of Indoor 3D Scenes](https://arxiv.org/abs/2204.02960)<br>:tv:[video](https://www.youtube.com/watch?v=lhwwlrRfFp0)
* 深度估计
  * [Physical Attack on Monocular Depth Estimation with Optimal Adversarial Patches](https://arxiv.org/abs/2207.04718)
  * [Towards Scale-Aware, Robust, and Generalizable Unsupervised Monocular Depth Estimation by Integrating IMU Motion Dynamics](https://arxiv.org/abs/2207.04680)<br>:star:[code](https://github.com/SenZHANG-GitHub/ekf-imu-depth)
  * [JPerceiver: Joint Perception Network for Depth, Pose and Layout Estimation in Driving Scenes](https://arxiv.org/abs/2207.07895)<br>:star:[code](https://github.com/sunnyHelen/JPerceiver)
* 三维视觉
  * [A Closer Look at Invariances in Self-supervised Pre-training for 3D Vision](https://arxiv.org/abs/2207.04997)

<a name="7"/>

## 7.Object Tracking(目标跟踪)
* [Towards Grand Unification of Object Tracking](https://arxiv.org/abs/2207.07078)<br>:open_mouth:oral:star:[code](https://github.com/MasterBin-IIAU/Unicorn)
* 多目标跟踪
  * [Tracking Objects as Pixel-wise Distributions](https://arxiv.org/abs/2207.05518)<br>:open_mouth:oral

<a name="6"/>

## 6.Object Detection(目标检测)
* [Should All Proposals be Treated Equally in Object Detection?](https://arxiv.org/abs/2207.03520)<br>:star:[code](https://github.com/liyunsheng13/dpp)
* [HEAD: HEtero-Assists Distillation for Heterogeneous Object Detectors](https://arxiv.org/abs/2207.05345)<br>:star:[code](https://github.com/LutingWang/HEAD)
* [Adversarially-Aware Robust Object Detector](https://arxiv.org/abs/2207.06202)<br>:open_mouth:oral:star:[code](https://github.com/7eu7d7/RobustDet)
* [ObjectBox: From Centers to Boxes for Anchor-Free Object Detection](https://arxiv.org/abs/2207.06985)<br>:open_mouth:oral:star:[code](https://github.com/MohsenZand/ObjectBox)
* [Point-to-Box Network for Accurate Object Detection via Single Point Supervision](https://arxiv.org/abs/2207.06827)<br>:star:[code](https://github.com/ucas-vg/P2BNet)
* [You Should Look at All Objects](https://arxiv.org/abs/2207.07889)<br>:star:[code](https://github.com/CharlesPikachu/YSLAO)
* [Class-agnostic Object Detection with Multi-modal Transformer](https://arxiv.org/abs/2111.11430)<br>:star:[code](https://github.com/mmaaz60/mvits_for_class_agnostic_od)<br>使用多模态 ViTs 和人类可理解的文本查询来生成高质量的OP
* 半监督目标检测
  * [Dense Teacher: Dense Pseudo-Labels for Semi-supervised Object Detection](https://arxiv.org/abs/2207.02541)<br>:star:[code](https://github.com/Megvii-BaseDetection/DenseTeacher)
* 显著目标检测  
  * [SESS: Saliency Enhancing with Scaling and Sliding](https://arxiv.org/abs/2207.01769)<br>:star:[code](https://github.com/neouyghur/SESS)
  * [SPSN: Superpixel Prototype Sampling Network for RGB-D Salient Object Detection](https://arxiv.org/abs/2207.07898)<br>:star:[code](https://github.com/Hydragon516/SPSN)
* 目标定位
  * [Bagging Regional Classification Activation Maps for Weakly Supervised Object Localization](https://arxiv.org/abs/2207.07818)<br>:star:[code](https://github.com/zh460045050/BagCAMs)
* 3D目标检测
  * [DID-M3D: Decoupling Instance Depth for Monocular 3D Object Detection](https://arxiv.org/abs/2207.08531)<br>:star:[code](https://github.com/SPengLiang/DID-M3D)
  
<a name="5"/>

## 5.Image/Video Retrieval(图像/视频检索)
* 图像检索
  * [Hierarchical Average Precision Training for Pertinent Image Retrieval](https://arxiv.org/abs/2207.04873)<br>:star:[code](https://github.com/elias-ramzi/HAPPIER)
  * [Adaptive Fine-Grained Sketch-Based Image Retrieval](https://arxiv.org/abs/2207.01723)<br>:star:[code](https://github.com/AyanKumarBhunia/Adaptive-FGSBIR)
* 视频检索
  * Video Geo-localization(检索)
    * [GAMa: Cross-view Video Geo-localization](https://arxiv.org/abs/2207.02431)<br>:star:[code](https://github.com/svyas23/GAMa)
* 文本-视频检索
  * [TS2-Net: Token Shift and Selection Transformer for Text-Video Retrieval](https://arxiv.org/abs/2207.07852)<br>:star:[code](https://github.com/yuqi657/ts2_net)

<a name="4"/>

## 4.Image Captioning(图像字幕)

<a name="3"/>

## 3.Image Progress(图像处理)
* 图像修补(image retouching)
  * [Neural Color Operators for Sequential Image Retouching](https://arxiv.org/abs/2207.08080)<br>:star:[code](https://github.com/amberwangyili/neurop)
* 图像变形(Image Warping)
  * [Learning Local Implicit Fourier Representation for Image Warping](https://arxiv.org/abs/2207.01831)<br>:star:[code](https://github.com/jaewon-lee-b/ltew)
* 图像恢复
  * [D2HNet: Joint Denoising and Deblurring with Hierarchical Network for Robust Night Image Restoration](https://arxiv.org/abs/2207.03294)<br>:star:[code](https://github.com/zhaoyuzhi/D2HNet)
* 图像增强
  * [SepLUT: Separable Image-adaptive Lookup Tables for Real-time Image Enhancement](https://arxiv.org/abs/2207.08351)
* 图像和谐化 
  * [DCCF: Deep Comprehensible Color Filter Learning Framework for High-Resolution Image Harmonization](https://arxiv.org/abs/2207.04788)<br>:open_mouth:oral:star:[code](https://github.com/rockeyben/DCCF)
* 语义图像编辑
  * [Context-Consistent Semantic Image Editing with Style-Preserved Modulation](https://arxiv.org/abs/2207.06252)<br>:star:[code](https://github.com/WuyangLuo/SPMPGAN)

<a name="2"/>

## 2.Image Segmentation(图像分割)
* [PseudoClick: Interactive Image Segmentation with Click Imitation](https://arxiv.org/abs/2207.05282)
* 语义分割
  * [2DPASS: 2D Priors Assisted Semantic Segmentation on LiDAR Point Clouds](https://arxiv.org/abs/2207.04397)<br>:star:[code](https://github.com/yanx27/2DPASS)
  * [Open-world Semantic Segmentation via Contrasting and Clustering Vision-Language Embedding](https://arxiv.org/abs/2207.08455)
* 实例分割 
  * [OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers](https://arxiv.org/abs/2207.02255)<br>:star:[code](https://github.com/PJLallen/OSFormer)
  * [3D Instances as 1D Kernels](https://arxiv.org/abs/2207.07372)<br>:star:[code](https://github.com/W1zheng/DKNet)
* 小样本分割
  * [Dense Cross-Query-and-Support Attention Weighted Mask Aggregation for Few-Shot Segmentation](https://arxiv.org/abs/2207.08549)<br>:star:[code](https://github.com/pawn-sxy/DCAMA)

<a name="1"/>

## 1.其它
* [Differentiable Rendering for Synthetic Aperture Radar Imagery](https://arxiv.org/abs/2204.01248)
* [Batch-efficient EigenDecomposition for Small and Medium Matrices](https://arxiv.org/abs/2207.04228)<br>:star:[code](https://github.com/KingJamesSong/BatchED)
* [Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling](https://arxiv.org/abs/2207.02196)
* [Improving Covariance Conditioning of the SVD Meta-layer by Orthogonality](https://arxiv.org/abs/2207.02119)<br>:star:[code](https://github.com/KingJamesSong/OrthoImproveCond)
* [Contrastive Deep Supervision](https://arxiv.org/abs/2207.05306)<br>:star:[code](https://github.com/ArchipLab-LinfengZhang/contrastive-deep-supervision)
* [Organic Priors in Non-Rigid Structure from Motion](https://arxiv.org/abs/2207.06262)<br>:open_mouth:oral
* [Bootstrapped Masked Autoencoders for Vision BERT Pretraining](https://arxiv.org/abs/2207.07116)<br>:star:[code](https://github.com/LightDXY/BootMAE)
* [Lipschitz Continuity Retained Binary Neural Network](https://arxiv.org/abs/2207.06540)<br>:star:[code](https://github.com/42Shawn/LCR_BNN)
* [NeFSAC: Neurally Filtered Minimal Samples](https://arxiv.org/abs/2207.07872)<br>:star:[code](https://github.com/cavalli1234/NeFSAC)
* [Towards Understanding The Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search](https://arxiv.org/abs/2207.08350)
* [Latency-Aware Collaborative Perception](https://arxiv.org/abs/2207.08560)<br>:star:[code](https://github.com/MediaBrain-SJTU/SyncNet)

扫码CV君微信（注明：CVPR）入微信交流群：
![image](https://user-images.githubusercontent.com/62801906/178399331-6a7c8997-b0d0-49a1-8fd7-4f1202d46382.png)
