## ❌ Test Results — Flipkart_OS_2258_penny.spec.js

**Status:** FAILED | **Run at:** 6/11/2026, 6:27:46 AM

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
| Total Tests | 13 |
| ✅ Passed | 0 |
| ❌ Failed | 13 |
| ⏭️ Skipped/Pending | 0 |
| Pass Rate | 0% |
| Duration | 33m 44s |

### ❌ Failed cases
- A1 — Tier-1 PASS (name matches bank) → Completed, no CPA
- A2 — Tier-1 fail → Tier-2 PASS via GSTIN → Completed, no CPA
- A3 — Tier-1 fail → Tier-2 FAIL via GSTIN → CPA
- A4 — Tier-1 fail → Tier-2 PASS no GSTIN (max across pool) → Completed
- A7 — business_name typed in Create must NOT rescue → CPA
- A5 — Tier-1 fail → no GSTIN → all names fail → CPA
- A6 — GSTIN sent but NOT in soft-pull → app rejected (GSTIN mismatch with Soft Pull)
- E1 — RESULT: Tier-1 PASS (name matches) → Completed, no CPA
- E2 — RESULT: Tier-1 fail → Tier-2 PASS via GSTIN → Completed, no CPA
- E3 — RESULT: Tier-1 fail → Tier-2 FAIL via GSTIN → CPA
- E4 — RESULT: Tier-1 fail → Tier-2 PASS no GSTIN (max across pool) → Completed
- E5 — RESULT: Tier-1 fail → no GSTIN → all names fail → CPA
- E7 — RESULT: business_name typed in Create must NOT rescue → CPA

📈 [View Full HTML Report](https://anirudhpenumaka-incred.github.io/Embedded-reports/pl-ui-automation/2026-06-11-00-57-46/)
