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
> The whole Quiz-3 fixed-asset block turns on **one decision made over and over**: when money moves near an asset, does it go *onto* the balance sheet (capitalise) or *through* the income statement (expense)? This note works the three moments where that decision gets examined — **buying, selling, and swapping** — with the professor's own traps.

[[FRA Session 11]] teaches all of this through the full **Stafford Press** story end-to-end; this note is the exam-compression, with the **Fun Quiz** items (Q1, Q2, Q6, Q7) worked. Read S11 once for the narrative, drill this before the quiz.

---

## 1. Acquisition — what goes into "cost"

The cost of an asset is its purchase price net of trade discount, plus **every cost needed to bring it to the location and condition where it can operate as intended** (Ind AS 16, paras 16–17). The instant it is *ready to use*, capitalising stops (para 20); anything spent after that is an expense. So into cost go delivery and freight, installation *wages*, site preparation, testing, non-refundable duties, professional fees, and borrowing cost incurred during construction (Ind AS 23) — everything that gets the asset working.

What stays out is the handful of things that only *feel* like they belong:

| Tempting to add | Why it's out |
|---|---|
| **General overhead / admin** | Head-office rent isn't part of a machine you happened to buy that month |
| **Your own profit margin** on self-built assets | You record what it *cost* you (wages), never what you'd *charge* a client — you can't profit off yourself |
| **Opportunity cost** of staff pulled off paying jobs | Real, but never gets an entry |
| **Fuel / consumables to run it** | A *running* cost, not a cost of getting it ready → expense |

The Stafford press purchase (T3) is where the professor plants the classic slips: a cash discount is not income, it just makes the asset cheaper; installation labour is valued at **wage cost** ($15/hr), never the **billing rate** ($30.50); and the revenue "lost" by pulling staff off paying jobs never gets an entry at all.

> [!example] Fun Quiz Q1 — the capitalisation trap
> Used tractor **$17,500**; before use: new tyres **$1,100**, overhaul **$1,400**, first tank of fuel **$750**. Life 6 yrs, residual $2,000. First-year SLM depreciation?
>> Cost = 17,500 + 1,100 + 1,400 = **$20,000**. **Fuel is excluded** — it runs the tractor, it doesn't make it *ready*.
>> Depreciation = (20,000 − 2,000) / 6 = **$3,000**.
>> The whole question is a disguised "which costs capitalise?" test. Add the fuel by mistake → $3,125, the wrong option.

Two sub-rules the professor keeps circling back to. *Land* is costed at whatever it takes to make the plot usable — purchase price, plus demolishing a **worthless** building on it, plus **permanent** improvements like drainage (Stafford T4). Had the demolished building been worth something, knocking it down would be a *loss* rather than part of land cost; and a *limited-life* improvement is a separate depreciable item, not part of the land, which is itself **never depreciated**. *Relocation* is the mirror-image trap (Stafford T7), and the professor's favourite: installing a **new** press is capitalised, but **relocating equipment that already works** is expensed — Ind AS 16 para 19 names "relocation costs" outright. Bolting a machine to a floor is the same physical act either way, but moving working kit only restores the status quo; it buys no *future* benefit.

---

## 2. Disposal — remove the asset at its GROSS value

On a sale you wipe out **both** the asset's original cost **and** all the accumulated depreciation piled against it, then compare the cash received to the net book value (Ind AS 16, para 68):

$$\text{Gain / (Loss)} = \text{Cash received} - \text{Net Book Value}$$

That gain or loss runs through the **P&L, but it is not "revenue"** — selling a machine isn't your business — and it is never an "extraordinary item," a category that no longer exists. The single most-tested point here is the **gross** credit: the asset leaves the books at its *original* cost, not its net book value, with accumulated depreciation debited separately. Miss that debit and the entry won't balance.

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

And when two assets are sold in two separate deals, their loss and gain show **separately** on the P&L — one on the expense side, one on the income side — never netted off against each other.

---

## 3. Exchange (trade-in) — record at what you GAVE UP

You record the new asset at the **fair value of what you handed over** (the old asset's fair value + cash), provided the exchange has commercial substance and that fair value is measurable. If not — no commercial substance, or fair value unreliable — you fall back to the **book value of the old asset + cash** and recognise no gain or loss (Ind AS 16, para 24).

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

The trap underneath all of this is the **trade-in allowance**: dealers pad it and quietly pad the new asset's price by the same amount, so recording the inflated allowance overstates the asset and hides a loss. Whenever fair value is ascertainable, use it and ignore the allowance; only with no fair value available do you fall back to the allowance as a proxy.

---

## Before the quiz

- **Capitalise** what makes an asset *ready for future benefit*; **expense** what merely runs or restores it — so fuel and running costs are out (Q1), and so is relocating, reinstalling or repairing equipment that already works.
- A cash discount lowers cost (it's not income); self-built assets carry **wage cost**, never billing rate or profit margin.
- **Land** absorbs demolition of a worthless building and permanent improvements into its cost — and is never depreciated.
- **Disposal:** credit the asset at **gross** cost, debit accumulated depreciation separately; gain/loss = cash − NBV, through P&L (not revenue), never netted across two deals. "Disposed on 1 April" forces part-year depreciation *only* if the question asks for it.
- **Exchange:** dissimilar → **FV + cash** (gain/loss recognised); similar → **BV + cash** with the gain deferred, but a **loss is still booked** (FV + cash) when FV < BV. Trade-in allowance is only a last-resort proxy for FV.

**Related:** [[FRA Session 11]] · [[14-Depreciation-Methods-and-Changes]] · [[16-Revaluation-of-Fixed-Assets]] · [[17-Impairment-of-Assets]] · [[90-Master-Formula-Sheet]] · [[95-Fun-Quiz-Session-14-Worked]]
