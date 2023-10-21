### Pre_Trained Image Encoder for Generalizable Visual Reinforcement Learning
date: Oct 12th 2023
summary:
Pre_train a ImageNet (ResNet) encoder and better extract more generalizable representation 

Batch Normalization are crucial for this process.

Essence: Real world prior

### Masked World Models for Visual Control
date: Oct 13th 2023
summary:
decouple visual representation learning and dynamics learning
autoencoder--reconstruct pixels given masked convolutional features
introduce an auxiliary reward prediction object

pixel patch masking can't learn fine-grained details (e.g. small objects) and small-size patched leads to quadratic complexity of self-attention layers
so train autoencoder to reconstruct convolutional features

### Multi-View Masked World Models for Visual Robotic Manipulation
date: Oct 13th 2023
summary:
multi-view version MWM
want view-invariant representations
mask not only one viewpoint but also random features from remaining viewpoints

can extract single-view images' representations

### MoVie: Visual Model-Based Policy Adaptation for View Generalization
date: Oct 13th 2023
summary:
catagorize view generalization into four scenarios
spatial adaptive encoder: use STN blocks to do projection
#TODO: need to read Spatial transformer networks for better understanding
