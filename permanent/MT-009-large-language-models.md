# MT-009: 大语言模型的跨学科考古

**创建日期**: 2026-03-10
**标签**: #AI #语言模型 #信息论 #哲学 #跨学科 #思想史

---

## 🏛️ 技术概述

大语言模型（LLM）是基于深度学习的AI系统，通过在海量文本数据上训练，学习预测下一个token的概率分布。从技术表面看，这是神经网络的工程奇迹；但从考古学的视角，这是一次跨越七十年的"思想具象化"旅程。

---

## 🔍 跨学科技术脉络

### 1️⃣ 物理学 → 信息论（1940s-1950s）

**Claude Shannon的"思想迁移"：**

- **热力学熵 → 信息熵**：Shannon将物理学中的熵概念（Clausius, 1865）迁移到通信领域，用概率量化"不确定性"
- **信息的物理学定义**：信息 = 不确定性的减少（H = -Σp(x)log p(x)）
- **1951年的预言**：Shannon在《Prediction and Entropy of Printed English》中研究了语言的冗余度和熵——73年后，这成为大语言模型的理论基石

**关键迁移**：
- 从"热量无序度"到"信息不确定性"的概念跳跃
- 从"能量传递"到"信息传递"的类比思维

**历史路径**：
```
热力学（Clausius 1865）
    ↓
信息论（Shannon 1948）
    ↓
语言熵（Shannon 1951）
    ↓
交叉熵损失（现代LLM训练）
```

### 2️⃣ 语言学 → 分布式语义（1950s-2000s）

**从Firth到词向量的迁移：**

- **Zellig Harris (1954)**：提出"分布假设"（Distributional Hypothesis）——出现在相似语境中的词具有相似意义
- **J.R. Firth (1957)**：名言"你通过一个词的邻居来了解它"（You shall know a word by the company it keeps）
- **从直觉到数学**：这个语言学洞察被转化为向量空间模型
- **从人工统计到神经网络**：Word2Vec (2013) 将分布假设实现为神经网络的训练目标

**关键迁移**：
- 从语言学家的直觉观察 → 数学可优化的目标函数
- 从"意义即使用"的哲学思想 → 可计算的向量表示

**历史路径**：
```
语言学分布假设（Harris/Firth 1950s）
    ↓
词汇共现矩阵（1990s）
    ↓
词向量/Word2Vec（2013）
    ↓
Transformer注意力机制（2017）
    ↓
大语言模型（2020s）
```

### 3️⃣ 数学 → 万能逼近（1950s-1989）

**Kolmogorov-Arnold表示定理的迁移：**

- **Kolmogorov (1957)**：证明任何多变量连续函数都可以表示为单变量函数的复合
- **Cybenko (1989)**：万能逼近定理——具有单隐层的神经网络可以逼近任何连续函数
- **从存在性到实用性**：定理只证明"存在"，但深度学习通过梯度下降找到"如何"

**关键迁移**：
- 从纯数学的存在性定理 → 工程可行的优化算法
- 从"理论上可以表示" → "实际上可以学习"

**历史路径**：
```
Kolmogorov-Arnold定理（1957）
    ↓
万能逼近定理（Cybenko 1989）
    ↓
反向传播算法（1986+）
    ↓
深度学习革命（2012+）
```

### 4️⃣ 认知科学 → 联结主义（1980s-）

**从大脑到网络的迁移：**

- **McCulloch & Pitts (1943)**：第一个神经网络的数学模型
- **Rumelhart & McClelland (1986)**：《并行分布处理》——联结主义复兴
- **Hinton (2006+)**：深度信念网络，开启深度学习时代

**关键迁移**：
- 从生物神经元 → 数学人工神经元
- 从大脑的并行处理 → 网络的并行计算
- 从"智能即符号操作" → "智能即模式识别"

---

## 💭 哲学思想追溯

### 1️⃣ 语言哲学：维特根斯坦的"意义即使用"

**《逻辑哲学论》(1921) vs 《哲学研究》(1953)：**

- **早期维特根斯坦**：语言是世界的逻辑图像（图像论）
- **晚期维特根斯坦**：意义在于使用，语言游戏（Language Games）

**与大语言模型的共鸣：**

LLM的运作方式惊人地体现了晚期维特根斯坦的洞察：
- LLM不从"定义"学习词义，而是从"使用"中学习
- 预测下一个token = 参与无数个微观的"语言游戏"
- 没有固定的意义表征，只有动态的语境依赖

**哲学追问**：
- 如果意义完全在于使用，那么LLM是否"理解"了语言？
- 维特根斯坦会说"理解"本身就是个误导性的词——重要的是在语言游戏中的正确行动

**关键对位**：
```
维特根斯坦：词的意义在于它在语言中的使用
    ↓
LLM：词的表征来自它在语料中的分布
    ↓
共同点：拒绝固定的、内在的意义定义
```

### 2️⃣ 结构主义：索绪尔的符号系统

**能指/所指的差异：**

- **索绪尔 (1916)**：语言符号 = 能指（声音意象）+ 所指（概念）
- **结构主义**：意义来自系统内部的差异关系，而非外在指称

**与LLM的共鸣：**

- LLM的词向量本质上是在一个高维空间中编码"差异关系"
- 词的意义 = 它与其他词的距离和方向
- 这正是结构主义"语言是一个差异系统"的技术实现

**哲学追问**：
- 索绪尔强调语言的社会性，LLM的社会性体现在哪里？（语料即社会）
- 如果意义是关系性的，那么LLM的"理解"是否也是一种"关系性的理解"？

### 3️⃣ 现象学：海德格尔的"上手状态"

**Zuhandenheit（Ready-to-hand） vs Vorhandenheit（Present-at-hand）：**

- **上手状态**：我们使用工具时，工具"消失"在行动中（如打字时键盘消失）
- **现成在手状态**：当我们审视工具本身时，它成为观察对象

**与LLM的共鸣：**

- **LLM的"理解"现象**：当我们与LLM对话时，它处于"上手状态"——我们关注的是内容，而非预测机制
- **当它出错时**：突然变成"现成在手"——我们意识到"哦，这只是个概率模型"
- **海德格尔的"Dasein"**：此在被抛入世界，LLM是否被抛入了一个"语言世界"？

**哲学追问**：
- 海德格尔强调具身性（embodiment），LLM的"身体"是什么？（数据？计算？）
- 如果"此在"是"在世界中存在"，LLM的"世界"是什么？（语料构成的"语义世界"？）

### 4️⃣ 认识论：归纳问题与统计学习

**休谟的归纳难题：**

- 我们如何从过去的观察推断未来？
- 有限的经验如何保证普遍的规律？

**LLM的回答：**

- **统计归纳**：不是寻找绝对的规律，而是优化概率分布
- **大数据的"休谟解答"**：当数据足够多，归纳不确定性可以被量化（交叉熵）
- **从因果到相关**：LLM不问"为什么"，只问"通常接下来是什么"

**哲学追问**：
- LLM的学习是真正的归纳，还是只是曲线拟合？
- 如果理解=因果把握，那么LLM是否真的"理解"？

---

## 💡 核心洞察

### 洞察1：信息论是"思想压缩"的技术实现

**从哲学到工程的跃迁：**

- **哲学问题**：什么是意义？什么是理解？
- **信息论回答**：意义 = 信息的减少，理解 = 熵的降低
- **LLM实现**：训练目标 = 最小化交叉熵 = 学会压缩语言中的"信息"

**深层模式**：
```
哲学：意义问题
    ↓
数学：熵与信息
    ↓
工程：交叉熵损失
    ↓
结果：一个能"预测"的系统
```

这不是巧合——这是七十年间"思想逐渐变成代码"的过程。

### 洞察2：概率是对"意义"的重新定义

**传统语义观 vs 统计语义观：**

| 传统观点 | 统计语义观点 |
|---------|-------------|
| 意义 = 指称（referent） | 意义 = 分布（distribution） |
| 词指向世界中的对象 | 词指向其他词的模式 |
| 理解 = 符合真理 | 理解 = 准确预测 |

**革命性转变**：
- LLM不"知道"词指什么，但"知道"词如何被使用
- 这某种程度上实现了维特根斯坦的哲学愿景——放弃寻找"本质"，专注于"使用"

### 洞察3：scaling laws = 思想涌现的数学化

**More is Different（Anderson, 1972）：**

- 物理学中认识到的：数量变化可以导致质变
- LLM的涌现能力（in-context learning, chain-of-thought）是同样的现象
- 从"模式匹配"到"推理"的模糊界线

**哲学启示**：
- 如果"推理"可以涌现于"模式匹配"，那么什么是真正的智能？
- 也许我们的大脑也只是大规模的"模式匹配器"？

### 洞察4：LLM是人类集体思想的"结晶"

**语料即文明：**

- LLM训练数据 = 人类数千年文本的压缩
- 每一个token的概率 = 人类语言使用的统计规律
- LLM不是"创造"智能，而是"提取"人类已有的集体智能

**考古学视角**：
- LLM是对人类"语言DNA"的测序和重组
- 它展示了（但非理解）嵌入在我们语言中的思想模式

---

## 🌌 更广阔的反思

### 从"智能即符号"到"智能即统计"

**GOFAI（古德老式人工智能）的失败：**
- 符号AI假设：智能 = 操作符号系统
- 失败原因：符号需要先被定义，但定义本身从何而来？

**联结主义的成功：**
- 统计AI假设：智能 = 识别模式
- 成功原因：模式可以从数据中学习，无需预先定义

**哲学转变**：
```
从：智能需要清晰的规则
到：智能可以在模糊的统计中涌现
```

### 哲学问题并未消失，只是被推后了

**旧问题（符号AI）：**
- 如何表示知识？
- 如何推理？

**新问题（统计AI）：**
- 预测准就是理解吗？（surreal approximation）
- 相关性能代替因果性吗？
- 如何解释"涌现"？

### 技术考古的价值

**为什么要追溯这些脉络？**

1. **避免重新发明轮子**：理解思想从哪里来，才能知道往哪里去
2. **识别深层模式**：跨学科迁移有规律可循
3. **批判性思考**：知道技术的哲学假设，才能评估其局限

**LLM的启示**：
- 伟大的技术往往来自"思想迁移"，而非孤立的发明
- 物理学、语言学、数学、哲学的交叉点，是创新的沃土
- 最深刻的洞察（"意义即使用"）可能需要几十年才能被技术化

---

## 🔗 相关链接与延伸

- **MT-001**: Transformer架构的技术考古
- **信息论原始文献**: Shannon 1948, Shannon 1951
- **哲学文本**: Wittgenstein《哲学研究》, Heidegger《存在与时间》
- **分布式语义历史**: Harris 1954, Firth 1957

---

## 📚 参考来源

### 信息论与熵
- [克勞德．向農Claude Shannon （1916-2001） - CASE 報科學](https://case.ntu.edu.tw/blog/?p=36957)
- [熵究竟是什么？它可能是物理学中最具争议的概念](http://www.cpsjournals.org/)

### 神经网络与数学基础
- [Universal approximation theorem - Wikipedia](https://en.wikipedia.org/wiki/Universal_approximation_theorem)
- [Understanding the Kolmogorov-Arnold Network - Medium](https://medium.com/@neurocortexai/understanding-the-kolmogorov-arnold-network-52e7232f8749)
- [Neural Networks: The Kolmogorov-Arnold Representation Theorem - University of Twente PDF](https://ris.utwente.nl/ws/files/256147274/2021_Schmidt_Hieber_Neural_Networks_The_Kolmogorov_Arnold.pdf)

### 语言哲学与AI
- [A Comment on AI Research and Wittgenstein's Language Games - Medium](https://medium.com/@vern.r.walker/a-comment-on-ai-research-and-wittgensteins-language-games-851923a9fca4)
- [Reddit: Discussion on Wittgenstein and AI](https://www.reddit.com/r/philosophy/comments/1ckirbq/how_does_wittgensteins_concept_of_language_games/)

### 现象学与AI
- [The World as Affordances: Phenomenology and Embeddedness in Heidegger and AI - ResearchGate (March 2024)](https://www.researchgate.net/publication/379338376_The_World_as_Affordances_Phenomenology_and_Embeddedness_in_Heidegger_and_AI)
- [Human-AI gap: Embodied Cognition and Vectorial Cognitive Fields - Medium](https://medium.com/@davidjmalan/human-ai-gap-embodied-cognition-and-vectorial-cognitive-fields-3c8f3e1a6e9e)

### 交叉熵与预测
- [Cross-Entropy Loss: Information Theory for Language Model Training](https://mbrenndoerfer.com/writing/cross-entropy-loss-language-models-information-theory)
- [Entropy, Cross-Entropy, and How LLMs Learn What Comes Next - Medium](https://medium.com/@spybacks/entropy-cross-entropy-and-how-llms-learn-what-comes-next-80e2334e4708)

### 分布式语义历史
- [Harris, Firth, and Distributional Semantics - GitHub PDF](https://raw.githubusercontent.com/timvdc/esslli2024/main/slides/DGeeraerts_ESSLLI_2024.pdf)
- [A Conceptual Historical Analysis of Distributional Semantics - CUNY](https://aclanthology.org/2024.acl-long.348/)

### 结构主义与计算语言学
- [Reconceptualizing AI Language Systems through Structuralist and... - arXiv](https://arxiv.org/html/2410.13065v1)
- [Saussurian Structuralism in Linguistics - CORE PDF](https://files01.core.ac.uk/download/pdf/234693195.pdf)

---

**编号**: MT-009
**最后更新**: 2026-03-10
