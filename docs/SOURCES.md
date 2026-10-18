# 溯源索引 · 原书章节 → 本仓库承接

底本：马歇尔·卢森堡《非暴力沟通（修订版）》，华夏出版社，2022。epub 正文文件为 `OEBPS/Text/chapterN.xhtml`，**第 N 章 = chapter(N+4)**（chapter1–4 为中文版序、译序、序言、致谢；chapter19 为后记，chapter20 为附录）。

---

## 总表

| 原书章节 | epub 文件 | 本仓库承接 | 属性 |
|---|---|---|---|
| 第一章 由衷的给予 | chapter5 | `SKILL.md` §唯一引擎；`references/scenarios-seven-domains.md`（七大应用领域）；`docs/METHODOLOGY.md` §0 | 原著 |
| 第二章 疏离生命的语言 | chapter6 | `references/anti-patterns.md` | 原著 |
| 第三章 不带评论的观察 | chapter7 | `references/engine-four-components.md` §1 | 原著 |
| 第四章 体会与表达感受 | chapter8 | `references/feelings-needs-vocab.md` §1–§4；`engine-four-components.md` §2 | 原著（词表中英对应关系） |
| 第五章 为自己的感受负责 | chapter9 | `references/self-inner-work.md`（四种选择、情绪自由三阶段）；`feelings-needs-vocab.md` §5（需要 7 大类）；`engine-four-components.md` §3 | 原著（7 大类**只有类名**，无子项） |
| 第六章 提出请求，丰盈生命 | chapter10 | `references/engine-four-components.md` §请求三标准、配套动作 | 原著 |
| 第七章 以同理心倾听 | chapter11 | `references/listening-empathy.md` | 原著 |
| 第八章 同理心的力量 | chapter12 | `references/listening-empathy.md` §同理心的力量、说"不"、沉默 | 原著 |
| 第九章 爱自己 | chapter13 | `references/self-inner-work.md`（哀悼、自我宽恕、不得不→我选择、动机 6 类） | 原著 |
| 第十章 充分表达愤怒 | chapter14 | `references/anger-conflict-force.md` §愤怒 | 原著 |
| 第十一章 化解冲突，调和纷争 | chapter15 | `references/anger-conflict-force.md` §冲突 | 原著 |
| 第十二章 为了保护使用强制力 | chapter16 | `references/anger-conflict-force.md` §强制力 | 原著 |
| 第十三章 解放自我，协助他人 | chapter17 | `references/self-inner-work.md` §取代诊断 | 原著 |
| 第十四章 用非暴力沟通表达感激与赞赏 | chapter18 | `references/voice-and-gratitude.md` | 原著 |
| 附录 人类共有的一些基本感受 | chapter20 | `references/feelings-needs-vocab.md` §4 精简速查表 | 原著 |

---

## 原著观点 vs 本仓库扩展

### 属于原书观点（已溯源）

- 四要素（观察—感受—需要—请求）及其两个方向
- 四个核心区分：观察 vs 评论 / 感受 vs 想法 / 需要 vs 策略 / 请求 vs 要求
- 请求的三条硬标准（正向、具体可行、此刻可回应）与两条配套动作
- 听到不中听的话的四种选择
- 情绪自由三阶段（情绪的奴隶 / 面目可憎 / 情绪的主人）
- 妨碍同理的行为清单
- 同理心的力量五个场景
- 无法同理时的三个选项（同理急救 / 非暴力呐喊 / 离开现场）
- 哀悼与自我宽恕
- "不得不"转化为"我选择"三步
- 行为动机 6 类
- 表达愤怒四步骤、先同理对方
- 刺激 vs 原因
- 化解冲突五步骤、调解七要点、行动语言、翻译"不"
- 保护性 vs 惩罚性强制力；惩罚的种类、代价与局限
- 感激三要素与接收感激的两个极端
- 推卸责任的 8 类话术
- 普世需要 7 大类的**分类名**
- 感受词汇表与伪感受黑名单的**中英对应关系**
- 七大应用领域的**领域名**

### 属于本仓库扩展（非原书观点，已标注）

| 项目 | 位置 | 说明 |
|---|---|---|
| 需要 7 大类下的子项说明 | `feelings-needs-vocab.md` §5 | 原书只有 7 个类名，未列子项；子项取自 NVC 通行实践清单 |
| 感受词表的编排方式与语义簇 | `feelings-needs-vocab.md` §6 | 原书按英文首字母排列；中文语义簇为本仓库重组 |
| 伪感受的替身索引 | `feelings-needs-vocab.md` §3 | 替身词来自原书词表，索引关系为本仓库建立 |
| 七大应用领域每域的原则、句式、翻车点 | `scenarios-seven-domains.md` | 原书只列举域名并配学员来信，未给原则 |
| 全文的危机信号处置与求助资源 | `references/safety-boundaries.md` | 依据通用危机干预原则，非原书内容 |
| "以同理心化解危险"的安全修正 | `listening-empathy.md` §3.5 | 原书示范用同理化解危险；本仓库补充"正在发生的人身侵害优先脱离与报警" |
| 马歇尔语气 5 条指纹 | `voice-and-gratitude.md` §语气 | 依据全书行文特征归纳 |
| 交付模板 | `assets/templates/` | 本仓库设计 |
| 测试用例集 | `eval/cases.md` | 本仓库设计 |
| FAQ | `docs/METHODOLOGY.md` §10 | 本仓库编写 |
| 蒸馏方法六步法 | `docs/DISTILL-WORKFLOW.md` | 本仓库原创方法，与《非暴力沟通》内容无关 |
| 文档结构与溯源标注体系 | 全仓库 | 本仓库方法 |

---

## 引用边界声明

1. **不复制原书正文**。所有知识点以蒸馏后重述的方式呈现。
2. **不复述原书案例原文**。案例只取骨架并用自己的话改写，长度控制在三五句内，标注"（源自第X章）"。
3. **短引控制在两句以内**并注明章节。
4. **词表保留中英事实对应关系**（事实性内容），编排、语义簇、替身索引为本仓库增值。
5. 本仓库不声称方法论原创——它属于马歇尔·卢森堡与原书出版方。本仓库的原创部分限于上表"扩展"一列。

想深入学习请支持正版原书。
