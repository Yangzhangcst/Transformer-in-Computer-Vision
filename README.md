Transformer-in-Vision[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A paper list of some recent Transformer-based CV works. If you find some ignored papers, please open issues or pull requests.

The list is too long and unreadable. A version update will be made as soon as possible in the future.

**Last updated: 2024/03/24

## Table of Contents

- [Survey](main/survey.md)
- [Recent Papers](#recent-papers)
  - [Action](main/action.md)
  - [Active Learning](main/active-learning.md)
  - [Adversarial Attacks](main/adversarial-attacks.md)
  - [Anomaly Detection](main/anomaly-detection.md)
  - [Assessment](main/assessment.md)
  - [Augmentation](main/augmentation.md)
  - [Audio](main/audio.md)
  - [Bird's-Eye-View](main/birds-eye-view.md)
  - [Captioning](main/captioning.md)
  - [Change Detection](main/change-detection.md)
  - [Classification (Backbone.md)](main/classification-backbone.md)
  - [Clustering](main/clustering.md)
  - [Completion](main/completion.md)
  - [Compression](main/compression.md)
  - [Cross-view](main/cross-view.md)
  - [Crowd](main/crowd.md)
  - [Deblurring](main/deblurring.md)
  - [Depth](main/depth.md)
  - [Deepfake Detection](main/deepfake-detection.md)
  - [Dehazing](main/dehazing.md)
  - [Deraining](main/deraining.md)
  - [Denoising](main/denoising.md)
  - [Detection](main/detection.md)
  - [Diffusion](main/diffusion.md)
  - [Edge](main/edge.md)
  - [Enhancement](main/enhancement.md)
  - [Face](main/face.md)
  - [Federated Learning](main/federated-learning.md)
  - [Few-shot Learning](main/few-shot-learning.md)
  - [Fusion](main/fusion.md)
  - [Gait](main/gait.md)
  - [Gaze](main/gaze.md)
  - [Generative Model](main/generative-model.md)
  - [Graph](main/graph.md)
  - [Hand Gesture](main/hand-gesture.md)
  - [High Dynamic Range Imaging](main/high-dynamic-range-imaging.md)
  - [HOI](main/hoi.md)
  - [Hyperspectral](main/hyperspectral.md)
  - [Illumination](main/illumination.md)
  - [Incremental Learning](main/incremental-learning.md)
  - [In-painting](main/in-painting.md)
  - [Instance Segmentation](main/instance-segmentation.md)
  - [Knowledge Distillation](main/knowledge-distillation.md)
  - [Lane](main/lane.md)
  - [Layout](main/layout.md)
  - [Lighting](main/lighting.md)
  - [LLM](main/llmlvm.md)
  - [Matching](main/matching.md)
  - [Matting](main/matting.md)
  - [Medical](main/medical.md)
  - [Mesh](main/mesh.md)
  - [Metric learning](main/metric-learning.md)
  - [Motion](main/motion.md)
  - [Multi-label](main/multi-label.md)
  - [Multi-task/modal](main/multi-taskmodal.md)
  - [Multi-view Stereo](main/multi-view-stereo.md)
  - [NAS](main/nas.md)
  - [Navigation](main/navigation.md)
  - [Neural Rendering](main/neural-rendering.md)
  - [OCR](main/ocr.md)
  - [Octree](main/octree.md)
  - [Open World](main/open-world.md)
  - [Optical Flow](main/optical-flow.md)
  - [Panoptic Segmentation](main/panoptic-segmentation.md)
  - [Point Cloud](main/point-cloud.md)
  - [Pose](main/pose.md)
  - [Planning](main/planning.md)
  - [Pruning & Quantization](main/pruning--quantization.md)
  - [Recognition](main/recognition.md)
  - [Reconstruction](main/reconstruction.md)
  - [Referring](main/referring.md)
  - [Registration](main/registration.md)
  - [Re-identification](main/re-identification.md)
  - [Remote Sensing](main/remote-sensing.md)
  - [Restoration](main/restoration.md)
  - [Retrieval](main/retrieval.md)
  - [Robotic](main/robotic.md)
  - [Salient Detection](main/salient-detection.md)
  - [Scene](main/scene.md)
  - [Self-supervised Learning](main/self-supervised-learning.md)
  - [Semantic Segmentation](main/semantic-segmentation.md)
  - [Shape](main/shape.md)
  - [SLAM](main/slam.md)
  - [SNN](main/snn.md)
  - [Style Transfer](main/style-transfer.md)
  - [Super-Resolution](main/super-resolution.md)
  - [Synthesis](main/synthesis.md)
  - [Text-to-Image/Video](main/text-to-imagevideo.md)
  - [Texture](main/texture.md)
  - [Time Series](main/time-series.md)
  - [Tracking](main/tracking.md)
  - [Traffic](main/traffic.md)
  - [Transfer learning](main/transfer-learning.md)
  - [Translation](main/translation.md)
  - [Unsupervised learning](main/unsupervised-learning.md)
  - [UAV](main/uav.md)
  - [Video](main/video.md)
  - [Visual Grounding](main/visual-grounding.md)
  - [Visual Question Answering](main/visual-question-answering.md)
  - [Visual Reasoning](main/visual-reasoning.md)
  - [Visual Relationship Detection](main/visual-relationship-detection.md)
  - [Voxel](main/voxel.md)
  - [Weakly Supervised Learning](main/weakly-supervised-learning.md)
  - [Zero-Shot Learning](main/zero-shot-learning.md)
  - [Others](main/others.md)
- [Contact & Feedback](#contact--feedback)

  
## Survey: 
- (arXiv 2024.03) A Survey of Vision Transformers in Autonomous Driving: Current Trends and Future Directions. [[Paper]](https://arxiv.org/pdf/2403.07542.pdf)

- (arXiv 2024.02) A Survey on Transformer Compression. [[Paper]](https://arxiv.org/pdf/2402.05964.pdf)

- (arXiv 2024.02) Exploring the Synergies of Hybrid CNNs and ViTs Architectures for Computer Vision: A survey. [[Paper]](https://arxiv.org/pdf/2402.02941.pdf)

- (arXiv 2024.01) Transformer for Object Re-Identification: A Survey. [[Paper]](https://arxiv.org/pdf/2401.06960.pdf)

- (arXiv 2023.12) A Comprehensive Study of Vision Transformers in Image Classification Tasks. [[Paper]](https://arxiv.org/pdf/2312.01232.pdf)

- (arXiv 2023.12) A Recent Survey of Vision Transformers for Medical Image Segmentation. [[Paper]](https://arxiv.org/pdf/2312.00634.pdf)

- (arXiv 2023.11) Explainability of Vision Transformers: A Comprehensive Review and New Perspectives. [[Paper]](https://arxiv.org/pdf/2311.06786.pdf)

- (arXiv 2023.10) Understanding Video Transformers for Segmentation: A Survey of Application and Interpretability. [[Paper]](https://arxiv.org/pdf/2310.12296.pdf)

- (arXiv 2023.10) Unsupervised Object Localization in the Era of Self-Supervised ViTs: A Survey. [[Paper]](https://arxiv.org/pdf/2310.12904.pdf), [[Awesome]](https://github.com/valeoai/Awesome-Unsupervised-Object-Localization)

- (arXiv 2023.09) Transformers in Small Object Detection: A Benchmark and Survey of State-of-the-Art. [[Paper]](https://arxiv.org/pdf/2309.04902.pdf)

- (arXiv 2023.09) A survey on efficient vision transformers: algorithms, techniques, and performance benchmarking. [[Paper]](https://arxiv.org/pdf/2309.02031.pdf)

- (arXiv 2023.07) A Survey of Techniques for Optimizing Transformer Inference. [[Paper]](https://arxiv.org/pdf/2307.07982.pdf)

- (arXiv 2023.07) Transformers in Reinforcement Learning: A Survey. [[Paper]](https://arxiv.org/pdf/2307.05979.pdf)

- (arXiv 2023.07) Vision Language Transformers: A Survey. [[Paper]](https://arxiv.org/pdf/2307.03254.pdf)

- (arXiv 2023.06) 2D Object Detection with Transformers: A Review. [[Paper]](https://arxiv.org/pdf/2306.04670.pdf), [[Awesome]](https://github.com/mindgarage-shan/trans_object_detection_survey)

- (arXiv 2023.05) Vision Transformers for Mobile Applications: A Short Survey. [[Paper]](https://arxiv.org/pdf/2305.19365.pdf)

- (arXiv 2023.05) A survey of the Vision Transformers and its CNN-Transformer based Variants. [[Paper]](https://arxiv.org/pdf/2305.09880.pdf)

- (arXiv 2023.05) Semantic Segmentation using Vision Transformers: A survey. [[Paper]](https://arxiv.org/pdf/2305.03273.pdf)

- (arXiv 2023.04) Transformer-based models and hardware acceleration analysis in autonomous driving: A survey. [[Paper]](https://arxiv.org/pdf/2304.10891.pdf)

- (arXiv 2023.04) Transformer-Based Visual Segmentation: A Survey. [[Paper]](https://arxiv.org/pdf/2304.09854.pdf), [[Awesome]](https://github.com/lxtGH/Awesome-Segmenation-With-Transformer)

- (arXiv 2023.02) Transformer-based Generative Adversarial Networks in Computer Vision: A Comprehensive Survey. [[Paper]](https://arxiv.org/pdf/2302.08641.pdf)

- (arXiv 2023.02) A Survey on Efficient Training of Transformers. [[Paper]](https://arxiv.org/pdf/2302.01107.pdf)

- (arXiv 2023.01) Advances in Medical Image Analysis with Vision Transformers: A Comprehensive Review. [[Paper]](https://arxiv.org/pdf/2301.03505.pdf), [[Awesome]](https://github.com/mindflow-institue/Awesome-Transformer)

- (arXiv 2022.11) Vision Transformers in Medical Imaging: A Review. [[Paper]](https://arxiv.org/pdf/2211.10043.pdf)

- (arXiv 2022.11) A Comprehensive Survey of Transformers for Computer Vision. [[Paper]](https://arxiv.org/pdf/2211.06004.pdf)

- (arXiv 2022.09) A Survey on Graph Neural Networks and Graph Transformers in Computer Vision: A Task-Oriented Perspective. [[Paper]](https://arxiv.org/pdf/2209.13232.pdf)

- (arXiv 2022.09) Vision Transformers for Action Recognition: A Survey. [[Paper]](https://arxiv.org/pdf/2209.05700.pdf)

- (arXiv 2022.09) Transformers in Remote Sensing: A Survey. [[Paper]](https://arxiv.org/pdf/2209.01206.pdf), [[Awesome]](https://github.com/VIROBO-15/Transformer-in-Remote-Sensing)

- (arXiv 2022.08) Medical image analysis based on transformer: A Review. [[Paper]](https://arxiv.org/pdf/2208.06643.pdf)

- (arXiv 2022.08) 3D Vision with Transformers: A Survey. [[Paper]](https://arxiv.org/pdf/2208.04309.pdf), [[Awesome]](https://github.com/lahoud/3d-vision-transformers)

- (arXiv 2022.05) Multimodal Learning with Transformers: A Survey. [[Paper]](https://arxiv.org/pdf/2206.06488.pdf)

- (arXiv 2022.05) Transformers in 3D Point Clouds: A Survey. [[Paper]](https://arxiv.org/pdf/2205.07417.pdf)

- (arXiv 2022.03) Vision Transformers in Medical Computer Vision - A Contemplative Retrospection. [[Paper]](https://arxiv.org/pdf/2203.15269.pdf)

- (arXiv 2022.03) Transformers Meet Visual Learning Understanding: A Comprehensive Review. [[Paper]](https://arxiv.org/pdf/2203.12944.pdf)

- (arXiv 2022.03) Recent Advances in Vision Transformer: A Survey and Outlook of Recent Work. [[Paper]](https://arxiv.org/pdf/2203.01536.pdf)

- (arXiv 2022.02) Transformers in Medical Image Analysis: A Review. [[Paper]](https://arxiv.org/pdf/2202.12165.pdf)

- (arXiv 2022.01) Transformers in Medical Imaging: A Survey. [[Paper]](https://arxiv.org/pdf/2201.09873.pdf), [[Awesome]](https://github.com/fahadshamshad/awesome-transformers-in-medical-imaging)

- (arXiv 2022.01) A Comprehensive Study of Vision Transformers on Dense Prediction Tasks. [[Paper]](https://arxiv.org/pdf/2201.08683.pdf)

- (arXiv 2022.01) Video Transformers: A Survey. [[Paper]](https://arxiv.org/pdf/2201.05991.pdf)

- (arXiv 2021.11) A Survey of Visual Transformers. [[Paper]](https://arxiv.org/pdf/2111.06091.pdf)

- (arXiv 2021.09) Survey: Transformer based Video-Language Pre-training. [[Paper]](https://arxiv.org/pdf/2109.09920.pdf)

- (arXiv 2021.03) Multi-modal Motion Prediction with Stacked Transformers. [[Paper]](https://arxiv.org/pdf/2103.11624.pdf), [[Code]](https://github.com/decisionforce/mmTransformer)

- (arXiv 2021.03) Perspectives and Prospects on Transformer Architecture for Cross-Modal Tasks with Language and Vision. [[Paper]](https://arxiv.org/pdf/2103.04037.pdf)

- (arXiv 2020.09) Efficient Transformers: A Survey. [[Paper]](https://arxiv.org/pdf/2009.06732.pdf)

- (arXiv 2020.01) Transformers in Vision: A Survey. [[Paper]](https://arxiv.org/pdf/2101.01169.pdf)



## Contact & Feedback

If you have any suggestions about this project, feel free to contact me.

- [e-mail: yzhangcst[at]gmail.com]
