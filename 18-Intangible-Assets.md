---
title: 18 · Intangible Assets
course: Financial Reporting & Analysis
tags:
  - fra
  - mba
  - intangibles
  - ind-as
  - quiz-3
standards:
  - Ind AS 38
  - AS 26
  - IFRS
running-case: Brand (Q8) · Software (Q9)
status: reviewed
dg-publish: false
---

← [[17-Impairment-of-Assets]] | [[00-Course-Map|Course Map]] →

> [!abstract] In one line
> Intangibles ask the same question as any asset — *does it buy future benefit?* — but because they're **invisible and easy to fake**, accounting splits into **two rules**: an asset you **buy** goes on the books; one you **grow yourself** (brand, goodwill) mostly does not. That split is the whole topic, and the source of every trap.

> [!info] Sources
> [[FRA Session 11#7. Intangible Assets|S11 §7]] + the **Fun Quiz** (Q8 brand, Q9 software) + the reading **"Intangible Assets: A Search for Right Accounting"** (Bhattacharyya, *Business Standard*, 2012) and the professor's intangibles reference table.

---

## 1. The intuition — why two different rules?

> [!important] The duality (get this and the rest follows)
> - **Acquired** intangibles (bought, or picked up in a business combination) → **recognised** on the balance sheet, because there's a **verifiable price** — an arm's-length transaction fixed the number.
> - **Internally generated** intangibles (your own brand, customer list, goodwill) → **not recognised**, because any value you'd put on them is **self-assessed and easy to inflate**. **Software is the practical exception** — but only because its *development-phase* costs pass the normal capitalise test (below), not because internally generated software is waved onto the books wholesale.
>
> **Why it matters (the analyst's problem):** this duality **breaks comparability**. Two firms with identical economics look different — the one that *bought* its brand shows an asset; the one that *built* its brand shows nothing but a trail of expenses. So analysts **restructure**: they treat brand/R&D spend as an *"expensed investment,"* capitalise and amortise it over an assumed life, and restate goodwill at cost — purely to make **ROI comparable** across the industry. Research shows the capital market prices the economics correctly *as long as it understands the policy* — the accounting label doesn't change value, but it does change the reported ratios.

> [!note] The deeper point the reading makes
> We happily apply **complex, costly, judgemental** rules (value-in-use, fair-value-less-costs-to-sell) to *acquired* intangibles, while **refusing to recognise** the *internally generated* ones that are often a firm's most valuable assets. The "right" accounting is unsettled; the pragmatic answer is **simple rules + enough disclosure for analysts to make their own adjustments.** (Good exam "discuss" point.)

---

## 2. The rules that matter (Ind AS 38 / AS 26)

> [!important] Recognition
> - **Purchased** intangible (patent, licence, brand, franchise) → **capitalise** at cost.
> - **Internally generated** brand, customer list, masthead, **goodwill** → **cannot** be capitalised (paras 48, 63). **Software** is treated under the research/development rule below — its *development* costs *can* be capitalised (as in Q9).
> - **Research** phase → **always expensed** (too speculative). **Development** phase → **capitalise** *only* once technically feasible and saleable (paras 54, 57).

> [!important] Amortisation — Indian AS vs IFRS (a live exam contrast)
> | | **Indian AS** (AS 26 / AS 14) | **IFRS / Ind AS** |
> |---|---|---|
> | **Goodwill** | amortise over **≤ 5 years** | **not amortised**; annual **impairment** test |
> | **Other intangibles** | amortise over **≤ 10 years** unless a longer life is justified | **finite life** → amortise over useful life; **indefinite life** → not amortised, impairment-tested annually |
> | **"Indefinite life"** | (not a category) | when management **cannot** estimate a useful life (e.g. goodwill, some brands) |
>
> **The rule you apply to a computation:** amortise a finite-life intangible over its **useful life, or its legal life if shorter** — whichever is less. IFRS is "theoretically superior" (matches economics) but its estimates are judgemental; Indian AS is cruder but simpler.

---

## 3. The reference table (from the handout) — legal vs useful life

| Intangible | Legal life | How to account |
|---|---|---|
| **Patent** | 20 years (monopoly to make/use/sell an invention) | Cost of acquisition; if from in-house research, capitalise **development** costs; amortise over **useful life if shorter than legal life** |
| **Copyright** | Author's life + 60 years | Cost of acquisition; amortise over **useful life if shorter than legal life** |
| **Trademark / Brand** | 10 years, **renewable indefinitely** | Cost of acquisition; amortise over useful life; **do not recognise internally generated brands** |
| **Franchise / Licence** | Term of the contract | Record the lump-sum payment; amortise over the **franchise/licence period** |
| **Goodwill** | — (excess of purchase price over FV of net assets) | Record **purchased** goodwill at cost; Indian AS amortise over ≤5 yrs / IFRS impairment-only; **never recognise internal goodwill** |

> [!tip] The recurring computational move
> "Legal life is X, useful life is Y (< X) → amortise over **Y**." A trademark is the odd one out — its legal life is *indefinitely renewable*, so **useful life always governs**. Franchises are the other way: amortise over the **contract term**, even if you think you'd use it longer.

---

## 4. Worked questions

> [!example] Fun Quiz Q8 — purchased brand + internal spend to "strengthen" it
> XYZ bought a brand from ABC for **₹50 lakhs**, then spent **₹10 lakhs** to strengthen it. Carrying amount (ignore amortisation)?
>> **Purchased ₹50 lakhs → capitalise.** The ₹10 lakhs is **internally generated brand enhancement → expensed** (para 63). **Carrying amount = ₹50 lakhs.**
>> Trap: adding the ₹10 lakhs (→ ₹60 lakhs). You capitalise a brand you **buy**, never the spend to build/boost it yourself.

> [!example] Fun Quiz Q9 — research vs development, then amortise over useful life
> Software: research **$2,50,000**, development **$1,75,000**, copyright life 40 yrs, viability **5 yrs**. Balance-sheet value after 1 year?
>> **Research $2,50,000 → expensed.** **Development $1,75,000 → capitalised.** Amortise over **useful life 5 yrs** (not 40): 1,75,000/5 = 35,000. Carrying = 1,75,000 − 35,000 = **$1,40,000.**
>> Two traps: capitalising research, and amortising over the 40-yr legal life.

> [!example] Patent — legal 20, useful 8
> A patent is bought for ₹16,00,000; management expects it useful for **8 years** though the legal life is 20. Annual amortisation? Carrying amount after 3 years?
>> Amortise over the **shorter** = 8 yrs → 16,00,000/8 = **₹2,00,000/yr**. After 3 yrs: 16,00,000 − 6,00,000 = **₹10,00,000.**

> [!example] Franchise — over the contract term
> A 6-year franchise costs ₹30,00,000. Annual amortisation?
>> Over the **franchise period** = 6 yrs → **₹5,00,000/yr** (regardless of how long you *hope* to trade).

> [!example] Goodwill — AS vs IFRS on the same facts
> Firm buys a business; purchased goodwill = ₹50,00,000. Amortisation in year 1?
>> **Indian AS:** amortise over ≤5 yrs → e.g. 5 yrs = **₹10,00,000/yr.**
>> **IFRS / Ind AS:** **no amortisation** → ₹0; instead test for impairment annually. Same goodwill, opposite P&L — a clean "contrast the frameworks" answer.

---

## 5. Goodwill impairment lives at the CGU level

> [!important] Why goodwill can't be tested alone — and the write-off order
> Goodwill generates no cash by itself, so it's tested inside a **Cash Generating Unit (CGU)** — the smallest group of assets that earns cash independently (e.g. a division the goodwill was allocated to).
> - Compute the CGU's **recoverable amount** = higher of **VIU** and **fair value less costs to sell**.
> - If recoverable ≥ aggregate book value → **no impairment**.
> - If recoverable < book value → impairment loss, allocated in a **strict order**: **write down goodwill FIRST**; only if the loss exceeds goodwill is the **remainder spread across the other assets** (including other intangibles), pro-rata.
> - **Goodwill impairment is never reversed** (even under Ind AS).

> [!example] CGU allocation
> A division: goodwill ₹8 lacs, other assets ₹40 lacs (book values); recoverable amount ₹42 lacs. Impairment and its allocation?
>> Aggregate book = 48; recoverable 42 → impairment **₹6 lacs**. It's **≤ goodwill (8)**, so **all ₹6 lacs reduces goodwill** (→ goodwill 2 lacs); other assets untouched.
>> *If* recoverable were ₹36 lacs → impairment 12 > goodwill 8: write goodwill to **0**, then allocate the remaining **₹4 lacs** across the other assets pro-rata.

---

## Traps

> [!warning]
> - **Capitalising internal brand-building / customer lists / internal goodwill** — expensed; only *purchased* intangibles go on the books (software follows the research/development rule).
> - **Capitalising research** — always expensed; only *development* (feasible + saleable) is capitalised.
> - **Amortising over the legal/copyright life** when useful life is shorter — use the **shorter**. (Trademark: useful life always governs; franchise: contract term governs.)
> - **Amortising goodwill under IFRS** — it isn't (Indian AS ≤5 yrs; IFRS impairment-only). Know **which framework** the question uses.
> - **Testing goodwill on its own** — it's tested at the **CGU** level, and impairment hits **goodwill first**, never reversed.

## Key takeaways

- **Duality:** acquired → recognised (verifiable price); internally generated brand/goodwill → not (except software). This breaks comparability, so analysts restructure ("expensed investment").
- Research **expensed**, development **capitalised**; amortise finite-life intangibles over **useful life or legal life, whichever is shorter**.
- **AS vs IFRS:** goodwill — AS amortise ≤5 yrs, IFRS impairment-only; other intangibles — AS ≤10 yrs unless justified, IFRS finite-amortise / indefinite-impair.
- **Q8:** brand = **₹50 lakhs**; **Q9:** software = **$1,40,000**.
- **Goodwill impairment** at the **CGU** level, written off **first**, **never reversed**.

**Related:** [[FRA Session 11]] · [[03-Balance-Sheet-Assets]] · [[17-Impairment-of-Assets]] · [[95-Fun-Quiz-Session-14-Worked]] · [[90-Master-Formula-Sheet]]
