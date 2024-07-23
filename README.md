# Global Clue-Guided Cross-Memory Quaternion Transformer Network for Multisource Remote Sensing Data Classification

Related code will be released gradually.

# Abstract:

Multisource remote sensing data classification is a challenging research topic, and how to address the inherent heterogeneity between multimodal data while exploring their complementarity is crucial. Existing deep learning models usually directly adopt feature-level fusion designs, most of which, however, fail to overcome the impact of heterogeneity, limiting their performance. As such, a multimodal joint classification framework, called global clue-guided cross-memory quaternion transformer network (GCCQTNet), is proposed for multisource data i.e., hyperspectral image (HSI) and synthetic aperture radar (SAR)/light detection and ranging (LiDAR) classification. First, a three-branch structure is built to extract the local and global features, where an independent squeeze-expansion-like fusion (ISEF) structure is designed to update the local and global representations by considering the global information as an agent, suppressing the negative impact of multimodal heterogeneity layer by layer. A cross-memory quaternion transformer (CMQT) structure is further constructed to model the complex inner relationships between the intramodality and intermodality features to capture more discriminative fusion features that fully characterize multimodal complementarity. Finally, a cross-modality comparative learning (CMCL) structure is developed to impose the consistency constraint on global information learning, which, in conjunction with a classification head, is used to guide the end-to-end training of GCCQTNet. Extensive experiments on three public multisource remote sensing datasets illustrate the superiority of our GCCQTNet with regards to other state-of-the-art methods.


# Paper
Please cite our paper if you find the code or dataset useful for your research.

@ARTICLE{10557680,
  author={Hu, Wen-Shuai and Li, Wei and Li, Heng-Chao and Huang, Feng-Hua and Tao, Ran},<br>
  journal={IEEE Transactions on Neural Networks and Learning Systems}, <br>
  title={Global Clue-Guided Cross-Memory Quaternion Transformer Network for Multisource Remote Sensing Data Classification}, <br>
  year={2024},<br>
  volume={},<br>
  number={},<br>
  pages={1-15},<br>
  keywords={Feature extraction;Transformers;Quaternions;Data models;Laser radar;Synthetic aperture radar;Data mining;Attention mechanism;fusion and classification;global consistency;multisource remote sensing data;quaternion;transformer},<br>
  doi={10.1109/TNNLS.2024.3406735}}

# Requirements

CUDA Version: 11.8
Pytorch Version: 2.0
Python Version: 3.10

# Note
