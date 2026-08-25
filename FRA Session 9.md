---
title: FRA Session 9 — Bad Debts, Loyalty Points & Revenue Recognition
course: FRA
session: 9
tags:
  - mba
  - fra
  - accounting
  - session-notes
  - receivables
  - revenue-recognition
  - ifric-13
status: reviewed
draft: false
dg-publish: false
---

← [[FRA Session 8]] | [[FRA — Index|FRA Index]] | [[Acads/FRA/FRA Session 10]] →

> [!abstract] Session in one line
> Receivables are never worth their face value — the allowance method forces you to book the expected loss *before* you know who defaults. Then: how deferred revenue works when the promise is a loyalty point rather than a good.

---

## 1. Bad debts — the allowance method

### 1.1 Setting up the provision

Trade receivables Rs 1,00,000, estimated uncollectible 5%.

| Particulars | Dr (Rs) | Cr (Rs) |
| :--- | ---: | ---: |
| Bad Debt Expense A/c | 5,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Provision for Doubtful Debts A/c | | 5,000 |

[[Provision for Doubtful Debts]] is a **contra asset** — it sits against trade receivables and reduces the carrying amount to Rs 95,000 on the face of the balance sheet. The gross figure stays intact in the ledger.

> [!note] Why estimate at all
> Matching. The revenue was recognised in this period, so the cost of the credit extended to earn it belongs in this period too — even though the identity of the defaulter is unknown at year-end.

### 1.2 Actual default — Mr. X absconds on Rs 1,000

| Particulars | Dr (Rs) | Cr (Rs) |
| :--- | ---: | ---: |
| Provision for Doubtful Debts A/c | 1,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Accounts Receivable (Mr. X) A/c | | 1,000 |

> [!important] The P&L is untouched
> The hit was taken when the provision was created. A write-off is only a *reclassification* — both sides of the entry are balance sheet accounts. Net receivables don't move either: gross A/R falls by 1,000 **and** the contra asset falls by 1,000.

### 1.3 Carry-forward of the unused provision

Whatever is left in the provision after write-offs **carries forward** as long as the underlying receivables are still on the books. Next period's bad debt expense is therefore only the *top-up* needed to bring the provision to the required closing balance — not the full closing balance itself. This is exactly the plug that Q8 below asks you to reconstruct.

### 1.4 Recovery — Mr. X comes back

| Particulars | Dr (Rs) | Cr (Rs) |
| :--- | ---: | ---: |
| Cash A/c | 1,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Provision for Doubtful Debts A/c | | 1,000 |

> [!question]- Why doesn't Mr. X reappear on the balance sheet? *(the prof's point, worked out)*
> Mr. X's personal account was already **credited to nil** at write-off. If you now credit it again on recovery, it goes to a **credit balance of Rs 1,000** — and a credit balance in a receivable account reads as a *payable*: it looks like you're holding Rs 1,000 of his money, i.e. that you owe him. You don't. He owes you nothing and you owe him nothing; the debt is settled.
>
> So the credit goes to the provision (or to a **Bad Debts Recovered** income account) instead, and Mr. X's personal ledger stays flat at zero.
>
> The textbook alternative is the **two-step reinstatement**: A/R (Mr. X) Dr / Provision Cr, then Cash Dr / A/R (Mr. X) Cr. Same net effect, and it preserves the audit trail in the subsidiary ledger — but the personal account still nets to zero, which is the whole point.

---

## 2. Q8 — Heaven Sight Seeing Corporation

> [!question] Question
> Determine (a) receivables actually written off in 2024, (b) cash collected from customers in 2024, (c) the journal entries for A/R and the allowance during 2024.

**Given** *(Rs; assume all sales are on credit)*

| | 2023 | 2024 |
| :--- | ---: | ---: |
| Sales | 2,36,250 | 2,70,000 |
| Accounts Receivable (closing) | 58,500 | 68,625 |
| Allowance for Doubtful Debts (closing) | 2,025 | 2,700 |
| Bad Debt Expense (for the year) | 9,450 | 10,800 |

### (a) Write-offs during 2024

The allowance is *increased* by the bad debt expense and *decreased* by actual write-offs:

$$\text{Opening} + \text{Bad Debt Expense} - \text{Write-offs} = \text{Closing}$$
$$2{,}025 + 10{,}800 - \text{Write-offs} = 2{,}700$$
$$\text{Write-offs} = \boxed{\textbf{Rs 10,125}}$$

**Allowance for Doubtful Debts A/c**

| Particulars | Rs | Particulars | Rs |
| :--- | ---: | :--- | ---: |
| To Accounts Receivable (write-offs) | 10,125 | By Balance b/d | 2,025 |
| To Balance c/d | 2,700 | By Bad Debt Expense | 10,800 |
| | **12,825** | | **12,825** |

### (b) Cash collected in 2024

$$\text{Opening} + \text{Credit Sales} - \text{Write-offs} - \text{Collections} = \text{Closing}$$
$$58{,}500 + 2{,}70{,}000 - 10{,}125 - \text{Collections} = 68{,}625$$
$$\text{Collections} = \boxed{\textbf{Rs 2,49,750}}$$

**Accounts Receivable A/c**

| Particulars | Rs | Particulars | Rs |
| :--- | ---: | :--- | ---: |
| To Balance b/d | 58,500 | By Cash (collections) | 2,49,750 |
| To Sales (credit) | 2,70,000 | By Provision for Doubtful Debts (write-offs) | 10,125 |
| | | By Balance c/d | 68,625 |
| | **3,28,500** | | **3,28,500** |

### (c) Journal entries — 2024

| Particulars | L.F. | Debit (Rs) | Credit (Rs) |
| :--- | :--: | ---: | ---: |
| Accounts Receivable A/c ...... Dr | | 2,70,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Sales A/c | | | 2,70,000 |
| *(Credit sales for the year)* | | | |
| Cash A/c ...... Dr | | 2,49,750 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Accounts Receivable A/c | | | 2,49,750 |
| *(Cash collected from customers)* | | | |
| Bad Debt Expense A/c ...... Dr | | 10,800 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Provision for Doubtful Debts A/c | | | 10,800 |
| *(Bad debt expense estimated for the year)* | | | |
| Provision for Doubtful Debts A/c ...... Dr | | 10,125 | |
| &nbsp;&nbsp;&nbsp;&nbsp;To Accounts Receivable A/c | | | 10,125 |
| *(Uncollectible accounts written off)* | | | |

> [!tip] Exam pattern
> Both parts are the same trick: **reconstruct the T-account and solve for the missing plug.** Whichever of the five figures is withheld — opening, expense, write-offs, collections, closing — the identity is the same. Note also that the *provision* is the credit in the write-off entry, never Bad Debt Expense (that would double-count the charge).

---

## 3. Customer loyalty programmes — [[IFRIC 13]] illustrative example

**Setup.** A grocery retailer grants 100 loyalty points. Fair value of groceries per point = Rs 1.25, already net of the discount that would otherwise be offered to non-members. Management expects only **80 points** to be redeemed.

$$\text{FV per point} = \frac{80}{100} \times 1.25 = \text{Re } 1.00 \quad\Rightarrow\quad \textbf{Rs 100 of revenue deferred}$$

The points are a separately identifiable component of the original sale — a performance obligation that hasn't been satisfied yet. So Rs 100 sits as [[Unearned Revenue|deferred revenue]] until redemption.

**Recognition pattern:** cumulative revenue = Rs 100 × (points redeemed to date ÷ *currently expected* total redemptions), less what's already been recognised.

| Year | Redeemed (cumulative) | Expected total redemptions | Cumulative revenue | Recognised this year |
| :--- | ---: | ---: | ---: | ---: |
| 1 | 40 | 80 | 100 × 40/80 = **50** | 50 |
| 2 | 81 | 90 *(revised)* | 100 × 81/90 = **90** | 40 |
| 3 | 90 | 90 | 100 × 90/90 = **100** | 10 |

> [!note] The two moving parts
> The **numerator** changes with actual redemptions; the **denominator** changes when management revises its expectation of ultimate redemptions. A revision is a **change in estimate** — handled prospectively through the cumulative catch-up, never by restating prior years.
>
> In Year 2 the denominator rose from 80 to 90, which *dampens* the revenue recognised despite 41 points being redeemed. Higher expected redemptions ⇒ each point is worth proportionally less revenue today.

**Breakage.** The 10 points never expected to be redeemed are the reason FV per point is Re 1 and not Rs 1.25. If points expire unredeemed, the residual deferred revenue is released.

---

## 4. Revenue recognition — first principles

> [!important] The rule
> Revenue is recognised when the **performance obligation is satisfied** — not when cash moves, and not when the order is placed.

- **Amazon order** → revenue on **delivery**, not at checkout. Cash received earlier sits as a contract liability.
- **Gift card** → revenue when the card is **redeemed**, not when it's sold. Sale of the card is Cash Dr / Deferred Revenue Cr; redemption moves it to revenue. Cards that will never be redeemed (breakage) are recognised in proportion to the pattern of actual redemptions, based on historical experience.

Carried into [[Acads/FRA/FRA Session 10]]: the agent-vs-principal distinction (ticket aggregator vs airline), and what happens when the "asset" being created is R&D rather than a receivable.

---

## Concepts touched

[[Allowance Method]] · [[Provision for Doubtful Debts]] · [[Contra Asset]] · [[Matching Principle]] · [[Change in Accounting Estimate]] · [[Unearned Revenue]] · [[IFRIC 13]] · [[Revenue Recognition]]
