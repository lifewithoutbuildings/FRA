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

> [!important] The definition to write in the exam
> Depreciation is the **allocation of the depreciable amount** (cost − residual value) of an asset over its useful life, so that profit or loss is measured properly (matching). It is **not** valuation and **not** a source of cash.

---

## 1. The three methods

| Method | Assumption | Yearly depreciation |
|---|---|---|
| **Straight-line (SLM)** | Value used up by **passage of time** | $\dfrac{\text{Cost} - \text{Residual}}{\text{Useful life}}$ — same every year |
| **Written-down value (WDV) / reducing balance** | Value used up **faster early** | Rate × *opening book value* each year |
| **Production-unit** | Value used up by **use**, not time | Unit rate × output; unit rate = $\dfrac{\text{Cost} - \text{Residual}}{\text{Total estimated output}}$ |

> [!important] The WDV rate formula (Day 2 takeaway)
> $$r = 1 - \left(\frac{R}{C}\right)^{1/n}$$
> where **R** = residual value, **C** = cost, **n** = life in years. This rate is applied to the **opening book value** each year, so the charge falls over time.
>
> **For tax purposes in India, only WDV is allowed.** (SLM is common for the published accounts.)

### Worked schedules — the bus (Cost ₹8,00,000, residual ₹80,000, life 6 yrs)

**SLM** — depreciable ₹7,20,000 ÷ 6 = **₹1,20,000/yr**, flat.

**WDV** — rate = 1 − (80,000/8,00,000)^(1/6) = 1 − 0.6813 = **0.3187 (31.87%)**, applied to opening book value:

| Year | Opening BV | Dep @ 31.87% | Closing BV |
|---|---:|---:|---:|
| 1 | 8,00,000 | 2,54,960 | 5,45,040 |
| 2 | 5,45,040 | 1,73,705 | 3,71,335 |
| 3 | 3,71,335 | 1,18,345 | 2,52,990 |
| 6 | … | 37,428 | 80,000 |

**Production-unit** — unit rate = 7,20,000 ÷ 2,00,000 km = **₹3.60/km**; charge = 3.60 × km run that year (e.g. 70,000 km → ₹2,52,000).

> [!tip] Which method gives more depreciation *early*?
> **WDV front-loads** (₹2,54,960 vs SLM's ₹1,20,000 in year 1). Over the whole life all three write off the *same total* (cost − residual); they only differ in **timing**. Higher early depreciation → lower early profit → lower early tax.

---

## 2. Part-year depreciation

> [!important] Pro-rate to the months in use
> $$\text{Depreciation} = \text{Annual charge} \times \frac{\text{Months in use}}{12}$$

> [!example] Fun Quiz Q4 — part-year
> Machine bought **1 July**, cost ₹34,000, life 5 yrs, residual ₹2,000. Year ends **31 March** → **9 months** in use.
>> Annual = (34,000 − 2,000)/5 = 6,400. Part-year = 6,400 × 9/12 = **₹4,800**.
>> The trap: an Indian fiscal year ends 31 March, so July→March is **9 months (0.75)**, not a full year.

---

## 3. Change in ESTIMATE — always prospective (Ind AS 8)

> [!important] The rule
> When new information says your **residual value, useful life, or (Ind AS view) method** guess was wrong, **don't rewrite past years.** Spread the *remaining* book value (less revised residual) over the *remaining* revised life. **No entry on the day the estimate changes** — it only shows up in future depreciation.

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

> [!important] SLM → WDV (the past-Quiz-3 Q1 pattern)
> A change of method is treated as a **change in estimate** → **prospective**. Take the **carrying amount at the date of change** and apply the new method over the **remaining life**. Do **not** recompute earlier years.

> [!warning] The WDV-rate trap when switching mid-life
> When you switch to WDV partway through, the rate is derived from the **carrying amount and remaining life**, *not* from original cost and original life.
> $$r = 1 - \left(\frac{\text{Revised residual}}{\text{Carrying amount now}}\right)^{1/\text{remaining life}}$$

> [!example] "Asif" — SLM → WDV at start of year 4 (S13 exercise, rate verified)
> Car ₹5,00,000, residual ₹50,000, life 6 yrs, SLM. After 3 yrs switch to WDV.
>> SLM dep = (5,00,000 − 50,000)/6 = 75,000/yr → accumulated 2,25,000 → carrying **₹2,75,000**. Remaining life 3 yrs.
>> WDV rate = 1 − (50,000/2,75,000)^(1/3) = **0.4335 (43.35%)** — *from carrying amount, remaining life*, **not** 1 − (50,000/5,00,000)^(1/6) = 31.87%.
>> Year-4 dep = 2,75,000 × 43.35% = **₹1,19,213**.
>> **If you'd used 31.87% you'd be wrong** — that's the whole trap.

---

## Traps

> [!warning]
> - **Full-year depreciation for a part-year** (Q4) — pro-rate; Indian FY ends 31 March.
> - **Rewriting past years** when an estimate/method changes — prospective only, no back-entry.
> - **WDV rate off original cost/life** when switching mid-life — use **carrying amount & remaining life** (Asif: 43.35%, not 31.87%).
> - **Booking an entry on the day an estimate changes** — there is none.
> - **Forgetting India uses WDV for tax**, SLM common for books.
> - **Thinking depreciation is a cash fund or a market-value write-down** — it is neither.

## Key takeaways

- Depreciable amount = **cost − residual**; SLM flat, WDV front-loaded, units by output; all write off the same total.
- WDV rate off *cost*: $1-(R/C)^{1/n}$; WDV rate when *switching* mid-life: off *carrying amount & remaining life*.
- Part-year = annual × months/12.
- Change in estimate **or** method → **prospective**: remaining BV over remaining life.

**Related:** [[13-Long-Term-Assets-Acquisition-Disposal-Exchange]] · [[15-Depreciation-Delta-Singapore-Airlines]] · [[16-Revaluation-of-Fixed-Assets]] · [[Depreciation Slide]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
