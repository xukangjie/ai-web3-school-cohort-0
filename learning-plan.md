# 学习计划

> 随学习进度持续更新 · 最后更新：2026-05-21
> 每日投入：1-2 小时 · 目标：做出一款 AI × Web3 落地产品

---

## 第一阶段：打基础（第 1-2 周）

### 第 1 周：AI 基础
目标：建立 AI/LLM/Agent 的系统认知

- [ ] **Day 1-2：LLM 基础**
  - 阅读 Handbook：[LLM](https://aiweb3.school/zh/handbook/ai/llm/)
  - 理解：大模型能做什么/不能做什么、Token、上下文窗口
- [ ] **Day 3：Prompt 工程**
  - 阅读 Handbook：[Prompt](https://aiweb3.school/zh/handbook/ai/prompt/)
  - 实践：用我（Hermes Agent）尝试不同 Prompt 写法
- [ ] **Day 4：Context 与 RAG**
  - 阅读 Handbook：[Context](https://aiweb3.school/zh/handbook/ai/context/) + [RAG](https://aiweb3.school/zh/handbook/ai/rag/)
- [x] **Day 5-6：Agent 基础** ✅ 已完成（2026-05-24）
  - 阅读 Handbook：[Agent](https://aiweb3.school/zh/handbook/ai/agent/) + [MCP](https://aiweb3.school/zh/handbook/ai/mcp/)
  - 理解：工具调用、多步执行、Agent 工作流
- [ ] **Day 7：回顾与整理**
  - 整理笔记，标记疑问，提交 Handbook feedback

### 第 2 周：Web3 基础
目标：建立区块链/钱包/智能合约的系统认知

- [ ] **Day 1-2：区块链网络**
  - 阅读 Handbook：[Network](https://aiweb3.school/zh/handbook/web3/network/) + [密码学](https://aiweb3.school/zh/handbook/web3/cryptography/)
- [ ] **Day 3-4：钱包与智能合约**
  - 阅读 Handbook：[Wallet](https://aiweb3.school/zh/handbook/web3/wallet/) + [Smart Contract](https://aiweb3.school/zh/handbook/web3/smart-contract/)
  - 动手：安装 MetaMask，获取测试币，交互一个 dApp
- [ ] **Day 5：Account Abstraction**
  - 阅读 Handbook：[Account Abstraction](https://aiweb3.school/zh/handbook/web3/account-abstraction/)
  - 理解 Smart Account 与 Agent 权限的关系
- [ ] **Day 6-7：回顾与实践**
  - 整理笔记，在 `experiments/` 记录第一次链上交互

---

## 第二阶段：AI × Web3 Bridge（第 3-4 周）

### 第 3 周：理解交叉点
目标：理解 AI 和 Web3 如何真正结合

- [x] **Day 1-2：Chain-aware Context** ✅ 已完成（2026-06-03）
  - 阅读：[Chain-aware Context](https://aiweb3.school/zh/handbook/bridge/chain-aware-context/)
  - 理解：链上状态如何进入 Agent 上下文
  - 最小实践：组装了一笔真实 USDC 交易的上下文包（事实 vs 解释 + Citation）
- [ ] **Day 3：Web3 Tool Use**
  - 阅读：[Web3 Tool Use](https://aiweb3.school/zh/handbook/bridge/web3-tool-use/)
  - 理解：Agent 如何调用 RPC、钱包、合约工具
- [ ] **Day 4-5：Agent Wallet + Workflow**
  - 阅读：[Agent Wallet](https://aiweb3.school/zh/handbook/bridge/agent-wallet/) + [Agent Workflow](https://aiweb3.school/zh/handbook/bridge/agent-workflow/)
  - 思考：我的产品需要什么权限模型
- [ ] **Day 6-7：Machine Payment + Settlement**
  - 阅读：[Machine Payment](https://aiweb3.school/zh/handbook/bridge/machine-payment/) + [Settlement & Escrow](https://aiweb3.school/zh/handbook/bridge/settlement-and-escrow/)

### 第 4 周：选定方向 + 原型设计
- [ ] 浏览[前沿探索赛道](https://aiweb3.school/zh/handbook/tracks/agentic-commerce/)
- [ ] **选定一个产品方向**（Agentic Commerce / Wallet Permission / AI Security 等）
- [ ] 在 `tasks/` 中写产品构思文档
- [ ] 列出 MVP 功能清单

---

## 第三阶段：动手做产品（第 5 周+）

> 具体计划待第 4 周末选定方向后细化

### MVP 开发
- [ ] 搭建开发环境
- [ ] 实现核心功能
- [ ] 测试与迭代

### 提交与展示
- [ ] 在 `submissions/` 准备提交材料
- [ ] 参与 Bootcamp 展示 / Hackathon
- [ ] 沉淀到 `experiments/` 作为学习记录

---

## 资源索引

| 资源 | 链接 |
|------|------|
| 📖 Handbook | https://aiweb3.school/zh/handbook/ |
| 🏫 Bootcamp 课程 | https://web3career.build/zh/programs/AI-Web3-School |
| 📚 WCB Learning | https://web3career.build/zh/programs/AI-Web3-School#tab=learning |
| 📱 Telegram 社群 | https://t.me/aiweb3school |
| 🐙 GitHub 仓库 | https://github.com/xukangjie/ai-web3-school-cohort-0 |
| 🤖 我的 Agent | 通过 Telegram 使用 Hermes Agent |

## 学习原则

- ⏱ **每天 1-2 小时**，质量比数量重要
- 📝 **学完必记**，每节 Handbook 读完写一句自己理解的话
- ❓ **卡住就问**，把问题记到 `handbook-feedback/` 并问我
- 🔁 **每周回顾**，调整下一周计划
- 🎯 **始终盯着目标**：做出一款能用的产品
