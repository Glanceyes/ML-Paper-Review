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

> *I regret you to inform that this GitHub repository is primarily operated for my own AI study, so the some comments in code and paper review posts on my tech blog are **written in Korean**.*

<br/>

The code below is a simplified version and typically based on `.ipynb` files.

<br/>

------

### Fundamental

<br/>

#### Convolution

| Name       | Paper                                                        | Paper Review | Code                                                         | Code Reference |
| ---------- | ------------------------------------------------------------ | ------------ | ------------------------------------------------------------ | -------------- |
| **ResNet** | [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385) |              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/Fundamental/ResNet) |                |

<br/>

<br/>

------

### Computer Vision

<br/>

#### Generative Model

| Name         | Paper                                                        | Paper Review                                                 | Code | Code Reference |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------- |
| **StyleGAN** | [A Style-Based Generator Architecture for Generative Adversarial Networks](https://arxiv.org/abs/1812.04948) | [Link](https://glanceyes.tistory.com/entry/StyleGAN-Style-transfer???-mapping-network???-????????????-disentanglement???-????????????-generative-Model) |      |                |
| **HoloGAN**  | [HoloGAN: Unsupervised learning of 3D representations from natural images](https://arxiv.org/abs/1904.01326) | [Link](https://glanceyes.tistory.com/entry/HoloGAN-Natural-??????????????????-3D-representation???-??????-unsupervised-learning-???-???-??????-??????) |      |                |

<br/>

#### Implicit Function

| Name       | Paper                                                        | Paper Review | Code                                                         | Code Reference                                     |
| ---------- | ------------------------------------------------------------ | ------------ | ------------------------------------------------------------ | -------------------------------------------------- |
| **PIFuHD** | [Pixel-Aligned Implicit Function for High-Resolution Clothed Human Digitization](https://arxiv.org/abs/1905.05172) |              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/ComputerVision/ImplicitFunction/PIFuHD) | [Link](https://github.com/facebookresearch/pifuhd) |

<br/>

#### Radiance Field

| Name           | Paper                                                        | Paper Review                                                 | Code                                                         | Code Reference                                     |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------------- |
| **NeRF**       | [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934) | [Link](https://glanceyes.tistory.com/entry/NeRF-2D-????????????-3D-????????????-Reconstruction??????-Novel-View-Synthesis???-?????????-Neural-Radiance-Fields) | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/ComputerVision/RadianceField/NeRF) | [Link](https://github.com/yenchenlin/nerf-pytorch) |
| **InstantNGP** | [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://arxiv.org/abs/2201.05989) |                                                              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/ComputerVision/RadianceField/InstantNGP) | [Link](https://github.com/NVlabs/instant-ngp)      |

<br/>

#### Renderer

| Name          | Paper                                                        | Paper Review                                                 | Code | Code Reference |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------- |
| **RenderNet** | [RenderNet: A deep convolutional network for differentiable rendering from 3D shapes](https://arxiv.org/abs/1806.06575) | [Link](https://glanceyes.tistory.com/entry/RenderNet-3D-shape???-?????????-differentiable-rendering???-?????????-???-??????-Convolutional-network) |      |                |

<br/>

<br/>

------

### Recommendation System



#### Autoencoder

| Name          | Paper                                                        | Paper Review                                                 | Code                                                         | Code Reference                                 |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------- |
| **EASE**      | [Embarrassingly Shallow Autoencoders for Sparse Data](https://arxiv.org/abs/1905.03375) | [Link](https://glanceyes.tistory.com/entry/Embarrassingly-Shallow-Autoencoders-for-Sparse-Data-?????????-??????-????????????-??????-??????) | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/RecommendationSystem/Autoencoder/EASE) | [Link](https://github.com/Darel13712/ease_rec) |
| **RecVAE**    | [RecVAE: a New Variational Autoencoder for Top-N Recommendations with Implicit Feedback](https://arxiv.org/abs/1912.11160) |                                                              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/RecommendationSystem/Autoencoder/MultiDAE) |                                                |
| **Multi-DAE** | [Variational Autoencoders for Collaborative Filtering](https://dl.acm.org/doi/10.1145/3178876.3186150) |                                                              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/RecommendationSystem/Autoencoder/MultiVAE) |                                                |
| **Multi-VAE** | [Variational Autoencoders for Collaborative Filtering](https://dl.acm.org/doi/10.1145/3178876.3186150) |                                                              | [File](https://github.com/Glanceyes/ML-Paper-Review/tree/main/RecommendationSystem/Autoencoder/RecVAE) |                                                |

<br/>

<br/>

## Acknowledgments

<br/>

The code and the review in this repository is based on the original implementation by the authors of each paper. We thank them for releasing their code.

<br/>

<br/>

## License

<br/>

This project is licensed under the MIT License - see the [LICENSE](https://en.wikipedia.org/wiki/MIT_License) file for details. Some kinds of codes for paper's implementation are protected under the licenses specified by the authors. In such cases, the source of the code is left together.