---
tags:
  - fra
  - topic
  - balance-sheet
  - equity
  - liabilities
  - session-2
  - session-3
course: Financial Reporting & Analysis
syllabus: Session 2 / Session 3
dg-publish: false
---

# 04 · The Balance Sheet — Equity & Liabilities

> [!info] What this note covers
> The other side of the balance sheet: **equity** (share capital, other equity, book vs market value, primary vs secondary market, types of share capital, NCI) and **liabilities** (current vs non-current, provisions, contingent liabilities), plus the **claim hierarchy** of who gets paid first. Assets are in [[03-Balance-Sheet-Assets]].

---

## 1. Why equity and liabilities sit on the same side

> [!question] The recurring question: why are Equity and Liabilities together, opposite Assets?
> Because both are **sources of funds** — claims on the firm's assets. **Assets** show *where the money is deployed* (uses); **equity and liabilities** show *where it came from* (sources — owners vs outsiders). Sources must exactly fund uses, so:
> $$\boxed{\text{Assets} = \text{Liabilities} + \text{Equity}}$$
> Assets are **uses/application of funds**; liabilities + equity are **sources of funds**. They are equal by construction. Full treatment: [[08-The-Accounting-Equation]].

---

## 2. Equity — the owners' residual claim

> [!note] Definition
> **Equity** is the **residual interest** in the assets of the firm after deducting all its liabilities.
> $$\text{Equity} = \text{Assets} - \text{Liabilities}$$

Equity shareholders have a **residual claim**: their dividend is *variable*, and in a winding-up they rank **last** — paid only after every creditor and preference holder. Highest risk, highest potential reward.

> [!note] Net worth — four names for one number
> **Net worth = Shareholders' equity = Net assets = Book value.**
> $$\text{Net worth} = \text{Total Assets} - \text{Total Liabilities} = \text{Equity Share Capital} + \text{Other Equity}$$
> $$\text{Book value per share} = \frac{\text{Net worth}}{\text{No. of shares}}$$

### The two equity heads on the balance sheet

Indian balance sheets show equity as **two lines** (three on consolidation):

| Head | What's inside |
|---|---|
| **Equity Share Capital** | **Face (nominal) value × number of shares** — *only* the face value, nothing else |
| **Other Equity** | Everything else: **securities premium**, reserves, **retained earnings** |
| *(Non-controlling interest)* | *On consolidation only — see §6* |

---

## 3. Share capital vs premium 

When shares are issued **above face value**, the excess is a **premium** kept **separate** from share capital.

- **Equity Share Capital** = face value only → stays clean and comparable regardless of market conditions.
- **Securities Premium** = the excess over face value → sits in **Other Equity**; it is a capital reserve and is **not freely distributable as dividend**.

$$\text{Issue Price} = \text{Face Value} + \text{Premium}$$

> [!example] Issue 1,00,000 shares of ₹10 face value at ₹25 each
> Per share: **₹10 → Equity Share Capital** (total ₹10,00,000); **₹15 → Securities Premium** (total ₹15,00,000).
> ```
> Bank A/c                      Dr. 25,00,000
>     To Equity Share Capital A/c        10,00,000
>     To Securities Premium A/c          15,00,000
> ```

### Why net worth changes even when share capital is frozen

**Other Equity** moves with profits, losses and dividends, so net worth changes yearly even though the **share capital line stays put**:

| | Equity Share Capital | Other Equity | **Net worth** | BV/share |
|---|---:|---:|---:|---:|
| At issue | 10,00,000 | 15,00,000 | **25,00,000** | ₹25 |
| After Yr 1 — ₹5L profit retained | 10,00,000 | 20,00,000 | **30,00,000** | ₹30 |
| After Yr 2 — ₹3L profit, ₹2L dividend | 10,00,000 | 21,00,000 | **31,00,000** | ₹31 |

> [!tip] Rule of thumb — which head moves?
> **Capital transactions** (fresh issue, bonus, buyback) touch **Share Capital**. **Operating results** (profit, loss, dividend) touch **only Other Equity**.
> - **Equity Share Capital:** fresh issue **↑** (face value only) · buyback **↓** · bonus issue **↑** (funded *from* Other Equity → net worth unchanged) · split/consolidation → no change.
> - **Other Equity:** premium on issue **↑** · profit **↑** / loss **↓** · dividend **↓** · bonus issue **↓**.

> [!example] HUL FY26
> Share capital is a tiny **₹235 cr** (face value **₹1**/share) against Other Equity of **₹48,504 cr** — nearly all net worth is **accumulated reserves**, not paid-in capital. Exactly the face-value-vs-other-equity split.

---

## 4. Face value vs book value vs market price

| | What it is | Moves? | On the balance sheet? |
|---|---|---|---|
| **Face value** (e.g. ₹10) | Nominal value printed on the share | Fixed | **Yes** — drives share capital |
| **Book value** (e.g. ₹31) | Net worth ÷ shares | With retained profits | **Yes** — derived from it |
| **Market price** (e.g. ₹140) | Exchange trading price | Daily | **No, not directly** |

> [!note] Why book value and market price diverge
> **Book value is backward-looking** — capital put in *plus* profits accumulated **to date**. **Market price is forward-looking** — it prices in *expected future* earnings and growth. A firm expected to grow trades **above** book; a struggling one can trade **below** it.

### Primary vs secondary market — which one hits the balance sheet?

- **Primary market** — the company issues **new** shares and **receives the cash** (IPO, rights, preferential). **This hits the balance sheet:** Cash ↑, Share Capital + Securities Premium ↑. A high market price lets the firm charge a bigger premium — so market price reaches the books **indirectly, through the premium it enables**.
- **Secondary market** — investors trade **existing** shares among themselves (the daily stock exchange). Cash passes buyer→seller; **the company gets nothing and the balance sheet is unchanged.**
- **Buyback** — company pays cash (≈ market price) to cancel shares: Cash ↓, Share Capital ↓.

> [!warning] Classic exam point
> A shareholder selling shares on the NSE (secondary market) has **no effect on the company's balance sheet** — the company is not a party to the trade. Only *who owns* the equity changes, not its total. (This is Music Mart event 12 — see [[08-The-Accounting-Equation]].)

---

## 5. Types of share capital & providers of capital

### Stages of share capital (broad → narrow)
**Authorised → Issued → Subscribed → Called-up → Paid-up**

| Stage | Meaning |
|---|---|
| **Authorised** | Ceiling the company may raise, per its Memorandum of Association |
| **Issued** | Portion of authorised capital actually offered to investors |
| **Subscribed** | Portion of issued capital investors agreed to take |
| **Called-up** | Portion of subscribed capital the company has demanded payment on |
| **Paid-up** | Amount **actually received** — this is what appears on the balance sheet |

### Providers of capital — the claim hierarchy

| | Lenders | Preference Shareholders | Equity Shareholders |
|---|---|---|---|
| **Role** | Creditors | Owners — *hybrid* | Owners — *true* |
| **Return** | Interest — fixed | Dividend — fixed % | Dividend — variable |
| **Paid from** | Any year (contractual obligation) | Profits, before equity | Profits, after all |
| **Priority (paid first)** | **1st** | **2nd** | **Last (residual)** |
| **Voting** | None | Usually none | Full |
| **Risk / reward** | Lowest | Middle | Highest |
| **Sits on B/S under** | **Liabilities** | Equity | Equity |

> [!tip] The mnemonic
> **Priority runs Lenders → Preference → Equity; risk/reward runs in reverse.** Lenders sit on the *liabilities* side; both share classes sit under *equity*.

### Liability vs limited liability
- **Liability** = an obligation to pay.
- **Limited liability** = a shareholder's liability is **capped at the unpaid amount on their shares**. Fully paid → nil further liability; partly paid → only the uncalled portion can be demanded. **Personal assets are protected.** (Contrast sole proprietorships / partnerships → *unlimited* liability. See [[01-Firm-Governance-and-Reporting-Environment#Forms of business]].)

---

## 6. Non-Controlling Interest (NCI)

> [!note] Definition
> **NCI** (older term: *minority interest*) = the portion of a subsidiary's equity (net assets) **not owned by the parent**. Parent owns 80% of a subsidiary → the outside **20% = NCI**.

- Arises **only on consolidation**: the group adds **100%** of the subsidiary's assets and liabilities line-by-line, so NCI captures the **outsiders' share** of that net worth.
- Shown as a **separate line within equity** on the *consolidated* balance sheet; consolidated **profit is likewise split** into *owners of parent* vs *NCI*.Ttt 

> [!warning] Not in the standalone balance sheet
> Standalone, the parent shows only *"Investment in Subsidiary"* (at cost) — no consolidation, no NCI. NCI is purely a **group-accounts** figure.

> [!example] HUL FY26
> **NCI = ₹269 cr** in equity, and the [[05-Income-Statement-PandL|P&L]] splits profit into "Owners of the Holding Company **15,040**" and "Non-controlling interests **19**." Both appear *because the statement is consolidated*.

---

## 7. Liabilities

> [!note] Definition
> A **liability** is a **present obligation** arising from a **past event**, whose settlement is expected to cause an **outflow of resources** (usually cash). It is the **creditors' claim** on the firm's assets.

Classified by **when it falls due**:

| Type | Due within | Examples |
|---|---|---|
| **Current** | 12 months (or one operating cycle) | Trade payables, short-term borrowings, outstanding expenses, tax payable, **current portion of long-term debt** |
| **Non-current** | Beyond 12 months | Long-term loans, debentures, deferred tax liabilities, long-term provisions, lease liabilities |

- **Trade payables / sundry creditors** — owed to suppliers for goods/services bought on credit.
- **Current portion of long-term debt** — the slice of a long-term loan repayable within the coming year, reclassified as **current**.
- **Outstanding (accrued) liabilities** — arise from [[07-Conceptual-Framework-and-Core-Concepts#Accrual Concept|accrual accounting]]: an expense recognised *before* cash is paid.
- **Debt capital** — long-term funds, often raised via **debentures**. Debenture holders get a **fixed interest** *whether or not the firm is profitable*, and rank **ahead of** equity in liquidation. **Secured** loans have specific assets pledged; **unsecured** loans don't.

### Provisions
> [!note] A **provision** is a liability of **uncertain timing or amount.**
> Recognised only when **all three** hold:
> 1. A **present obligation** exists from a past event,
> 2. an outflow of resources is **probable**, and
> 3. a **reliable estimate** of the amount can be made.

Examples: provisions for **doubtful debts, warranty, tax, gratuity/employee benefits, restructuring, legal claims.** Created by a **charge against profit** (reduces the P&L) — the prudence principle: account for a likely cost *before* it crystallises.

### Contingent liabilities
> [!note] A **contingent liability** is a **potential** obligation that may arise depending on an **uncertain future event** (a pending lawsuit, a guarantee on another party's debt, a tax dispute, warranty claims).

Because it is **not yet a present obligation**, it is **not recognised** on the face of the balance sheet — it is **disclosed as a footnote**. Under **Ind AS 37 / IAS 37**, treatment depends on likelihood:

| Likelihood of outflow | Reliable estimate? | Treatment |
|---|---|---|
| **Probable** | Yes | Recognise a **provision** (a real liability on the B/S) |
| Possible, or probable but not measurable | — | **Disclose** as a contingent liability (footnote) |
| **Remote** | — | Ignore — no recognition, no disclosure |

> [!warning] Provision vs contingent liability — the exam favourite
> A **provision** *is booked* as a liability (probable **and** estimable). A **contingent liability** is *only disclosed*. The dividing line is whether the outflow is **probable AND reliably measurable**. HUL's balance sheet carries the standard footnote line "Contingent liabilities and commitments (Note 26)."

---

## 8. Applied example — HUL's equity & liabilities side (FY26)

> [!example] Reading the HUL consolidated balance sheet (₹ cr)
> | | FY26 | FY25 |
> |---|---:|---:|
> | Equity share capital | 235 | 235 |
> | Other equity | 48,504 | 49,167 |
> | Non-controlling interests | 269 | 207 |
> | **Total equity** | **49,008** | **49,609** |
> | Non-current liabilities | 15,195 | 13,734 |
> | Current liabilities | 15,549 | 16,537 |
> | **Total equity + liabilities** | **79,752** | **79,880** |
>
> **What it tells you:**
> - **Funded by equity (~61%) and supplier credit, not debt** — borrowings are essentially **zero**; the only debt-like items are **lease liabilities** (Ind AS 116).
> - **Suppliers finance operations:** trade payables (~13,325) ≈ **4× trade receivables** (3,379) — pays slowly, collects quickly. Ties to [[03-Balance-Sheet-Assets]].
> - **Tiny share capital, huge Other Equity** — the reserves story from §3.
> - **NCI ₹269 cr** — the consolidation fingerprint from §6.
> - **It balances:** ₹79,752 cr each side — the accounting equation, live.

---

## Common mistakes (Equity & Liabilities)

> [!warning] Gotchas
> - **Recording shares at issue price on the share-capital line** — no: share capital is **face value only**; the premium goes to **Other Equity**.
> - **Getting the claim hierarchy backwards** — Lenders **first**, then Preference, then Equity.
> - **Treating a secondary-market trade / buying-selling of shares by owners as affecting the company** — it doesn't (Quiz-style; Music Mart event 12).
> - **Booking a contingent liability as a real liability** — only *disclose* it unless it becomes probable **and** estimable (then it's a provision).
> - **Forgetting dividends reduce equity (Other Equity), while a fresh issue raises Share Capital.** Quiz 1 Q6, Q19.
> - **Thinking NCI appears standalone** — it's consolidation-only.

---

## Key takeaways

- Equity is the **residual** (Assets − Liabilities); net worth = **Share Capital (face value) + Other Equity**.
- **Premium ≠ share capital** — it lives in Other Equity and isn't freely distributable.
- **Book value = backward-looking; market price = forward-looking**; only **primary-market** issues (and buybacks) hit the balance sheet.
- Claim hierarchy: **Lenders → Preference → Equity** (paid in that order; risk in reverse).
- **Provision = recognised** (probable + estimable); **contingent liability = disclosed only**.
- **NCI** is a consolidation-only line within equity.

---

**Related:** [[03-Balance-Sheet-Assets]] · [[05-Income-Statement-PandL]] · [[07-Conceptual-Framework-and-Core-Concepts]] · [[08-The-Accounting-Equation]] · [[HUL Balance Sheet]] · [[90-Master-Formula-Sheet]]
