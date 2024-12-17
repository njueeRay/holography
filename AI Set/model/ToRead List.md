> 在数字角色生成领域，兼顾肢体、表情和语言的模型架构需要在生成质量和推理速度之间取得平衡。以下是一些值得参考的架构及其相关论文：

#TODO

### Latest Works
#### **XAGen: 3D Expressive Human Avatars Generation**

- [ ] paper: [[2311.13574] XAGen: 3D Expressive Human Avatars Generation](https://arxiv.org/abs/2311.13574?utm_source=chatgpt.com)

#model/数字角色/多部位
#model/数字角色/表达控制

XAGen 是首个能够对人体、面部和手部进行表达式控制的 3D 生成模型。它采用多尺度、多部分的 3D 表示，提升面部和手部等细节区域的逼真度。通过多部分渲染技术，XAGen 将身体、面部和手部分离合成，简化模型训练并增强几何质量。实验表明，XAGen 在真实感、多样性和表达控制能力方面优于现有方法。

#### 🌟**Digital Life Project: Autonomous 3D Characters with Social Intelligence** 

- [ ] paper: [[2312.04547] Digital Life Project: Autonomous 3D Characters with Social Intelligence](https://arxiv.org/abs/2312.04547?utm_source=chatgpt.com)

#model/数字角色/多部位 
#model/数字角色/自主对话
#model/数字角色/个性自主

该项目提出了一个框架，利用语言作为通用媒介，构建具有社交智能的自主 3D 角色。框架包括两个主要组件：SocioMind（数字大脑）和 MoMat-MoGen（文本驱动的动作合成范式）。SocioMind 模拟角色的个性和自主性，而 MoMat-MoGen 结合动作匹配和生成技术，控制角色的数字身体。实验显示，该框架使虚拟角色能够自主发起和维持对话，并执行上下文相关的身体动作。

#### 🌟**EMO: Emote Portrait Alive -- Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions**

- [ ] paper: [[2402.17485] EMO: Emote Portrait Alive -- Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions](https://arxiv.org/abs/2402.17485)

#model/数字角色/音频驱动
#model/数字角色/头部面部 
#model/数字角色/Diffusion

在这项工作中，我们通过关注音频提示和面部动作之间的动态和微妙关系来解决增强头部说话视频生成的真实性和表现力的挑战。我们发现传统技术的局限性，这些技术往往无法捕捉人类表情的全部范围和个人面部风格的独特性。为了解决这些问题，我们提出了 EMO，这是一种利用直接音频到视频合成方法的新颖框架，绕过了对中间 3D 模型或面部标志的需求。我们的方法可确保整个视频中的无缝帧过渡和一致的身份保留，从而产生高度表现力和逼真的动画。实验结果表明，EMO不仅能够制作令人信服的口语视频，还能够制作各种风格的歌唱视频，在表现力和真实感方面明显优于现有的最先进的方法。

#### **VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time**

- [ ] paper: [[2404.10667] VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time](https://arxiv.org/abs/2404.10667)

#model/数字角色/实时生成
#model/数字角色/音频驱动
#model/数字角色/音画同步
#model/数字角色/头部面部

VASA-1 是一种实时生成逼真音频驱动的说话人脸的框架。 该方法从单一静态图像和语音音频片段出发，生成与音频精确同步的唇部动作，以及丰富的面部细节和自然的头部运动，提升了生成视频的真实性和生动性。 其核心创新包括在面部潜在空间中进行整体面部动态和头部运动生成，并通过视频数据开发出表达性强且解耦的面部潜在空间。 实验结果显示，VASA-1 在视频质量、面部和头部动态的真实性等多个方面显著优于现有方法。 此外，该方法支持在线生成 512×512 分辨率的视频，帧率可达 40 FPS，启动延迟极低，为模拟人类对话行为的实时虚拟化身互动铺平了道路。

#### **JoyVASA: Portrait and Animal Image Animation with Diffusion-Based Audio-Driven Facial Dynamics and Head Motion Generation**

- [ ] paper: [[2411.09209] JoyVASA: Portrait and Animal Image Animation with Diffusion-Based Audio-Driven Facial Dynamics and Head Motion Generation](https://arxiv.org/abs/2411.09209)

#model/数字角色/Diffusion 
#model/数字角色/音频驱动 
#model/数字角色/头部面部

音频驱动的肖像动画在基于扩散的模型方面取得了重大进展，提高了视频质量和口型同步准确性。然而，这些模型日益复杂，导致训练和推理效率低下，以及视频长度和帧间连续性的限制。在本文中，我们提出了 JoyVASA，一种基于扩散的方法，用于在音频驱动的面部动画中生成面部动态和头部运动。具体来说，在第一阶段，我们引入了一个解耦的面部表示框架，它将动态面部表情与静态 3D 面部表示分开。这种解耦允许系统通过将任何静态 3D 面部表征与动态运动序列相结合来生成更长的视频。然后，在第二阶段，训练Diffusion Transformer直接根据音频提示生成运动序列，而与角色身份无关。最后，在第一阶段训练的生成器使用 3D 面部表示和生成的运动序列作为输入来渲染高质量的动画。凭借解耦的面部表示和独立于身份的运动生成过程，JoyVASA 超越了人类肖像，无缝地制作了动物面部动画。该模型在私人中文和公共英语数据的混合数据集上进行训练，从而实现多语言支持。实验结果验证了我们方法的有效性。未来的工作将集中于提高实时性能和细化表情控制，进一步扩展在人像动画中的应用。该代码位于：[this https URL](https://github.com/jdh-algo/JoyVASA).


---
## Prior Works

#### 🌟**A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild**

- [ ] paper: [[2008.10010] A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](https://arxiv.org/abs/2008.10010)

#model/数字角色/音画同步
#model/数字角色/音频驱动
#model/数字角色/动作生成

在这项工作中，我们研究了对任意身份的说话人脸视频进行口型同步以匹配目标语音片段的问题。目前的工作擅长在训练阶段看到的特定人物的静态图像或视频上产生准确的嘴唇运动。然而，它们无法准确地改变动态、不受约束的说话面部视频中任意身份的嘴唇运动，导致视频的重要部分与新音频不同步。我们确定了与此相关的关键原因，并通过向强大的口型同步鉴别器学习来解决这些问题。接下来，我们提出新的、严格的评估基准和指标，以准确测量无约束视频中的唇同步。对我们具有挑战性的基准进行的广泛定量评估表明，我们的 Wav2Lip 模型生成的视频的口型同步精度几乎与真实同步视频一样好。

我们在我们的网站上提供了一个演示视频，清楚地展示了我们的 Wav2Lip 模型和评估基准的重大影响： \url{[this http URL](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild)}。代码和模型在此 GitHub 存储库中发布：\url{[this http URL](http://github.com/Rudrabha/Wav2Lip)}。您还可以通过以下链接尝试交互式演示：\url{[this http URL](http://bhaasha.iiit.ac.in/lipsync)}。

#### **Text2Gestures: A Transformer-Based Network for Generating Emotive Body Gestures for Virtual Agents**  

- [ ] paper: [[2101.11101] Text2Gestures: A Transformer-Based Network for Generating Emotive Body Gestures for Virtual Agents](https://arxiv.org/abs/2101.11101?utm_source=chatgpt.com)

#model/数字角色/肢体动作
#model/数字角色/文本驱动
#model/数字角色/Transformer

Text2Gestures 是一个基于 Transformer 的网络，用于根据自然语言文本输入生成虚拟代理的情感化全身动作。该方法通过利用与身体表达相关的生物力学特征，生成符合文本叙述或对话的情感表达动作。实验结果表明，该网络在生成与文本对齐的动作方面达到了先进水平，并能够以交互速度生成这些动作。

#### **Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion**

- [ ] paper: [Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://www.semanticscholar.org/paper/9318d7a44a4098222ccd573ad14e968ba09fbdd4)

#model/数字角色/头部面部
#model/数字角色/音频驱动

Audio2Head 提出了一种音频驱动的头部说话方法，可以从单个参考图像生成逼真的头部说话视频。在这项工作中，Audio2Head解决了两个关键挑战：
1. 产生与语音韵律相匹配的自然头部运动
2. 在稳定非面部区域的同时保持说话者在大头部运动中的外观。

Audio2Head首先通过使用运动感知循环神经网络 (RNN) 对刚性 6D 头部运动进行建模来设计头部姿势预测器。通过这种方式，预测的头部姿势充当说话头部的低频整体运动，从而使我们的后一个网络能够专注于详细的面部运动生成。为了描述由音频产生的整个图像运动，我们利用基于关键点的密集运动场表示。然后，我们开发了一个运动场生成器，根据输入音频、头部姿势和参考图像生成密集运动场。由于这种基于关键点的表示对面部区域、头部和背景的运动进行了整体建模，因此我们的方法可以更好地限制生成视频的空间和时间一致性。最后，采用图像生成网络根据估计的基于关键点的运动场和输入参考图像来渲染逼真的头部说话视频。大量的实验表明，我们的方法生成的视频具有合理的头部运动、同步的面部表情和稳定的背景，并且优于最先进的方法。

