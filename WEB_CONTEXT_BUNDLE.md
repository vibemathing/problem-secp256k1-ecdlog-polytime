# Web Research Context Bundle

This file is generated from repository truth and bounded for the web channel. It is navigation context, not a Result, EvidenceLink, verifier receipt, or permission grant.

## Mandatory order

1. Read `AGENTS.md`, `governance/harness/PROJECT_AGENTS.md`, and `WEB_BOOTSTRAP.md`.
2. Check the exact ProblemContract and its SHA-256 below.
3. Select exactly one pre-admitted Attempt/Route/ObligationGraph/Obligation.
4. Search registered mathematical knowledge sources before inventing a new theorem.
5. After repository admission, autonomously complete Issue, candidate branch/file edits, commit, PR review, checks/rerun, merge, and checkpoint within the profile.
6. Write only candidate files under the profile allowlist and one `WEB_ATTEMPT_PACKET`; do not wait for project-added routine human approvals.
7. Never claim that Issue, PR, AI review, merge, Actions status, package build, search hit, test success, or this context closes mathematics.

## Compiled repository truth

```json
{
  "active_skills": [
    {
      "entry": ".codex/skills/math-computation/SKILL.md",
      "entry_sha256": "80c447221725ec198bee4b104d43ca28425110a7dac17afa9cad56ec69b57f48",
      "skill_id": "math-computation",
      "version": "0.6.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/math-derivation/SKILL.md",
      "entry_sha256": "3f3b567729f1e5dd24f87e832fdac702577f4add14b8cf6be12d538e1fe787c1",
      "skill_id": "math-derivation",
      "version": "0.4.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-discovery/SKILL.md",
      "entry_sha256": "ceb54d773cd970ca42d0243fb1a39b109cab3ffdbe2dd87b98b43539f988d471",
      "skill_id": "math-discovery",
      "version": "0.4.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-formalization/SKILL.md",
      "entry_sha256": "8ade921dacd277f425f424064a6002806c057f160555081dbdb4ec05c1f5ea05",
      "skill_id": "math-formalization",
      "version": "0.5.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/math-proof/SKILL.md",
      "entry_sha256": "61006c732ad69e73f56be126acb6fa9e25c866e18733ce1f0f3863c1f8eea80f",
      "skill_id": "math-proof",
      "version": "0.5.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-toolchain/SKILL.md",
      "entry_sha256": "f6514e01358aa2e40f8b7e3bb9221fd9abca6b7ff37ec6920f2c2cf537533f7b",
      "skill_id": "math-toolchain",
      "version": "0.2.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/solve/SKILL.md",
      "entry_sha256": "ff557dc3fc2fa10df4b21e8bef251a37928f5572ccf0092c79f0d9ab90a00ec0",
      "skill_id": "solve",
      "version": "0.3.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/vibe-mathing-router/SKILL.md",
      "entry_sha256": "65f6b25fe152a4cc2fa9ecb03626dad6e3b70473fc256ac9acbabd0ef7cb9e8e",
      "skill_id": "vibe-mathing-router",
      "version": "0.4.0",
      "web_status": "active"
    }
  ],
  "attempts": [],
  "failed_routes": [],
  "knowledge_operators": [
    {
      "evidence_ceiling": "discovery_only",
      "external_effect": "none",
      "operator_id": "op:identify-mathematical-object",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_local",
      "operator_id": "op:search-formal-theorem",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_network",
      "operator_id": "op:search-mathematical-database",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_local",
      "operator_id": "op:resolve-formal-package",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:compare-statements",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:compose-reuse-plan",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:prove-reuse-gap",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "bounded_candidate_build",
      "operator_id": "op:build-formal-candidate",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "verifier_receipt",
      "external_effect": "bounded_candidate_build",
      "operator_id": "op:verify-formal-candidate",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "verifier_receipt",
      "external_effect": "none",
      "operator_id": "op:review-reuse-semantics",
      "owner_skill": "math-proof"
    }
  ],
  "knowledge_sources": [
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "installed",
      "operational_status": "quarantined",
      "source_class": "formal_library_index",
      "source_id": "lean-mathlib-local"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_package_registry",
      "source_id": "lean-reservoir"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_library_index",
      "source_id": "mathlib-docs-search"
    },
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "proof_archive",
      "source_id": "isabelle-afp"
    },
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_package_registry",
      "source_id": "rocq-mathcomp"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "mathematical_object_database",
      "source_id": "oeis"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "mathematical_object_database",
      "source_id": "lmfdb"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "available",
      "source_class": "formula_reference",
      "source_id": "nist-dlmf"
    },
    {
      "evidence_ceiling": "computation_evidence",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "algorithm_distribution",
      "source_id": "sagemath"
    }
  ],
  "obligation_graphs": [],
  "problem_contract": {
    "acceptance": {
      "policy": "solution-admission-v1"
    },
    "aliases": [
      "secp256k1 ECDLP",
      "secp256k1 discrete logarithm"
    ],
    "allowed_axioms": [
      "finite-field arithmetic",
      "elliptic-curve group law",
      "classical probability",
      "standard randomized-Turing-machine cost model"
    ],
    "assumptions": [
      "n is prime and the standard secp256k1 cofactor is h=1",
      "the input point Q belongs to <G>",
      "the computational model is classical and excludes quantum queries",
      "generic-group lower bounds are not treated as impossibility proofs for non-generic algorithms",
      "all computational experiments must use explicit time, memory, output and stopping budgets"
    ],
    "constraints": {
      "allowed_adapters": [],
      "allowed_methods": [
        "discovery",
        "derivation",
        "computation",
        "proof",
        "formalization"
      ],
      "max_attempts": 4,
      "runtime": {
        "max_output_bytes": 8388608,
        "max_retries": 2,
        "max_transitions": 128,
        "timeout_seconds": 3600
      }
    },
    "created_at": "2026-09-01T20:23:17Z",
    "definitions": [
      {
        "definition": "secp256k1 base-point order n = 0xFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFEBAAEDCE6AF48A03BBFD25E8CD0364141",
        "term": "n"
      },
      {
        "definition": "given (G,Q) with Q=[k]G, return the unique k in Z/nZ",
        "term": "ECDLP inverse"
      },
      {
        "definition": "worst-case expected running time bounded by a polynomial in the bit length log p on a classical randomized machine",
        "term": "classical polynomial time"
      },
      {
        "definition": "probability over the algorithm's classical random bits that the returned scalar satisfies [k]G=Q",
        "term": "success probability"
      }
    ],
    "domain": {
      "description": "标准 secp256k1 素数域上的椭圆曲线群、离散对数逆映射、经典随机算法及其渐近资源界",
      "objects": [
        "prime p = 0xFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFEFFFFFC2F",
        "elliptic curve E/F_p: y^2 = x^3 + 7",
        "prime-order subgroup <G> of order n",
        "classical randomized algorithms"
      ]
    },
    "lifecycle": "active",
    "msc": [
      "11G05",
      "11Y16",
      "68Q25"
    ],
    "problem_id": "problem:secp256k1-ecdlog-polytime",
    "quantifiers": [
      {
        "domain": "classical randomized algorithms with input (p,E,G,Q) and output k",
        "kind": "find",
        "variables": [
          "A"
        ]
      },
      {
        "domain": "Q = [k]G with k in Z/nZ",
        "kind": "forall",
        "variables": [
          "Q",
          "k"
        ]
      }
    ],
    "schema_version": "1.0.0",
    "sources": [
      {
        "retrieved_at": "2026-09-01T20:23:17Z",
        "source": "SEC 2 v2.0",
        "source_record_id": null,
        "url": "https://www.secg.org/sec2-v2.pdf"
      },
      {
        "retrieved_at": "2026-09-01T20:23:17Z",
        "source": "IACR ePrint 2011/008",
        "source_record_id": null,
        "url": "https://eprint.iacr.org/2011/008.pdf"
      },
      {
        "retrieved_at": "2026-09-01T20:23:17Z",
        "source": "libsecp256k1 scalar implementation",
        "source_record_id": null,
        "url": "https://github.com/bitcoin-core/secp256k1/blob/master/src/scalar_impl.h"
      },
      {
        "retrieved_at": "2026-09-01T20:23:17Z",
        "source": "MIT 18.783 Lecture Notes 9",
        "source_record_id": null,
        "url": "https://math.mit.edu/classes/18.783/2021/LectureNotes9.pdf"
      }
    ],
    "statement": {
      "language": "zh-CN",
      "text": "给定标准 secp256k1 参数 p、E: y^2 = x^3 + 7 over F_p、基点 G 及任意 Q = [k]G，寻找一个经典随机算法 A，在所有合法输入上输出 k，并证明其运行时间为 poly(log p) 且成功概率至少为 2/3；若只能得到平方根复杂度或有限范围实验，则只能登记为部分结果，不能宣称原目标已解决。",
      "version": 1
    },
    "title": "secp256k1 离散对数逆映射的经典多项式时间性审计",
    "updated_at": "2026-09-01T20:23:17Z"
  },
  "problem_contract_sha256": "d9b3d6554f59b9ec8544bddd33f89f66af7db315bb01bb9fe8a0c5316963529e"
}
```
