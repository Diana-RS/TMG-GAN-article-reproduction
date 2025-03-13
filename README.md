This study investigates the integration of deep learning techniques, particularly Generative Adversarial Networks (GANs), into intrusion detection systems to address the challenge of class imbalance in network security datasets. We focus on reproducing and evaluating the model proposed in the paper "TMG-GAN: Generative Adversarial Networks-Based Imbalanced Learning for Network Intrusion Detection" by Ding et al. (https://ieeexplore.ieee.org/document/10312801), which introduces a novel GAN-based framework for enhancing the detection of minority classes in imbalanced datasets.

To assess the generalizability and effectiveness of the proposed approach, we conducted experiments on the widely used KDD Cup 99 dataset, a benchmark in intrusion detection research. This dataset was chosen to complement the results reported in the original study and to provide additional insights into the model's performance across different data distributions. Our experiments aimed to validate the robustness of the TMG-GAN framework and its ability to handle class imbalance in real-world scenarios.

The implementation details, including the architecture and operational mechanisms of the TMG-GAN model, are thoroughly documented in the project's code repository and technical report. Specifically, we integrated a Deep Convolutional Generative Adversarial Network (DCGAN) to optimize the generation of synthetic samples for underrepresented classes. Furthermore, we performed comparative analyses against established data augmentation techniques, such as the Synthetic Minority Over-sampling Technique (SMOTE) and Spectral Normalization GAN (SNGAN), to evaluate their relative efficacy in addressing class imbalance.
