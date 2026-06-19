# Vignette Survey Design: 为 NOP→Perceived Heightened Expectation 机制提供直接证据

> 针对 ISR 审稿人意见而设计的两套互补 Vignette 实验。
>
> - **Survey 1 (赛前 / Pre-entry)**：检验 *Perceived Heightened Expectation → Deterrence of High-ability Solvers* 机制。
> - **Survey 2 (赛中 / Post-entry)**：检验 *Perceived Heightened Expectation → Greater Effort by Participating Solvers* 机制，并直接排除"seeker只是更大方/钱多"的替代解释。
>
> 设计原则：(1) 直接测量 perception；(2) 同时测量并排除多个 alternative attributions；(3) 区分 selection vs. effort response；(4) 高/低 ability solver 异质性可识别；(5) 真实情境化的 stimuli；(6) 行为意图 + 开放题双重验证。

---

## 0. 总体设计

### 0.1 样本与招募 (两套共同)

- **目标人群**：在 crowdsourcing 平台（99designs, Designhill, Crowdspring, DesignCrowd, 猪八戒, ZBJ 等）有实际 logo / 视觉设计参赛经历的 solvers。
- **优先渠道**：
  1. 与论文使用数据的同一平台合作，向其平台 solver 直接发放（最理想，可消除生态有效性质疑）；
  2. 在专业设计师社区（Behance, Dribbble, Reddit r/graphic_design, 国内"站酷"）发放；
  3. Prolific / Upwork 上 pre-screen 为 *freelance designer with crowdsourcing contest experience*。
- **样本量**：每套 ≥ 250（粗略检验 d ≈ 0.25 时的 80% power），最好 300–400 以支持 ability 异质性子样本分析。
- **筛选题 (screening)**：
  - 是否参加过至少 1 个 logo / visual-design 在线 contest？(必须 Yes 才能继续)
  - 过去 12 个月内参赛次数（用于后续 ability segmentation）。
- **报酬**：固定报酬 + 通过 attention check 的 bonus。
- **预注册**：建议在 AsPredicted / OSF 预注册假设、样本量、主要分析。

### 0.2 通用控制变量 (Block 末尾收集)

- 参赛次数、赢过的次数、累计奖金（用于自定义 *high-ability* dummy）；
- 平台从业年数；
- 自评设计能力 (1–7)；
- 性别、年龄、教育、所在地区；
- 主要收入是否依赖 crowdsourcing。

### 0.3 通用质量控制

- 1 个直接 attention check（"请选择第三个选项"）；
- 1 个 instructional manipulation check（IMC, Oppenheimer et al. 2009）；
- 1 个 manipulation check：直接询问哪一个 contest 的 prize 是 standard / NOP；
- 答题时长 < 平均时长 1/3 的样本剔除；
- 直线作答（straight-lining）样本剔除。

---

## 1. Survey 1 — 赛前 (Pre-entry) Vignette
### 目标：检验 *NOP → Perceived Higher Expectation → 高能力 solver 被 deter*

### 1.1 设计要点

- **Within-subject** 设计：每位 respondent 同时看到两个 contest（标准 vs NOP），主要构念都对两个 contest 各测一次。优势：直接对比，统计效力高，且类似于实际平台 solver 浏览 listing page 的真实场景。
- **顺序随机化**：A/B 两版本随机展示左右 / 上下位置，以排除呈现顺序效应。
- **匹配设计**：两个 contest 在 *task description、风格偏好、颜色偏好、duration、seeker历史、参赛人数* 等方面完全一致，**仅 prize 形式不同**：
  - Contest A (Standard): prize = **$190** (平台 Tier A 标签 "Standard");
  - Contest B (NOP): prize = **$201** (NOP 标签 "Custom Prize")。
- 选用 $190 vs $201 既贴合原文实证设置（仅 ~5% 差异），又能直接呼应审稿人第 6.1 节"prize amount 排除"的逻辑——若 perceptions 仍然显著不同，则证据无法用 monetary value 解释。

### 1.2 Stimuli 示意 (mock platform listing card)

```
┌────────────────────────────────────────────┐
│  [LOGO needed for Northwind Coffee Roasters]│
│  Prize: $190  (Standard)                    │
│  Duration: 7 days                           │
│  Color preference: Brown / Cream            │
│  Style: Modern, Minimalist                  │
│  Brief: ...140 words description...         │
│  Attachments: 2  |  Examples: 5             │
└────────────────────────────────────────────┘

┌────────────────────────────────────────────┐
│  [LOGO needed for Eastwind Coffee Roasters] │
│  Prize: $201  (Custom Prize)  ⭐ NOP        │
│  Duration: 7 days                           │
│  Color preference: Brown / Cream            │
│  Style: Modern, Minimalist                  │
│  Brief: ...140 words description...         │
│  Attachments: 2  |  Examples: 5             │
└────────────────────────────────────────────┘
```

> 注：建议用平台真实截图风格 mock。两个 brand name (Northwind / Eastwind) 随机分配到 standard / NOP 条件，以排除品牌名效应。

### 1.3 问卷结构与题项

#### Block 0. 同意书 + Screening + 平台情境介绍

- "在接下来的问卷中，你会看到来自一个 logo-design crowdsourcing 平台的两个真实风格的 contest 卡片，请仔细阅读，并把自己设想为正在浏览平台 listing 页面、考虑参与的 solver。"
- 解释 *standard prize tier* vs *custom (NOP) prize* 的平台机制（确保所有 respondent 对两种 prize-setting 方式有共同认知）。

#### Block 1. 阅读 Stimuli (两张卡片同时呈现)

- 强制最低停留时间（30 秒）。
- 阅读后插入一道 manipulation check：
  - "Contest A 的 prize 是按平台标准档位还是由 seeker 自己设定？" / "Contest B 同上。"

#### Block 2. Perceived Seeker Expectations (PE) — 主构念

> 对 Contest A 和 Contest B **分别**测量 (7-point Likert, Strongly disagree → Strongly agree)。建议至少 4 题取平均；α 期望 ≥ 0.80。

1. The seeker of this contest has **high quality expectations** for the winning design.
2. To win this contest, a submission would need to **meet a very demanding quality bar**.
3. The seeker would likely **reject mediocre submissions** rather than accept the best of a weak pool.
4. Compared with the average contest on this platform, **the seeker is asking for more**.
5. (Reverse) The seeker seems **easy to satisfy**.

#### Block 3. Attribution for the Prize Choice (PA) — **直接回应审稿人**

> 题干："In your opinion, why might the seeker of **Contest B** have chosen to set a custom prize of $201 rather than the standard $190?" (7-point: 1 = Not at all a reason, 7 = Definitely a reason)

为了同时测量 target 与 alternative 解释，每位 respondent 对以下原因都打分（随机化展示顺序）：

| Code | Attribution Item | 对应解释 |
|------|------------------|----------|
| PA1 | The seeker has **higher quality expectations** than typical seekers. | **Target (heightened expectation)** |
| PA2 | The seeker wants to **signal a high standard** to attract serious solvers. | **Target (signaling)** |
| PA3 | The seeker is simply a **generous person**. | Alt-1 Generosity |
| PA4 | The seeker has a **larger budget / more money to spend**. | Alt-2 Budget abundance |
| PA5 | The seeker wants the contest to **stand out / grab attention** on the listing page. | Alt-3 Attention/Distinctiveness |
| PA6 | The seeker has **unique or unusual requirements** not captured by standard tiers. | Alt-4 Task-uniqueness |
| PA7 | The seeker is **trying random prices** without a particular reason. | Alt-5 Noise / no signal |
| PA8 | The seeker **does not understand** the platform's standard tiers. | Alt-6 Inexperience |

随后插入 1 道 forced-ranking 题，让 respondent **排出最主要的 3 个原因**，以获得更稳健的相对重要性证据。

最后 1 道开放题（用于后续 LDA / 人工编码）：
- "In your own words, what does it tell you about this seeker that they chose $201 rather than the standard $190?"

> **关键检验**：若 PA1+PA2（target）显著高于 PA3+PA4（最强的"钱多/大方"alternative），即可直接驳斥审稿人提出的"could be that just the prize is higher, not really that the seeker is asking more"。

#### Block 4. Perceived Difficulty of Winning (PD)

> 对两个 contest 分别测 (7-point)

1. It would be **difficult to win** this contest.
2. The chance that **any single submission gets selected** as the winner is low.
3. The **bar for being chosen** as the winner is high.
4. I would need to **invest a lot of effort** to have a real chance of winning.

#### Block 5. Participation Intention (PI) & Choice — **测 deterrence 效应**

1. (各自测) "How likely would you be to **submit a design** to this contest?" (1 = Very unlikely → 7 = Very likely)
2. (各自测) "How confident are you that **you personally could win** this contest?" (1 = Not at all → 7 = Very confident)
3. **Forced choice**: "If you could only enter one of the two contests, which would you choose?" [A / B / Indifferent]
4. **Allocation**: "If you had time to participate in only 10 hours of contests this week, how would you split that time between these two?" (slider, sums to 10)
5. 开放题: "What is the main reason you would (or would not) enter Contest B (NOP)?"

#### Block 6. Solver Ability & Controls (见 §0.2)

- 历史参赛次数（连续变量 + 三分位）
- 历史获胜次数（用于定义 top-25% high-ability dummy，复刻论文 §5.1 的操作化）
- 自评设计能力 (1–7)
- 设计领域专业训练 (Y/N)
- demographics

#### Block 7. (可选) Open-ended de-brief

- "请告诉我们你认为本研究在研究什么。" → 用于排除 demand effects 严重的样本。

### 1.4 主分析

| 分析 | 方法 | 假设 |
|------|------|------|
| H1a: PE(NOP) > PE(Standard) | paired t-test / WLS with subject FE | NOP 显著提升感知预期 |
| H1b: PA1+PA2 > PA3+PA4 | within-subject paired contrast | "高预期"归因强于"钱多/大方"归因 |
| H1c: PD(NOP) > PD(Standard) | paired t-test | NOP 显著提升感知难度 |
| H1d (deterrence): High-ability solvers 在 forced-choice 中更倾向选 Standard | logit; ability × treatment interaction | 复刻并直接证伪 selection-only 解释 |
| H1e: PI(NOP) − PI(Standard) 随 self-rated ability 上升而下降？(non-monotonic 预期：top-25% 显著下降) | spline / interaction | 与论文 §5.1 现场证据一致 |
| Mediation: PE → PI / Choice | within-subject mediation (Judd et al. 2001; Montoya & Hayes 2017) | PE 中介 NOP 对 PI 的影响 |
| Robust 排除 alternative: 控制 PA3/PA4 后 PE 的中介系数仍然显著 | bootstrapped mediation | 直接排除"钱多"解释 |

---

## 2. Survey 2 — 赛中 (Post-entry) Vignette
### 目标：检验 *已参赛 solver 在 NOP contest 中付出更多 effort* 机制；直接排除"钱多 / seeker generous"的替代解释

### 2.1 设计要点

- **2-condition, between-subject** 主设计 + **within-subject after-condition extension**（详见下文）。原因：在 effort intention 的测量上，让同一个人评两种 contest 容易产生 demand artifact（"我应该对 NOP 更努力"）；between-subject 更干净。
  - Condition S (Standard): 参加一个 $190 的 standard contest；
  - Condition N (NOP): 参加一个 $195 的 NOP contest（比 standard 只高 ~2.6%，即审稿人最关注的"prize 几乎一样"情形）。
- **Within-subject extension**：在主测之后，再给被试呈现*另一种 prize 形式*的对照 scenario，做 within-subject 重测（次要分析，提升 statistical power）。
- **Sample 与平台情境**：明确告知"平台中 standard tiers 通常是 $190"，让 $195 显得是 seeker 主动 NOP 的而非比 standard 高很多。

### 2.2 Stimuli 与情境描述

主 vignette（向被试呈现）：

> *"Please carefully read the following scenario and imagine yourself in the situation described."*
>
> *On the crowdsourcing platform, the standard prize tier for logo-design contests is **$190**. A seeker has just posted a new logo-design contest. The contest details are:*
>
> *— Prize: **\$195 (Custom Prize, set by the seeker — NOP)***  ←  (Condition N)
> *— Prize: **\$190 (Standard Tier A)***  ←  (Condition S)
> *— Duration: 7 days*
> *— Color preference: Brown / Cream*
> *— Style preference: Modern, Minimalist*
> *— Brief: 140-word description (identical across conditions)*
>
> ***You have just submitted your first design to this contest, so you are officially competing.** You will be competing with approximately **100 other solvers** for the prize. The seeker will pick **at most one** winner; if none of the submissions satisfies the seeker, **no prize will be awarded** and your effort will not be compensated.*

接着进入度量。

### 2.3 问卷结构

#### Block 0. 同意书 + Screening (同 Survey 1)

#### Block 1. 阅读 vignette + 强制理解题

- "What is the prize amount?" (回答正确才能继续)
- "Was the prize set by the seeker (custom) or chosen from the platform's standard tiers?"
- "How many competitors are you facing?"

#### Block 2. Perceived Seeker Expectations (PE) — 复用 Survey 1 PE 量表 (4–5 题)

#### Block 3. Attribution Battery (PA) — 复用 Survey 1 PA1–PA8

> 给 Condition N 被试：题干 = "Why do you think this seeker chose a custom $195 rather than the standard $190?"
> 给 Condition S 被试（用于对比）：题干 = "Why do you think this seeker chose the standard $190 tier?"（项目相应改写）

#### Block 4. Effort Intention (EI) — **核心 DV**

> 7-point Likert, 1 = Strongly disagree → 7 = Strongly agree。

1. I would invest **significant effort** in this contest.
2. I would spend **more time** on this contest than on a typical logo contest.
3. I would create **multiple iterations** of my design before finalizing.
4. I would **carefully refine** my submission to maximize quality.
5. I would aim for a **higher quality bar** than I usually do.
6. I would **seek feedback** (e.g., from peers, the seeker's intermediate ratings) before submitting my best work.

外加 3 道**行为/资源 anchor 题**（连续变量，更难受 demand effect 污染）：

7. About **how many hours in total** would you invest in your designs for this contest? [open-ended numeric]
8. About **how many distinct designs** would you submit? [open-ended numeric]
9. On a 1–5 scale, **what is the minimum quality** (1 = a quick first draft, 5 = your absolute best work) you would be willing to submit?

#### Block 5. Reasons for Exerting Effort (RE) — **直接驳斥替代解释**

> 题干: "Earlier you indicated how much effort you would invest in this contest. To what extent does each of the following reasons explain **why** you would invest that level of effort?" (1 = Not at all, 7 = Very much)

随机化展示顺序：

| Code | Reason | 对应机制 |
|------|--------|---------|
| RE1 | **Because the seeker seems to expect high-quality work**, and meeting that bar is necessary to win. | **Target (heightened expectation)** |
| RE2 | **Because if the seeker is willing to set a non-standard price, the seeker likely has a clear, demanding vision** — *"there is no free lunch."* | **Target (no-free-lunch belief)** |
| RE3 | Because **the prize money is large enough** to be worth more effort. | Alt-1 Monetary incentive |
| RE4 | Because the seeker seems **generous**, and I want to **reciprocate** with high effort. | Alt-2 Reciprocity / generosity |
| RE5 | Because **the contest looks special / stands out**, so I want to do well on it. | Alt-3 Attention / salience |
| RE6 | Because the seeker likely has **more budget**, so the chance of getting paid (winner being selected) is higher. | Alt-4 Budget-abundance |
| RE7 | Because **competition is intense** (100 other solvers). | Alt-5 Competition (general) |
| RE8 | Because **I always invest the same level of effort** regardless of the contest. | Alt-6 Baseline / habitual |

接 1 道 forced-ranking（Top 2 reasons）+ 1 道开放题：
- "In your own words, why would you (or would not) invest more effort in this kind of contest?"

#### Block 6. Counterfactual Probe — *cleanest test*

> 给 Condition N 被试: "Now imagine instead that this contest had the **same prize ($195) but was labeled as a regular Standard tier** rather than a Custom (NOP) prize. **Holding the money constant**, would your effort change?" (7-point bipolar: -3 = Much less effort, 0 = No change, +3 = Much more effort)

> 给 Condition S 被试: 镜像题，"Now imagine the seeker had set a Custom (NOP) prize of \$190 instead of the Standard \$190…"

这道题**直接 hold prize amount 恒定**，把"NOP 标签效应"剥离出来——若回答系统性偏向"NOP labeled → more effort"，则给出**该论文最直接的因果证据**。

#### Block 7. Mediation Check Variables

- Perceived likelihood that *no winner* will be selected (1–7).
- Perceived probability of *winning given equal-quality submission* (1–7).

#### Block 8. Solver Ability & Controls

（同 Survey 1）

#### Block 9. De-brief / 开放题

### 2.4 主分析

| 分析 | 方法 | 假设 |
|------|------|------|
| H2a: EI(N) > EI(S) | between-subject t-test / ANCOVA controlling ability | NOP 显著提升 effort intention |
| H2b: PE(N) > PE(S) | between-subject t-test | manipulation 起作用 |
| H2c: Mediation PE → EI | PROCESS Model 4 / bootstrap | PE 中介 NOP→EI |
| H2d: 控制 PA3+PA4+PA5（钱多/大方/注意力）后 PE→EI 中介仍显著 | conditional mediation | 排除 alternative attribution |
| H2e: RE1+RE2 > RE3–RE6 | within-subject paired contrast | "高预期"reason 强于"钱多/大方"reason |
| H2f (counterfactual): Block 6 mean > 0 | one-sample t-test | hold prize 恒定时 NOP 标签本身就增 effort |
| H2g: Heterogeneity by ability | Treatment × Ability interaction | effort 反应是否对所有 ability 一致 |

### 2.5 (可选) Survey 2 扩展设计 — Robustness

为进一步排除 "$195 比 $190 多了 $5 所以努力多" 的极端解释，可加一个 *third condition* 实验：

- Condition E: 参加一个 $195 的 standard contest（即假设平台另有 $195 Standard tier）。

这样 3-condition 比较：

| 条件 | Prize | Format | 对比 |
|------|-------|--------|------|
| S | $190 | Standard | baseline |
| E | $195 | Standard | 纯 monetary effect |
| N | $195 | NOP | NOP-label effect on top of money |

若 EI(N) > EI(E) > EI(S)，则可同时证明：
- $5 多确实有微小 monetary effect (E vs S)；
- **NOP 标签在控制 prize 后仍带来额外 effort (N vs E)**——这是审稿人想要的"hold money constant"证据，比 Block 6 counterfactual 更外部有效。

---

## 3. 两套 Survey 的对应关系与互补性

| 论文章节 | 论文 mechanism | 对应 Survey | Survey 直接测量 | 排除的 alternative |
|---------|----------------|------------|----------------|--------------------|
| §5.1 Number of high-ability solvers | NOP 让高能力 solver 退出 | Survey 1 (赛前) | PE, PD, PI, Choice × ability | "高能力 solver 只是恰好不参与"（selection-as-noise） |
| §5.2 Perceived expectation 提升 first-rating | NOP 让参赛者 effort↑ | Survey 2 (赛中) | PE, EI, RE, Counterfactual | "更多钱"、"seeker 大方"、"reciprocity"、"attention" |
| §6.1 Ruling out additional prize amount | 现场实证已部分排除 | Survey 2 Block 5/6 + 3-condition extension | 直接 attribution + counterfactual | 进一步从 perception 层面排除 |
| §6.3 Ruling out attraction effect | lower-NOP 不带来效益 | Survey 1 PA5 + PA8 + Survey 2 RE5 | 让 respondent 自己评 "stand out" | 直接测出 attraction motive 弱于 expectation motive |

---

## 4. 报告与稿件 integration 建议

1. **新增一节 §5.3 "Survey Evidence on the Perceived Heightened Expectation Mechanism"**，分两个小节呈现 Survey 1 和 Survey 2 结果。
2. 强调三点说服审稿人：
   - **直接测量** perception（不再是从行为推断）；
   - **多个 alternative attribution** 被同时测量，target 显著强于 alternatives；
   - **Counterfactual / 3-condition** 设计在 prize amount 恒定下仍找到 NOP-label 的额外 effort 提升。
3. 在 Appendix 提供：完整问卷、stimuli 截图、样本特征、信效度 (α, CFA)、manipulation check 通过率、robustness（剔除快速答题者 / 失败 manipulation check 者 / demand-aware 者）。
4. 强调样本来自**真实 crowdsourcing solver**（而非 student / MTurk naive worker），提升外部有效性。
5. **Pre-registration**：在 AsPredicted 上预注册主要假设和分析路径，并在文中显式提及——能极大缓解审稿人对"事后讲故事"的疑虑。

---

## 5. Timeline / Effort 提示（非日历估计）

依任务复杂度递增：
- 量表试点 & cognitive interview（5–10 个 solver）→ 优化措辞 & 排除歧义；
- 软启动（n ≈ 30）→ 检查 PE/EI 信度、manipulation check 通过率；
- 正式收集 → 完成 attention/IMC 过滤；
- 数据分析 (within-subject mediation, conditional mediation) ；
- Appendix 写作 + 主稿件 §5.3 整合。

---

> *建议把本设计在投回前与 Editor 一起短信沟通（"We are designing two pre-registered vignette experiments to directly measure perceived seeker expectations …"），以确认审稿人接受 vignette 作为机制证据形式。*
