# nvc-distill · 非暴力沟通落地工具箱

**一个从马歇尔·卢森堡《非暴力沟通（修订版）》原书独立蒸馏出来的 AI Skill。**

它把任何一句话翻译成「观察—感受—需要—请求」，重新与普世需要连结，并直接产出可发送、可落盘的成果。

支持 WorkBuddy / CodeBuddy、Claude Code、Cursor、Codex 等采用开放 Agent Skill 规范的平台。

---

## 独立性声明

本仓库**不是**任何现有 NVC Skill 的 fork 或衍生版本。

- **知识源**：马歇尔·卢森堡《非暴力沟通（修订版）》（华夏出版社，2022）epub 原书。全部方法论从原书章节逐条抽取后独立成文，未复制任何第三方 Skill 的文本。
- **借鉴的部分**：入口 `SKILL.md` + 按需加载 `references/` 的渐进式加载架构。这是开源 Agent Skill 社区的通用范式，不涉及版权。
- **溯源**：每个知识点标注原书章节 `[第X章]`；本仓库推演的内容标注 `[本仓库扩展]`。完整索引见 [`docs/SOURCES.md`](./docs/SOURCES.md)。

> 如果你在找原书，请支持购买正版。本仓库只是结构化的工具化提炼。

---

## 这版多做了三件事

| 能力 | 说明 |
|---|---|
| **原书溯源** | 每条原则标注章节来源，明确区分「原著观点」与「本仓库扩展」，附完整索引表 |
| **真实场景测试** | [`eval/cases.md`](./eval/cases.md) 含 34 条用例：触发语 / 预期路由 / 判据要点 / 翻车点 / 总评分表 |
| **安全边界** | 家暴、性侵、儿童虐待、自伤自杀等危机信号**优先于一切话术流程**，独立门禁 + 转介资源 |

另外补齐了容易被漏掉的原书内容：感受词汇表（满足 106 条 / 未满足 136 条 / 伪感受黑名单 32 条）、普世需要 7 大类、推卸责任 8 类话术、同理心的力量 5 场景、行为动机 6 类、惩罚性强制力的种类与代价、NVC 的七大应用领域。

---

## 安装

目录名必须保持为 `nvc-distill`（与 `SKILL.md` 的 `name` 字段一致）。

**WorkBuddy / CodeBuddy（Windows）**

```bash
git clone https://github.com/qfc123/nvc-distill.git "$HOME/.workbuddy/skills/nvc-distill"
```

**WorkBuddy / CodeBuddy（macOS / Linux）**

```bash
git clone https://github.com/qfc123/nvc-distill.git ~/.workbuddy/skills/nvc-distill
```

**Claude Code**

```bash
git clone https://github.com/qfc123/nvc-distill.git ~/.claude/skills/nvc-distill
```

**Cursor**

```bash
git clone https://github.com/qfc123/nvc-distill.git ~/.cursor/skills/nvc-distill
```

装完新开一个会话即可被自动召回。仓库根就是 skill 目录，clone 完直接用，无需移动文件。

---

## 怎么用

直接说你的真实场景，它会自动路由到对应的知识文件。

| 你说 | 它做什么 |
|---|---|
| "帮我改一下这句话别那么冲" | 输出对照卡片：原文 → 命中的豺狗语言类型 → NVC 改写 → 四要素拆解 → 请求自检 |
| "他说『你从来不管这个家』，我该怎么回应？" | 走同理倾听：探询式复述句，听背后的需要，不给安慰和建议 |
| "我好内疚，昨天对孩子发了脾气" | 走哀悼 + 自我宽恕：我指责自己是因为什么需要没被满足 |
| "帮我复盘昨天这场争吵" | 走冲突五步骤：双方需要清单、需要 vs 策略区分、策略矩阵 |
| "帮我表达一次真诚的感谢" | 走感激三要素，避免评判式赞美 |
| "存成文件" | 用 `assets/templates/` 下的模板落盘为 .md |

默认输出**对照卡片 + 3–5 句可直接发送的短句**；只有你明确要文件时才落盘。

---

## 目录结构

```
nvc-distill/
├── SKILL.md                        入口：安全门禁 + 四要素引擎 + 双路由 + 交付契约 + 红线
├── AGENTS.md                       维护规则：溯源标注、术语一致性、提交前自检（给 AI 看）
├── references/                     按需懒加载
│   ├── safety-boundaries.md        危机识别与处置（最高优先级）
│   ├── engine-four-components.md   四要素 + 四个核心区分 + 请求硬标准
│   ├── feelings-needs-vocab.md     感受词表 + 伪感受黑名单 + 需要 7 大类
│   ├── listening-empathy.md        同理倾听 + 同理的力量 5 场景
│   ├── self-inner-work.md          哀悼 + 自我宽恕 + 动机 6 类 + 取代诊断
│   ├── anger-conflict-force.md     愤怒 + 冲突调解 + 保护性/惩罚性强制力
│   ├── anti-patterns.md            疏离生命的语言（豺狗语言）清单
│   ├── scenarios-seven-domains.md  七大应用领域
│   └── voice-and-gratitude.md      作者语气 + 表达与接收感激
├── assets/templates/               交付模板（不进上下文，用时才读）
│   ├── rewrite-card.md             话术改写对照卡片
│   ├── session-plan.md             一次沟通剧本
│   └── conflict-workbook.md        冲突调解工作簿
├── eval/
│   └── cases.md                    34 条测试用例 + 总评分表
└── docs/
    ├── METHODOLOGY.md              核心方法论长文
    ├── SOURCES.md                  原书章节溯源索引
    ├── TERMINOLOGY.md              中英术语总表
    └── DISTILL-WORKFLOW.md         「一本书 → 一个 Skill」六步法
```

---

## 危机处置声明

本 Skill **不提供心理治疗、不做诊断、不替代危机干预**。

遇到家暴、性侵、儿童虐待、自伤自杀等信号时，它会停止话术改写与冲突调解，转入安全流程并提供求助资源（110 / 12338 / 12355 / 12356 / 希望24热线 400-161-9995）。它不会要求受害方"先同理施害者"，也不会为施害者包装话术。

如果你或身边的人正处于危险中，请优先联系上述专业渠道。

---

## 方法论边界

- 只蒸馏原书的框架、原则、清单，不复制正文。
- 案例只取骨架并用自己的话改写，标注"（源自第X章）"，短引控制在两句以内。
- 感受词表保留中英事实对应关系，编排方式（语义簇、替身索引、使用规则）为本仓库增值。
- 原书第五章的普世需要**只有 7 个分类名、无子项**；本仓库补充的子项已明确标注"通行实践补充，非原书列举"。

---

## License

[MIT](./LICENSE) © 2026 qfc123

方法论本身属于马歇尔·卢森堡与原书出版方，本仓库不主张其对《非暴力沟通》内容的权利。
