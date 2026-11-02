# Runtigil
## 许可说明 · License Notice

> **本仓库使用自定义许可，不是 MIT / Apache-2.0**。平台显示为 `Other`（NOASSERTION），
> 属识别算法的正常结果，**不代表本仓库处于无许可状态**。

- **权利状态**：全部内容保留所有权利（All Rights Reserved）。未经书面许可，
  不得复制、改编、再分发、公开传播或用于衍生作品。
- **可否引用**：可以。允许在**注明出处**的前提下引用与学术、公共讨论；
  引用时请同时标注仓库名、原文链接 `https://github.com/zhaoxinghua09-cell/runtigil`
  与权利人：© 2026 赵兴华 / Steven Zhao (ORCID 0009-0001-0512-1237). All rights reserved.
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **免责**：本仓库内容不构成法规意见或注册代理服务；关键数据以监管机构最新发布为准。

---


**运行时门禁治理 · Runtime Gatekeeping**

> A coined theoretic term in the **LGD (凡自治之物 · 全程治理论)** theory stack.
> Theory-layer zero-collision: the descriptive English name is settled by others; the coined term is ours.

---

## Definition

**Runtigil** — gatekeeping enforced **while an autonomous thing is running**, not only at design time.

Conventional governance gates are *pre-deployment*: review the design, approve the model card, sign off the risk assessment, release. Once the thing is live, governance reverts to monitoring and logging — observing, not gating. But the decisions that matter happen **at runtime**: this tool call, this delegation, this data egress, this autonomous retry.

Runtigil holds that the essential gate can be **executed in-flight** — a decision point that can pass, hold, or block *between* an agent's intention and its action:

- **Registry (LGD-I)** — the runtime gate is a registered object with a defined authority and a declared scope.
- **Evidence (LGD-II)** — every gate decision leaves a trace: what was proposed, what rule applied, what verdict issued.
- **Gate (LGD-III)** — the verdict has teeth: PASS proceeds, HOLD suspends, FAIL blocks — and the block is *enforced*, not advisory.

## Why the term was coined

This is the **most severe collision** in the angle set: *Runtime Governance* is not merely used — it is **settled**. The industry has fixed the phrase; anyone using it now is borrowing, not claiming.

**Runtigil** names the *act* rather than the *field* — a coinage fusing **run** + **vigil** (watching that does something). It avoids a phrase already owned while keeping the concept exact. The descriptive subtitle carries search; the coined term carries the claim.

## Position in the stack

| | |
|---|---|
| **Angle ID** | TH-ANG-004 |
| **Domain code** | ANG (cross-domain governance angles) |
| **Parent** | TH-ANG-000 跨域治理角度矩阵 (Cross-Domain Governance Angle Matrix) |
| **Related** | LGD-III 有门禁 · agent-kill-switch · gate-policy-generator |
| **Collision verdict** | Theory layer 🔴🔴🔴 (**"Runtime Governance" is an industry-settled name**) → Coined term 🟢 |

## Real-world referents (mapped, not invented)

| Domain | Referent | Mapping |
|---|---|---|
| Agent runtime | MI9 agent runtime | enforcement hooks at runtime |
| Agent contracts | Agent Behavioral Contracts | the rule object a gate evaluates |
| AI risk management | NIST AI RMF Manage 2.3–2.4 | the management function the gate instantiates |
| Traded finance | pre-trade risk checks, circuit breakers | the mature in-flight gate paradigm |
| Aviation | in-flight envelope protection | an enforced, non-advisory limit |
| Medical devices | SaMD post-market performance monitoring | the regulated analogue |

## Citation

If you use or cite this term, please reference:

> Zhao, S. (2026). *Runtigil: Runtime Gatekeeping — LGD Angle Matrix #4*. SynomosAI.
> https://github.com/zhaoxinghua09-cell/runtigil

## Theory stack

- **LGD — 凡自治之物 · 全程治理论 (Lifecycle Governance Doctrine)** — the parent framework: *有籍 · 有证 · 有门禁* (registered · evidenced · gated) across the full life of an autonomous thing.
- **Cross-domain angle matrix** — 5 angles × 13+ domains; this repo is angle #4.
- Companion angles: Terminance · Mnemoship · Culpachain · Assurability.

## Author

**Author**: 赵兴华 / Steven Zhao
ORCID [0009-0001-0512-1237](https://orcid.org/0009-0001-0512-1237) · https://medxpert.cn

Proposed and named 2026-09-10. Co-created with Lao Paidang (老拍档), AI research partner.
Human authorship, judgment, and final responsibility rest with the author.

## License

Theory names and definitions — all rights reserved by the author. Any citation, use, or extension shall trace back to this source.
