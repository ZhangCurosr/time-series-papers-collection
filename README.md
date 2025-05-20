# 时间序列论文集合 (Time Series Papers Collection)

[![更新日期](https://img.shields.io/badge/更新日期-2025.05.20-blue.svg)](https://github.com/ZhangCurosr/time-series-papers-collection)
[![论文数量](https://img.shields.io/badge/论文数量-280+-brightgreen.svg)](https://github.com/ZhangCurosr/time-series-papers-collection)
[![开源协议](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📚 简介

本仓库收集了时间序列分析与预测领域的最新研究论文，主要关注2024年发表的工作。论文涵盖了预训练模型、大语言模型(LLM)应用、CNN架构、GNN、SSM（状态空间模型）、Transformer以及其他创新方法在时间序列分析中的应用。

该集合旨在帮助研究人员和从业者跟踪时间序列领域的最新进展，提供便捷的文献访问，促进相关技术的发展与应用。

## 🗂️ 目录结构

本仓库按照不同的方法论和技术路线组织论文，主要包括以下分类：

- **2024基于预训练** - 利用预训练技术的时间序列模型研究
- **2024基于LLM** - 大语言模型在时间序列分析中的应用
- **2024年基于CNN** - 使用卷积神经网络的时间序列模型
- **2024年基于GNN** - 图神经网络在时间序列建模中的应用
- **2024年基于SSM** - 基于状态空间模型的时间序列研究
- **2024年基于transformer的** - 使用Transformer架构的时间序列模型
- **2024年基于插拔** - 采用模块化和可插拔设计的时间序列方法
- **2024年基于生成** - 生成模型在时间序列中的应用
- **2024年综述** - 时间序列领域的综述和评测论文

## 📑 内容概述

### 2024基于预训练

该目录包含利用预训练技术提高时间序列模型性能和泛化能力的研究论文。重点关注基础模型、迁移学习及跨域适应能力。

主要论文包括：
- A Mamba Foundation Model for Time Series Forecasting
- CrossDomain Pretraining with Language Models for Transferable Time Series Representations
- MOMENT A Family of Open Timeseries Foundation Models
- NuwaTS a Foundation Model Mending Every Incomplete Time Series
- Timer Generative Pretrained Transformers Are Large Time Series Models
- TimeMoE BillionScale Time Series Foundation Models with Mixture of Experts

### 2024基于LLM

本目录探讨了大语言模型(LLM)在时间序列分析中的创新应用。研究如何利用LLM的强大语义理解能力和上下文处理能力来增强时间序列建模。

主要论文包括：
- CALF Aligning LLMs for Time Series Forecasting via Crossmodal FineTuning
- LLMMixer Multiscale Mixing in LLMs for Time Series Forecasting
- LSTPrompt Large Language Models as ZeroShot Time Series Forecasters by LongShortTerm Prompting
- TimeRAG BOOSTING LLM Time Series Forecasting via RetrievalAugmented Generation
- Towards Time Series Reasoning with LLMs

### 2024年基于CNN

收集了利用卷积神经网络架构处理时间序列数据的最新研究，探索CNN在捕获时间序列局部模式和特征提取方面的优势。

主要论文包括：
- ConvTimeNet A Deep Hierarchical Fully Convolutional Model for Multivariate Time Series Analysis
- EffiCANet Efficient Time Series Forecasting with Convolutional Attention
- TimeCNN Refining CrossVariable Interaction on Time Point for Time Series Forecasting
- TimeMixer A General Time Series Pattern Machine for Universal Predictive Analysis

### 2024年基于GNN

该目录关注图神经网络在时间序列建模中的应用，特别是对多变量时间序列和具有复杂依赖关系的系统建模。

主要论文包括：
- ForecastGrapher Redefining Multivariate Time Series Forecasting with Graph Neural Networks
- Graph Neural Flows for Unveiling Systemic Interactions Among Irregularly Sampled Time Series
- SAGDFN A Scalable Adaptive Graph Diffusion Forecasting Network for Multivariate Time Series Forecasting
- TEAM Topological Evolutionaware Framework for Traffic ForecastingExtended Version

### 2024年基于SSM

汇集了基于状态空间模型(特别是Mamba等架构)的时间序列研究，这些模型在处理长序列和捕获长期依赖方面具有显著优势。

主要论文包括：
- BiMamba Bidirectional Mamba for Time Series Forecasting
- CMamba Channel Correlation Enhanced State Space Models for Multivariate Time Series Forecasting
- DTMamba Dual Twin Mamba for Time Series Forecasting
- Is Mamba Effective for Time Series Forecasting
- MambaTS Improved Selective State Space Models for Longterm Time Series Forecasting
- TimeMachine A Time Series is Worth 4 Mambas for Longterm Forecasting

### 2024年基于transformer的

包含使用Transformer架构及其变体的时间序列模型研究，探索自注意力机制在时间序列建模中的应用。

主要论文包括：
- Are SelfAttentions Effective for Time Series Forecasting
- Attention as Robust Representation for Time Series Forecasting
- Caformer Rethinking Time Series Analysis from Causal Perspective
- Leveraging 2D Information for Longterm Time Series Forecasting with Vanilla Transformers
- TimeBridge NonStationarity Matters for Longterm Time Series Forecasting

### 2024年基于插拔

收集了采用模块化和可插拔设计的时间序列方法，这些方法允许灵活组合不同的组件以适应各种时间序列场景。

主要论文包括：
- ChannelAware LowRank Adaptation in Time Series Forecasting
- DisenTS Disentangled Channel Evolving Pattern Modeling for Multivariate Time Series Forecasting
- FDF Flexible Decoupled Framework for Time Series Forecasting with Conditional Denoising and Polynomial Modeling
- From Similarity to Superiority Channel Clustering for Time Series Forecasting

### 2024年基于生成

探讨生成模型(如扩散模型、流模型等)在时间序列生成、预测和补全中的应用。

主要论文包括：
- ANT Adaptive Noise Schedule for Time Series Diffusion Models
- Channelaware Contrastive Conditional Diffusion for Multivariate Probabilistic Time Series Forecasting
- Flow Matching with Gaussian Process Priors for Probabilistic Time Series Forecasting
- FMTS Flow Matching for Time Series Generation
- SeriestoSeries Diffusion Bridge Model
- TimeDiT Generalpurpose Diffusion Transformers for Time Series Foundation Model

### 2024年综述

包含时间序列领域的综述和评测论文，提供对研究现状、发展趋势和开放问题的系统性评估。

主要论文包括：
- A Comprehensive Survey of Time Series Forecasting Architectural Diversity and Open Challenges
- A Survey of Time Series Foundation Models Generalizing Time Series Representation with Large Language Model
- A Survey on Diffusion Models for Time Series and SpatioTemporal Data
- Foundation Models for Time Series Analysis A Tutorial and Survey
- The Rise of Diffusion Models in TimeSeries Forecasting

## 🔄 更新日志

- **2025.05.20**: 初始版本发布，收录280+篇2024年时间序列领域最新研究论文

## 📝 引用

如果您在研究中使用了本仓库的资源，请考虑引用相关论文以及本仓库：

```bibtex
@misc{timeseries-papers-collection,
  author = {Zhang Cursor},
  title = {Time Series Papers Collection},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/ZhangCurosr/time-series-papers-collection}}
}
```

## 📩 贡献

我们非常欢迎您通过提交新论文、改进分类或优化仓库结构来为本项目做出贡献！

### 🔍 如何提交新论文？

我们提供了详细的贡献指南，特别是关于如何提交新论文的完整教程：

👉 **[查看详细贡献指南](CONTRIBUTING.md)**

贡献步骤概述：

1. Fork 本仓库
2. 克隆仓库到本地
3. 将论文添加到合适的分类目录
4. 提交更改并推送到您的远程仓库
5. 创建 Pull Request

有关详细操作步骤、分类指南和最佳实践，请参阅我们的 [CONTRIBUTING.md](CONTRIBUTING.md) 文件。

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## ⭐ 致谢

感谢所有对本仓库做出贡献的研究者和维护者。
特别感谢各论文作者对时间序列领域的杰出贡献。

---

*注意：本仓库仅收集公开发表的研究论文，仅用于学术研究和教育目的。如有版权问题，请联系我们删除。*
