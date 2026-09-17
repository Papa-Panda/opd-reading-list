# OPD Reading List — On-Policy Distillation

OPD = On-Policy Distillation（在线策略蒸馏）。

来源：Bilibili UP主"丁师兄大模型"视频《10 篇值得阅读的 OPD Paper｜2026 年，别死磕 RL 了》评论区整理的清单（视频简介为空）；arXiv 链接按论文标题交叉验证补上。

## 清单（10 篇）

| # | Paper | arXiv | 一句话 |
|---|-------|-------|--------|
| 1 | [A Survey of On-Policy Distillation for Large Language Models](https://arxiv.org/abs/2604.00626) | `2604.00626` | OPD 综述：定义、方法分类与开放问题 |
| 2 | [The Many Faces of On-Policy Distillation: Pitfalls, Mechanisms, and Fixes](https://arxiv.org/abs/2605.11182) | `2605.11182` | OPD 的典型陷阱、内在机制与系统性修复 |
| 3 | [ExOPD: Learning beyond Teacher — Generalized On-Policy Distillation with Reward Extrapolation](https://arxiv.org/abs/2602.12125) | `2602.12125` | 用 reward 外推实现 generalized OPD，让学生超越老师 |
| 4 | [Revisiting On-Policy Distillation: Empirical Failure Modes and Simple Fixes](https://arxiv.org/abs/2603.25562) | `2603.25562` | 实证研究 OPD 的失败模式并给出简单修复 |
| 5 | [Lightning OPD: Efficient Post-Training for Large Reasoning Models with Offline On-Policy Distillation](https://arxiv.org/abs/2604.13010) | `2604.13010` | 离线 OPD：大推理模型的高效后训练 |
| 6 | [Prune-OPD: Efficient and Reliable On-Policy Distillation for Long-Horizon Reasoning](https://arxiv.org/abs/2605.07804) | `2605.07804` | 面向长程推理的高效可靠 OPD（剪枝） |
| 7 | [Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models](https://arxiv.org/abs/2601.18734) | `2601.18734` | On-policy 自蒸馏：不需要外部 teacher |
| 8 | [f-OPD: Stabilizing Long-Horizon On-Policy Distillation with Freshness-Aware Control](https://arxiv.org/abs/2605.17862) | `2605.17862` | freshness-aware 控制稳定长程 OPD 训练 |
| 9 | [DiffusionOPD: A Unified Perspective of On-Policy Distillation in Diffusion Models](https://arxiv.org/abs/2605.15055) | `2605.15055` | 扩散模型中的 OPD 统一视角 |
| 10 | [Uni-OPD: Unifying On-Policy Distillation with a Dual-Perspective Recipe](https://arxiv.org/abs/2605.03677) | `2605.03677` | 双视角统一配方统一 OPD |

## 结构

```
opd-reading-list/
├── README.md                 # 清单
├── PAPER_TEMPLATE.md         # 读 paper 的固定模板
├── reading-log.csv           # 阅读进度索引
└── papers/
    └── {year}_{short-name}/  # 每篇一个文件夹
        └── NOTES.md          # 按模板填（元信息已预填）
```

## 怎么用

1. 按清单顺序（或挑兴趣）读一篇 paper
2. 把 `papers/{...}/NOTES.md` 按模板填完
3. 在 `reading-log.csv` 把该行 Status 改为 `done`
