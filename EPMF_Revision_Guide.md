# EPMF — 考前复习手册 (Revision Guide)

> **速查·公式·关键概念·易错点**
> UESTC 3031 & UESTCHN 3012 | Based on PMBOK® Guide

---

## 🧮 MASTER FORMULA SHEET

### 项目评估 (Lecture 1)
| # | 公式 | 说明 |
|---|------|------|
| PV | $PV = \frac{FV}{(1+r)^n}$ | 现值 = 终值/(1+利率)^期数 |
| BCR | $BCR = \frac{Benefits}{Costs}$ | >1 值得做; ≤1 不值得 |
| NPV | $NPV = PV_b - PV_c$ | 正 = 项目有吸引力 |
| IRR | $\sum \frac{V_i}{(1+IRR)^i} = 0$ | IRR 越大越好 |

### 估算与进度 (Lecture 2)
| # | 公式 | 说明 |
|---|------|------|
| Triangular | $E = \frac{O+M+P}{3}$ | 三角PERT |
| Beta PERT | $E = \frac{O+4M+P}{6}$ | 传统PERT (考试用这个!) |
| σ (PERT) | $\sigma = \frac{P-O}{6}$ | 标准差 |
| Variance | $\sigma^2$ | 方差 |
| Total Float | $LF - EF = LS - ES$ | 关键路径上=0 |
| Channels | $\frac{n(n-1)}{2}$ | 沟通渠道数 (含PM) |

### 挣值分析 EVA (Lecture 3)
| # | 公式 | >0 / >1 含义 |
|---|------|------------|
| SV | $EV - PV$ | 进度超前 |
| CV | $EV - AC$ | 低于预算 |
| SPI | $\frac{EV}{PV}$ | 进度超前 |
| CPI | $\frac{EV}{AC}$ | 低于预算 |

### 风险 (Lecture 4)
| # | 公式 | 说明 |
|---|------|------|
| EMV | $\sum(P_i \times I_i)$ | 预期货币价值 |

### 质量控制 (Lecture 6)
| # | 公式 | 说明 |
|---|------|------|
| X̄ | $\frac{\sum x_i}{N}$ | 均值(控制图中心线) |
| σ̂ | $\sqrt{\frac{\sum(x_i - \bar{X})^2}{N}}$ | 标准差 |
| UCL | $\bar{X} + A\hat{\sigma}$ | 上控制限 |
| LCL | $\bar{X} - A\hat{\sigma}$ | 下控制限 |

### 田口损失函数 (Lecture 7)
| # | 公式 |
|---|------|
| 二次损失 | $L(y) = k(y-m)^2$ |
| 损失系数 | $k = \frac{A_0}{\Delta_0^2}$ |
| 平均损失(大样本) | $Q = k[(\mu-m)^2 + \sigma^2]$ |

### 过程能力 (Lecture 8)
| # | 公式 | 衡量 |
|---|------|------|
| Cp | $\frac{USL-LSL}{6\sigma}$ | 潜在能力(不含中心化) |
| Cpk | $\min(\frac{USL-\mu}{3\sigma}, \frac{\mu-LSL}{3\sigma})$ | 实际能力(含中心化) |

### 工程经济学 (Lectures 10–13)
| # | 公式 |
|---|------|
| BEP | $\frac{FC}{SP - VC}$ |
| 目标利润产量 | $\frac{FC + TargetProfit}{SP - VC}$ |
| 安全边际 | 当前产量 – BEP 产量 |
| 复利 | $F = P(1+r)^n$ |
| 折现 | $P = \frac{F}{(1+r)^n}$ |
| 多期PV | $\sum\frac{V_i}{(1+r)^i}$ |
| 等额支付 | $F = A\frac{(1+i)^n-1}{i}$ |
| B/C | $\frac{NPV_b}{NPV_c}$ |

---

## 📋 五大过程组速记

| 过程组 | 做什么 | 关键词 |
|--------|--------|--------|
| **Initiating** | 定义新项目, 授权, 创建 Charter | Project Charter, Sponsor |
| **Planning** | 建立总范围, 制定行动方案 | Progressive Elaboration, PM Plan |
| **Executing** | 完成工作, **消耗最多资源** | Deliverables, Team |
| **Monitoring & Controlling** | 跟踪评审, 管理变更 | **仅实施已批准的变更** |
| **Closing** | 正式完成, 验收, 经验教训 | Lessons Learned |

---

## 📋 十大知识领域速记

| # | 知识领域 | 过程数 | 关键记忆点 |
|---|---------|--------|-----------|
| 1 | Integration | — | 整合所有 |
| 2 | **Scope** | 6 | Plan→Collect→Define→WBS→Validate→Control |
| 3 | **Schedule** | 6 | Plan→Define→Sequence→Estimate→Develop→Control |
| 4 | **Cost** | 4 | Plan→Estimate→Determine Budget→Control |
| 5 | Quality | — | QA(主动预防) vs QC(被动识别) |
| 6 | **Resource** | 6 | Plan→Estimate→Acquire→Develop→Manage→Control |
| 7 | **Communications** | 3 | Plan→Manage→Monitor |
| 8 | **Risk** | 7 | Plan→Identify→Qual→Quant→Plan Resp→Implement→Monitor |
| 9 | Procurement | — | 采购合同 |
| 10 | Stakeholder | — | 相关方 |

---

## 📋 范围管理 6 过程

| 过程 | 关键输出 | 关键工具 |
|------|---------|---------|
| Plan Scope | Scope mgmt plan | Meetings |
| Collect Requirements | Requirements doc, RTM | Brainstorming, Interviews, Prototypes |
| Define Scope | Project scope statement | Product analysis |
| **Create WBS** | **Scope baseline** | **Decomposition** |
| Validate Scope | Accepted deliverables | **Inspection** |
| Control Scope | Change requests | **Variance analysis, Trend analysis** |

🔥 **WBS = Work Breakdown Structure** (NOT "Statement")  
🔥 WBS 包含 100% 项目工作

---

## 📋 进度管理 6 过程

| 过程 | 关键工具 |
|------|---------|
| Plan Schedule | Meetings |
| Define Activities | Decomposition, **Rolling wave planning** |
| Sequence Activities | **PDM (4种依赖), Leads & Lags** |
| Estimate Durations | **Three-point (PERT)**, Analogous, Parametric, Bottom-up |
| Develop Schedule | **CPM**, Resource optimization, **Crashing/Fast Tracking** |
| Control Schedule | Variance analysis, Schedule compression |

### PDM 四种依赖

| 类型 | 逻辑 |
|------|------|
| **FS** (最常用) | 前完成后开始 |
| FF | 前完成后完成 |
| SS | 前开始后开始 |
| SF (最少用) | 前开始后完成 |

### 进度压缩
- **Crashing**: +资源 = +成本 (关键路径)
- **Fast Tracking**: 并行 = +风险

---

## 📋 成本管理 4 过程

| 过程 | 关键输出 |
|------|---------|
| Plan Cost | Cost mgmt plan |
| Estimate Costs | ROM (–25%~+75%) or Definitive (–5%~+10%) |
| **Determine Budget** | **Cost baseline** (含 contingency, 不含 mgmt reserve) |
| Control Costs | EVA (SV, CV, SPI, CPI, TCPI) |

🔥 成本基准是 Determine Budget 的输出  
🔥 项目最大成本在执行阶段 (不是初始阶段!)

---

## 📋 资源管理 6 过程 + RACI + Tuckman

### RACI
- **R**esponsible: 做事的
- **A**ccountable: 最终拍板的 (每任务只有1个A!)
- **C**onsulted: 决策前问的
- **I**nformed: 决策后通知的

### Tuckman 团队模型
**Forming → Storming → Norming → Performing → Adjourning**

Storming 是关键成败阶段 (冲突/竞争)

### 冲突管理 5 种技术
| 技术 | 谁赢 |
|------|------|
| Avoiding | 没人管 |
| Accommodating | 对方赢 |
| Compromising | 各赢一半 |
| Competing | 你赢 |
| **Collaborating** | **双赢 (最佳!)** |

---

## 📋 沟通管理 3 过程

| 过程 | 记住 |
|------|------|
| Plan Communications | 沟通渠道公式 |
| Manage Communications | **Project reporting** 是工具 |
| Monitor Communications | 确保信息流最优 |

### 三大沟通方法
| 方法 | 性质 | 示例 |
|------|------|------|
| Interactive | 双向实时 | 会议 |
| Push | 发送(不保证收到) | 邮件 |
| Pull | 自行访问 | 内网 |

🔥 Pull 最适合大量分发

---

## 📋 风险管理 7 过程

| # | 过程 | 关键工具 |
|---|------|---------|
| 1 | Plan Risk | Risk mgmt plan |
| 2 | **Identify Risks** | **SWOT**, Root cause, Brainstorming |
| 3 | **Qualitative Analysis** | **Probability & Impact Matrix**, Bubble Chart |
| 4 | Quantitative Analysis | Monte Carlo, Decision Tree, **EMV**, Tornado |
| 5 | Plan Responses | Strategies (见下) |
| 6 | Implement Responses | 执行 |
| 7 | Monitor Risks | Audits, Data analysis |

🔥 识别后下一步 = 定性分析 (不是定量!)  
🔥 定量分析**不是每个项目都需要**

### 风险应对策略

**对 Threats (负面)**:
| 策略 | 怎么做 |
|------|--------|
| Escalate | 上报 |
| **Avoid** | 完全消除(移除活动) |
| Transfer | 转给第三方(保险/外包) |
| Mitigate | 降低概率/影响 |
| Accept | 接受(主动=储备; 被动=不动) |

**对 Opportunities (正面)**:
| 策略 | 怎么做 |
|------|--------|
| Escalate | 上报 |
| Exploit | 确保实现 |
| Share | 合作获取 |
| Enhance | 提高概率/影响 |
| Accept | 出现时利用 |

---

## 📋 DFM 速记

### DFM 六大原则
1. Simplicity (简单)
2. Standardization (标准化)
3. Tolerance (公差)
4. Material Selection (材料)
5. Automation (自动化)
6. Process Integration (流程整合)

🔥 **70-80% 生产成本由设计决定**

### 可持续性设计七大原则
1. Dematerialization
2. Modular Design
3. Renewable Energy
4. Product-Service Systems
5. Design for Longevity
6. Limit Long-Distance Outsourcing
7. Invest in Simulation

🔥 三支柱: Economic + Environmental + Social (NOT Technological!)  
🔥 4R: Reduce, Reuse, Repair, Recycle (NOT Replace!)

### 7-QC Tools
Flowchart | Check Sheet | **Fishbone (因果图)** | **Pareto (80/20)** | **Control Chart** | Histogram | Scatter

🔥 Linear Programming **不是** QC 工具

### COQ 四类成本
Prevention → Appraisal → Internal Failure → External Failure

🔥 External Failure 最严重  
🔥 增加 Prevention + Appraisal → 减少 Internal + External Failure

### Taguchi 三类特性
Nominal-the-best | Smaller-the-better | Larger-the-better

🔥 "Target-the-zero" 不是田口类型!

### P-Diagram 三类参数
Signal | Control | Noise (不可控或太贵)

### DMAIC
**D**efine → **M**easure → **A**nalyze → **I**mprove → **C**ontrol

🔥 "Calibrate" 不是 DMAIC 阶段!

### Cpk 风险等级

| Cpk | 风险 |
|-----|------|
| < 1.00 | 高 (无能力) |
| 1.00–1.33 | 中 (需改进) |
| 1.33–1.67 | 低 (有能力) |
| ≥ 1.67 | 最小 (高度有能力) |

🔥 目标 Cpk ≥ 2.00

---

## 📋 工程经济学速记

### P&L 结构 (从上到下)
```
Sales
– Cost of Sales
= Gross Profit
– Other Expenses
= EBITDA (Operating Profit)
– ITDA
= Net Income
```

### Make or Buy
🔥 只看 **Relevant Costs** (方案间不同的成本)  
🔥 Fixed Overhead 如果不能避免 = 无关  
🔥 机会成本可以翻转决策

### Break-Even
🔥 $BEP = \frac{FC}{SP - VC}$  
🔥 安全边际 = 当前产量 – BEP  
🔥 BEP 收入(服务业) = $\frac{FC}{1 - VC/Price}$

### Outsourcing
🔥 PwC 2×2: Strategic/Non × Competitive/Non  
🔥 Rightsourcing: 不盲目全外包, 仔细分析核心竞争力

### CapEx vs OpEx
- CapEx: 多年寿命, 折旧 | OpEx: 日常运营, 当期扣除
- TCO = 总拥有成本 (明显+不明显成本)

### DCF
🔥 $P = F/(1+r)^n$ (折现 = 复利的倒数)  
🔥 NPV > 0 → 项目好; IRR 越大越好  
🔥 B/C > 1 → 值得  
🔥 等值取决于利率!

---

## 📋 公司 & 战略速记

### 公司类型
Sole Trader (个人全责) | Limited (财务独立) | Partnership (共同责任) | PLC (公开交易)

### Greiner 五阶段
Creativity → Direction → Delegation → Coordination → Collaboration

### 四种战略类型
**Defenders** (稳守) | **Prospectors** (探索) | **Analyzers** (分析) | **Reactors** (混乱)

### 战略的三个基本问题 (Ken Favaro)
1. 谁是目标客户?
2. 价值主张是什么?
3. 需要什么关键能力?

🔥 Strategy ≠ Vision / Mission / Goals / Plans

### 工程职业四条路
1. 行业工程师  2. 学术研究  3. 转行用工程学位  4. 完全不同的事

---

## 🚨 高频易错/易考题

1. PM 花 **~90%** 时间沟通
2. PM **不授权**商业论证 → Sponsor 授权
3. 标准可选; 法规强制
4. WBS = Work Breakdown **Structure** (不是 Statement)
5. 成本基准含 contingency reserve, **不含** management reserve
6. 成本基准是 **Determine Budget** 的输出
7. 最大成本在**执行阶段**, 不是初始阶段
8. CPI > 1 = **低于预算**(好); SPI < 1 = 落后进度
9. **Collaborating** 是冲突解决最佳方法
10. SWOT 在 **Identify Risks** 中使用
11. 概率影响矩阵在 **Qualitative Risk Analysis** 中使用
12. 定量风险分析**不是每项目必须**
13. DFM 在**初始设计阶段**最有效
14. 三支柱不含 Technological
15. 4R 不含 Replace
16. DMAIC 不含 Calibrate
17. Pareto Chart = 80/20 原则
18. CoQ: External Failure 最严重; Equipment upgrades = Prevention (不是 Appraisal)
19. Taguchi 三类不含 Target-the-zero
20. BCR ≤ 1 = 不值得 (除非有无形收益)
21. 机会成本可能翻转 Make-or-Buy 决策
22. Strategy-Structure Fit: 结构不应静态

---

## 🎯 考前自测速问

1. PV 公式? → $FV/(1+r)^n$
2. Beta PERT 公式? → $(O+4M+P)/6$
3. 沟通渠道公式(7人)? → $7×6/2 = 21$
4. SV 公式? → $EV - PV$
5. CV 公式? → $EV - AC$
6. SPI公式? → $EV/PV$
7. CPI > 1 什么意思? → 低于预算
8. EMV 公式? → $\sum(P×I)$
9. BEP 公式? → $FC/(SP-VC)$
10. Taguchi Loss? → $k(y-m)^2$
11. Cp 公式? → $(USL-LSL)/6σ$
12. Cpk 公式? → $\min(\frac{USL-\mu}{3\sigma}, \frac{\mu-LSL}{3\sigma})$
13. 五种冲突管理策略? → Avoid/Accommodate/Compromise/Compete/Collaborate
14. Tuckman 五阶段? → Forming/Storming/Norming/Performing/Adjourning
15. 风险管理七个过程? → Plan/Identify/Qual/Quant/PlanResp/Implement/Monitor
16. 范围管理六个过程? → Plan/Collect/Define/WBS/Validate/Control
17. 进度管理六个过程? → Plan/Define/Sequence/Estimate/Develop/Control
18. 成本管理四个过程? → Plan/Estimate/Budget/Control
19. DMAIC 五个阶段? → Define/Measure/Analyze/Improve/Control
20. DFM 六大原则? → 简单/标准化/公差/材料/自动化/流程整合
