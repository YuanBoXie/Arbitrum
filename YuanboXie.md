---
timezone: Asia/Shanghai
---

---

# YuanBoXie

1. 自我介绍: Web3/AI研究员
2. 你认为你会完成本次残酷学习吗？：尽力而为

## Notes

<!-- Content_START -->

## 第一周
第一周（1-7 天）：基础概念与技术入门
本周重点学习 Arbitrum 的基本介绍和技术架构的初级知识点：
• 第 1-2 天：了解 Arbitrum 的使命、特点及基本原理
• 第 3-5 天：认识 Rollup 概念并深入理解欺诈证明机制

### 2024.12.10
- 学习目标：了解 Arbitrum 的使命、特点及基本原理
- 参考资料：
    - https://docs.arbitrum.io/welcome/arbitrum-gentle-introduction

学习笔记：

Arbitrum 是 ETH 的一条 L2，继承了以太坊级安全性，关键技术是 Arbitrum Rollup（一种 Optimistic rollup）。L2 的主要原因是因为 L1 TPS 过低（20-40），TPS 低导致 gas war。用户体验很差。TPS 低主要是因为：1）每个节点都必须处理每笔交易，2）希望运行节点成本相对低；Arb 为什么可以解决这个问题：Optimistic rollup。Layer 1 最初“乐观地假设”Arbitrum 上的活动都是正确的，如果有人不诚实，用户可以提交欺诈证明（fraud proof）。其中欺诈方会收到经济惩罚。

- validators：在 L1 上推动 arb 状态更新的角色，提交更新状态、对其他人的提交质疑。只要有一个诚实的验证者，这条链就会保持安全。
- fraud proof：欺诈证明需要一个时间窗口，所以对用户来说，资金提款（withdrawing）有一个锁定期。通常需要等待 1 周才能在 L1 上收到资金。可以用 fast-bridge 应用绕过这个周期（需要一些额外费用）。将资金从 eth 存到 arb 没有这个滞后。



### 2024.12.11


<!-- Content_END -->
