---
title: 16 · Revaluation of Fixed Assets
course: Financial Reporting & Analysis
tags:
  - fra
  - mba
  - revaluation
  - ppe
  - ind-as
  - quiz-3
standards:
  - Ind AS 16
  - IAS 16
running-case: Jiva Industries · Yash Limited
status: reviewed
dg-publish: false
---

← [[15-Depreciation-Delta-Singapore-Airlines]] | [[17-Impairment-of-Assets]] →

> [!abstract] In one line
> The revaluation model lets you carry a **whole class** of assets at current fair value instead of cost. An **increase** goes to a **Revaluation Reserve in equity (via OCI) — never through P&L**; a **decrease** hits **P&L** — unless it reverses a prior surplus on the same asset. Then depreciation is recomputed on the revalued amount, and the extra depreciation is transferred **reserve → general reserve** so distributable profit is untouched.

The single biggest India-vs-US contrast in the topic (S11 §5): **US GAAP bans marking assets up, Ind AS allows revaluation.** If a question asks what an Indian company can do that a US one cannot, this is the answer.

---

## 1. The rules (Ind AS 16 / IAS 16)

Revaluation is a **policy choice** applied to an **entire class** at once — all land, or all buildings, never one cherry-picked asset (paras 29, 36). A revaluation gain isn't something you *earned* by trading; the market simply moved, so it's parked in equity rather than run through this year's profit, and becomes distributable only as it's realised through use or sale. That logic drives the routing:

> [!important] Direction rules
> - Value **UP** → **Revaluation Reserve** in equity, through **OCI**, **not** profit. *(para 39)*
> - Value **DOWN** → **P&L**, *except* to the extent it reverses a surplus already sitting in the reserve for **that same asset** (then it reduces the reserve/OCI first). *(para 40)*
> - **On disposal**, the **whole** surplus for that asset transfers **directly to retained/general reserve** — **not** through P&L (the sale gain/loss is a separate P&L line).

Once revalued, the reserve then moves for two reasons. First, **excess depreciation**: depreciation on the revalued amount runs higher than it would on original cost, and that excess *may* be transferred **Revaluation Reserve → General Reserve** each year so the revaluation doesn't inflate distributable profit. Second, **fresh revaluations**: a later up-revaluation adds to the reserve, a down-revaluation reduces it.

---

## 2. Gross vs net basis

There are two mechanical routes to the same revalued carrying amount. On the **gross basis** you restate *both* gross cost and accumulated depreciation proportionately, so the net figure lands at fair value (Jiva, below). On the **net basis** you first eliminate accumulated depreciation against the asset, then restate the net figure to fair value (Yash, below). The carrying amount comes out identical either way — only the split between cost and accumulated depreciation on the face of the balance sheet differs.

---

## 3. Worked — JIVA INDUSTRIES (gross basis)

**Setup.** Machine cost ₹52,00,000, life 5 yrs, net realisable value ₹2,60,000. SLM.
- Depreciable = 52,00,000 − 2,60,000 = ₹49,40,000 → **annual ₹9,88,000**, rate 9,88,000/52,00,000 = **19%**.
- After 3 yrs: accumulated ₹29,64,000; carrying = 52,00,000 − 29,64,000 = **₹22,36,000**.

**Beginning of year 4** a valuer appraises it at **₹65,00,000**, revised residual **₹3,25,000**.
- New annual depreciation = (65,00,000 − 3,25,000)/5 = **₹12,35,000**; rate = 12,35,000/65,00,000 = **19%**.
- Net book value on revalued amount at start of yr 4 = 65,00,000 − (12,35,000 × 3) = 65,00,000 − 37,05,000 = **₹27,95,000**.
- **Revaluation Reserve = 27,95,000 − 22,36,000 = ₹5,59,000.**

| Balance-sheet disclosure | Year 4 | Year 5 |
|---|---:|---:|
| Cost | 52,00,000 | 65,00,000 |
| Add: increase on revaluation | 13,00,000 | — |
| **Cost after revaluation** | **65,00,000** | **65,00,000** |
| Accum. dep at beginning | 29,64,000 | 49,40,000 |
| Add: accum. dep on the ₹13,00,000 uplift, 3 yrs @19% | 7,41,000 | — |
| **Accum. dep after revaluation** | **37,05,000** | **49,40,000** |
| Add: depreciation for the year (on revalued amt) | 12,35,000 | 12,35,000 |
| **Total accumulated depreciation** | **49,40,000** | **61,75,000** |
| **Net book value** | **15,60,000** | **3,25,000** |
| **Revaluation Reserve** | **5,59,000** | **5,59,000** |

Notice Jiva's reserve sits still at ₹5,59,000 across both years. The annual transfer of *excess depreciation* from Revaluation Reserve to General Reserve is **permitted, not required** (Ind AS 16, para 41): Jiva simply doesn't make it, so its reserve holds until disposal, whereas Yash (below) *does* make it and draws its reserve down year by year. Both are acceptable — just don't expect the reserve to move on its own when the transfer isn't being made.

---

## 4. Worked — YASH LIMITED (net basis, 3-yearly cycle)

**Setup.** Building acquired 1 Jan 2010, cost ₹5,00,000, life 20 yrs, residual nil, SLM (₹25,000/yr). Revalued every 3 years. Fair values: 2013 = 6,00,000; 2016 = 5,60,000; 2019 = 4,00,000. *(FY ends 31 Dec; table runs 2010–2020.)*

| Year | CA begin | Dep | CA end | Reval gain/(loss) | RR→GR transfer | RR end |
|---|---:|---:|---:|---:|---:|---:|
| 2010 | 5,00,000 | 25,000 | 4,75,000 | — | — | — |
| 2011 | 4,75,000 | 25,000 | 4,50,000 | — | — | — |
| 2012 | 4,50,000 | 25,000 | 4,25,000 | — | — | — |
| **2013** | 6,00,000 | 35,300 | 5,64,700 | **1,75,000** | 10,300 | 1,64,700 |
| 2014 | 5,64,700 | 35,300 | 5,29,400 | — | 10,300 | 1,54,400 |
| 2015 | 5,29,400 | 35,300 | 4,94,100 | — | 10,300 | 1,44,100 |
| **2016** | 5,60,000 | 40,000 | 5,20,000 | **65,900** | 15,000 | 1,95,000 |
| 2017 | 5,20,000 | 40,000 | 4,80,000 | — | 15,000 | 1,80,000 |
| 2018 | 4,80,000 | 40,000 | 4,40,000 | — | 15,000 | 1,65,000 |
| **2019** | 4,00,000 | 36,360 | 3,63,640 | **(40,000)** | 11,360 | 1,13,640 |
| 2020 | 3,63,640 | 36,360 | 3,27,240 | — | 11,360 | 1,02,280 |

> [!note] How each revaluation year is built
> - **2013 gain** = 6,00,000 − CA 4,25,000 = ₹1,75,000 → Revaluation Reserve.
> - **New depreciation 2013–15** = 6,00,000 / **17 remaining years** = ₹35,300.
> - **RR→General Reserve each year** = excess depreciation = 35,300 − 25,000 = **₹10,300** (revaluation must not inflate distributable profit).
> - **2016** revalued to 5,60,000 (CA was 4,94,100) → gain ₹65,900; dep = 5,60,000/14 = 40,000; transfer 15,000.
> - **2019 is a LOSS**: CA 4,40,000 → 4,00,000 = ₹40,000 down. It reverses part of the existing surplus on this asset, so it **reduces the Revaluation Reserve (OCI)**, not P&L. Dep = 4,00,000/11 = 36,360; transfer 11,360.

The rule behind that 2019 loss is worth stating cleanly (para 40): when an asset's value **falls**, first check whether a surplus for *that same asset* still sits in the reserve — reduce the reserve (through OCI) up to that balance, and only the excess beyond it drops to **P&L**. A rise works as the mirror image: to the extent it reverses a past P&L loss on that asset it goes back through P&L, and the rest to the reserve.

---

## 5. Revaluation + disposal (Fun Quiz Q5 pattern)

> [!important] On disposal, the whole surplus for that asset → General Reserve (not P&L)
> When the asset leaves the books, the **entire** revaluation surplus sitting against it transfers **directly** to retained/general reserve, bypassing the income statement (Ind AS 16 — "transfer the whole of the revaluation surplus … when the asset is disposed of"). The gain or loss on the sale itself is a **separate** line that does go through **P&L**.

> [!example] Fun Quiz Q5 — revalue, then sell immediately
> Machine BV ₹3,00,000, revalued to ₹3,50,000 (Revaluation Reserve ₹50,000). Sold immediately for ₹3,20,000. **Amount transferred to General Reserve?**
>> Two separate moves. **(1) Reserve transfer:** the full ₹50,000 surplus goes RR → General Reserve. **(2) P&L:** loss on sale = proceeds − revalued carrying = 3,20,000 − 3,50,000 = **₹30,000 loss**. The *net* addition to reserves/retained earnings = 50,000 − 30,000 = **₹20,000**, which equals the true gain over *original* book value (3,20,000 − 3,00,000). **The professor's answer is ₹20,000 — the net figure.**
>> **Watch the wording.** ₹20,000 is the *net* effect. The amount that actually leaves the *revaluation reserve* is the whole **₹50,000**; only if the question asks for the **net** landing in general reserve is it ₹20,000 (= proceeds − original BV). Read which one it wants.

---

## Before the quiz

- **Up → Revaluation Reserve (OCI); down → P&L** unless it reverses that asset's own surplus (then reduce the reserve first). It's a **policy choice** applied to the **whole class**, never one cherry-picked asset.
- After revaluing, **depreciate on the revalued amount over remaining life**, not on old cost; the **excess depreciation** may be transferred RR → General Reserve each year so distributable profit is unchanged (Yash: 10,300 / 15,000 / 11,360).
- **Jiva:** RR ₹5,59,000, rate 19%, revalued dep ₹12,35,000 (reserve held flat — no annual transfer made).
- **Yash:** 2019's downward revaluation reduces the reserve (OCI), not P&L, because a surplus for that asset still exists.
- **Disposal (Q5):** the whole surplus (₹50,000) transfers to General Reserve and the sale loss (₹30,000) hits P&L separately; the **net** to reserves = proceeds − original BV = ₹20,000 — check which figure the question wants.

**Related:** [[FRA Session 13]] · [[17-Impairment-of-Assets]] · [[14-Depreciation-Methods-and-Changes]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
