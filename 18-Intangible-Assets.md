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

Built from [[FRA Session 11#7. Intangible Assets|S11 §7]], the **Fun Quiz** (Q8 brand, Q9 software), the reading *"Intangible Assets: A Search for Right Accounting"* (Bhattacharyya, *Business Standard*, 2012), and the professor's intangibles reference table.

---

## 1. The intuition — why two different rules?

The whole topic comes from one duality, and once you have it the rest follows. An **acquired** intangible — one you bought outright or picked up in a business combination — goes **onto the balance sheet**, because an arm's-length transaction fixed a **verifiable price**. An **internally generated** intangible — your own brand, customer list, or goodwill — mostly does **not**, because any value you'd assign is self-assessed and easy to inflate. Software is the practical exception, but only because its *development-phase* costs pass the ordinary capitalise test (below), not because home-grown software is waved onto the books wholesale.

Why does the split matter? Because it **breaks comparability**. Two firms with identical economics can look completely different — the one that *bought* its brand shows an asset, the one that *built* the same brand shows nothing but a trail of expenses. So analysts **restructure**: they treat brand and R&D spend as an *"expensed investment,"* capitalise and amortise it over an assumed life, and restate goodwill at cost, purely to make ROI comparable across an industry. The evidence is that the capital market prices the economics correctly *as long as it understands the policy* — the accounting label doesn't change value, only the reported ratios.

The reading's deeper point makes a good "discuss" line for the exam: we cheerfully apply complex, costly, judgemental rules (value-in-use, fair-value-less-costs-to-sell) to *acquired* intangibles while flatly **refusing to recognise** the *internally generated* ones that are often a firm's most valuable assets. The "right" accounting is genuinely unsettled; the pragmatic answer the profession has settled on is **simple rules plus enough disclosure for analysts to make their own adjustments.**

---

## 2. The rules that matter (Ind AS 38 / AS 26)

Recognition follows straight from the duality. A **purchased** intangible — patent, licence, brand, franchise — is **capitalised at cost**. An **internally generated** brand, customer list, masthead or **goodwill cannot** be capitalised at all (paras 48, 63); **software** is the one that runs through the research/development test instead, so its *development* costs can be capitalised (as in Q9). And that test is the general rule for any in-house project: **research**-phase spend is **always expensed** (too speculative), while **development**-phase spend is **capitalised only** once the project is technically feasible and saleable (paras 54, 57).

Amortisation is where Indian AS and IFRS visibly part company — a live exam contrast:

| | **Indian AS** (AS 26 / AS 14) | **IFRS / Ind AS** |
|---|---|---|
| **Goodwill** | amortise over **≤ 5 years** | **not amortised**; annual **impairment** test |
| **Other intangibles** | amortise over **≤ 10 years** unless a longer life is justified | **finite life** → amortise over useful life; **indefinite life** → not amortised, impairment-tested annually |
| **"Indefinite life"** | (not a category) | when management **cannot** estimate a useful life (e.g. goodwill, some brands) |

For a computation, the rule is simply: amortise a finite-life intangible over its **useful life, or its legal life if shorter** — whichever is less. IFRS is the "theoretically superior" framework (it matches the economics) but leans on judgemental estimates; Indian AS is cruder but simpler.

---

## 3. The reference table (from the handout) — legal vs useful life

| Intangible | Legal life | How to account |
|---|---|---|
| **Patent** | 20 years (monopoly to make/use/sell an invention) | Cost of acquisition; if from in-house research, capitalise **development** costs; amortise over **useful life if shorter than legal life** |
| **Copyright** | Author's life + 60 years | Cost of acquisition; amortise over **useful life if shorter than legal life** |
| **Trademark / Brand** | 10 years, **renewable indefinitely** | Cost of acquisition; amortise over useful life; **do not recognise internally generated brands** |
| **Franchise / Licence** | Term of the contract | Record the lump-sum payment; amortise over the **franchise/licence period** |
| **Goodwill** | — (excess of purchase price over FV of net assets) | Record **purchased** goodwill at cost; Indian AS amortise over ≤5 yrs / IFRS impairment-only; **never recognise internal goodwill** |

The recurring computational move is "legal life is X, useful life is Y (< X) → amortise over **Y**." Two assets buck it: a **trademark**'s legal life is indefinitely renewable, so **useful life always governs**; a **franchise** goes the other way — amortise over the **contract term**, even if you expect to trade longer.

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

Goodwill earns no cash by itself, so it can't be impairment-tested alone — it's tested inside a **Cash Generating Unit (CGU)**, the smallest group of assets that generates cash independently (typically the division the goodwill was allocated to). You compare the CGU's **recoverable amount** — the higher of value-in-use and fair value less costs to sell — with the aggregate book value of everything in it: if recoverable is at least book value there's no impairment, and if it's below, the loss is allocated in a **strict order** — **goodwill written down first**, and only any excess beyond goodwill spread pro-rata across the other assets (other intangibles included). Goodwill impairment is **never reversed**, even under Ind AS.

> [!example] CGU allocation
> A division: goodwill ₹8 lacs, other assets ₹40 lacs (book values); recoverable amount ₹42 lacs. Impairment and its allocation?
>> Aggregate book = 48; recoverable 42 → impairment **₹6 lacs**. It's **≤ goodwill (8)**, so **all ₹6 lacs reduces goodwill** (→ goodwill 2 lacs); other assets untouched.
>> *If* recoverable were ₹36 lacs → impairment 12 > goodwill 8: write goodwill to **0**, then allocate the remaining **₹4 lacs** across the other assets pro-rata.

---

## Before the quiz

- **Duality:** acquired → recognised (a verifiable price fixed it); internally generated brand/goodwill → not (software is the exception, via the development-cost test). This is what breaks comparability, so analysts restructure with an "expensed investment" adjustment.
- **Research expensed, development capitalised** (only when feasible and saleable); never capitalise internal brand-building, customer lists, or internal goodwill.
- Amortise a finite-life intangible over its **useful life or legal life, whichever is shorter** — but a **trademark** is governed by useful life (legal life is renewable) and a **franchise** by its contract term.
- **AS vs IFRS on goodwill:** AS amortises over ≤5 yrs, IFRS/Ind AS doesn't amortise at all (annual impairment) — always check which framework the question is in. Other intangibles: AS ≤10 yrs unless justified; IFRS amortises finite lives, impairs indefinite ones.
- Key answers: **Q8** brand = ₹50 lakhs; **Q9** software = $1,40,000. **Goodwill impairment** is tested at the **CGU** level, written off **first**, and **never reversed**.

**Related:** [[FRA Session 11]] · [[03-Balance-Sheet-Assets]] · [[17-Impairment-of-Assets]] · [[95-Fun-Quiz-Session-14-Worked]] · [[90-Master-Formula-Sheet]]
