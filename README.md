# Shanghai Bund Conference | AI Research Notes

上海外滩大会（2026 年 9 月 12 日）AI 相关分享的笔记整理仓库。

现场拍摄的幻灯片、录音转写稿和事后下载的论文散落在各个来源里，这个仓库把它们收敛成一份可读的主题笔记：每条主线一份，讲清楚**问题背景 → 方法取舍 → 自己的判断**，并保留原始材料以便随时回查。

## 目录结构

| 路径 | 作用 |
|---|---|
| `README.md` | 本文件，仓库总览与阅读入口 |
| `00_overview.md` | 索引页：三条主线、建议阅读顺序、图片中识别出的重点材料 |
| `01_agent_environment_and_scaling.md` | Agent 环境构建与 Scaling 策略 |
| `02_ai_research_and_mathematics.md` | AI 科研创新与数学猜想突破 |
| `03_recursive_self_improvement_and_rsi.md` | 递归自演进与 RSI |
| `04_image_paper_method_mapping.md` | 图片 ↔ 论文/方法 ↔ 录音重点 的对应表 |
| `original_materials/` | 收到的原始材料，未重命名、未编辑 |
| `papers/` | 已下载的论文 PDF 及其 arXiv 链接 |

### `original_materials/`（25MB）

保留下载时的原始形态，作为笔记的一手依据：

- `20260912*.md`（4 份）— 各场分享的自动语音转写草稿。**存在误识别**，只能当线索用，不是权威记录。
- `IMG_20260912_*.jpg`、哈希名 `.jpg`、`wx_camera_*.jpg`（17 张）— 现场照片与幻灯片截图。
- 部分文件名是相机自动生成或哈希值，因此**以图片内容而不是文件名作为主索引**，对应关系见 `04_image_paper_method_mapping.md`。

### `papers/`（81MB）

按主线分目录存放，每个 PDF 的标题和 arXiv 链接记录在 `papers/README.md`：

- `agent_environment_and_scaling/` — MOLT、ScaleEnv、MineExplorer、UrbanGround、MAP(Map-then-Act)
- `recursive_self_improvement_and_rsi/` — OOPS (Optimal Ordered Problem Solver)

演讲页里出现过但信息不足以定位到单篇论文的（Apex Research、ASI-Bench、"Look Before You Leap"），统一记在 `papers/README.md` 的"尚未下载"一节，没有强行匹配同名论文。

## 三条主线

1. **Agent 环境与 Scaling** — Agent 的能力上限不只取决于模型大小，还取决于能否构造可控难度、接近真实、可并发运行、能持续反馈的训练环境。环境、算法和 Infra 必须联合设计。
2. **AI 科研与数学** — AI 已表现出研究助理甚至研究同事的能力，但科学研究的瓶颈正从**生成结果**转向**创新、验证、传播和责任归属**。
3. **递归自演进 / RSI** — 核心不是让 Agent 多做几个任务，而是让系统能根据经验改进自己的程序、策略、结构和训练流程。

## 阅读顺序

1. `00_overview.md` — 先建立整体地图
2. `01_agent_environment_and_scaling.md` — 训练环境与异步系统的地基
3. `02_ai_research_and_mathematics.md` — 研究型 Agent 面临的挑战
4. `03_recursive_self_improvement_and_rsi.md` — 把前两条接成能自我改进的系统
5. `04_image_paper_method_mapping.md` — 需要回查具体图片或论文时再翻

## 已知问题与使用提醒

- 录音稿来自自动转写，**英文术语、人名、论文名存在误识别**。
- 笔记内容以图片和录音的**共同信息**为准；需要正式引用论文时，应依据图片里的 arXiv 编号、GitHub 地址或论文标题逐一核对，不要直接引用本仓库笔记。
- 文中关于论文接收率、生产力倍数、未来时间点等说法，先作为**演讲者观点**记录，不代表已被严格证明。
- 本仓库为个人学习笔记，非官方材料。`original_materials/` 中的转写稿和 `papers/` 中的 PDF 版权归原作者所有，仅供个人查阅。
