# 溯源索引 · 原书章节 → 本仓库承接

底本：马歇尔·卢森堡《非暴力沟通（修订版）》，华夏出版社，2022。epub 正文文件为 `OEBPS/Text/chapterN.xhtml`，**第 N 章 = chapter(N+4)**（chapter1–4 为中文版序、译序、序言、致谢；chapter19 为后记，chapter20 为附录）。

---

## 总表

| 原书章节 | epub 文件 | 本仓库承接 | 属性 |
|---|---|---|---|
| 第一章 由衷的给予 | chapter5 | `SKILL.md` §唯一引擎；`references/scenarios-seven-domains.md`（七大应用领域）；`docs/METHODOLOGY.md` §0 | 原著 |
| 第二章 疏离生命的语言 | chapter6 | `references/anti-patterns.md` | 原著 |
| 第三章 不带评论的观察 | chapter7 | `references/engine-four-components.md` §1 | 原著 |
| 第四章 体会与表达感受 | chapter8 | `references/feelings-needs-vocab.md` §1–§4；`references/engine-four-components.md` §2 | 原著（词表中英对应关系） |
| 第五章 为自己的感受负责 | chapter9 | `references/self-inner-work.md`（四种选择、情绪自由三阶段）；`references/feelings-needs-vocab.md` §5（需要 7 大类）；`references/engine-four-components.md` §3 | 原著（7 大类**只有类名**，无子项） |
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
- 同理心的力量六个场景
- 无法同理时的三个选项（同理急救 / 非暴力呐喊 / 离开现场）
- 哀悼与自我宽恕
- "不得不"转化为"我选择"三步
- 行为动机 6 类
- 表达愤怒四步骤、先同理对方
- 刺激 vs 原因
- 化解冲突五步骤、调解七要点、行动语言、翻译"不"（**其前置"拒绝门禁"为本仓库扩展**，见下表 [外部依据·CNVC课程]）
- 保护性 vs 惩罚性强制力；惩罚的种类、代价与局限
- 感激三要素与接收感激的两个极端
- 推卸责任的 8 类话术
- 普世需要 7 大类的**分类名**
- 感受词汇表与伪感受黑名单的**中英对应关系**
- 七大应用领域的**领域名**

### 属于本仓库扩展（非原书观点，已标注）

| 项目 | 位置 | 说明 |
|---|---|---|
| 需要 7 大类下的子项说明 | `references/feelings-needs-vocab.md` §5 | 原书只有 7 个类名，未列子项；子项取自 NVC 通行实践清单 |
| 感受词表的编排方式与语义簇 | `references/feelings-needs-vocab.md` §6 | 原书按英文首字母排列；中文语义簇为本仓库重组 |
| 伪感受的替身索引 | `references/feelings-needs-vocab.md` §3 | 替身词来自原书词表，索引关系为本仓库建立 |
| 七大应用领域每域的原则、句式、翻车点 | `references/scenarios-seven-domains.md` | 原书只列举域名并配学员来信，未给原则 |
| 全文的危机信号处置与求助资源 | `references/safety-boundaries.md` | 依据通用危机干预原则，非原书内容 |
| "以同理心化解危险"的安全修正 | `references/listening-empathy.md` §3.5 | 原书示范用同理化解危险；本仓库补充"正在发生的人身侵害优先脱离与报警" |
| 马歇尔语气 5 条指纹 | `references/voice-and-gratitude.md` §语气 | 依据全书行文特征归纳 |
| 交付模板 | `assets/templates/` | 本仓库设计 |
| 测试用例集 | `eval/cases.md` | 本仓库设计 |
| FAQ | `docs/METHODOLOGY.md` §10 | 本仓库编写 |
| 蒸馏方法六步法 | `docs/DISTILL-WORKFLOW.md` | 本仓库原创方法，与《非暴力沟通》内容无关 |
| 文档结构与溯源标注体系 | 全仓库 | 本仓库方法 |
| "翻译'不'"的前置拒绝门禁 | `references/listening-empathy.md` §六个场景 第 4 项、§同理操作 第 3–4 项；`references/anger-conflict-force.md` §三个关键技巧、§需要 vs 策略 vs 分析；`references/engine-four-components.md` §4 请求 vs 要求、§请求的配套动作；`SKILL.md` §动作路由表 / §场景路由表 | 原书第八、十一章只讲"听见'不'背后的需要"；本仓库加装"先确认这是拒绝，不追问、不推进"的门禁 [外部依据·CNVC课程：第五课 学会说"不"、第六课 对行使权威说"不"] |
| **C1** 控制与虐待（原 C 类）的处置动作、话术与"不调解"边界 | `references/safety-boundaries.md` §一 C1、§二、§三、§四、§五；`references/scenarios-seven-domains.md` §5 边界、§7 例外；`assets/templates/conflict-workbook.md` 前置检查 | 原书无危机处置内容；本仓库依据 [外部依据·WHO] 亲密伴侣暴力定义与 controlling behaviours / economic abuse 分类加装 |
| **C2** 权力不对等的处置动作、话术与求助渠道 | `references/safety-boundaries.md` §一 C2、§三；`references/scenarios-seven-domains.md` §5 边界、§7 例外 | 原书无对应内容；**不属 WHO 亲密伴侣暴力定义范围**，为本仓库依据通用危机干预原则加装 |
| **C3** 诊断、用药与物质依赖的"不诊断 + 转介"边界 | `references/safety-boundaries.md` §一 C3、§三 | 原书第十三章讲"用 NVC 取代诊断"指**不贴标签**，**不含停止医学诊疗**；本仓库补明这条边界 |
| 输出档位（快速档 / 标准档 / 学习档） | `SKILL.md` §交付契约、§固定工作流第 3 步 | 原书无输出详略分级；本仓库为降低"被评判感"而设计 |
| 档位仲裁规则（快速档绝对优先；标准档与学习档并存取学习档；路由表"兜底档位"列仅在判据未命中时使用） | `SKILL.md` §固定工作流 第 3 步、§交付契约 | 原书无输出详略分级；本仓库为消除档位双命中而设计 |
| D4 自我梳理对话（结构、触发判据、与 D1 的边界、"情绪表达类输入的定档"决策树） | `references/self-inner-work.md` §D4 · 自我梳理对话、§情绪表达类输入的定档；`assets/templates/self-checkin.md` | 结构为本仓库设计；感受候选 / 需要澄清 / 动机 6 类 / "不得不→我选择" 部分见 [第九、十一章] |
| "为感受负责"的行为责任对冲条款 | `references/self-inner-work.md` §四种选择；`references/feelings-needs-vocab.md` §3 | 原书只讲感受的根源；本仓库补充"感受的根源 ≠ 行为的责任归属" |

---

## 外部依据（非原书）

| 标签 | 来源 | 支撑的内容 | 引用边界 |
|---|---|---|---|
| `[外部依据·CNVC课程]` | CNVC 官方培训课程大纲：第五课「学会说"不"」(Learning to say no)；第六课「敢于挑战权威」「对行使权威说"不"」(Standing up to authority / Saying no to authority) | 「翻译'不'」的前置拒绝门禁：拒绝是一个完整的、不需要被翻译的回应 | 只取课程主题名作为依据，不复制课程内容 |
| `[外部依据·WHO]` | WHO 亲密伴侣暴力与性暴力中文事实页；WHO 2018 年全球、区域及国家亲密伴侣暴力流行率估算报告 | **仅 C1** 控制与虐待子类中"心理虐待""控制性行为""经济控制 / 经济虐待"的表述与处置 | 只引用定义与分类名，**不引用任何统计数字**；求助资源仍以中国大陆本地热线为准。**不覆盖 C2 权力不对等、C3 诊断与用药**——WHO 定义对象是亲密伴侣暴力，这两个子类挂 `[本仓库扩展]` |

---

## 引用边界声明

1. **不复制原书正文**。所有知识点以蒸馏后重述的方式呈现。
2. **不复述原书案例原文**。案例只取骨架并用自己的话改写，长度控制在三五句内，标注"（源自第X章）"。
3. **短引控制在两句以内**并注明章节。
4. **词表保留中英事实对应关系**（事实性内容），编排、语义簇、替身索引为本仓库增值。
5. 本仓库不声称方法论原创——它属于马歇尔·卢森堡与原书出版方。本仓库的原创部分限于上表"扩展"一列。

想深入学习请支持正版原书。
