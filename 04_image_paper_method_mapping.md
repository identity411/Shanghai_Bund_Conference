# 图片—论文/方法—录音重点对应表

| 图片中可识别内容 | 所属领域 | 方法/系统 | 需要关注的故事点 |
|---|---|---|---|
| ScaleEnv / Tool Graph | Agent 环境、强化学习 | 工具图、工具链扩展、难度量化 | 如何把环境复杂度拆成可控变量，并从人工设计走向自动生成 |
| MineExplore | 开放世界 Agent、多智能体 | Minecraft、任务选择、场景设计、里程碑、任务验证 | 为什么需要动态环境来训练感知—推理—行动，而不是只做静态 benchmark |
| UrbanGround | 3D 环境、导航探索 | 城市沙盒、navigation、exploration | 从工具调用扩展到开放世界，环境必须有规则、状态和长程一致性 |
| Map-then-Act | 认知地图、规划 | 先探索、建图、再执行 | 模型如何知道自己还不了解环境，并主动补充探索 |
| Look Before You Leap | 探索策略、世界模型 | Explore-then-Act、认知地图、知识增强执行 | 直接行动为什么会失败，预探索如何减少盲目动作 |
| Three components. One asynchronous loop. | 训练系统、Infra | Python agent、vLLM rollout、Async Queue、Policy actor | 环境多样、交互轮数差异巨大时，为什么需要异步训练和联合 co-design |
| MOLT | RL Infra、系统设计 | 可读基础设施、单一异步循环、配置继承 | “可理解”不是牺牲规模，而是让研究可以持续扩展和修改 |
| Apex Research | AI for Science、研究 Agent | 论文生成、实验、评审模拟、研究协作 | 生成能力提升后，验证、筛选和专家注意力成为瓶颈 |
| ASI-Bench 与数据自进化 | Benchmark、数据工程 | 研究轨迹扩展、数据自进化 | 如何快速获得高质量研究过程数据，而不只是最终答案 |
| OOPS | 程序搜索、递归自演进 | 搜索树、程序前缀、通用解法、rewrite | 一次解决题目和发现可迁移程序之间的区别 |
| Ling | 基础模型、真实世界 Agent | 高智效、可专业化、可信执行 | 研究型/专业型 Agent 需要效率、领域训练和长期可信执行同时成立 |

## 当前最值得优先消化的三张图

1. **ScaleEnv / Tool Graph**：它是“如何制造可规模化训练任务”的核心。
2. **Three components. One asynchronous loop.**：它是“如何把训练系统真正跑起来”的核心。
3. **Map-then-Act + Look Before You Leap**：它是“开放世界 Agent 如何从探索走向行动”的核心。

## 图片文件说明

文件夹中包含现场拍摄图和若干裁切/截图图。由于部分文件名是相机自动生成或哈希名，当前以图片内容而不是文件名作为主索引。后续如果补充论文 PDF、论文标题或更清晰截图，可以继续把对应 arXiv、GitHub 和作者信息补齐。

