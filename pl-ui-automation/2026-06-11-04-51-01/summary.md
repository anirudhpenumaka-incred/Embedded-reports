## ❌ Test Results — Flipkart_OS_2258_penny.spec.js

**Status:** FAILED | **Run at:** 11/6/2026, 10:21:01 am

### ⚙️ Test Configuration
| Setting | Value |
|---|---|
| Suite | Flipkart_OS_2258_penny.spec.js |
| Environment | `—` |
| Partner | `—` |
| Grep filter | — |
| Spec file(s) | `Flipkart_OS_2258_penny.spec.js` |

### 📊 Metrics
| Metric | Value |
|---|---|
| Total Tests | 22 |
| ✅ Passed | 7 |
| ❌ Failed | 14 |
| ⏭️ Skipped/Pending | 1 |
| Pass Rate | 33% |
| Duration | 50m 31s |

### ❌ Failed cases
- A1 — Tier-1 PASS (name matches bank) → Completed, no CPA
- A2 — Tier-1 fail → Tier-2 PASS via GSTIN → Completed, no CPA
- A4 — Tier-1 fail → Tier-2 PASS no GSTIN (max across pool) → Completed
- A6 — GSTIN sent but NOT in soft-pull → app rejected (GSTIN mismatch with Soft Pull)
- B1 — Flipkart SALARIED → old logic (Retry), no CPA
- B2 — Non-Flipkart (Paytm) → old logic (Retry), no CPA
- E1 — RESULT: Tier-1 PASS (name matches) → Completed, no CPA
- E2 — RESULT: Tier-1 fail → Tier-2 PASS via GSTIN → Completed, no CPA
- E3 — RESULT: Tier-1 fail → Tier-2 FAIL via GSTIN → CPA
- E4 — RESULT: Tier-1 fail → Tier-2 PASS no GSTIN (max across pool) → Completed
- E5 — RESULT: Tier-1 fail → no GSTIN → all names fail → CPA
- E7 — RESULT: business_name typed in Create must NOT rescue → CPA
- C3 — account number mismatch on init → ACCOUNT_MISMATCH error
- D3 — result with account mismatch → ACCOUNT_MISMATCH error

<details><summary>⏭️ Skipped cases (1)</summary>

- C4 — primary score exactly at threshold → PASS [BLOCKED OQ-1 / `>` vs `>=`]

</details>

📈 [View Full HTML Report](https://anirudhpenumaka-incred.github.io/Embedded-reports/pl-ui-automation/2026-06-11-04-51-01/)
