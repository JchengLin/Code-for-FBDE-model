
# This repository provides the official Tensorflow implementation of the following paper:
FBDE: Full Body Privacy-Preserving Method via Adversarial Learning and Contrastive Learning

Jiacheng Lin, Zhiqiang Xiao, Yaping Li, Shutao Li, and Zhiyong Li.

ABSTRCT-Visual privacy protection has become difficult because of the large-scale application of visual devices. Although the methods of visual privacy protection have developed rapidly, it is mostly in face deidentification or visual privacy encryption. At present, there is still a lack of a deep learning method for visual privacy-preserving, especially for full-body privacy-preserving. Based on this, we propose a privacy-preserving method for full body based on adversarial learning and contrastive learning (FBDE). Firstly, the architecture of the generator and discriminator is designed for visual privacy-preserving. Secondly, a content mapping network and content loss function based on contrastive learning is designed for visual privacy-preserving. Then, to address the problem of misjudgment of discriminators in the process of visual privacy-preserving, an adversarial loss based on triple loss is proposed. Furthermore, a full body privacy-preserving dataset is made and implemented. Finally, the experiment results show that the FBDE model is not only better than state-of-the-art visual privacy-preserving models of parameters and training speed, but also in the effect of full body privacy-preserving. In addition, to the best of our knowledge, this is the first-time end-to-end framework used to perform full body privacy-preserving.

KEYWORD-Full-body privacy-preserving, Data privacy, Adversarial learning, Contrastive learning, Neural networks.

# Requirements

python == 3.6

tensorflow == 1.14


# Dataset

You can download this dataset on: https://github.com/JchengLin/FBPP_DATASET

# Train

RUN python privacy-preserving.py --dataset DATA_NAME

# Test

RUN python privacy-preserving.py --dataset DATA_NAME --phase test

# Evaluation

The evaluation protocal in the EVALUATION PROTOCAL.
