---
tags:
  - fra
  - topic
  - balance-sheet
  - assets
  - session-1
  - session-5
course: Financial Reporting & Analysis
syllabus: Session 1 / Session 5
dg-publish: false
---

# 03 · The Balance Sheet — Assets

> [!info] What this note covers
> What an asset *is* · the current/non-current split and *why* it exists · every major asset line (PPE, CWIP, goodwill, intangibles, equity-method & financial investments, inventory, receivables, cash & equivalents) · depreciation vs the asset it sits under · the HUL asset side read in full. Equity & liabilities are in [[04-Balance-Sheet-Equity-and-Liabilities]].

---

## 1. What is an asset?

> [!note] Definition
> An **asset** is a **resource controlled** by the firm as a result of a **past event**, from which **future economic benefits** are expected to flow to the firm.

Three tests, all required:

1. **Future economic benefit** — it will generate cash or reduce future outflows (a machine makes goods to sell; a receivable will turn into cash).
2. **Control** — the firm can direct its use and obtain the benefit (legal ownership usually, but control is the real test — e.g. a leased asset).
3. **Past event** — the transaction that gave control has already happened (you can't record next year's planned purchase).

> [!tip] Asset vs expense — the line that recurs all course
> An **asset** is an *unexpired* cost — future benefit still to come. An **expense** is an *expired* cost — benefit already consumed. Prepaid insurance is an **asset** today; each month a slice *expires* into insurance **expense**. Keep this handy — it is tested directly (Quiz 1 Q5, Q14). See [[07-Conceptual-Framework-and-Core-Concepts#Matching Concept]].

> [!warning] Common exam trap — "common characteristic of all assets"
> The single defining feature is **future economic benefit** — *not* "long life" (current assets are short-lived) and *not* "tangible" (intangibles are assets too). Quiz 1 Q17 tests exactly this.

---

## 2. The current / non-current split (and why it exists)

Assets are ordered by **liquidity** and split into two buckets by the **operating cycle** (typically **one year**; use *one year or the operating cycle, whichever is longer*):

- **Non-current** — benefits expected **beyond one year / one operating cycle**. Relatively **illiquid** (not easily turned into cash).
- **Current** — expected to be **converted to cash, sold, or consumed within one year / one operating cycle**. These fund **day-to-day operations**.

> [!note] Operating cycle
> The **operating cycle** is the time from spending cash on inputs → to collecting cash from customers (cash → inventory → receivables → cash). For an FMCG firm it is short; for a shipbuilder it can exceed a year, which is why the definition allows "whichever is longer."

Why split at all? Because a reader needs to judge **liquidity** — can the firm meet its short-term obligations? Comparing **current assets to current liabilities** (working capital, see [[04-Balance-Sheet-Equity-and-Liabilities]]) only makes sense once assets are bucketed this way.

$$\text{Working Capital} = \text{Current Assets} - \text{Current Liabilities}$$

---

## 3. Non-current assets, line by line

### Property, Plant & Equipment (PPE)
Tangible, long-lived operating assets: land, buildings, plant, machinery, furniture, vehicles. Recorded at **cost** (purchase price **plus** everything needed to make it ready for use — freight, installation, etc.), then **depreciated** over its useful life (§7 below). Shown at **net block**.

### Capital Work-in-Progress (CWIP)
Long-term assets **still under construction** — not yet ready for use, so **not yet depreciated**. When complete, CWIP is transferred into **PPE** and depreciation begins.

### Goodwill
> [!note] Definition
> **Goodwill** is the premium paid to acquire another business — the excess of the purchase price over the **fair value of the identifiable net assets** acquired.
> $$\text{Goodwill} = \text{Purchase price} - \text{Fair value of identifiable net assets acquired}$$

It represents things you paid for but can't put a separate label on: brand reputation, customer relationships, workforce, synergies.

> [!warning] Only *acquired* (purchased) goodwill is recorded
> **Internally generated / self-assessed goodwill is never recorded** (historical-cost + reliability). If a buyer offers ₹33,000 for a business whose equity is ₹26,970, the implied ₹6,030 of "goodwill" stays **off the books** unless and until an actual acquisition transaction happens. (This is the Music Mart no-effect event — see [[08-The-Accounting-Equation]].)

### Other intangible assets
Non-physical resources with legal or economic rights: **patents, copyrights, trademarks, licences, brands** (e.g. buying out a brand or a channel). Amortised over their useful life (§7).

> [!note] Tangible vs intangible
> **Tangible** = physical (land, machinery, inventory). **Intangible** = non-physical rights (patents, brands, goodwill). Both are assets — the test is *future benefit*, not physical form. **Quiz 1 Q10** ("long-term assets without physical existence but with certain rights") → **intangible assets.**

### Investments — the ownership ladder
How one company's stake in another is accounted depends on the **degree of influence**:

| Holding    | Relationship                          | Accounting treatment                                                                                                                               |
| ---------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| **> 50%**  | **Subsidiary** (control)              | **Full consolidation** — add line-by-line; creates goodwill & [[04-Balance-Sheet-Equity-and-Liabilities#6. Non-Controlling Interest (NCI) \| NCI]] |
| **20–50%** | **Associate** (significant influence) | **Equity method**                                                                                                                                  |
| **< 20%**  | Plain investment                      | Held as a financial asset (fair value / cost)                                                                                                      |

#### Equity-method investments
Used for **significant influence but not control** (≈20–50%), e.g. joint ventures. Recorded initially **at cost**, then adjusted each period for the investor's **proportionate share of the investee's profit or loss** (and reduced by dividends received).

> [!example] HUL FY26
> "Investments accounted for using the equity method" fell from **57 → 0**, and the P&L carries a **"Share of loss of equity-accounted investee (net of tax) −15."** That −15 is the equity method in action: HUL booked its share of the investee's loss. The line hit 0 after HUL disposed of the joint-venture stake (see the [[06-Cash-Flow-Statement|cash flow]]: "Profit on sale of stake in joint venture 256").

### Other financial assets
Contractual claims beyond plain shares/bonds: mutual funds, ETFs, derivatives, insurance contracts, bank deposits, **security deposits** (refundable later), receivables of a financial nature. Split into current/non-current by when they'll be realised.

### Deferred tax assets & non-current tax assets
Tax items expected to benefit future periods (deferred tax) or tax paid in advance/recoverable. Detail is beyond Session 5; recognise the line.

---

## 4. Current assets, line by line

### Inventories
Goods the firm will sell. A **manufacturer** holds **three** types flowing in sequence; a **retailer** holds one (**merchandise / stock-in-trade**):

```mermaid
flowchart LR
    RM[Raw Materials] --> WIP[Work-in-Progress] --> FG[Finished Goods] --> SALE[Sold → COGS]
```

Valued at the **lower of cost and net realisable value** (prudence). How inventory value flows into **COGS, gross margin and tax** is the classic linkage question — see [[05-Income-Statement-PandL#5. The "Changes in inventories" line — and the inventory → COGS → margin → tax chain]] and the worked example there.

### Trade receivables (debtors / accounts receivable)
Amounts owed by customers from **credit sales**. Reported at **net realisable value** = gross receivables − **provision for doubtful debts** (management's estimate of what won't be collected).

> [!note] Three names, one thing
> **Debtors = Trade receivables = Accounts receivable.** **Quiz 1 Q12** ("receives from a debtor") → the two accounts affected are **Cash ↑ and Debtors ↓** (an asset-for-asset swap; equity untouched).

### Cash and cash equivalents
- **Cash** — notes, coins, demand (current-account) deposits.
- **Cash equivalents** — short-term, highly liquid investments **convertible to a known amount of cash**, **maturity ≤ 3 months**, with **insignificant risk of value change** (e.g. treasury bills, some cheques).

> [!warning] What is *not* a cash equivalent
> **Gold is not** — its value is volatile (fails the "insignificant risk" test). Equity shares aren't either. The test is *known amount + short maturity + stable value*, not just "sellable quickly."

### Bank balances other than cash equivalents
Deposits with maturity **> 3 months** (so they fail the equivalent test) but still current — shown on their own line, as in HUL.

### Assets held for sale
Assets whose operational life is done and which the firm intends to **sell within a year**; carried separately from operating assets.

---

## 5. Depreciation, amortisation & depletion (the allocation idea)

A long-lived asset is **not** expensed when bought — its cost is **spread over the periods it benefits** (the [[07-Conceptual-Framework-and-Core-Concepts#Matching Concept|matching concept]]). The word changes with the asset type:

| Term | Applies to |
|---|---|
| **Depreciation** | Tangible fixed assets (buildings, machinery, vehicles) |
| **Amortisation** | Intangibles (patents, copyrights, goodwill, licences) |
| **Depletion** | Natural resources (oil & gas, minerals, timber) |

> [!warning] Land is not depreciated
> Land has a theoretically **unlimited useful life**, so it is *not* depreciated (though it can be impaired).

**Straight-line depreciation** (the standard method):
$$\text{Annual Depreciation} = \frac{\text{Cost} - \text{Estimated Residual (Salvage) Value}}{\text{Useful Life (years)}}$$

> [!note] Gross Block vs Net Block
> On any balance-sheet date, fixed assets are shown at **Net Block = Gross Block (original cost) − Accumulated Depreciation to date.** "Accumulated depreciation" is the running total charged since purchase; each year's charge also appears as an **expense** on the [[05-Income-Statement-PandL|P&L]].

> [!tip] Managerial discretion lives here (thrust 3)
> Depreciation depends on **estimated life**, **estimated residual value** and the **method chosen** — all management judgements. Two identical firms can report different profits purely through these choices. This is why depreciation is the headline example of *managerial choice* in the course.

> [!question] Quiz 1 Q15 — decrease in the value of intangible assets is…?
> **Amortisation.** (Depreciation → tangibles; depletion → natural resources.)

---

## 6. Applied example — HUL's asset side (FY26)

> [!example] Reading the HUL consolidated balance sheet (₹ cr)
> | | FY26 | FY25 |
> |---|---:|---:|
> | Non-current assets (A) | 60,731 | 57,829 |
> | Current assets (B) | 19,021 | 22,051 |
> | **Total assets** | **79,752** | **79,880** |
>
> **What the numbers tell you:**
> - **Intangible-heavy:** Goodwill (18,062) + Other intangibles (31,184) ≈ **62% of total assets**; PPE is only ~10%. FMCG built by **acquiring brands** is *asset-light in factories, asset-heavy in intangibles*.
> - **Cash collapsed 6,071 → 2,583:** not a business problem — the [[06-Cash-Flow-Statement|cash flow statement]] shows it went on **dividends, an acquisition, and the ice-cream demerger**.
> - **Receivables (3,379) are modest** vs trade payables (~13,325): HUL **collects fast, pays suppliers slowly** — suppliers finance its operations (negative cash-conversion cycle). Ties to [[04-Balance-Sheet-Equity-and-Liabilities]].
> - **Equity-method investment went to 0** — the JV stake was sold during the year.

---

## Common mistakes (Assets)

> [!warning] Gotchas
> - **"All assets are tangible / long-lived"** — false. The only universal is *future economic benefit*.
> - **Recording internally generated goodwill / writing land up to market** — never do it (historical cost; only *acquired* goodwill is booked). Music Mart events 7 & 10.
> - **Calling gold or shares a "cash equivalent"** — fails the stable-value / ≤3-month test.
> - **Depreciating land** — don't.
> - **Buying an asset for cash mistaken for an expense** — it's an **asset-for-asset swap** (Cash ↓, Asset ↑); *no* effect on profit or equity. Quiz 1 Q16, Q20.
> - **Prepaid item treated as expense when paid** — it's an **asset** until it expires (Quiz 1 Q5, Q8).

---

## Key takeaways

- Asset = **controlled resource, past event, future benefit** — that last part is the universal test.
- Split **current vs non-current** by the one-year/operating-cycle line to reveal **liquidity**.
- **Acquired goodwill only**; **land isn't depreciated**; **cash equivalents ≤ 3 months, stable value.**
- **Depreciation/amortisation/depletion** *allocate* cost over benefit — and are a prime site of **managerial discretion**.
- HUL shows a real, intangible-dominated, asset-light FMCG balance sheet.

---

**Related:** [[04-Balance-Sheet-Equity-and-Liabilities]] · [[05-Income-Statement-PandL]] · [[07-Conceptual-Framework-and-Core-Concepts]] · [[HUL Balance Sheet]] · [[90-Master-Formula-Sheet]]
