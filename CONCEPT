# CrewOS — Product Concept

> **The next unit of AI is not the task. It's the business.**

---

# 00. 我们到底在做什么？

CrewOS 最初的想法很简单：

> 让 AI 不只是回答问题，而是真正进入企业工作。

最开始，我们自然会想到：

* Agent
* Multi-Agent
* Skill
* Tool
* MCP
* Workflow
* Memory
* Permission

于是产品很容易变成：

> 一个更完整的 Agent 平台。

但当我们把市场上的产品重新看一遍之后，会发现：

**这条路已经非常拥挤。**

通用模型越来越强。

通用 Agent 越来越强。

像 WorkBuddy 这样的产品，已经可以让一个人用自然语言把复杂工作交给 AI，由 AI 自己规划、调用工具、执行并交付结果。

所以如果 CrewOS 只是：

> Agent + Skill + MCP + Multi-Agent + Workflow

那么它没有足够强的存在理由。

我们必须往上走。

---

# 01. 一个重要判断

我们认为：

> **AI 的下一场竞争，不一定是谁拥有更多 Agent，而是谁能够让 AI 真正进入业务运行。**

这是 CrewOS 最核心的判断。

---

# 02. 三层 AI

我们可以把现在的 AI 产品粗略分成三层。

## Layer 1 — Intelligence

Foundation Models。

它们解决：

> AI 能不能理解和推理？

例如：

* 理解语言
* 推理
* 生成
* 编程
* 视觉
* 多模态

这是模型层。

---

## Layer 2 — Task Execution

AI Agents。

它们解决：

> AI 能不能自己完成一个任务？

例如：

```text
用户：
帮我研究这个客户。

Agent：
理解目标
↓
搜索
↓
读取资料
↓
分析
↓
生成报告
↓
交付
```

这是 Agent 层。

---

## Layer 3 — Business Operation

CrewOS。

我们想解决：

> **AI 能不能持续负责一项业务？**

例如：

```text
企业：
从现在开始，你负责我的财税业务。

CrewOS：
建立 Finance Business
↓
连接财务系统
↓
初始化 Business State
↓
启动 Finance Crew
↓
持续接收业务事件
↓
持续执行
↓
发现异常
↓
请求人工决策
↓
更新 Business State
↓
进入下一周期
```

这是我们认为还没有被充分产品化的一层。

---

# 03. 为什么不是继续做 Agent？

因为 Agent 本身不是最终业务对象。

Agent 是：

> **Worker**

它回答：

> 谁来做？

但企业真正关心的是：

> **什么业务要被完成？**

以及：

> **最终结果怎么样？**

因此我们重新定义：

```text
Outcome
    ↓
Business
    ↓
Crew
    ↓
Agent
    ↓
Skill
    ↓
Tool
```

而不是：

```text
Agent
 ↓
Skill
 ↓
Tool
 ↓
Task
```

这是 CrewOS 最重要的抽象转变。

---

# 04. Task 与 Business

这是整个 Concept 的核心。

## Task

Task 有明确开始和结束。

```text
Start
 ↓
Work
 ↓
Result
 ↓
End
```

例如：

> 分析 8 月财务数据。

---

## Business

Business 没有真正的结束。

```text
Start
 ↓
Operate
 ↓
Change
 ↓
Exception
 ↓
Decision
 ↓
Operate
 ↓
Next Cycle
 ↓
Operate
```

例如：

> 负责公司的财税业务。

这不是一个 Prompt。

也不是一个 Task。

这是一个：

> **持续责任。**

---

# 05. Business Responsibility

因此 CrewOS 的真正对象不是：

> Task Execution

而是：

> **Business Responsibility**

我们希望未来用户可以说：

```text
“这项业务你负责。”
```

而不是不断说：

```text
“这个任务你帮我做。”
```

这两者之间的差距，就是 CrewOS 想占据的空间。

---

# 06. 为什么 WorkBuddy 很重要？

我们并不认为 WorkBuddy 是“竞争对手所以要绕开”。

恰恰相反：

> **WorkBuddy 证明了一个非常重要的事情。**

即：

> 人已经开始愿意把真实工作交给 AI Agent。

这是整个行业非常重要的一步。

通用 Agent 已经可以：

```text
理解任务
 ↓
制定计划
 ↓
调用工具
 ↓
执行
 ↓
交付结果
```

这个模型非常合理。

问题是：

> **当 Task 完成以后呢？**

如果老板说：

> “以后公司的财税业务你负责。”

这时候一个 Task Agent 的抽象开始不够用了。

因为系统需要知道：

* 公司是谁
* 当前财务周期是什么
* 上个月发生了什么
* 当前有哪些未完成事项
* 当前有哪些风险
* 哪些数据已经确认
* 哪些数据发生变化
* 哪些事情需要老板审批
* 下一个截止日期是什么
* 业务什么时候应该再次运行

这已经不是 Task Context。

这是：

> **Business Context。**

---

# 07. 所以我们和 WorkBuddy 的差异是什么？

不是：

> WorkBuddy 不会做 X，CrewOS 会。

这种比较很容易过时。

真正的差异应该是：

|      | General Model    | General AI Agent | CrewOS                   |
| ---- | ---------------- | ---------------- | ------------------------ |
| 核心对象 | Intelligence     | Task             | Business                 |
| 用户输入 | Prompt           | Task             | Outcome / Responsibility |
| 时间尺度 | 当前上下文            | 任务生命周期           | 长期运行                     |
| 状态   | Context          | Task State       | Business State           |
| 目标   | Answer           | Result           | Outcome                  |
| 工具   | Model capability | Task tools       | Business infrastructure  |
| 工作方式 | Respond          | Execute          | Operate                  |
| 结束条件 | Answer generated | Task completed   | Business continues       |
| 异常   | 用户重新提问           | Agent处理          | Business Runtime持续处理     |
| 人工介入 | 对话               | Task approval    | Business decision        |
| 核心价值 | Intelligence     | Productivity     | Continuity               |

所以：

> **我们不是想把 WorkBuddy 做得更像企业。**

而是：

> **把 AI Agent 的工作单位从 Task 向 Business 推进。**

---

# 08. Business State

如果 Business 是核心对象，那么最大的技术问题之一就是：

> **AI 如何知道业务现在是什么状态？**

这是普通 Chat Context 无法解决的。

Business State 至少应该包含：

```text
Business State
│
├── Current Goals
├── Current Period
├── Current Tasks
├── Completed Tasks
├── Pending Decisions
├── Exceptions
├── Risks
├── Business Data
├── People
├── Permissions
├── Deadlines
└── Historical State
```

例如 Finance Business：

```text
Period
September 2026

Closing
73%

Invoices
2,831

Bank Transactions
6,421

Unmatched
3

Tax Risks
4

Pending Approvals
2

Next Deadline
September 15
```

这个 State 会持续变化。

因此 AI 每次行动都会：

```text
Observe
 ↓
Reason
 ↓
Act
 ↓
Update State
```

---

# 09. Business Event

Business 不应该依赖人不断发送 Prompt。

现实世界会产生 Event。

例如：

```text
Invoice Received
Bank Transaction Created
Contract Signed
Customer Replied
Month Ended
Tax Deadline Approaching
Payment Failed
Risk Detected
```

因此：

```text
Event
 ↓
Business State
 ↓
Agent Crew
 ↓
Planning
 ↓
Execution
 ↓
State Update
```

AI 开始从：

> **Prompt-driven**

走向：

> **Event-driven**

这是 Business Runtime 与普通 Chat Agent 的重要区别。

---

# 10. Outcome

Task 的最终结果是 Result。

Business 的最终目标是 Outcome。

例如：

### Task

> 检查 100 张发票。

Result：

> 发现 3 张异常。

---

### Outcome

> 确保本月所有发票被正确处理，并不存在重大财税风险。

这时系统不能因为：

> “3 张发票已经检查完了。”

就结束。

因为 Outcome 还没有完成。

它需要：

```text
发现异常
 ↓
调查
 ↓
判断
 ↓
处理
 ↓
确认
 ↓
更新状态
 ↓
重新检查
 ↓
直到 Outcome 达成
```

所以：

> **Outcome 是比 Task 更高一级的产品抽象。**

---

# 11. Crew

Crew 也因此需要重新定义。

传统理解：

> Crew = 多个 Agent。

我们不认同这个定义。

我们的定义是：

> **Crew = 对一个 Business Outcome 持续负责的 AI 组织。**

例如：

```text
Finance Crew
│
├── Accounting Agent
├── Cash Agent
├── Invoice Agent
├── Tax Agent
├── Risk Agent
└── Analyst Agent
```

这些 Agent 之所以存在，不是因为：

> “Multi-Agent 很酷。”

而是因为：

> **一个 Business Outcome 需要多个专业角色共同完成。**

因此：

```text
Business
 ↓
Outcome
 ↓
Crew
 ↓
Agents
```

而不是反过来。

---

# 12. Business Runtime

如果 Agent Runtime 解决：

> Agent 如何执行？

那么 Business Runtime 解决：

> **Business 如何持续运行？**

它至少需要：

```text
Business State
Event System
Task Runtime
Agent Runtime
Scheduler
Planner
Memory
Rules
Permissions
Approval
Exception Handling
Audit
```

其中最重要的是：

> **State + Event + Execution + Decision**

它们形成一个循环：

```text
        ┌──────────────┐
        │ Business     │
        │ State        │
        └──────┬───────┘
               ↓
            Event
               ↓
            Planning
               ↓
           Execution
               ↓
          Observation
               ↓
       Human Decision?
          ↙         ↘
        Yes          No
         ↓            ↓
     Approval       Execute
         └──────┬─────┘
                ↓
          State Update
                ↓
             Continue
```

这才是我们所谓的：

> **Business Runtime。**

---

# 13. 为什么不是 Workflow？

Workflow 假设：

> 我们知道下一步是什么。

例如：

```text
A → B → C → D
```

企业真实业务经常是：

```text
A
 ↓
Observe
 ↓
What happened?
 ├── Normal → B
 ├── Exception → Investigate
 ├── Risk → Human
 └── Unknown → Re-plan
```

因此 AI-operated Business 不可能完全依赖固定 Workflow。

它需要：

> **Dynamic Planning + Business State**

Workflow 仍然存在。

但 Workflow 只是 Runtime 的一部分。

---

# 14. 为什么财税是一个好的第一实验？

财税不是因为“市场大”这么简单。

它适合作为实验，是因为它具备完整的 Business Runtime 特征。

## 长周期

每天、每周、每月、每年持续运行。

## 多角色

出纳、会计、税务、风控、分析。

## 多系统

银行、ERP、发票、税务系统、邮箱、文件。

## 高数据密度

发票、流水、凭证、合同、报表。

## 规则密集

税率、税种、申报周期、政策。

## 高风险

付款、记账、申报、税务风险。

## Human-in-the-loop

很多动作必须经过人工确认。

## 可审计

每一个动作都需要知道：

> 谁做的？

> 为什么做？

> 使用了什么数据？

> 得到了什么结果？

> 谁批准的？

这使财税成为一个非常好的：

> **AI Business Runtime Test Case。**

---

# 15. Finance Business 不应该只是一个 Agent

我们现在已有的财税 Prototype 中，已经存在很多角色：

```text
出纳
开票员
总账会计
税务师
税务风控官
财务分析师
```

以前我们容易把它理解为：

> “我们做了很多 Agent。”

现在应该重新理解：

> **这些 Agent 是 Finance Business 的组织结构。**

例如：

```text
                Finance Business
                       │
                  Finance Crew
                       │
        ┌──────────────┼──────────────┐
        │              │              │
       Cash         Accounting        Tax
        │              │              │
        └──────────────┼──────────────┘
                       │
                     Risk
                       │
                    Analysis
```

产品真正需要展示的不是：

> “我们有 6 个 Agent。”

而是：

> **“你的 Finance Business 正在运行。”**

---

# 16. 一个完整的 Business Cycle

例如月结。

老板的目标：

> **完成 9 月财税月结。**

CrewOS 创建：

```text
Outcome
September Closing
```

然后：

```text
Business State
       ↓
Collect Events
       ↓
Invoice Agent
       ↓
Cash Agent
       ↓
Accounting Agent
       ↓
Tax Agent
       ↓
Risk Agent
       ↓
Analysis Agent
       ↓
Human Approval
       ↓
Complete
```

如果过程中发生：

```text
银行流水 ≠ ERP
```

系统不是简单返回：

> “数据不一致。”

而是：

```text
Exception
 ↓
Investigate
 ↓
Collect Evidence
 ↓
Reason
 ↓
Propose Action
 ↓
Human Approval
 ↓
Execute
 ↓
Update State
 ↓
Continue Closing
```

这才是真正的 Business Operation。

---

# 17. 产品界面的变化

这会直接改变 UI。

## 传统 Agent UI

```text
Agents

Finance Agent
Tax Agent
Sales Agent
Research Agent
```

这是：

> **AI-centric**

---

## CrewOS

```text
My Businesses

Finance
  ● Running
  73%

Sales
  ● Running
  42%

Operations
  ● Attention Required
```

这是：

> **Business-centric**

进入 Finance：

```text
Finance Business
─────────────────────────

Outcome
September Closing

Progress
73%

Running
5

Exceptions
4

Pending Decisions
2

Next Deadline
September 15

AI Crew
Accounting
Tax
Risk
Analysis
```

用户看到的是：

> **业务状态。**

而不是：

> Agent 状态。

---

# 18. 用户真正应该购买什么？

如果我们最终做成产品，我认为用户不应该购买：

> 100 个 Agent。

也不应该购买：

> 500 个 Skills。

甚至不应该购买：

> 一个 Agent OS。

用户应该购买：

> **一个可以接管某项业务的 AI Business。**

例如：

```text
Finance Business
Sales Business
Operations Business
```

Business Template 内部包含：

```text
Agents
Skills
Tools
Rules
Workflows
Permissions
Business State
Runtime
```

技术复杂性被隐藏。

业务价值被暴露。

---

# 19. 这也改变了商业模式的想象空间

如果卖的是：

> Agent

那么很容易变成：

> Agent Marketplace。

如果卖的是：

> Token / Usage

那么容易变成：

> AI API pricing。

但如果卖的是：

> **Business Operation**

那么商业单位可能变成：

```text
Finance Business
$X / month

Sales Business
$X / month

Operations Business
$X / month
```

最终客户购买的不是 AI。

而是：

> **一项业务的 AI operating capacity。**

这只是当前假设，未来需要真实市场验证。

---

# 20. 我们不做什么

这是非常重要的边界。

CrewOS 不应该为了追逐热点而做：

### ❌ Another Chatbot

因为：

> Model already does this.

### ❌ Another General AI Agent

因为：

> Agent products are already moving quickly.

### ❌ Agent Marketplace first

因为：

> Agent 数量不是我们的核心价值。

### ❌ Skill Marketplace first

因为：

> Skill 只是能力组件。

### ❌ Workflow Builder

因为：

> Business 不是完全确定性的流程。

### ❌ Multi-Agent for the sake of Multi-Agent

因为：

> 多 Agent 不是产品价值本身。

---

# 21. 我们真正要证明什么？

CrewOS 不是一个已经被证明的答案。

它是一组 Hypothesis。

---

## H1 — Business State

AI 能否理解一个长期运行业务的状态？

---

## H2 — Business Continuity

AI 能否跨越多个 Task 持续工作？

---

## H3 — Outcome Ownership

AI 能否围绕一个 Outcome，而不是单个 Task，持续推进？

---

## H4 — Exception Handling

AI 能否面对业务中的异常，而不是遇到异常就停止？

---

## H5 — Human Decision

AI 能否知道什么时候应该自己做，什么时候应该找人？

---

## H6 — Enterprise Execution

AI 能否真正操作企业已有系统，而不仅仅生成文本？

---

## H7 — Business Adoption

企业是否真的愿意：

> **把一项业务交给 AI？**

---

# 22. 最重要的验证

最终我们不需要证明：

> “我们的 Agent 很厉害。”

也不需要证明：

> “我们的模型很聪明。”

我们只需要证明一个东西：

> **一家真实企业，是否愿意让 CrewOS 持续运行一项真实业务。**

例如：

```text
Day 1
连接财务系统

Day 2
开始处理发票

Day 7
发现异常

Day 15
准备税务数据

Day 30
完成月结

Day 31
进入下一个周期
```

如果整个过程中：

> 人越来越少地“指挥 AI”。

而：

> AI 越来越多地“推进业务”。

那么 CrewOS 的假设就开始成立。

---

# 23. 最终的产品抽象

我们现在暂时把 CrewOS 的核心抽象定义为：

```text
Outcome
   ↓
Business
   ↓
Business State
   ↓
Crew
   ↓
Agent
   ↓
Skill
   ↓
Tool
   ↓
Enterprise Systems
```

其中：

### Outcome

我要什么结果？

### Business

什么业务对这个结果负责？

### Business State

业务现在是什么状态？

### Crew

谁负责推动这个结果？

### Agent

谁具体执行？

### Skill

它会什么？

### Tool

它可以使用什么？

### Enterprise Systems

真实业务数据在哪里？

---

# 24. 最终愿景

我们并不认为未来企业会突然：

> “不要软件了，全用 Agent。”

更可能发生的是：

```text
ERP
CRM
Finance
Bank
Email
OA
Database
Documents
        ↓
      AI
        ↓
Business Runtime
        ↓
Business
```

软件继续存在。

数据继续存在。

系统继续存在。

但：

> **人不再是连接所有软件的唯一执行者。**

AI 开始成为：

> **这些企业系统之上的业务运行层。**

这可能是 CrewOS 真正值得探索的地方。

---

# 25. 最后

我们不是因为：

> “AI Agent 很火。”

所以做 CrewOS。

也不是因为：

> “Multi-Agent 很酷。”

所以做 CrewOS。

更不是因为：

> “WorkBuddy 已经证明市场存在。”

所以做 CrewOS。

我们的判断恰恰相反：

> **正因为模型已经足够聪明，Agent 已经开始能够完成任务，我们才第一次有机会去讨论：AI 是否可以承担一项长期业务。**

Task 是一次工作的最小单位。

Business 是企业运行的基本单位。

如果 AI 最终要真正进入企业：

> **它最终需要理解的，不只是 Task。**

而是：

> **Business。**

这就是 CrewOS 想探索的东西。

---

# CrewOS

> **From Intelligence → Execution → Operation.**
>
> **From Tasks → Outcomes → Businesses.**

**The next unit of AI is not the task. It's the business.**
