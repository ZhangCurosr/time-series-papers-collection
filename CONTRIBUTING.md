# 如何贡献论文到时间序列论文集合

感谢您对时间序列论文集合的关注！本文档将详细指导您如何通过Fork方式提交和上传新的时间序列相关论文。

## 目录

- [前提条件](#前提条件)
- [Step 1: Fork 仓库](#step-1-fork-仓库)
- [Step 2: 克隆仓库到本地](#step-2-克隆仓库到本地)
- [Step 3: 添加新论文](#step-3-添加新论文)
- [Step 4: 提交更改](#step-4-提交更改)
- [Step 5: 推送更改到您的Fork](#step-5-推送更改到您的fork)
- [Step 6: 创建Pull Request](#step-6-创建pull-request)
- [提交注意事项](#提交注意事项)
- [论文分类指南](#论文分类指南)
- [常见问题解答](#常见问题解答)

## 前提条件

在开始之前，请确保您已经：

1. 拥有GitHub账号。如果没有，请前往[GitHub官网](https://github.com/)注册
2. 安装了Git。如果没有，请参考[Git安装指南](https://git-scm.com/book/zh/v2/起步-安装-Git)
3. 对基本的Git操作有初步了解

## Step 1: Fork 仓库

1. 访问[时间序列论文集合仓库](https://github.com/ZhangCurosr/time-series-papers-collection)
2. 点击页面右上角的"Fork"按钮
3. 等待几秒钟，GitHub会创建一个属于您的仓库副本
4. 完成后，您将被重定向到您的个人账户下的仓库副本：`https://github.com/您的用户名/time-series-papers-collection`

![Fork仓库示意图](https://i.imgur.com/FPLAG3H.png)

## Step 2: 克隆仓库到本地

打开终端（命令行界面），执行以下命令将仓库克隆到您的本地计算机：

```bash
git clone https://github.com/您的用户名/time-series-papers-collection.git
cd time-series-papers-collection
```

如果您已设置SSH密钥，可以使用SSH地址进行克隆：

```bash
git clone git@github.com:您的用户名/time-series-papers-collection.git
cd time-series-papers-collection
```

为了保持与原始仓库同步，建议添加原始仓库作为上游仓库：

```bash
git remote add upstream https://github.com/ZhangCurosr/time-series-papers-collection.git
```

## Step 3: 添加新论文

1. 确认您要添加的论文属于哪个类别。我们的主要分类有：
   - `2024基于预训练`
   - `2024基于LLM`
   - `2024年基于CNN`
   - `2024年基于GNN`
   - `2024年基于SSM`
   - `2024年基于transformer的`
   - `2024年基于插拔`
   - `2024年基于生成`
   - `2024年综述`

2. 将您的论文PDF文件复制到相应的目录中：

   ```bash
   cp /您的论文路径/论文名称.pdf /time-series-papers-collection/相应类别/
   ```

3. 如果您认为需要创建新的类别，请在仓库根目录创建新文件夹，并将论文放入其中：

   ```bash
   mkdir -p "2024年基于新技术/"
   cp /您的论文路径/论文名称.pdf "2024年基于新技术/"
   ```

## Step 4: 提交更改

1. 查看您添加的文件状态：

   ```bash
   git status
   ```

2. 将新添加的论文文件添加到Git暂存区：

   ```bash
   git add "2024年基于XXX/您的论文名称.pdf"
   ```

   如果添加了多个论文，可以一次性添加所有新文件：

   ```bash
   git add .
   ```

3. 提交更改，附带有意义的提交信息：

   ```bash
   git commit -m "添加新论文：《论文标题》 - 作者，发表于XX会议/期刊"
   ```

   提交信息应包含论文的基本信息，以便于其他人了解您添加的内容。

## Step 5: 推送更改到您的Fork

将您的更改推送到您的GitHub远程仓库：

```bash
git push origin main
```

如果您在新分支上工作：

```bash
git push origin 您的分支名
```

## Step 6: 创建Pull Request

1. 访问您的GitHub仓库页面：`https://github.com/您的用户名/time-series-papers-collection`
2. 您应该会看到一个提示，显示您刚刚推送的分支比原始仓库领先几个提交。点击"Compare & pull request"按钮
3. 填写Pull Request表单：
   - 标题：简要描述您添加的论文内容，例如"添加：《XXX》论文到基于LLM目录"
   - 正文：详细描述您添加的论文信息，包括：
     * 论文标题（中英文均可）
     * 作者信息
     * 发表年份、会议/期刊名称
     * 论文主要贡献或技术亮点（可选）
     * 论文链接（如有公开链接）
4. 点击"Create pull request"按钮提交

![创建Pull Request示意图](https://i.imgur.com/YZpQRKr.png)

## 提交注意事项

1. **确保PDF文件名清晰**：文件名应能够反映论文内容，最好采用论文原标题或易于识别的缩写形式
2. **版权合规**：请只上传符合开放获取政策的论文或您有权分享的论文
3. **避免重复**：提交前请检查仓库中是否已经包含相同的论文
4. **文件大小**：如果论文PDF文件过大（>50MB），请考虑在PR描述中提供下载链接而非直接上传
5. **分类准确**：请确保将论文放在最合适的分类目录中

## 论文分类指南

为了保持仓库的组织结构清晰，请参考以下指南确定论文分类：

- **基于预训练**：包含使用预训练技术的时间序列模型，如基础模型、迁移学习相关研究
- **基于LLM**：涉及大语言模型在时间序列中应用的论文
- **基于CNN**：主要使用卷积神经网络架构的时间序列模型
- **基于GNN**：使用图神经网络的时间序列建模相关论文
- **基于SSM**：状态空间模型，特别是Mamba等新型架构相关研究
- **基于Transformer**：采用Transformer及其变体的时间序列研究
- **基于插拔**：模块化设计、适配器等可插拔架构的论文
- **基于生成**：扩散模型、流匹配等生成模型应用于时间序列的研究
- **综述**：时间序列领域的综述、评测、比较研究

如有疑问，可以在PR中说明您对分类的考虑，我们会一起讨论最合适的归类。

## 常见问题解答

**Q: 我可以一次性提交多篇论文吗？**
A: 可以，但建议相关论文集中在一个或少量PR中提交，便于审核。

**Q: 我应该用什么格式命名论文文件？**
A: 推荐使用论文原始英文标题，保留空格，例如：`A Survey on Time Series Foundation Models.pdf`

**Q: 如何处理与原始仓库的冲突？**
A: 如果您的PR与原始仓库发生冲突，您需要先更新您的本地仓库：

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

解决冲突后，再推送到您的Fork仓库并更新PR。

**Q: 提交后多久能看到我的论文被合并？**
A: 这取决于仓库维护者的审核时间，通常会在1-7天内处理。

---

感谢您为时间序列论文集合做出贡献！如有其他问题，请在PR中提出或联系仓库维护者。
