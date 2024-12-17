---
title: "zyj-2000/AIGC-Digital-Human: Collections of papers, databases, and codes targeted at Digital Human"
source: https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file
author: []
published: 
created: 2024-12-13
description: Collections of papers, databases, and codes targeted at Digital Human - zyj-2000/AIGC-Digital-Human
tags:
  - model/数字角色
---

## 📚AIGC Digital Human (Update)This is a repository for organizing papres, codes and other resources related to AIGC Digital Human.

## Contents- [AIGC Digital Human](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#aigc-digital-human-update)
- [Introduction](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#introduction)
- [2D Digital Human](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#2d-digital-human)
- [Large Language Model](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#large-language-model-llm)
- [Text2Speech Conversion](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#text2speech-conversion)
- [Speech Clone](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#speech-clone)
- [Face Driving](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#face-driving)
- [Cloth Modification](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#cloth-modification)
- [Style Transfer](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#style-transfer)
- [Quality Assessment](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#quality-assessment)
- [3D Digital Human](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#3d-digital-human)
- [NeRF](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#nerf)
- [Gaussian](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#gaussian)
- [3D Quality Assessment](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#3d-quality-assessment)
- [Databases](https://github.com/zyj-2000/AIGC-Digital-Human?tab=readme-ov-file#databases)

### Introduction

In this documentation, we have collected papers, databases, and code resources related to AIGC Digital Human. Digital Humans refer to virtual entities generated and simulated by computers, possessing human characteristics and behaviors.

### 🌟2D Digital Human
#### Large Language Model (LLM)
| #   | LLM         | Paper                                                                                                | Code/Project                                  |
| --- | ----------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| 1   | ChatGPT-3.5 | \-                                                                                                   | [ChatGPT](https://openai.com/chatgpt)         |
| 2   | ChatGLM-6B  | ["GLM-130B: An Open Bilingual Pre-trained Mode"](https://arxiv.org/abs/2210.02414)                   | [github](https://github.com/THUDM/ChatGLM-6B) |
| 3   | Qwen (通义千问) | ["QWEN TECHNICAL REPORT"](https://qianwen-res.oss-cn-beijing.aliyuncs.com/QWEN_TECHNICAL_REPORT.pdf) | [github](https://github.com/QwenLM/Qwen)      |

#### Text2Speech Conversion
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | Espeaker | \- | [Web](https://espeak.sourceforge.net/) |

#### Speech Clone
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | MockingBird | \- | [github](https://github.com/babysor/MockingBird) |
| 2 | Real-Time-Voice-Cloning | ["Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis"](https://arxiv.org/abs/1806.04558) | [github](https://github.com/CorentinJ/Real-Time-Voice-Cloning) |

#### Face Driving
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | MakeIttalk | ["MakeItTalk: Speaker-Aware Talking-Head Animation"](https://arxiv.org/abs/2004.12992) | [github](https://github.com/yzhou359/MakeItTalk) |
| 2 | Audio2Head | ["Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion"](https://arxiv.org/abs/2107.09293) | [github](https://github.com/wangsuzhen/Audio2Head) |
| 3 | Sadtalker | ["SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation"](https://arxiv.org/abs/2211.12194) | [github](https://github.com/OpenTalker/SadTalker) |
| 4 | Dreamtalk | ["DreamTalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models"](https://arxiv.org/abs/2312.09767) | [github](https://github.com/ali-vilab/dreamtalk) |
| 5 | Wav2Lip | ["A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild"](https://arxiv.org/abs/2008.10010) | [github](https://github.com/Rudrabha/Wav2Lip) |
| 6 | Video-Retalking | ["VideoReTalking: Audio-based Lip Synchronization for Talking Head Video Editing In the Wild"](https://arxiv.org/abs/2211.14758) | [github](https://github.com/OpenTalker/video-retalking) |
| 7 | DINet | ["DINet: Deformation Inpainting Network for Realistic Face Visually Dubbing on High Resolution Video"](https://arxiv.org/abs/2303.03988) | [github](https://github.com/MRzzm/DINet) |
| 8 | IP-LAP | ["Identity-Preserving Talking Face Generation with Landmark and Appearance Priors"](https://arxiv.org/abs/2305.08293) | [github](https://github.com/Weizhi-Zhong/IP_LAP) |

#### Cloth Modification
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | VITON-HD | ["Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis"](https://arxiv.org/abs/1806.04558) | [github](https://github.com/shadow2496/VITON-HD) |

#### Style Transfer
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | VToonify | ["VToonify: Controllable High-Resolution Portrait Video Style Transfer"](https://arxiv.org/abs/2209.11224) | [github](https://github.com/williamyang1991/VToonify) |
| 2 | DCT-Net | ["DCT-Net: Domain-Calibrated Translation for Portrait Stylization"](https://arxiv.org/abs/2207.02426) | [gihub](https://github.com/menyifang/DCT-Net) |

#### Super Resolution
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | BasicVSR++ | ["On the Generalization of BasicVSR++ to Video Deblurring and Denoising"](https://arxiv.org/abs/1806.04558) | [github](https://github.com/ckkelvinchan/BasicVSR_PlusPlus) |

#### Quality Assessment
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | VSFA | ["Quality Assessment of In-the-Wild Videos"](https://arxiv.org/abs/1908.00375) | [github](https://github.com/lidq92/VSFA) |

### 🌟3D Digital Human
#### NeRF
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | HumanNeRF | ["HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video"](https://arxiv.org/abs/2201.04127) | [github](https://github.com/alvinliu0/HumanGaussian) |

#### Gaussian
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | HumanGaussian | ["HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting"](https://arxiv.org/abs/2311.17061) | [github](https://github.com/chungyiweng/humannerf) |

#### 3D Quality Assessment
| # | Model | Paper | Code/Project |
| --- | --- | --- | --- |
| 1 | \- | ["A No-Reference Quality Assessment Method for Digital Human Head"](https://ieeexplore.ieee.org/document/10221964) | \- |
| 2 | \- | ["Geometry-Aware Video Quality Assessment for Dynamic Digital Human"](https://ieeexplore.ieee.org/document/10222061) | \- |
| 3 | \- | [Advancing Zero-Shot Digital Human Quality Assessment through Text-Prompted Evaluation](https://arxiv.org/abs/2307.02808) | \- |
| 4 | \- | [Perceptual Quality Assessment for Digital Human Heads](https://arxiv.org/abs/2209.09489) | \- |

#### Databases
| # | Database Name | Type | Title & Link | Database Link |
| --- | --- | --- | --- | --- |
| 1 | NoW | Generation | ["Learning to Regress 3D Face Shape and Expression from an Image without 3D Supervision"](https://arxiv.org/abs/1905.06817) | [Link](http://ringnet.is.tuebingen.mpg.de/) |
| 2 | FaceScape | Generation | ["FaceScape: a Large-scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction"](https://arxiv.org/abs/2003.13989) | [Link](https://github.com/zhuhao-nju/facescape) |
| 3 | Human3.6M | Generation | ["Human3.6M: Large Scale Datasets and Predictive Methods for 3D Human Sensing in Natural Environments"](https://ieeexplore.ieee.org/document/6682899) | [Link](http://vision.imar.ro/human3.6m) |
| 4 | ZJU-Mocap | Generation | ["Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans"](https://arxiv.org/abs/2012.15838) | [Link](https://zju3dv.github.io/neuralbody/) |
| 5 | BEAT | Gesture Synthesis | ["BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis"](https://arxiv.org/abs/2203.05297) | [Link](https://pantomatrix.github.io/BEAT/) |
| 6 | VOCA | Face Driving | ["Capture, Learning, and Synthesis of 3D Speaking Styles"](https://arxiv.org/abs/1905.03079) | [Link](https://voca.is.tue.mpg.de/) |
| 7 | MultiFace | Face Driving | ["Multiface: A Dataset for Neural Face Rendering"](https://arxiv.org/abs/2207.11243) | [Link](https://github.com/facebookresearch/multiface) |
| 8 | DHHQA | Quality Assessment | [Perceptual Quality Assessment for Digital Human Heads](https://arxiv.org/abs/2209.09489) | [Link](https://github.com/zzc-1998/DHHQA) |
| 9 | DDH-QA | Quality Assessment | [DDH-QA: A DYNAMIC DIGITAL HUMANS QUALITY ASSESSMENT DATABASE](https://arxiv.org/pdf/2212.12734.pdf) | [Link](https://github.com/zzc-1998/DDH-QA) |
| 10 | SJTU-H3D | Quality Assessment | [Advancing Zero-Shot Digital Human Quality Assessment through Text-Prompted Evaluation](https://arxiv.org/abs/2307.02808) | [Link](https://github.com/zzc-1998/SJTU-H3D) |
| 11 | 6G-DHQA | Quality Assessment | [Quality-of-Experience Evaluation for Digital Twins in 6G Network Environments](https://ieeexplore.ieee.org/abstract/document/10381636/) | [Link](https://github.com/zyj-2000/6G-DHQA) |
| 12 | THQA | Quality Assessment | [THQA: A PERCEPTUAL QUALITY ASSESSMENT DATABASE FOR TALKING HEADS](https://www.researchgate.net/publication/378609270_THQA_A_PERCEPTUAL_QUALITY_ASSESSMENT_DATABASE_FOR_TALKING_HEADS?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6ImxvZ2luIiwicGFnZSI6InNlYXJjaCIsInBvc2l0aW9uIjoicGFnZUhlYWRlciJ9fQ) | [Link](https://github.com/zyj-2000/THQA) |

### Related Reference
- [Awesome-Talking-Face](https://github.com/JosephPai/Awesome-Talking-Face)