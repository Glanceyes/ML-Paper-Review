# Machine Learning Paper Review

<br/>

## Introduction

<br/>

As a novice researcher in the field of artificial intelligence, I find it important not only to read papers quickly and understand them well to gain insight, but also to implement them in code and review their performance.

In this repository, I will share my code implementations and reviews of various papers in the field of machine learning. My hope is that this repository will be a useful resource for other researchers who want to learn more about the latest developments in the field and implement them in code.

My primary focus is on papers related to computer vision and recommendation systems, but I may expand to other areas in the future. If you have any suggestions or requests for papers to review, please feel free to let me know.

<br/>

<br/>

## Papers Review

<br/>

>  *The code below is a simplified version and typically based on `.ipynb` files.*

<br/>

------

### Computer Vision

<br/>

#### Radiance Field

| Name           | Paper                                                        | Paper Review                                                 | Code                                                         | Code Reference                                     |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------------- |
| **NeRF**       | [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934) | [Link](https://glanceyes.tistory.com/entry/NeRF-2D-이미지를-3D-이미지로-Reconstruction하여-Novel-View-Synthesis이-가능한-Neural-Radiance-Fields) | [File](https://github.com/Glanceyes/ML-Paper-Review/blob/main/ComputerVision/RadianceField/NeRF.ipynb) | [Link](https://github.com/yenchenlin/nerf-pytorch) |
| **InstantNGP** | [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf) |                                                              | [File](https://github.com/Glanceyes/ML-Paper-Review/blob/main/ComputerVision/RadianceField/InstantNGP.ipynb) | [Link](https://github.com/NVlabs/instant-ngp)      |

<br/>

#### Generative Model

| Name         | Paper                                                        | Paper Review                                                 | Code | Code Reference |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------- |
| **StyleGAN** | [A Style-Based Generator Architecture for Generative Adversarial Networks](https://arxiv.org/abs/1812.04948) | [Link](https://glanceyes.tistory.com/entry/StyleGAN-Style-transfer와-mapping-network를-사용하여-disentanglement를-향상시킨-generative-Model) |      |                |
| **HoloGAN**  | [HoloGAN: Unsupervised learning of 3D representations from natural images](https://arxiv.org/abs/1904.01326) | [Link](https://glanceyes.tistory.com/entry/HoloGAN-Natural-이미지로부터-3D-representation에-관해-unsupervised-learning-할-수-있는-모델) |      |                |

<br/>

#### Renderer

| Name          | Paper                                                        | Paper Review                                                 | Code | Code Reference |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------- |
| **RenderNet** | [RenderNet: A deep convolutional network for differentiable rendering from 3D shapes](https://arxiv.org/abs/1806.06575) | [Link](https://glanceyes.tistory.com/entry/RenderNet-3D-shape를-가지고-differentiable-rendering을-수행할-수-있는-Convolutional-network) |      |                |

<br/>

<br/>

------

### Recommendation System



#### Autoencoder

| Name          | Paper                                                        | Paper Review                                                 | Code                                                         | Code Reference                                 |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------- |
| **EASE**      | [Embarrassingly Shallow Autoencoders for Sparse Data](https://arxiv.org/abs/1905.03375) | [Link](https://glanceyes.tistory.com/entry/Embarrassingly-Shallow-Autoencoders-for-Sparse-Data-모델이-희소-데이터에-강한-이유) | [File](https://github.com/Glanceyes/ML-Paper-Review/blob/main/RecommendationSystem/Autoencoder/EASE.ipynb) | [Link](https://github.com/Darel13712/ease_rec) |
| **RecVAE**    | [RecVAE: a New Variational Autoencoder for Top-N Recommendations with Implicit Feedback](https://arxiv.org/abs/1912.11160) |                                                              |                                                              |                                                |
| **Multi-VAE** | [Variational Autoencoders for Collaborative Filtering](https://dl.acm.org/doi/10.1145/3178876.3186150) |                                                              |                                                              |                                                |
| **Multi-DAE** | [Variational Autoencoders for Collaborative Filtering](https://dl.acm.org/doi/10.1145/3178876.3186150) |                                                              |                                                              |                                                |

<br/>

<br/>

## Acknowledgments

<br/>

The code and the review in this repository is based on the original implementation by the authors of each paper. We thank them for releasing their code.

<br/>

> *I regret you to inform that this GitHub repository is primarily operated for my own AI study, so the some comments in code and paper review posts on my tech blog are **written in Korean**.*

<br/>

<br/>

## License

<br/>

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/chat/LICENSE) file for details. Some kinds of codes for paper's implementation are protected under the licenses specified by the authors. In such cases, the source of the code is left together.