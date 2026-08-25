---
title: 13 · Long-Term Assets — Acquisition, Disposal & Exchange
course: Financial Reporting & Analysis
tags:
  - fra
  - mba
  - long-term-assets
  - ppe
  - ind-as
  - quiz-3
standards:
  - Ind AS 16
running-case: Stafford Press
status: reviewed
dg-publish: false
---

← [[00-Course-Map|Course Map]] | [[FRA Session 11]] (full Stafford narrative) | [[14-Depreciation-Methods-and-Changes]] →

> [!abstract] In one line
> The whole Quiz-3 fixed-asset block turns on **one decision made over and over**: when money moves near an asset, does it go *onto* the balance sheet (capitalise) or *through* the income statement (expense)? This note nails the three moments where that decision is examined — **buying, selling, and swapping** — as fast MCQ-ready rules with the professor's own traps.

> [!info] How this note relates to Session 11
> [[FRA Session 11]] teaches this through the full **Stafford Press** story end-to-end. This note is the **exam-compression** of it: the rules stripped to what a quiz question tests, plus the **Fun Quiz** items (Q1, Q2, Q6, Q7) worked. Read S11 once for the narrative; drill this before the quiz.

---

## 1. Acquisition — what goes into "cost"

> [!important] The rule (Ind AS 16, paras 16–17)
> **Cost = purchase price (net of trade discount) + every cost needed to bring the asset to the location and condition where it can operate as intended.** The moment it is *ready to use*, capitalising stops (para 20). Anything after that is an expense.

**Capitalise (in):** purchase price − cash/trade discount · delivery/freight · installation *wages* · site preparation · testing · non-refundable duties · professional fees · borrowing cost during construction (Ind AS 23).

**Expense (out):** the three the professor keeps flagging —
| Tempting to add | Why it's out |
|---|---|
| **General overhead / admin** | Head-office rent isn't part of a machine you happened to buy that month |
| **Your own profit margin** on self-built assets | You record what it *cost* you (wages), never what you'd *charge* a client — you can't profit off yourself |
| **Opportunity cost** of staff pulled off paying jobs | Real, but never gets an entry |
| **Fuel / consumables to run it** | A *running* cost, not a cost of getting it ready → expense |

> [!example] Fun Quiz Q1 — the capitalisation trap
> Used tractor **$17,500**; before use: new tyres **$1,100**, overhaul **$1,400**, first tank of fuel **$750**. Life 6 yrs, residual $2,000. First-year SLM depreciation?
>> Cost = 17,500 + 1,100 + 1,400 = **$20,000**. **Fuel is excluded** — it runs the tractor, it doesn't make it *ready*.
>> Depreciation = (20,000 − 2,000) / 6 = **$3,000**.
>> The whole question is a disguised "which costs capitalise?" test. Add the fuel by mistake → $3,125, the wrong option.

> [!warning] The three classic acquisition slips (from Stafford T3)
> - Treating a **cash discount as income** — it just makes the asset *cheaper* (lower cost).
> - Valuing installation labour at the **billing rate** ($30.50) instead of **wage cost** ($15).
> - Trying to book the **revenue "lost"** by not doing paying jobs — no entry, ever.

Two sub-rules the professor keeps circling back to. *Land* is costed at whatever it takes to make the plot usable — purchase price, plus demolishing a **worthless** building on it, plus **permanent** improvements like drainage (Stafford T4). Had the demolished building been worth something, knocking it down would be a *loss* rather than part of land cost; and a *limited-life* improvement is a separate depreciable item, not part of the land, which is itself **never depreciated**. *Relocation* is the mirror-image trap (Stafford T7), and the professor's favourite: installing a **new** press is capitalised, but **relocating equipment that already works** is expensed — Ind AS 16 para 19 names "relocation costs" outright. Bolting a machine to a floor is the same physical act either way, but moving working kit only restores the status quo; it buys no *future* benefit.

---

## 2. Disposal — remove the asset at its GROSS value

> [!important] The core mechanic (Ind AS 16, para 68)
> On sale, wipe out **both** the original cost **and** all accumulated depreciation. Compare cash received to **net book value**.
> $$\text{Gain / (Loss)} = \text{Cash received} - \text{Net Book Value}$$
> The gain/loss goes through the **P&L — but it is not "revenue"** (selling a machine isn't your business). Never label it "extraordinary" — that category is abolished.

> [!warning] The single most-repeated exam point
> The asset is credited at its **GROSS (original) value**, not net book value — because the entire asset *and* its accumulated depreciation must both leave the books. Miss the accumulated-depreciation debit and the entry won't balance.

**Template (loss case — Day 1 takeaway):**
```
Dr  Cash                              90,000
Dr  Accumulated Depreciation          80,000
Dr  Loss on sale of equipment         30,000
        Cr  Equipment (gross)                 2,00,000
```

> [!example] Fun Quiz Q2 — disposal
> Equipment cost **$64,800**, accumulated depreciation **$36,000**, sold **$12,000**.
>> NBV = 64,800 − 36,000 = **$28,800**. Cash 12,000 < NBV → **loss $16,800**.
>> ```
>> Dr Cash 12,000 / Dr Accum. Dep 36,000 / Dr Loss 16,800  →  Cr Equipment 64,800
>> ```
>> *("Disposed of on 1 April" is a distractor — no part-year depreciation is asked for. If a question does ask, charge depreciation up to the disposal date first, then compute the gain/loss.)*

> [!warning] Don't net a gain against a loss
> Two assets sold in two deals → one loss (expense side) and one gain (income side) shown **separately** on the P&L, never offset.

---

## 3. Exchange (trade-in) — record at what you GAVE UP

> [!important] The rule (Ind AS 16, para 24) — and the professor's version
> Record the new asset at the **fair value of what you handed over** (old asset's FV + cash), *provided the exchange has commercial substance* and FV is measurable. If not — no commercial substance, or FV unreliable — fall back to the **book value of the old asset + cash**, with **no gain or loss**.

The professor runs this off **similar vs dissimilar** assets, which is the older (APB 29 / pre-2016 AS 10) framing — Ind AS 16 itself keys off **commercial substance** (do the asset's cash flows really change?), not literal similarity. And the "similar → no gain/loss" shorthand hides one catch: on a *similar* swap you **defer a gain but still book a loss**. So if the old asset's fair value has slipped *below* its book value, you record at **FV + cash and recognise the loss now**, even for a similar asset — which is exactly what Stafford does with the composing machine (T5): FV ₹6,050 < BV ₹6,800, so it lands at FV + cash with a ₹750 loss booked, not BV + cash.

> [!important] The decision that separates Q6 from Q7
> | Situation | Value new asset at | Gain / loss | Example |
> |---|---|---|---|
> | **Dissimilar** (commercial substance) | **FV of old + cash** | both recognised | **Q7** → 2,20,000 + 1,70,000 = **₹3,90,000** (₹20,000 gain) |
> | **Similar**, FV ≥ BV (a gain) | **BV of old + cash** | gain **deferred** | **Q6** → 2,00,000 + 1,70,000 = **₹3,70,000** |
> | **Similar**, FV < BV (a loss) | **FV of old + cash** | loss **recognised now** | Stafford T5 → 6,050 + 20,830 = **₹26,880**, ₹750 loss |

> [!example] Fun Quiz Q6 vs Q7 — same numbers, different answer
> Old vehicle: BV ₹2,00,000, FV ₹2,20,000; cash paid ₹1,70,000; invoice price ₹4,00,000.
>> **Q6 — vehicle for a vehicle (similar):** no commercial substance → BV + cash = 2,00,000 + 1,70,000 = **₹3,70,000**. Fair value is *ignored*; no gain/loss.
>> **Q7 — vehicle for a machine (dissimilar):** commercial substance → FV + cash = 2,20,000 + 1,70,000 = **₹3,90,000**. The ₹20,000 excess of FV over BV is a **gain** recognised now.
>> **Q7 journal entry:**
>> ```
>> Dr  Machine (new)               3,90,000
>> Dr  Accumulated Dep — Vehicle      (to clear old asset)
>>         Cr  Vehicle (gross, old)
>>         Cr  Cash                    1,70,000
>>         Cr  Gain on exchange           20,000
>> ```
>> *(The invoice price ₹4,00,000 is a distractor — you never record at the sticker price.)*

> [!warning] Trade-in allowance ≠ fair value (Day 2 takeaway)
> Dealers **pad the trade-in allowance** and quietly pad the new asset's price by the same amount. If fair value is **ascertainable, use it and ignore the allowance.** Only if no FV is available do you fall back to the trade-in allowance as a proxy. Recording the inflated allowance overstates the asset and hides a loss.

---

## Traps (memorise before the quiz)

> [!warning]
> - **Fuel / running costs added to asset cost** → they're expensed (Q1).
> - **Crediting the asset at net book value** on disposal → must be **gross**; debit accumulated depreciation separately.
> - **"Disposed on 1 April" ⇒ automatically pro-rate** → only if the question asks for depreciation to date.
> - **Forgetting a *similar* swap still books a loss** — defer the gain (BV + cash), but if FV < BV record at FV + cash and take the loss now (Stafford T5).
> - **Using book value for a *dissimilar* swap** → dissimilar = **fair value + cash**, gain/loss recognised (Q7).
> - **Recording a trade-in at the dealer's allowance** when FV is known.
> - **Capitalising relocation / reinstallation / repairs** of an already-working asset.

## Key takeaways

- **Capitalise** what makes an asset *ready for future benefit*; **expense** what merely runs or restores it.
- Disposal: remove **gross cost + accumulated depreciation**; gain/loss = cash − NBV, shown in P&L (not revenue).
- Exchange: **dissimilar → FV + cash** (gain/loss recognised); **similar → BV + cash** with the gain deferred — but a **loss is still booked** (FV + cash) when FV < BV. Trade-in allowance is only a last-resort proxy for FV.

**Related:** [[FRA Session 11]] · [[14-Depreciation-Methods-and-Changes]] · [[16-Revaluation-of-Fixed-Assets]] · [[17-Impairment-of-Assets]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
