# TOMOAI Longform Skill

自媒体长文写作 skill —— 从选题验证到成稿润色，一条龙跑完一篇公众号 / 小红书长图文。

不是"帮你写篇文章"那种空话。每个阶段都有具体的方法论和产出格式：APAG 写作框架、23 种爆款标题公式、乐高式写作构件、AI 味排查清单，全部内置。

## 适用场景

- 帮我写篇文章 / 写个长文 / 写公众号文章 / 写自媒体内容
- 给了主题或素材，要生成长篇内容
- 已有初稿，想优化

不适用于短视频脚本、纯选题灵感、单条朋友圈文案这类短内容。

## 五个阶段

| 阶段 | 干什么 | 产出 |
|------|--------|------|
| **Phase 1 选题验证** | 验证选题值不值得写（已验证性 / 人群匹配 / 独特角度） | 选题方向 + 验证理由 + 切入角度 |
| **Phase 2 标题设计** | 用 23 种公式生成 3-5 个备选标题 | 带公式拆解的标题方案，选出最强一条 |
| **Phase 3 大纲搭建** | APAG 框架（Attention → Perspective → Advantage → Gamify）搭骨架 | 各部分占比 + 素材安排 + 个人故事位置 |
| **Phase 4 分段成稿** | 按大纲逐段写，乐高式构件拼装（痛点 / 例子 / 故事 / 数据 / 比喻 / 引用 / 重新框定） | 完整初稿 |
| **Phase 5 润色交付** | 7 项检查：开头 3 秒测试、标题一致性、情绪曲线、AI 味排查、个人故事、行动指引、错别字 | 终稿 + 写作元数据 |

## 你可以从不同阶段进入

不是每次都从零开始：

- 只给了模糊主题 → 从 Phase 1 开始
- 已有明确选题和素材 → 跳到 Phase 2
- 已有大纲想扩写 → 跳到 Phase 4
- 已有初稿想优化 → 直接进 Phase 5

## 核心原则

1. **人味优先**：文章必须读起来像真人写的。口语化、有情绪波动、有个人经历、有"不完美"的真实感
2. **结构先行**：先搭骨架再填肉，大纲不过关不动笔
3. **每步确认**：标题和大纲阶段必须确认后再推进，避免白费力气
4. **展示过程**：好内容不是"教你做什么"，而是"展示我是怎么做的"——用个人经历替代说教

## 文件结构

```
.
├── SKILL.md      # 完整方法论（五阶段 + APAG 框架 + 23 种标题公式 + 乐高式构件 + 润色清单）
├── LICENSE
└── README.md
```

## 安装

```bash
git clone https://github.com/NEKOINEKOI/tomoai-longform-skill ~/.workbuddy/skills/tomoai-longform-skill
```

支持 Claude Code、Codex、WorkBuddy、Cursor 等所有兼容开放 skill 标准的 Agent。Agent 不支持 Skill 也没关系，直接把 `SKILL.md` 全文贴进对话即可。

## 许可协议

本项目仅用于**个人学习与研究**，**禁止任何形式的商业使用**。

- ✅ **允许**：个人学习、研究、复制、修改、非商业性分享
- ❌ **禁止**：销售、出租、集成到付费产品、提供有偿服务、任何商业环境使用
- 📋 **要求**：保留原作者署名

详见 [LICENSE](LICENSE)。

---

<div align="center">

**扫码关注公众号「智井AI」**

<img src="https://raw.githubusercontent.com/NEKOINEKOI/tomoai-skills/main/docs/zhijing-ai-qrcode.png" alt="智井AI 公众号二维码" width="240" />

</div>

<div align="center">

Made by [@NEKOINEKOI](https://github.com/NEKOINEKOI)

</div>
