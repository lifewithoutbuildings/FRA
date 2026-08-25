---
title: 14 · Depreciation — Methods, Part-Years & Changes in Estimate/Method
course: Financial Reporting & Analysis
tags:
  - fra
  - mba
  - depreciation
  - ppe
  - ind-as
  - quiz-3
standards:
  - Ind AS 16
  - Ind AS 8
running-case: The bus (₹8,00,000)
status: reviewed
dg-publish: false
---

← [[13-Long-Term-Assets-Acquisition-Disposal-Exchange]] | [[15-Depreciation-Delta-Singapore-Airlines]] →

> [!abstract] In one line
> Depreciation is **spreading an asset's cost over the years it serves you** — not a fall in market value, not a cash fund. Three methods decide the *shape* of the spread; when your estimate turns out wrong you fix it **going forward, never backward**.

The definition to write in the exam: depreciation is the **allocation of the depreciable amount** (cost − residual value) of an asset over its useful life, so that profit or loss is measured properly — the matching idea. It is a cost-spreading exercise, **not** a valuation of the asset and **not** a source or fund of cash.

---

## 1. The three methods

The three methods differ only in the *shape* of the spread, never the total: over an asset's whole life every one of them writes off exactly cost − residual, and they part ways only on *when* the charge falls.

| Method | Assumption | Yearly depreciation |
|---|---|---|
| **Straight-line (SLM)** | Value used up by **passage of time** | $\dfrac{\text{Cost} - \text{Residual}}{\text{Useful life}}$ — same every year |
| **Written-down value (WDV) / reducing balance** | Value used up **faster early** | Rate × *opening book value* each year |
| **Production-unit** | Value used up by **use**, not time | Unit rate × output; unit rate = $\dfrac{\text{Cost} - \text{Residual}}{\text{Total estimated output}}$ |

> [!important] The WDV rate formula (Day 2 takeaway)
> $$r = 1 - \left(\frac{R}{C}\right)^{1/n}$$
> where **R** = residual value, **C** = cost, **n** = life in years. This rate is applied to the **opening book value** each year, so the charge falls over time.

For tax purposes in India **only WDV is allowed**, while SLM is the common choice for the published accounts — so the same asset can carry two different depreciation numbers, one for the tax return and one for the annual report.

### Worked schedules — the bus (Cost ₹8,00,000, residual ₹80,000, life 6 yrs)

**SLM** — depreciable ₹7,20,000 ÷ 6 = **₹1,20,000/yr**, flat.

**WDV** — rate = 1 − (80,000/8,00,000)^(1/6) = 1 − 0.6813 = **0.3187 (31.87%)**, applied to opening book value:

| Year | Opening BV | Dep @ 31.87% | Closing BV |
|---|---:|---:|---:|
| 1 | 8,00,000 | 2,54,960 | 5,45,040 |
| 2 | 5,45,040 | 1,73,705 | 3,71,335 |
| 3 | 3,71,335 | 1,18,345 | 2,52,990 |
| 4 | 2,52,990 | 80,629 | 1,72,361 |
| 5 | 1,72,361 | 54,933 | 1,17,428 |
| 6 | 1,17,428 | 37,428 | 80,000 |

**Production-unit** — unit rate = 7,20,000 ÷ 2,00,000 km = **₹3.60/km**; charge = 3.60 × km run that year (e.g. 70,000 km → ₹2,52,000).

WDV front-loads the charge — ₹2,54,960 in year 1 against SLM's flat ₹1,20,000 — so the choice of method only shuffles the *timing*: heavier early depreciation means lower early profit and lower early tax, but the same ₹7,20,000 is written off by the end either way.

---

## 2. Part-year depreciation

For an asset in service only part of a year, pro-rate the annual charge to the months in use:

$$\text{Depreciation} = \text{Annual charge} \times \frac{\text{Months in use}}{12}$$

> [!example] Fun Quiz Q4 — part-year
> Machine bought **1 July**, cost ₹34,000, life 5 yrs, residual ₹2,000. Year ends **31 March** → **9 months** in use.
>> Annual = (34,000 − 2,000)/5 = 6,400. Part-year = 6,400 × 9/12 = **₹4,800**.
>> The trap: an Indian fiscal year ends 31 March, so July→March is **9 months (0.75)**, not a full year.

---

## 3. Change in ESTIMATE — always prospective (Ind AS 8)

When new information shows your estimate of residual value, useful life (or, on the Ind AS view, the method itself) was wrong, you don't rewrite past years. You spread the *remaining* book value, less the revised residual, over the *remaining* revised life — and nothing is booked on the day the estimate changes; the revision surfaces only in future years' depreciation.

$$\text{Revised annual dep} = \frac{\text{Carrying amount now} - \text{Revised residual}}{\text{Remaining useful life}}$$

> [!example] Fun Quiz Q3 — revised useful life
> Computer ₹90,000, residual ₹10,000, life 8 yrs. After **2 years**, now expected to last **3 more years**, residual still ₹10,000.
>> Original annual = (90,000 − 10,000)/8 = 10,000. Accumulated after 2 yrs = 20,000. Carrying amount = **70,000**.
>> Revised = (70,000 − 10,000)/3 = **₹20,000/yr** from year 3.

> [!example] Stafford's damaged machine (S11 §4) — residual falls
> Cost ₹10,000, was ₹805/yr (10% of ₹8,050), 4 yrs done → BV ₹6,780, 6 yrs left. Residual drops ₹1,950→₹1,290.
>> New dep = (6,780 − 1,290)/6 = **₹915/yr**. Gut-check: ₹110 extra × 6 yrs = ₹660 = exactly the drop in residual. ✓

---

## 4. Change in METHOD — also prospective, from carrying amount

A change of *method* is handled the same way — treated as a change in estimate and applied **prospectively**: take the carrying amount at the date of change and run the new method over the remaining life, never recomputing earlier years. This is the classic past-Quiz-3 Q1 pattern (SLM → WDV). The trap when switching to WDV mid-life is the **rate**: derive it from the **carrying amount and remaining life**, not from original cost and original life.

$$r = 1 - \left(\frac{\text{Revised residual}}{\text{Carrying amount now}}\right)^{1/\text{remaining life}}$$

> [!example] "Asif" — SLM → WDV at start of year 4 (S13 exercise, rate verified)
> Car ₹5,00,000, residual ₹50,000, life 6 yrs, SLM. After 3 yrs switch to WDV.
>> SLM dep = (5,00,000 − 50,000)/6 = 75,000/yr → accumulated 2,25,000 → carrying **₹2,75,000**. Remaining life 3 yrs.
>> WDV rate = 1 − (50,000/2,75,000)^(1/3) = **0.4335 (43.35%)** — *from carrying amount, remaining life*, **not** 1 − (50,000/5,00,000)^(1/6) = 31.87%.
>> Year-4 dep = 2,75,000 × 43.35% = **₹1,19,213**.
>> **If you'd used 31.87% you'd be wrong** — that's the whole trap.

---

## Before the quiz

- Depreciable amount = **cost − residual**; SLM is flat, WDV front-loaded, units by output — but all three write off the **same total**, differing only in timing.
- WDV rate off *cost*: $1-(R/C)^{1/n}$. WDV rate when *switching* mid-life: off **carrying amount and remaining life** (Asif 43.35%, not the cost-based 31.87%) — the single biggest trap in this topic.
- Part-year = annual × months/12; remember the Indian FY ends 31 March, so July→March is 9 months, not a year (Q4).
- Change in estimate **or** method → **prospective**: remaining book value over remaining life, with **no entry** on the day of the change.
- India uses WDV for tax, SLM commonly for the books; depreciation is neither a cash fund nor a market-value write-down.

**Related:** [[13-Long-Term-Assets-Acquisition-Disposal-Exchange]] · [[15-Depreciation-Delta-Singapore-Airlines]] · [[16-Revaluation-of-Fixed-Assets]] · [[Depreciation Slide]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
