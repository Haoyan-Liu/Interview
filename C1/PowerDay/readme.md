## Capital One 数据分析岗位面经整合与详解（含全部高频 Case）

---

### 一、整体流程与准备建议

#### Power Day 面试流程（典型格式）| Typical Power Day Format
- 2轮 Case Interview（逻辑 + 数学能力 + Business Sense）
- 1轮 Data Challenge Q&A（展示项目思路）
- 1轮 Behavioral Interview（STAR模型）

#### 准备建议 | Preparation Tips
- 熟悉常考 Case 模板（Profit = Revenue - Cost）
- 高频题型集中在信用卡、贷款、移动支付、农业类优化模型等
- 面试时注意“Think Aloud”（边算边说）、单位转换准确、善于澄清模糊信息

---

### 二、全部 Case 类型汇总（按出现频率降序）

#### Case 1: Credit Card Profitability（最常见）

**Business 分析角度**：
- Revenue：Interchange Fee、Interest from Revolvers、Annual/Monthly Fees
- 收入：交易手续费、循环借款利息、年费/月费
- Cost：Fraud Losses、Rewards、运营费用、默认损失率
- 成本：欺诈损失、奖励发放、运营开销、违约率
- 用户分组：Transactor（不欠款） vs Revolver（产生利息）
- Customer Segmentation: Transactors vs Revolvers
- 目标：提升用户价值、促进刷卡频次、优化 reward 投放策略
- Goal: Maximize user value, increase card usage, optimize reward spending

---

#### Case 2: Wheat Harvesting / 拖拉机 Case

**Business 分析角度**：
- 收入 = 农户收成 × 单价 × 提成比例 | Revenue = Yield × Price × Commission Rate
- 成本 = 收割机 + 卡车租赁 | Costs = Equipment Rental (Combines + Trucks)
- 匹配土地、运输与收割能力 | Match land, transportation, harvesting capacity
- 优化资源组合以提升效率与利润 | Optimize resource allocation for max profit

---

#### Case 3: Short-Term Loan Case | 短期贷款产品可行性分析

**Business 分析角度**：
- 收入 = 各类借款按比例利率计算 | Revenue = Weighted loan interest
- 成本 = 服务成本 + 风控成本 + 违约损失 | Cost = Service + Risk Control + Defaults
- 评估客户信用风险、是否有抵押品 | Assess creditworthiness, collateral
- 与其他公司合作时需评估现金流趋势 | Evaluate partners by cash flow trend and risk

---

#### Case 4: Coder Productivity Case | 软件团队产能规划

**Business 分析角度**：
- 成本 = 正常工资 + 加班工资 + contractor 工资 | Cost = FT + OT + Contractors
- 制约因素：哪个岗位是瓶颈？ | Bottleneck role: coder, tester or doc?
- 决策点：是加班、招contractor 还是拒单？ | Decision: hire or overwork?

---

#### Case 5: Personalized Credit Card | 定制化信用卡功能推广

**Business 分析角度**：
- 收益：提升消费、增强客户忠诚度 | Benefit: more spend, better retention
- 成本：email成本、寄卡成本、系统开发 | Cost: emails, mailing, system dev
- 投放分析：response rate、消费变化、break-even
- Campaign evaluation: response rate, lift, break-even

---

#### Case 6: Venmo / P2P Payment Product | 点对点支付产品优化

**Business 分析角度**：
- 收入：交易手续费（信用卡/借记卡）| Revenue: Transaction fee
- 成本：fraud + infrastructure + partner fees | Cost: fraud, system, ops
- 战略拓展：向 P2B 转型、提高盈利能力 | Strategy: B2C → B2B for profit
- IPO目标下的盈利展示 | Show profit for IPO positioning

---

#### Case 7: Amusement Park / 主题公园 Case

**Business 分析角度**：
- 收入 = 门票 + 其他消费（餐饮、纪念品）| Revenue: Entry + Ancillaries
- 成本 = 固定支出 + 变动支出（与客流相关）| Costs: Fixed + Variable
- 决策点：是否购买地块？是否竞标？ | Expansion decisions, auction or not

---

#### Case 8: Mobile Check Deposit App | 移动支票处理方案

**Business 分析角度**：
- 成本结构对比 ATM vs App | Compare ATM vs App Cost
- fraud 风险、新功能 adoption rate、ROI | Risks, adoption rate, ROI
- 风控策略：限额、延迟、建模识别风险用户 | Controls: limits, hold time, fraud model

---

#### Case 9: 3D 打印机创业公司 | Startup Strategy: 3D Printer

**Business 分析角度**：
- 收入：售价 × 销量 | Revenue = Price × Volume
- 成本：固定 + 可变 + 维修保修支出 | Cost = Fixed + Variable + Warranty
- 渠道对比：直销 vs 零售商 | Sales Channels: Direct vs Retail
- 用户教育/品牌建设/保修政策影响销售 | Customer Education & Post-sale service

---

### 三、Behavioral Interview | 行为面试（综合讨论与表现）

使用 STAR 模型（Situation, Task, Action, Result）来讲述每一个故事，保持逻辑性、结构性与影响力。重点考察你的沟通能力、团队协作能力、解决问题的能力，以及对业务的理解。

#### 常见问题 | Common Behavioral Questions:
- Describe a time you failed.（讲述一次失败经历）
- Tell me about a time you led a project.（描述你带领项目的经验）
- Describe a time you went above and beyond.（你曾经额外付出的情境）
- Tell me about a time you had to manage your time effectively.（你如何管理时间）
- Describe a conflict you resolved in a team.（你如何解决团队冲突）
- Tell me about a time you worked with limited data to make a decision.（数据不充分时如何决策）
- How do you prioritize multiple tasks with the same deadline?（任务冲突如何排序）
- Describe a time you influenced someone without authority.（没有权力情况下如何影响他人）

---

### 四、Data Challenge (DC) & Behavioral | 项目讲解 & 行为面试

#### DC Q&A
- 自主讲解项目，用 slide + code | Self-lead explanation
- 展示业务假设、方法选择、结果呈现、局限性 | Assumption, Method, Result, Limitation
