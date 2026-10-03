# Shanghai Bund Conference | AI Research Notes

## 这批材料的三条主线

1. **Agent 环境与 Scaling**：如何把环境、任务、工具和基础设施一起做成可规模化训练系统。
2. **AI 科研与数学研究**：AI 已经能生成论文和数学结果，但真正的瓶颈逐渐转向创新性、验证和知识传播。
3. **递归自演进 / RSI**：Agent 不只是完成任务，而是能够改进自己的程序、策略、组织方式和训练流程。

## 建议阅读顺序

1. Read `01_agent_environment_and_scaling.md` for the training-environment and asynchronous-systems foundation.
2. Read `02_ai_research_and_mathematics.md` for the challenges in research agents.
3. Read `03_recursive_self_improvement_and_rsi.md` to connect the first two themes to systems that improve themselves.

## 图片中识别出的重点材料

- **ScaleEnv / Tool Graph**：用工具数量、依赖关系、任务推理深度等指标控制环境复杂度。
- **MineExplore / Minecraft 环境**：开放世界、动态环境、多智能体协作、感知—推理—行动。
- **UrbanGround**：3D 城市沙盒，用于导航和探索训练。
- **Map-then-Act / Look Before You Leap**：先探索、构建认知地图，再执行任务。
- **Three components. One asynchronous loop.**：Python agent、vLLM rollout、异步队列、policy actor 的训练闭环。
- **MOLT**：强调“可读、可理解的基础设施”本身就是研究规模化策略。
- **OOPS**：通过程序搜索发现通用解法，强调搜索、重写和长期收益。
- **ASI-Bench 与数据自进化**：关注如何快速扩展研究轨迹和数据。
- **Apex Research**：AI 生成顶会级论文的案例及其评估问题。
- **Ling**：面向真实世界的高智效、可专业化、可信执行的基础模型体系。

## 重要提醒

- 录音稿来自自动转写，英文术语、人名、论文名存在误识别。
- 本轮笔记以图片和录音的共同信息为准；需要正式引用论文时，应再根据图片里的 arXiv、GitHub 或论文标题逐一核对。
- “重要”不等于“已被严格证明”。文中关于论文接收率、生产力倍数、未来时间点等内容，先作为演讲者观点记录。
