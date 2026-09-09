# Candidate-only Eight-Category Conjecture Map (ChatGPT export)

- Repository: vibemathing/problem-secp256k1-ecdlog-polytime
- Problem: problem:secp256k1-ecdlog-polytime
- Source chat content SHA-256: `6c3ac2d2c5baa92de9198b461e78d85fddb8ea82310d5924d85f9e995b17a158`
- Status: candidate_only; statement_faithfulness pending; prior-art review pending; independent verification pending
- Transport classification: computation (bounded classification/catalog audit). This file claims no proof, counterexample, Evidence, Result, or Solution.
- Excerp from CONJECTURE_CATALOG.md section below (verbatim).

输入：`httpsgithub.comvibemathingproblem-secp256k1-ecdlog-polytime-开始猜想树-20260909-1742.md`
首先必须拆开固定 secp256k1 实例与随安全参数增长的 secp256k1-like 曲线族；固定 256-bit 实例不构成渐近 P-time 问题。
1. `ECDLP-E` 存在：存在可计算的 CM/坐标“隐藏线性化”结构，使统一曲线族上的 ECDLP 可由经典 `poly(log p)` 算法求解；这是进攻型候选。
2. `ECDLP-U` 全称：适当 secp256k1-like 素数阶曲线族的经典 ECDLP 不存在 `poly(log p)` 算法。
3. `ECDLP-R` 刚性：低次数 rational map 在子群上精确恢复 scalar 或 scalar bit 时，次数至少为 `Omega(n)`；需明确无极点、子群规模和函数域条件。
4. `ECDLP-Q` 对应：完整 ECDLP 存在 BPP 算法，当且仅当存在定义明确的低代数复杂度观察器能以非忽略优势预测某个 scalar bit；正向完备性是新猜想，反向要绑定 bit-security/HNP 定理。
5. `ECDLP-K` 分类：任何 polytime 突破必须利用 non-generic 坐标、代数下降、特征 p 提升或新的算术表示；这是路线分类候选，不是形式定理。
6. `ECDLP-B` 界：已知三阶 endomorphism 只能改善 generic ECDLP 常数因子，不能将 `sqrt(n)` 降为多项式；需明确模型和“免费 endomorphism”操作。
7. `ECDLP-A` 渐近：低代数复杂度坐标测试对 scalar bit 的预测优势随族参数趋于零；必须定义测试类、随机分布和优势。
8. `ECDLP-D` 复杂度：一般曲线族 ECDLP 仍需 `n^(1/2-o(1))` 经典时间；固定 secp 实例只能改写成具体电路/操作数或 time-memory tradeoff 命题。
首选后续路线：先把 rational-map barrier 写成可检查的引理草案，再查 generic-group、GLV、bit-security/HNP 的精确适用条件；不要把固定参数问题直接写成渐近结论。
- 所有条目：`candidate_only`, `statement_faithfulness: pending`, `prior_art: pending`, `independent_verification: pending`。
- 任何有限枚举、SAT/MaxSAT、数值、模型输出、CI、PR 或合并都不能直接升级为 Result。
- 建议每个问题仓库只先选一个主候选，建立一个 Attempt/Route/Obligation，再把其余七类作为同一研究路线的候选分支；不要一次把八类都伪装成八个已准入任务。
```text
b5140cc999c9bb98cb75f1095078783f8a0c37c9bfd6b0869a13b34bcc298ef7  ChatGPT-柯拉茨猜想提问-20260909-1842.md
f98ce03c7b1b2ec65c14af69842a0a8e1e7d4f05c926f03349d270dc2942eccc  ChatGPT-杨米尔斯猜想分类-20260909-1842.md
6abe3426bfb7995c3ffaf0a16b4d95ce755f1227c55da1142e296b4c1e692fa9  ChatGPT-提出黎曼猜想-20260909-1842.md
7be945b391d4010bcbbda6a73a2647b2d78923078e63577a3b9b8b6088488579  ChatGPT-提出霍奇猜想-20260909-1842.md
b4a38af0ec6ee591133fba197c6db79f9daff98ccb047fa737fd7c8ecc27abcd  ChatGPT-开始猜想制定-20260909-1842.md
24669214e94b72a5f9256da1025f36be92ca80461191c5800c55bfd160f6a5a0  ChatGPT-数学猜想分类 framework-20260909-1842.md
d49175321f0ef66554b161abb974329e7c14569a19d85626bb3db614b6251b5f  ChatGPT-数学猜想分类 framework-20260909-1825.md
32c5a617d459a1227280e3f887e2ea3996d206c422eb7d86aa4c37a6ca6e8947  httpsgithub.comvibemathingproblem-millennium-p-vs-np-提出猜想 !-20260909-1743.md
6c3ac2d2c5baa92de9198b461e78d85fddb8ea82310d5924d85f9e995b17a158  httpsgithub.comvibemathingproblem-secp256k1-ecdlog-polytime-开始猜想树-20260909-1742.md
```
