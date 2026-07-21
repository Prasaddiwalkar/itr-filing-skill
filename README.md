# 🇮🇳 ITR Filing Skill for Claude

A comprehensive Claude skill for filing Indian Income Tax Returns —
covers every salaried employee scenario from simple ITR-1 to complex
ITR-2 with foreign assets, RSUs, capital gains, and DTAA.

![AY 2026-27](https://img.shields.io/badge/AY-2026--27-blue)
![ITR Forms](https://img.shields.io/badge/Forms-ITR--1%20%7C%20ITR--2-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 Install in 30 Seconds

1. Download [itr-filing-latest.skill](./releases/itr-filing-latest.skill)
2. Open [Claude.ai](https://claude.ai)
3. Upload the `.skill` file in any chat
4. Click **Save skill**
5. Start a new chat — ask: *"Help me file my ITR"*

## 👥 Who Is This For?

| Employee Type | ITR Form | Path |
|---|---|---|
| Salary only, income ≤ ₹50L | ITR-1 | 🟢 Path A — Simple |
| Salary + stocks / mutual funds | ITR-2 | 🟡 Path B — Domestic |
| Salary + eTrade / RSU / foreign assets | ITR-2 | 🔴 Path C — Foreign |
| Income > ₹50L (Schedule AL + Surcharge) | ITR-2 | 🔵 Section D — High Income |

## 📋 What the Skill Does

**Phase 1 — Profile Assessment**
Asks a few quick questions to determine your filing path and documents needed.

**Phase 2 — Document Collection**
Shows a tailored checklist. Minimum for simple cases: Form 16 + Form 26AS.

**Phase 3 — Income Extraction**
Reads your uploaded documents and presents a complete income summary.

**Phase 4 — Portal Guidance**
Walks you through incometax.gov.in screen by screen with exact values.

**Phase 5 — Post Filing**
Explains verification, refund tracking, and handling notices.

## 📁 Reference Files Included

| File | Contents |
|---|---|
| `itr-forms.md` | ITR form selection decision tree |
| `regime-guide.md` | New vs Old regime comparison |
| `deductions-guide.md` | All 80C / 80D / 24b deduction rules |
| `dtaa-rates.md` | Country-wise DTAA rates |
| `schedule-fa-guide.md` | Foreign asset declaration categories |

## 🗓️ Coverage

| Item | Detail |
|---|---|
| Assessment Year | AY 2026-27 (FY 2025-26) |
| Tax Regime | New Regime + Old Regime |
| ITR Forms | ITR-1, ITR-2 |
| Schedules | S, HP, OS, CG, FA, FSI, TR, AL, VDA, VI-A |
| Special Topics | HRA, RSU/ESOP, EPF, Gratuity, Arrears, NRI |

## ⚠️ Disclaimer

This skill provides guidance based on publicly available tax rules.
Not a substitute for professional advice. For complex situations,
consult a qualified Chartered Accountant.

## 🤝 Contributing

PRs welcome! See [CONTRIBUTING.md](./CONTRIBUTING.md)

## 📄 License

MIT License — free to use, modify, and distribute.

---
*Built to simplify Indian tax filing for salaried employees*
