---
tags:
  - fra
  - exam-prep
  - formula-sheet
course: Financial Reporting & Analysis
dg-publish: false
---

# 90 · Master Formula Sheet

> [!info] How to use
> Every formula in the course, grouped by topic, with **each variable defined**. Links point to the topic note where the formula is derived and worked. Skim this the night before; drill the worked versions in [[91-Exam-Question-Bank]].

---

## A · The Accounting Equation → [[08-The-Accounting-Equation]]

**Basic:**
$$\text{Assets} = \text{Liabilities} + \text{Equity}$$
- **Assets** — resources controlled (uses of funds).
- **Liabilities** — outsiders' claims. **Equity** — owners' claim (sources of funds).

**Expanded:**
$$\text{Assets} = \text{Liabilities} + \text{Equity} + \text{Revenue} - \text{Expenses}$$

$$\text{Assets} = \text{Liabilities} + \text{Contributed Capital} + \text{Retained Earnings}$$

**Retained earnings roll-forward** (the P&L → balance-sheet bridge):
$$\text{Closing RE} = \text{Opening RE} + \text{Net Profit} - \text{Dividends}$$
- **Net Profit** = Revenue − Expenses. **Dividends** (or **drawings**) = amounts paid out to owners.

**Closing capital (proprietor):**
$$\text{Closing Capital} = \text{Opening Capital} + \text{Profit} - \text{Drawings} \; (+\,\text{fresh capital})$$

---

## B · Balance Sheet → [[03-Balance-Sheet-Assets]] · [[04-Balance-Sheet-Equity-and-Liabilities]]

$$\text{Equity (Net worth)} = \text{Total Assets} - \text{Total Liabilities} = \text{Equity Share Capital} + \text{Other Equity}$$

$$\text{Book Value per Share} = \frac{\text{Net worth}}{\text{No. of equity shares}}$$

$$\text{Equity Share Capital} = \text{Face Value} \times \text{No. of shares}$$
- **Face (nominal) value** — value printed on the share; only this hits the share-capital line.

$$\text{Issue Price} = \text{Face Value} + \text{Premium} \quad\Rightarrow\quad \text{Securities Premium (to Other Equity)} = \text{Premium} \times \text{No. of shares}$$

$$\text{Working Capital} = \text{Current Assets} - \text{Current Liabilities}$$

$$\text{Goodwill} = \text{Purchase Price} - \text{Fair Value of identifiable net assets acquired}$$
*(Acquired goodwill only; never internally generated — [[03-Balance-Sheet-Assets#Goodwill]].)*

$$\text{Net Realisable Value of Receivables} = \text{Gross Receivables} - \text{Provision for Doubtful Debts}$$

$$\text{NCI} = \text{Outsiders' \% ownership} \times \text{Subsidiary's net assets (equity)}$$

---

## C · Fixed Assets & Depreciation → [[03-Balance-Sheet-Assets#5. Depreciation, amortisation & depletion (the allocation idea)]]

**Straight-line depreciation (per year):**
$$\text{Annual Depreciation} = \frac{\text{Cost} - \text{Residual (Salvage) Value}}{\text{Useful Life (years)}}$$
- **Cost** — purchase price + costs to make ready for use. **Residual value** — expected proceeds at end of life. **Useful life** — years of expected service.

**Pro-rated for part of a year:**
$$\text{Depreciation} = \text{Annual Depreciation} \times \frac{\text{Months in use}}{12}$$

**Net Block (carrying value):**
$$\text{Net Block} = \text{Gross Block (original cost)} - \text{Accumulated Depreciation}$$

> Terms: **Depreciation** → tangibles; **Amortisation** → intangibles; **Depletion** → natural resources. Land is **not** depreciated.

---

## C2 · Quiz-3 Fixed Assets — Methods, Disposal, Revaluation, Impairment, Exchange
→ [[14-Depreciation-Methods-and-Changes]] · [[16-Revaluation-of-Fixed-Assets]] · [[17-Impairment-of-Assets]] · [[13-Long-Term-Assets-Acquisition-Disposal-Exchange]]

**WDV (reducing-balance) rate — from cost:**
$$r = 1 - \left(\frac{R}{C}\right)^{1/n} \qquad \text{charge}_t = r \times \text{opening book value}_t$$

**WDV rate when switching method mid-life** (use carrying amount & remaining life, **not** cost/original life):
$$r = 1 - \left(\frac{\text{Revised residual}}{\text{Carrying amount now}}\right)^{1/\text{remaining life}}$$

**Production-unit method:**
$$\text{unit rate} = \frac{\text{Cost} - \text{Residual}}{\text{Total estimated output}} \qquad \text{charge} = \text{unit rate} \times \text{output this year}$$

**Change in estimate / method (prospective):**
$$\text{Revised annual dep} = \frac{\text{Carrying amount now} - \text{Revised residual}}{\text{Remaining useful life}}$$

**Disposal:**
$$\text{Gain / (Loss)} = \text{Cash received} - \text{Net Book Value} \quad (\text{credit the asset at GROSS; debit accumulated dep separately})$$

**Exchange (trade-in):**
$$\text{Dissimilar (commercial substance)} \Rightarrow \text{FV of old} + \text{cash} \qquad \text{Similar} \Rightarrow \text{BV of old} + \text{cash (no gain/loss)}$$

**Revaluation:** Up → **Revaluation Reserve (OCI)**; Down → **P&L** (unless reversing that asset's surplus). Depreciate on the **revalued amount / remaining life**.
$$\text{Excess dep transferred RR}\to\text{General Reserve} = \text{dep on revalued amount} - \text{dep on original cost}$$
$$\text{On disposal: full surplus}\to\text{General Reserve};\ \text{sale gain/loss}\to\text{P\&L};\ \text{net to reserves}=\text{proceeds}-\text{original BV}$$

**Impairment:**
$$\text{Recoverable amount} = \max(\text{Net selling price},\ \text{Value in use}), \quad \text{VIU} = \sum \frac{\text{cash flow}_t}{(1+i)^t}$$
$$\text{Impairment} = \text{Carrying amount} - \text{Recoverable amount} \ (>0)$$
> Loss hits the **Revaluation Reserve first, then P&L**. Ind AS allows reversal (not goodwill); US GAAP never.

**Depreciation per $100 of gross value (Delta/Singapore comparability):**
$$\frac{100 \times (1 - \text{salvage \%})}{\text{depreciable life}}$$

**Intangibles:** purchased → capitalise; internally generated brand/goodwill → expense (software follows the research/development rule below). Research → expense; development → capitalise (when feasible & saleable); amortise over **useful life or legal life, whichever is shorter**.
- **AS vs IFRS:** goodwill — Indian AS amortise **≤5 yrs**; IFRS/Ind AS **no amortisation**, annual impairment. Other intangibles — AS **≤10 yrs** unless longer justified; IFRS finite→amortise, indefinite→impair.
- **Goodwill impairment** tested at **CGU** level; write down **goodwill first**, excess pro-rata to other assets; **never reversed**.

---

## D · Income Statement → [[05-Income-Statement-PandL]]

$$\text{Gross Profit} = \text{Revenue} - \text{COGS}$$

$$\text{COGS} = \text{Opening Inventory} + \text{Purchases (or production cost)} - \text{Closing Inventory}$$

**Cost of materials consumed (raw materials):**
$$\text{RM Consumed} = \text{Opening RM} + \text{Purchases} - \text{Closing RM}$$

**Changes in inventories line (Ind AS, output stock — FG/WIP/stock-in-trade):**
$$\text{Changes in Inventories} = \text{Opening Inventory} - \text{Closing Inventory}$$
- Positive → *adds* to expense (stock fell); Negative/bracketed → *reduces* expense (stock grew).

**Profit waterfall:**
$$\text{PBT} = \text{Total Income} - \text{Total Expenses} \pm \text{Exceptional items}$$
$$\text{PAT} = \text{PBT} - \text{Tax (current + deferred)}$$
$$\text{Total Comprehensive Income} = \text{PAT} + \text{Other Comprehensive Income (OCI)}$$

---

## E · Earnings Per Share → [[05-Income-Statement-PandL#Earnings Per Share (EPS)]]

**Basic EPS:**
$$\text{Basic EPS} = \frac{\text{PAT} - \text{Preference Dividends}}{\text{Weighted Avg. No. of equity shares}}$$

**Weighted average shares** — each tranche × (months outstanding ÷ 12).

**Diluted EPS (if-converted method):**
$$\text{Diluted EPS} = \frac{\text{PAT} - \text{Pref. Div.} + \big[\text{Interest on convertibles} \times (1 - t)\big]}{\text{Weighted Avg. shares} + \text{Potential new shares}}$$
- **t** — tax rate; interest is added back **net of tax** because conversion loses the tax shield.
- **Rule:** Diluted EPS ≤ Basic EPS; **anti-dilutive** securities are excluded.

---

## F · Cash Flow → [[06-Cash-Flow-Statement]]

$$\text{Net change in cash} = \text{CFO} + \text{CFI} + \text{CFF}$$
$$= \text{Closing cash} - \text{Opening cash}$$

**Operating cash flow (indirect method):**
$$\text{CFO} = \text{PBT} + \text{Non-cash expenses (dep'n, write-offs)} - \text{Non-operating gains} \pm \Delta\text{Working Capital} - \text{Tax paid}$$
- **ΔWorking Capital:** asset ↑ → subtract (cash tied up); liability ↑ → add (cash conserved).

---

## G · Ratios seen so far (introductory) → [[03-Balance-Sheet-Assets]] · HUL notes

$$\text{Return on Equity (indicative)} = \frac{\text{Profit}}{\text{Owner's Equity}} \quad\text{(Maria: } 4{,}600 / 30{,}000 \approx 16\%\text{ over 2 months)}$$
$$\text{P/E Ratio} = \frac{\text{Market Price per Share}}{\text{EPS}}$$

---

## H · Recording, Adjusting & Closing Entries → [[10-Journal-Ledger-and-Trial-Balance]] · [[11-Adjusting-Entries-and-Final-Accounts]]

**Trial balance check** — on every entry and in total:
$$\text{Total Debits} = \text{Total Credits}$$
- Account balance = debit side − credit side. **Assets/expenses** → debit balance; **liabilities/equity/revenue** → credit balance (DEAD CLIC).

**Accrued interest (time-based adjustment):**
$$\text{Accrued Interest} = \text{Principal} \times \text{Rate p.a.} \times \frac{\text{Months elapsed}}{12}$$
- e.g. 2,500 × 15% × 4/12 = **₹125** (Sept 1 → Dec 31).

**Supplies / inventory consumed (expense):**
$$\text{Consumed} = \text{Opening} + \text{Purchases} - \text{Closing on hand}$$

**Depreciation — contra-asset method:**
$$\text{Depreciation expense (Dr)} \;/\; \text{Accumulated Depreciation (Cr)} \qquad \text{Carrying amount} = \text{Cost} - \text{Accumulated Depreciation}$$
- Each year's charge **adds** to Accumulated Depreciation; original cost stays visible.

**The five adjusting entries (dual aspect):**

| Type | Debit | Credit |
|---|---|---|
| Accrued expense | Expense | Payable (liability) |
| Accrued revenue | Receivable (asset) | Revenue |
| Prepaid expiring | Expense | Prepaid asset |
| Unearned earned | Unearned revenue (liability) | Revenue |
| Depreciation | Depreciation expense | Accumulated depreciation |

**Closing entries (year-end — zero out the temporary accounts):**
$$\text{1) Revenue} \to \text{P\&L Summary} \quad \text{2) P\&L Summary} \to \text{Expenses}$$
$$\text{3) P\&L Summary} \to \text{Retained Earnings (net profit)} \quad \text{4) Retained Earnings} \to \text{Dividends}$$
- **Rule:** all **revenue, expense and dividend** accounts reset to **0** before the new year — **Sales restarts at ₹0** and accumulates afresh. **Only balance-sheet accounts carry forward.**

**Perpetual vs periodic inventory:**
$$\text{Perpetual: Inventory (asset)} \xrightarrow{\text{each sale}} \text{COGS} \qquad \text{Periodic: COGS} = \text{Opening} + \text{Purchases} - \text{Closing}$$
- Perpetual → *asset reduced into expense*; periodic → *Purchases expense reduced by closing stock (asset)*.

**Capital vs revenue expenditure:** repairs/maintenance → **expense**; renovation/improvement → **capitalise** (asset).

---

## Quick-reference constants & thresholds

| Item | Rule of thumb |
|---|---|
| Current vs non-current | 1 year (or operating cycle, whichever is longer) |
| Cash equivalent maturity | ≤ 3 months, insignificant risk of value change |
| Subsidiary (consolidate) | > 50% holding |
| Associate (equity method) | 20–50% holding |
| Provision recognised | present obligation + **probable** outflow + **reliable estimate** |
| Contingent liability | only *disclosed* (possible, or not measurable) |
| Diluted EPS interest add-back | Interest × (1 − tax rate) |

---

**Related:** [[00-Course-Map]] · [[91-Exam-Question-Bank]] · [[92-Past-Paper-Breakdown]]
