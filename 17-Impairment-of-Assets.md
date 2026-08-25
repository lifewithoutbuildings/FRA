---
title: 17 · Impairment of Assets
course: Financial Reporting & Analysis
tags:
  - fra
  - mba
  - impairment
  - ppe
  - ind-as
  - quiz-3
standards:
  - Ind AS 36
  - AS 28
running-case: Jaya Heavy Industries
status: reviewed
dg-publish: false
---

← [[16-Revaluation-of-Fixed-Assets]] | [[18-Intangible-Assets]] →

> [!abstract] In one line
> Impairment is the **nasty surprise** version of depreciation: the asset is suddenly worth less than the books say. Write it down to its **recoverable amount = the higher of (fair value less costs to sell) and (value in use)**, and take the hit to **P&L — but against any Revaluation Reserve first**.

An asset is impaired when its **carrying amount exceeds its recoverable amount** — the Day-4 test — and you write it down to that recoverable amount. Recoverable amount is the **higher** of the two ways you could still get value back from the asset:

$$\text{Recoverable amount} = \max\big(\text{Net selling price},\ \text{Value in use}\big)$$

Net selling price is fair value less costs to sell (AS 28 and Ind AS 36 wording for the same thing), and **value in use (VIU)** is the present value of the future cash flows from using the asset plus its eventual disposal, discounted at a pre-tax rate. It helps to see impairment as the unplanned cousin of depreciation: depreciation is the *planned* decline, impairment the *unplanned* one from damage, obsolescence or collapsed demand. And physical damage is only a **trigger to test** — the test can still conclude there is no impairment, as with Stafford's repaired machine (S11 §6).

---

## 1. Where the impairment loss goes

An impairment loss normally hits **P&L** (`Dr Impairment loss / Cr Asset`). The one twist: if a **Revaluation Reserve exists for that same asset**, the loss reduces that reserve (OCI) **first**, and only the **excess** beyond it drops to P&L — the mirror image of a revaluation decrease. That's why the same impairment can cost reported profit very differently depending on whether the asset was previously revalued. One further asymmetry with US GAAP: under Ind AS 36 you may **reverse** an impairment if conditions later improve (goodwill excepted), whereas US GAAP holds that once an asset is written down it stays down.

---

## 2. Worked — JAYA HEAVY INDUSTRIES (AS 28 / Ind AS 36)

**Setup.** As at 31 Mar 2006, machine net book value **₹95.32 lacs** (net of this year's ₹15.50 lacs depreciation). Sluggish demand → test for impairment. Pre-tax discount rate **16%**. Net selling price **₹65.50 lacs**. Estimated pre-tax cash flows over the remaining 6 years:

| Year | Operating CF | Disposal CF | Total | DF @16% | PV |
|---|---:|---:|---:|---:|---:|
| 2006–07 | 21.50 | — | 21.50 | 0.8621 | 18.53 |
| 2007–08 | 20.85 | — | 20.85 | 0.7432 | 15.49 |
| 2008–09 | 19.67 | — | 19.67 | 0.6407 | 12.60 |
| 2009–10 | 17.44 | — | 17.44 | 0.5523 | 9.63 |
| 2010–11 | 16.38 | — | 16.38 | 0.4761 | 7.80 |
| 2011–12 | 16.23 | 4.86 | 21.09 | 0.4104 | 8.66 |
| | | | | **Value in use** | **≈ 72.72** |

Discounting each year's total at 16% and summing gives a **value in use of ≈ ₹72.72 lacs** (the exact figure sits around ₹72.70–72.72 depending on how many decimals you keep in the discount factors). The recoverable amount is the higher of that and the ₹65.50 lac net selling price — so **₹72.72 lacs** — and since the machine is carried at ₹95.32 lacs, it is **impaired by ₹22.60 lacs**. With no revaluation reserve behind it, the whole write-down goes to P&L:

```
Dr  Impairment loss (P&L)        22.60
        Cr  Machine / Accum. impairment   22.60
```

Profit falls ₹22.60 lacs, the carrying amount drops to ₹72.72 lacs, and future depreciation is recomputed on that lower base over the remaining life.

Parts (5) and (6) are the exam's favourite twist — the same impairment routed through different revaluation histories. If a **₹12 lac** revaluation reserve exists for this machine, the loss hits the reserve first: ₹12.00 lacs is absorbed in OCI and the remaining **₹10.60 lacs** goes to P&L. If the reserve were **₹25 lacs**, it swallows the whole ₹22.60 lacs in OCI and **nothing** touches P&L. Same economic loss, very different reported profit.

---

## 2b. Goodwill & intangibles — the CGU test (from the intangibles reading)

Goodwill and indefinite-life intangibles earn no cash on their own, so they can't be impairment-tested in isolation. Instead they're tested inside the smallest group of assets that generates cash independently — a **Cash Generating Unit (CGU)**, typically a division — by comparing the CGU's recoverable amount (again the higher of VIU and fair value less costs to sell) with the aggregate book value of everything in it. If the CGU is impaired, the loss is allocated in a **strict order**: write **goodwill down first**, and only any excess beyond goodwill is spread pro-rata across the other assets, other intangibles included. Goodwill impairment, once taken, is **never reversed** — even under Ind AS.

> [!example] CGU allocation
> Division: goodwill ₹8 lacs + other assets ₹40 lacs (book) = ₹48 lacs. Recoverable amount ₹42 lacs.
>> Impairment = 48 − 42 = **₹6 lacs**, which is ≤ goodwill → **all ₹6 lacs off goodwill** (→ ₹2 lacs left); other assets untouched.
>> *If* recoverable were ₹36 lacs → impairment 12 > goodwill 8: goodwill to **0**, remaining **₹4 lacs** across the other assets pro-rata.
>> Full treatment: [[18-Intangible-Assets#5. Goodwill impairment lives at the CGU level|note 18 §5]].

---

## 3. The three lookalikes, kept straight (S11 §6)

| Situation | Response |
|---|---|
| Estimate of salvage/life was off | Adjust **depreciation going forward** ([[14-Depreciation-Methods-and-Changes|note 14]]) |
| Asset worth less than book value | **Write down** — impairment (this note) |
| Asset destroyed, no use left | **Remove entirely**, whole book value to loss |

---

## Before the quiz

- Recoverable amount is the **HIGHER** of net selling price and value in use — never the lower — and VIU must be **discounted** at the pre-tax rate (16% for Jaya); forgetting to discount is a classic slip.
- The loss hits any **Revaluation Reserve first, then P&L** — routing the whole thing to P&L when a reserve exists overstates the hit to profit.
- **Jaya:** VIU ≈ ₹72.72 lacs > NSP ₹65.50 → recoverable ₹72.72 → **impairment ≈ ₹22.60 lacs**; with RR ₹12 lacs, ₹10.60 to P&L; with RR ₹25 lacs, nil to P&L.
- Physical damage is a **trigger to test**, not automatic impairment — the test can find none.
- Ind AS allows an impairment **reversal** (never for goodwill); US GAAP never reverses. Goodwill is tested at the **CGU** level and written down **first**.

**Related:** [[FRA Session 13]] · [[16-Revaluation-of-Fixed-Assets]] · [[14-Depreciation-Methods-and-Changes]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
