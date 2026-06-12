## ❌ Test Results — Flipkart_OS_2254.spec.js

**Status:** FAILED | **Run at:** 12/6/2026, 10:54:33 am

### ⚙️ Test Configuration
| Setting | Value |
|---|---|
| Suite | Flipkart_OS_2254.spec.js |
| Environment | `—` |
| Partner | `—` |
| Grep filter | — |
| Spec file(s) | `Flipkart_OS_2254.spec.js` |

### 📊 Metrics
| Metric | Value |
|---|---|
| Total Tests | 8 |
| ✅ Passed | 4 |
| ❌ Failed | 4 |
| ⏭️ Skipped/Pending | 0 |
| Pass Rate | 50% |
| Duration | 10m 28s |

### ❌ Failed cases
- @os-2254 @ruleC @edge RC-02 income<15000 but turnover slab lifts it → no Rule C reject
- @os-2254 @ruleC @edge RC-05 income<15000 + top slab 'Rs.500 Cr. and above' (capped at 500 Cr) → derived ~4.16 Cr/mo ≥ 15000 → NO Rule C reject
- @os-2254 @ruleC @negative RC-06 income 0 (lowest) + no turnover → both 0 < 15000 → Rule C REJECT
- @os-2254 @ruleC @edge RC-08 income<15000 + mid slab 'Rs.1.5 Cr. to 5 Cr.' → derived 4,16,667 ≥ 15000 → NO Rule C reject

📈 [View Full HTML Report](https://anirudhpenumaka-incred.github.io/Embedded-reports/pl-ui-automation/2026-06-12-05-24-33/)
