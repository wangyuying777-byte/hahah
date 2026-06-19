# Vignette Survey 设计方案：为 NOP 机制提供直接的感知层证据

> 用途：回应审稿人对 "perceived heightened expectation" 机制缺乏直接测量的质疑。
> 论文核心机制：**NOP → solver 感知到 seeker 期望被抬高（perceived heightened expectation）→ (1) 赛前威慑部分 high-ability solvers 参与（selection/deterrence）；(2) 已参赛 solver 投入更多努力以求获胜（effort/incentive）。**
> 本方案用两套 vignette 实验直接测量 solver 的感知与意向，并把"机制"从二手数据推断升级为可检验的心理过程证据。

---

## 0. 这套设计如何逐条回应审稿人

| 审稿人质疑 | 本设计的回应手段 |
| --- | --- |
| ① 机制是 perception，但从未直接测量 perception | 用多题项量表**直接测量** perceived seeker expectation（PSE），作为显性中介变量 |
| ② 更高的首次提交评分可能来自 selection（不同类型 solver 进入 NOP）而非 effort 响应 | **Survey 2 把"是否参赛"固定为"你已经在比赛中"**，在同一参赛者内部测 effort 意向，从设计上剥离 selection；**Survey 1** 则专门测 selection（谁会被劝退） |
| ③ 为什么不同 NOP 奖金就意味着更高期望？也许只是 seeker 更有钱/更慷慨 | 同时测量竞争性构念 **perceived seeker generosity / budget（PSG）**，并加入**金钱控制条件**（标准高档位 \$280）；做**并行多重中介**，证明驱动 effort 的是 PSE 而非 PSG |
| ④ 机制章节把 behavioral outcome 与 psychological process 混为一谈 | vignette 中**奖金几乎相等（\$190 vs \$195）**，把"命名行为"与"金额"解耦；用中介+调节模型把"感知→行为"链条显性化 |

---

## 1. 构念与测量量表（Constructs & Measures）

所有 Likert 题项默认 7 点（1 = Strongly disagree ... 7 = Strongly agree），除非另注。题项用英文给出（平台/Prolific 实际投放语言），括注中文为说明，不进入问卷。

### 1.1 核心中介：Perceived Seeker Expectation（PSE，感知到的卖家期望）
衡量 solver 是否把 NOP 解读为"卖家要求更高/更难取悦"。
- PSE1. The seeker in this contest has high standards for the winning design.
- PSE2. This seeker expects higher-quality submissions than a typical seeker on this platform.
- PSE3. It would take an outstanding design to satisfy this seeker.
- PSE4. This seeker is harder to please than most seekers.
- PSE5. The quality bar for winning this contest is high.

> （中文）这是论文机制的"被测对象"。若 NOP 条件下 PSE 显著高于标准条件，即为机制的直接证据。

### 1.2 竞争性构念（替代解释）：Perceived Seeker Generosity / Budget（PSG，感知到的慷慨/预算）
直接把审稿人的替代解释"只是钱多/更慷慨"操作化，用于判别效度与并行中介。
- PSG1. This seeker simply has a larger budget to spend.
- PSG2. The slightly higher prize mainly reflects the seeker's generosity, not higher demands.
- PSG3. Offering a bit more money does not mean the seeker wants more from solvers.
- PSG4. The seeker is just being nice with the prize, not setting a higher bar.

> （中文）关键判别题。我们预期：NOP（\$195）相对标准（\$190）主要抬高 **PSE**；而标准高档位（\$280）这种"纯多给钱"主要抬高 **PSG**。这正面击穿"钱多≠要求高"的逻辑。

### 1.3 Perceived Winning Difficulty / Win Probability（感知获胜难度）
连接 PSE 与参赛/努力决策。
- DIFF1. It would be difficult to win this contest.
- DIFF2. Compared with a typical contest, my chance of winning here is lower. (用于 win-prob)
- DIFF3. Winning this contest requires clearing a very high quality bar.
- WINPROB（单题 0–100%）：Out of 100 entrants, what do you think your chance of winning this contest is? ___%

### 1.4 Perceived Competition（感知竞争强度，控制变量）
区别于"期望"机制，避免把竞争效应误算成期望效应。
- COMP1. The competition among solvers in this contest is intense.
- COMP2. Many strong solvers are likely to enter this contest.

### 1.5 Survey 1 专用：Participation / Entry Intention（参赛意向）
- ENTRY1. I would choose to enter this contest. （单条件评分式）
- ENTRY2（二选一/强制选择）：If you could only enter ONE of the two contests above, which would you enter? [Contest A / Contest B]
- ENTRY3（分配式）：Imagine you have time for only one contest this week. How likely are you to enter each? (each 0–100)

### 1.6 Survey 2 专用：Effort Intention / Anticipated Effort（努力意向）
- EFF1. I would invest a great deal of effort in my design for this contest.
- EFF2. I would spend more time on this contest than on a typical one.
- EFF3. I would submit my best possible work rather than a quick draft.
- EFF4. I would revise and refine my submission multiple times before the deadline.
- EFF5（锚定首次提交，呼应论文 solver_first_rating）：Even my very first submission would be highly polished.
- EFF_QTY（行为代理）：How many revised versions would you likely submit? [0 / 1 / 2 / 3 / 4+]
- EFF_TIME（行为代理）：About how many hours would you devote to this single contest? ___

### 1.7 努力归因（Effort Attribution，呼应"天下没有免费的午餐"）
让被试自评"为什么努力"，把 PSE 路径与 PSG 路径分开。
- ATR_exp. I would work hard because the seeker clearly expects high quality. （期望归因）
- ATR_bar. I would work hard because winning requires meeting a high bar. （期望归因）
- ATR_money. I would work hard because there is more prize money at stake. （金钱归因）
- ATR_nofree. A custom/named prize signals "no free lunch"—you must earn it with strong work. （直接对应你说的 no-free-lunch 直觉）
- 开放题 OE_why：In your own words, why would you put in this level of effort for this contest? （文本，供质性编码，补充审稿人建议的 textual analysis）

### 1.8 个体能力（用于 high- vs low-ability 调节分析）
- ABIL_self. How would you rate your design skills relative to others on such platforms? (1 = Bottom 25% ... 4 = Top 25%)
- ABIL_exp. How many design contests have you participated in? [0 / 1–5 / 6–20 / 21–50 / 50+]
- ABIL_win. Roughly what share of contests you entered did you win or place? ___%
- （若招募真实 solver，可直接用平台历史胜场切分 top 25%，与论文 top25_wins 对齐）

### 1.9 操纵检验 / 真实性 / 注意力检验
- MC1（操纵检验）：In the contest you just saw, the prize was a custom/named amount set by the seeker (not a standard platform tier). [True / False / Not sure]
- MC2（金额回忆）：What was the prize amount in the contest? [open / multiple choice]
- REAL1（真实性）：This contest scenario felt realistic and similar to contests I have seen. (1–7)
- ATT1（注意力陷阱）：To show you are reading, please select "Strongly disagree" for this item.

---

## 2. Survey 1 —— 赛前机制：感知 + 选择/威慑（Pre-entry: Perception & Self-selection）

**目标**：直接证明 (a) NOP 让 solver 感知到更高的 seeker 期望（PSE↑）；(b) 这种感知抬高了感知获胜难度，从而**劝退部分 solver，且对 high-ability solver 的劝退更强**（对应论文 Table 3：top25_wins / top25_prize 显著更低，但 num_solvers 不显著）。

### 2.1 推荐设计：混合设计（between-subjects 测感知 + within-subjects 测选择）
纯 within-subjects 同屏对比虽符合"同时展示两种比赛"的诉求，但易诱发 demand effect（被试猜到研究意图）。推荐两段式：

**Part A（between-subjects，干净测量感知与难度）**
- 随机把被试分到**仅看一个**比赛：
  - 条件 S：标准档，prize = \$190，带平台"Standard"标签。
  - 条件 N：NOP，prize = \$195，带平台"Custom / Named prize"标签。
- 其余信息**完全一致**：同一 logo brief、同一交付物、同一时长、同样显示"~100 solvers 已关注/参与"。
- 测量：PSE、PSG、DIFF、WINPROB、COMP、ENTRY1、MC1/MC2、REAL1。
- 这样可在**无对比线索**下纯净估计 NOP→PSE 的因果效应（避免被试通过两两对比反推假设）。

**Part B（within-subjects，捕捉你要的"同屏对比 + 强制选择"）**
- 在 Part A 之后，向**所有**被试展示一个模拟"任务列表页"，并排呈现 Contest A（标准 \$190）与 Contest B（NOP \$195），其余一致。
- 测量：
  - 比较式 PSE：Which seeker do you think has higher expectations for the winning design? (A 明显 / A 略 / 一样 / B 略 / B 明显)
  - 归因题（直接回应替代解释）：Why do you think Contest B offers a slightly different amount?（多选 + 强度评分）
    - Because the seeker demands higher quality. （期望）
    - Because the seeker simply has more money / is more generous. （慷慨/预算）
    - Because the seeker wants to stand out / attract attention.
    - No particular reason.
  - 难度比较：Which contest would be harder to win? (A/B/Same)
  - **强制选择 ENTRY2**：If you could enter only one, which would you choose? Why? (含开放题)

> 注：Part A 是主分析（因果识别），Part B 服务于"同屏对比 + 选择"诉求与稳健性；可用顺序随机化/反向计数平衡顺序效应。若担心 Part A 污染 Part B，可在两段间设缓冲题。

### 2.2 假设与预测（Survey 1）
- S1-H1：PSE(N) > PSE(S)。**→ 机制的直接感知证据。**
- S1-H2：DIFF(N) > DIFF(S)，WINPROB(N) < WINPROB(S)。
- S1-H3（中介）：NOP → PSE → DIFF/WINPROB（PSE 中介 NOP 对感知难度的影响）。
- S1-H4（威慑 + 能力调节）：PSE↑ 降低 ENTRY；且该负向效应在 **high-ability** 被试中更强（NOP × ability 交互），与论文"high-ability solver 被劝退"一致。
- S1-H5（判别）：在 \$190 vs \$195 这种"金额几乎相同"的对比里，PSG 差异应很小或不显著，而 PSE 差异显著——直接说明感知到的是"要求更高"而非"更有钱"。

---

## 3. Survey 2 —— 赛中机制：感知 + 努力（In-contest: Perception & Effort）

**目标**：在**参赛已成既定事实**的情境下，证明 NOP 通过 PSE（而非 PSG）促使 solver 投入更多努力、产出更高质量（对应论文 Table 4/5：solver_first_rating、solver_min_rating、solver_max_rating 在 NOP 下更高）。这一步把 selection 从 effort 中彻底剥离——因为"你已经在比赛里了"。

### 3.1 设计：between-subjects，含"金钱控制"条件
统一情境开场（所有条件相同）：
> "On this platform, the standard prize for a logo-design contest is usually **\$190**. A seeker has just posted a logo-design contest. **You have already entered this contest**, and you are competing against about **100 other solvers** for the prize. The deliverables, rules, and process are the platform's usual ones."

随机分配到以下条件（核心 3 条，必要时加第 4 条）：

| 条件 | 描述 | 作用 |
| --- | --- | --- |
| **C1 标准基线** | 这是一个标准档比赛，prize = **\$190**（Standard tier） | baseline |
| **C2 NOP（同金额）** | seeker 自定义命名了奖金 = **\$195**（Custom/Named prize） | 核心处理：命名行为，金额几乎不变 |
| **C3 标准高档（纯多给钱）** | 这是一个标准档比赛，prize = **\$280**（Standard tier B） | **金钱控制**：钱更多但无 NOP 命名 |
| （可选）**C4 NOP 高金额** | seeker 命名奖金 = **\$280** | 拆解金额×命名的交互 |

> （中文）**C2 vs C1** 隔离"命名/NOP"效应（金额几乎相等，\$5 不构成实质激励）。
> **C3** 是回应审稿人的关键：如果"钱多就更努力/更高期望"成立，C3 应该和 C2 一样甚至更强；但我们预测——C3 主要抬高 **PSG（慷慨/预算感知）**，而努力并不随之上升（甚至按论文发现，更高奖金因竞争加剧反而压低个体努力）；只有 **C2 的 NOP 命名**通过 **PSE** 抬高努力。这就同时证明了"是命名传递的期望、不是钱"。

### 3.2 测量顺序（Survey 2）
1. 情境呈现 + REAL1、MC1/MC2、ATT1。
2. **感知**：PSE、PSG、COMP（先测感知，后测努力意向，符合机制因果序）。
3. **努力**：EFF1–EFF5、EFF_QTY、EFF_TIME。
4. **努力归因**：ATR_exp / ATR_bar / ATR_money / ATR_nofree + 开放题 OE_why。
5. 个体能力 ABIL_*、人口学。

### 3.3 假设与预测（Survey 2）
- S2-H1（感知）：PSE(C2) > PSE(C1)。**→ 赛中情境下的直接感知证据。**
- S2-H2（努力）：Effort(C2) > Effort(C1)，且 EFF5（首次提交即高质量）↑，呼应 solver_first_rating。
- S2-H3（中介，核心）：C2 → PSE → Effort（PSE 显著中介 NOP 对努力的影响）。
- S2-H4（判别/反驳"钱多"）：
  - PSE(C2) ≈ 或 > PSE(C3)，但 PSG(C3) > PSG(C2)：钱多主要被解读为"慷慨"，命名才被解读为"要求高"。
  - **并行多重中介**（PROCESS Model 4，PSE 与 PSG 同时入模）：NOP→PSE→Effort 的间接效应显著；NOP→PSG→Effort 不显著或为负。→ 直接证明驱动努力的是期望感知而非慷慨感知。
- S2-H5（归因）：C2 下 ATR_exp / ATR_bar / ATR_nofree 评分高于 ATR_money；开放题文本中"高标准/必须配得上/no free lunch"类编码占比在 NOP 显著更高。
- S2-H6（与竞争机制区分）：控制 COMP 后，PSE→Effort 仍显著；且更高奖金（C3）若提高 COMP 反而压努力，与 PSE 路径方向相反，进一步分离两套机制。

---

## 4. 抽样、招募与样本量（Sampling）

- **被试**：理想是**平台真实 solvers**（最具说服力，且可用平台历史胜场客观切分 high-ability，与论文 top25 对齐）。若不可得，则在 Prolific / 设计众包社区（99designs、Fiverr、Upwork 设计师）招募**有 logo/平面设计众包经验**的被试，并用 ABIL_exp 作筛选门槛（如至少参加过 1 次设计比赛）。
- **筛选**：前置 screener（是否做过设计/众包比赛）；不合格者剔除。
- **样本量**：
  - 中介分析（bootstrap 间接效应，中等效应）建议**每组 ≥ 150–200**。
  - Survey 1：Part A 两组 → 总 n ≈ 350–450（留出剔除）。
  - Survey 2：三组（C1/C2/C3）→ 总 n ≈ 500–650；若含 C4 则 ≈ 650–850。
  - 建议先做小规模 pilot（每组 ~30）做量表信度与 vignette 真实性检验。
- **质量控制**：注意力检验（ATT1）、操纵检验（MC1）、最短作答时长、真实性下限（REAL1≥4 方进入主分析，并报告敏感性）。

---

## 5. 量表信效度与分析计划（Analysis Plan）

### 5.1 测量层面
- 信度：各多题项构念 Cronbach's α / CR ≥ 0.7。
- **判别效度（关键）**：对 PSE 与 PSG 做 CFA / EFA，报告 AVE 与 √AVE > 构念间相关（Fornell–Larcker），或 HTMT < 0.85，证明"期望感知"与"慷慨/预算感知"是**两个可区分的构念**——这是回应审稿人"钱多≠要求高"的统计基础。
- 共同方法偏差：Harman 单因子检验 / 标记变量法。

### 5.2 假设检验
- **操纵检验**：MC1 通过率；NOP 条件被正确识别。
- **主效应**：独立样本 t / ANOVA + 事后比较，比较各条件的 PSE、PSG、DIFF、Effort、Entry。报告效应量（Cohen's d / η²）。
- **中介**（PROCESS Model 4，5000 次 bootstrap）：
  - Survey 1：NOP → PSE → (DIFF, Win-prob, Entry)。
  - Survey 2：NOP → PSE → Effort。
  - **并行双中介**：同时放入 PSE 与 PSG，比较两条间接路径，证明 PSE 路径显著、PSG 路径不显著（核心反驳替代解释）。
- **调节中介**（PROCESS Model 7/14，Survey 1 为主）：ABIL 调节 PSE→Entry（high-ability 被劝退更强），对齐论文 selection 发现。
- **质性补充**：对 OE_why 开放文本做编码（期望/高标准 vs 金钱/慷慨 vs 竞争），报告各主题频次随条件的变化，呼应审稿人建议的"textual analysis of solver communications"。

### 5.3 结果如何写回论文（mapping）
| 论文原二手数据发现 | 本 survey 提供的直接证据 |
| --- | --- |
| NOP→success↑（Table 2） | 整体机制闭环的心理基础 |
| top25_wins/prize↓（Table 3，selection） | Survey 1：PSE↑→感知难度↑→high-ability 参赛意向↓（调节中介） |
| solver_first_rating↑（Table 4/5，effort） | Survey 2：参赛固定下，NOP→PSE↑→effort↑、首次提交质量意向↑ |
| solver_min/max_rating↑（effort 全域上移） | Survey 2：EFF_QTY/EFF_TIME/最优努力意向↑ |
| 排除"仅奖金"解释（Table 6） | Survey 2 的 C3 金钱控制条件 + PSE/PSG 判别 + 并行中介，直接在感知层证明"是命名传递期望，不是钱" |

---

## 6. 关键设计要点小结（给审稿回复信用）

1. **直接测量了 perception**（PSE 多题项量表），不再是从行为反推。
2. **把 selection 与 effort 分开测**：Survey 1 测谁被劝退，Survey 2 把"已参赛"设为前提、纯测努力，从设计上排除 selection 解释首次提交评分。
3. **正面拆解"只是钱多/更慷慨"**：金额近乎相等（\$190 vs \$195）+ 标准高档金钱控制条件（\$280）+ PSE/PSG 判别效度 + 并行双中介，三重证据表明驱动效应的是"命名→更高期望"而非"更多预算→更慷慨"。
4. **质性文本编码**回应审稿人"survey or textual analysis"的具体建议。
5. **可与平台真实 solver 能力数据对齐**（top 25%），与论文实证口径一致，增强外部效度。

---

## 附录 A：Survey 2 vignette 范例文案（NOP 条件 C2，可直接改写部署）

> **Background.** On this crowdsourcing platform, seekers post logo-design contests and award the full prize to the single submission they like best. If no submission satisfies the seeker, no prize is awarded. The standard prize for such a contest is usually **\$190**.
>
> **This contest.** A seeker has just posted a logo-design contest. Instead of using the standard prize, the seeker has **named their own custom prize of \$195** (the platform marks this contest with a "Custom prize" tag). The brief, deliverables, duration, and rules are the platform's usual ones.
>
> **Your situation.** You have **already entered** this contest. You are now competing against about **100 other solvers**. Please answer the following questions about how you perceive this contest and how you would approach it.

（C1 把第二段替换为 "the seeker is offering the **standard \$190** prize (Standard tier)"；C3 替换为 "the **standard \$280** prize (Standard tier B)"；其余完全一致。）

## 附录 B：Survey 1 Part B 同屏对比版式（示意）

```
[ Task Listing Page ]
┌───────────────────────────┬───────────────────────────┐
│ Contest A                 │ Contest B                 │
│ Logo design               │ Logo design               │
│ Prize: $190  [Standard]   │ Prize: $195  [Custom prize]│
│ Brief: <identical text>   │ Brief: <identical text>   │
│ Duration: 7 days          │ Duration: 7 days          │
│ Entrants so far: ~100     │ Entrants so far: ~100     │
└───────────────────────────┴───────────────────────────┘
```
（A/B 左右位置随机化以平衡位置效应。）
