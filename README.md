# SmartEdge-LLM


<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Stargazers][stars-shield]][stars-url]


<br />
<!-- PROJECT LOGO -->


<p align="center">
  <a href="https://github.com/8baby8/SmartEdge-LLM">
    <img src="/assets/logo.png" alt="Logo" width="50%">
  </a>

<h3 align="center">SmartEdge-LLM</h3>
  <p align="center">
    <br />
    <a href="https://github.com/8baby8/SmartEdge-LLM"><strong>探索本项目的文档 »</strong></a>
    <br />
    <br />
    <a href="https://openxlab.org.cn/apps/detail/Farewell1/CHAT-OCR">查看Demo</a>
    ·
    <a href="https://github.com/8baby8/SmartEdge-LLM/issues">报告Bug</a>
    ·
    <a href="https://github.com/8baby8/SmartEdge-LLM/issues">提出新特性</a>
  </p>

</p>

<!-- 本篇README.md面向开发者 -->

**SmartEdge-LLM** 是一个能够支持 **边缘-LLM-生产** 的工具，由 [InternLM2-chat-7B](https://github.com/InternLM/InternLM) 指令微调而来，欢迎大家star~⭐⭐

---

SmartEdge-LLM是一个前沿的多模态智能问答与分析系统，它集成了文档问答、语音对话、数据分析与图形绘制，以及基于图片的问答等多种功能于一体。该项目旨在通过整合这些先进的技术，为用户提供一种高效、全面且智能的信息交互体验。

RAG系统不仅具备从海量文档中快速检索并回答用户问题的能力，还支持用户通过语音与系统进行自然、流畅的对话。此外，系统内置了强大的数据分析引擎，能够处理各类数据并自动生成统计图表，帮助用户更好地理解数据。更为独特的是，RAG系统还具备基于图片的问答功能，能够识别图片中的信息并据此回答用户的问题，为用户提供全新的交互体验。

通过RAG系统，我们期望能够为用户带来更高效、便捷的信息服务，提升用户体验和工作效率。同时，该系统也展示了人工智能技术在多模态信息处理领域的强大潜力和广阔应用前景。
### 最近更新
- 2024.5.4 完成SmartEdge-LLM工具 v1.0版本测试开发 😀

## 目录

- [SmartEdge-LLM](#关键信息提取大模型)
  - [开发前的配置要求](#开发前的配置要求)
  - [**使用指南**](#使用指南)
    - [数据构建](#数据构建)
    - [微调指南](#微调指南)
    - [部署指南](#部署指南)
    - [使用到的框架](#使用到的框架)
    - [如何参与本项目](#如何参与本项目)
    - [版本控制](#版本控制)
    - [作者（排名不分先后）](#作者排名不分先后)
    - [版权说明](#版权说明)
    - [特别鸣谢](#特别鸣谢)
  - [🌟 Contributors](#-contributors)

###### 开发前的配置要求

- 硬件：A100 40G（目前测试调节app.py中的参数显存推理时显存最低占用6G,使用Xtuner微调时占用16G左右）

###### **使用指南**

1. Clone the repo

```sh
git clone https://github.com/8baby8/SmartEdge-LLM.git
```

2. 依次阅读或者选择感兴趣的部分阅读：
   - [数据构建](#数据构建)
   - [微调指南](#微调指南)
   - [部署指南](#部署指南)
   - 查看更多详情

<details>
<summary>更多详情</summary>


### 数据构建

请阅读[数据构建指南](generate_data/tutorial.md)查阅

本次微调用到的数据集见[datasets](datasets/data.json)

### 微调指南

详见[微调指南](xtuner_config/README.md)

### 部署指南

详见[部署指南](demo/README.md)

### 使用到的框架

- [Xtuner](https://github.com/InternLM/xtuner)
- [Transformers](https://github.com/huggingface/transformers)
- [Pytorch](https://pytorch.org/)
- …



#### 如何参与本项目

贡献使开源社区成为一个学习、激励和创造的绝佳场所。你所作的任何贡献都是**非常感谢**的。

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 版本控制

该项目使用Git进行版本管理。您可以在repository参看当前可用版本。

</details>

### 作者（排名不分先后）

[杜朝科](https://github.com/8baby8)@飞桨星河社区UID:2460331

[王大兴]

[王小兴]

### 版权说明

该项目签署了MIT 授权许可，详情请参阅 [LICENSE](https://github.com/8baby8/EmoLLM/blob/master/LICENSE)

### 特别鸣谢

- [上海人工智能实验室](https://www.shlab.org.cn/)
- [闻星大佬（小助手）](https://github.com/vansin)

<!-- links -->

<!-- [linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555 -->

<!-- [linkedin-url]: https://linkedin.com/in/aJupyter -->

<!-- 太少了，没必要放 -->

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=8baby8/internllm-ocr&type=Date)](https://star-history.com/#8baby8/internllm-ocr&Date)

## 🌟 Contributors

[![mm-chatocr contributors](https://contrib.rocks/image?repo=8baby8/internllm-ocr&max=50)](https://github.com/8baby8/internllm-ocr/graphs/contributors)

[your-project-path]: 8baby8/internllm-ocr
[contributors-shield]: https://img.shields.io/github/contributors/8baby8/internllm-ocr.svg?style=flat-square
[contributors-url]: https://github.com/8baby8/internllm-ocr/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/8baby8/internllm-ocr.svg?style=flat-square
[forks-url]: https://github.com/8baby8/internllm-ocr/network/members
[stars-shield]: https://img.shields.io/github/stars/8baby8/internllm-ocr.svg?style=flat-square
[stars-url]: https://github.com/8baby8/internllm-ocr/stargazers
[issues-shield]: https://img.shields.io/github/issues/8baby8/internllm-ocr.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/8baby8/internllm-ocr.svg
[license-shield]: https://img.shields.io/github/license/8baby8/internllm-ocr.svg?style=flat-square
[license-url]: https://github.com/8baby8/internllm-ocr/tree/main/LICENSE
