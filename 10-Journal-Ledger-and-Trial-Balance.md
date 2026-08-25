---
tags:
  - fra
  - topic
  - double-entry
  - journal
  - ledger
  - trial-balance
  - session-5
course: Financial Reporting & Analysis
syllabus: Session 5
dg-publish: false
---

# 10 · Journal, Ledger & Trial Balance

> [!info] What this note covers
> Session 5 is where the **recording machinery** stops being theory and gets *practised*. It takes the debit/credit rules from [[09-The-Accounting-Cycle-Recording-Transactions]] and works a full business through the cycle: **journal → ledger (T-accounts) → balancing off → trial balance → Trading & P&L account → balance sheet.** The spine of the session is one capstone case — a small trading business with **ten transactions** — carried all the way from first journal entry to finished statements. Content here follows the teacher's *Rules of Debit and Credit* handout.

> [!note] How this sits next to note 09
> Note 09 introduced the *cycle* and the debit/credit *rules*; this note is the **hands-on drill**. Where note 09 used cases about profit-vs-cash (Maria Hernandez) and statement prep (Lone Pine), Session 5 is deliberately mechanical — get fluent at journalising and posting before the Session 6 adjustments arrive.

---

## 1. The rule that governs everything

$$\boxed{\text{Assets} = \text{Liabilities} + \text{Equity} + \text{Revenue} - \text{Expenses}}$$

and, as a consequence of [[07-Conceptual-Framework-and-Core-Concepts#Dual Aspect (Duality) Concept|dual aspect]], for **every** transaction:

$$\boxed{\text{Total Debits} = \text{Total Credits}}$$

> [!warning] Correcting two slips in the raw Session 5 notes
> The rough notes wrote the expanded equation as "A = L + E + Rev − Equity" and gave two of the five rules incorrectly. The correct statements are below. The errors were:
> - "…a decrease in **cash** is a debit" (under equity) → should be "a decrease in **equity** is a **debit**".
> - "an increase in expense is a debit, while a decrease in **liabilities** is a credit" → should be "a decrease in **expense** is a **credit**".

### The five rules, stated cleanly

| Account type | Increase | Decrease | Normal balance |
|---|---|---|---|
| **Asset** | Debit | Credit | Debit |
| **Expense** | Debit | Credit | Debit |
| **Liability** | Credit | Debit | Credit |
| **Equity / Capital** | Credit | Debit | Credit |
| **Revenue / Income** | Credit | Debit | Credit |

> [!tip] Mnemonic — **DEAD CLIC**
> **D**ebit increases **E**xpenses, **A**ssets, **D**rawings. **C**redit increases **L**iabilities, **I**ncome, **C**apital. Everything else is the mirror image.

> [!note] Why revenue is a credit and expense is a debit (the teacher's derivation)
> The five rules are not arbitrary — the last two *fall out of* the equity rule. Start from the three balance-sheet elements: **assets increase on the debit side; liabilities and equity increase on the credit side** (this keeps A = L + E in balance). Then:
> - **Revenue / gains increase equity** → since equity increases by a **credit**, revenue and gains are **credits**.
> - **Expenses / losses decrease equity** → since equity decreases by a **debit**, expenses and losses are **debits**.
>
> So only *one* rule is fundamental (the equity rule); revenue and expense rules are its consequences. At any moment, an account's **balance** is the difference between its debit and credit entries: **assets, expenses and losses normally carry debit balances; liabilities, equity, revenues and gains normally carry credit balances.**

---

## 2. The three records — journal, ledger, trial balance

> [!note] Definition — Journal
> The **journal** is the *first* record of a transaction ("the book of original entry" / book of prime entry), written in debit/credit form in date order. Using a journal ensures **every** entry passes through a book of prime entry before it reaches the ledger. In Indian convention the credit line is prefixed with **"To"** and indented. One journal entry can have several credit lines as long as **total Dr = total Cr**.

> [!tip] The three-step procedure for any journal entry (teacher's method)
> For every transaction, ask in order:
> 1. **Which accounts are affected?**
> 2. **Is each account debited or credited?** (apply the rules above)
> 3. **What amounts are debited or credited?**
>
> Get those three right and the entry writes itself. This is the routine to run on every line of the ten-transaction case below.

> [!note] Definition — Ledger (T-account)
> After journalising, each entry is **posted** to a **ledger account** — one running record per account (Cash, Sales, Creditors…). Drawn as a **T-account**: debits on the **left**, credits on the **right**. Ledger posting is simply re-sorting the journal *by account* instead of *by date* so you can see each account's running balance.

> [!note] Definition — Trial Balance
> A **trial balance** lists the **closing balance of every ledger account** at a date, in two columns (debit balances / credit balances), usually in order of liquidity. It is an internal check: **the two columns must be equal.** A match proves the books are *arithmetically* balanced — it does **not** prove the entries were *classified* correctly (a wrong-account error still balances).

### Balancing off an account — "balance c/d" and "balance b/d"

> [!important] What c/d and b/d actually mean
> To close a T-account at period-end you make both sides total to the same figure:
> - **Balance c/d** ("carried down") is the plug written on the *lighter* side so the two totals match. It is the account's closing balance.
> - **Balance b/d** ("brought down") is that same figure re-entered on the *opposite* side to *open* the next period.
>
> A **debit** balance c/d (written on the credit side to close) reappears as a **debit** b/d — the account is *debit-natured* (an asset or expense). Example: if Cash has ₹1,950 of debits and ₹1,580 of credits, you write **"By balance c/d 370"** on the credit side to make both sides ₹1,950; next period opens with **"To balance b/d 370"** on the debit side.

---

## 3. Capstone case — a trading business in ten transactions

> [!question] The case (as set — solve with explanation)
> The following transactions are recorded in journals *(all figures in Rs.)*. 
>
> | # | Transaction | Rs. |
> |---|---|---:|
> | 1 | Business started with a capital | 1,000 |
> | 2 | Raise a loan for cash | 500 |
> | 3 | Buy plant for cash | 1,000 |
> | 4 | Buy inventory for cash | 250 |
> | 5 | Buy inventory on credit | 350 |
> | 6 | Sell inventory on credit | 550 |
> | 7 | Cost of goods sold | 350 |
> | 8 | Collect cash from debtors | 450 |
> | 9 | Pay cash to creditors | 250 |
> | 10 | Pay general expenses in cash | 80 |
>
> **Required:** journalise all ten transactions, post them to ledger (T-)accounts, balance off each account, and prepare the trial balance.
>
> *Indian terms: a credit customer who owes us is a **debtor / accounts receivable**; a credit supplier we owe is a **creditor / accounts payable**.*

### Step 1 — Journal entries

| # | Transaction | Journal entry |
|---|---|---|
| 1 | Capital introduced | Cash A/c **Dr 1,000** · To Capital A/c **1,000** |
| 2 | Loan taken in cash | Cash A/c **Dr 500** · To Loan A/c **500** |
| 3 | Plant bought for cash | Plant A/c **Dr 1,000** · To Cash A/c **1,000** |
| 4 | Inventory bought for cash | Inventory A/c **Dr 250** · To Cash A/c **250** |
| 5 | Inventory bought on credit | Inventory A/c **Dr 350** · To Accounts Payable **350** |
| 6 | Goods sold on credit | Accounts Receivable **Dr 550** · To Sales A/c **550** |
| 7 | Cost of goods sold | COGS A/c **Dr 350** · To Inventory A/c **350** |
| 8 | Cash collected from debtors | Cash A/c **Dr 450** · To Accounts Receivable **450** |
| 9 | Cash paid to creditors | Accounts Payable **Dr 250** · To Cash A/c **250** |
| 10 | General expenses paid in cash | General Expenses **Dr 80** · To Cash A/c **80** |

> [!note] Explanation — why each entry is debited/credited
> Apply the [[#1. The rule that governs everything|DEAD CLIC]] rule to each transaction. In every case, identify the two accounts, their type, and the direction of change:
> 1. **Capital introduced** — Cash (asset) comes in → **debit Cash**; the owner's claim (equity) rises → **credit Capital**. Asset ↑ / Equity ↑.
> 2. **Loan for cash** — Cash (asset) rises → **debit Cash**; a liability is created → **credit Loan**. Asset ↑ / Liability ↑.
> 3. **Plant for cash** — Plant (asset) acquired → **debit Plant**; Cash (asset) paid out → **credit Cash**. An asset-for-asset **swap** — total assets unchanged.
> 4. **Inventory for cash** — Inventory (asset) in → **debit Inventory**; Cash (asset) out → **credit Cash**. Another asset swap.
> 5. **Inventory on credit** — Inventory (asset) in → **debit Inventory**; we now owe the supplier → **credit Accounts Payable** (creditor). Asset ↑ / Liability ↑.
> 6. **Sell on credit** — the customer owes us → **debit Accounts Receivable** (debtor); revenue earned → **credit Sales**. Asset ↑ / Revenue ↑. *(Revenue side of the sale only.)*
> 7. **Cost of goods sold** — the goods that left are an expense → **debit COGS**; Inventory (asset) falls → **credit Inventory**. Expense ↑ / Asset ↓. *(Cost side of the same sale — see tip below.)*
> 8. **Collect from debtors** — Cash (asset) in → **debit Cash**; the debtor owes less → **credit Accounts Receivable**. Asset ↑ / Asset ↓ swap.
> 9. **Pay creditors** — the liability falls → **debit Accounts Payable**; Cash (asset) out → **credit Cash**. Liability ↓ / Asset ↓.
> 10. **General expenses** — expense incurred → **debit General Expenses**; Cash (asset) out → **credit Cash**. Expense ↑ / Asset ↓.

> [!tip] Why a sale is *two* journal entries (rows 6 and 7)
> Recording the sale (revenue) and recording the **cost of what was sold** are separate events on the books. Row 6 raises revenue and the debtor; row 7 removes the inventory that left the business and books it as an expense. This is the [[07-Conceptual-Framework-and-Core-Concepts#Matching Concept|matching concept]] in action — you cannot recognise the ₹550 of sales without also recognising the ₹350 of cost that earned it.

### Step 2 — Ledger (T-accounts)

**Cash A/c**

| Dr (Particulars) | ₹ | Cr (Particulars) | ₹ |
|---|---:|---|---:|
| To Capital | 1,000 | By Plant | 1,000 |
| To Loan | 500 | By Inventory | 250 |
| To Accounts Receivable | 450 | By Accounts Payable | 250 |
| | | By General Expenses | 80 |
| | | **By balance c/d** | **370** |
| **Total** | **1,950** | **Total** | **1,950** |

**Capital A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To balance c/d | 1,000 | By Cash | 1,000 |
| **Total** | **1,000** | **Total** | **1,000** |

**Loan A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To balance c/d | 500 | By Cash | 500 |
| **Total** | **500** | **Total** | **500** |

**Plant A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Cash | 1,000 | By balance c/d | 1,000 |
| **Total** | **1,000** | **Total** | **1,000** |

**Inventory A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Cash | 250 | By COGS | 350 |
| To Accounts Payable | 350 | By balance c/d | 250 |
| **Total** | **600** | **Total** | **600** |

**Accounts Payable (Creditors) A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Cash | 250 | By Inventory | 350 |
| To balance c/d | 100 | | |
| **Total** | **350** | **Total** | **350** |

**Accounts Receivable (Debtors) A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Sales | 550 | By Cash | 450 |
| | | By balance c/d | 100 |
| **Total** | **550** | **Total** | **550** |

**Sales A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To balance c/d | 550 | By Accounts Receivable | 550 |
| **Total** | **550** | **Total** | **550** |

**COGS A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Inventory | 350 | By balance c/d | 350 |
| **Total** | **350** | **Total** | **350** |

**General Expenses A/c**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Cash | 80 | By balance c/d | 80 |
| **Total** | **80** | **Total** | **80** |

> [!note] Reading the Inventory account
> Inventory received ₹250 + ₹350 = **₹600** in (debits) and gave up ₹350 to COGS (credit). The **₹250 balance c/d is closing stock** — goods bought but not yet sold. This single account is doing the job a Trading Account does later: opening stock + purchases − cost of goods sold = closing stock.

### Step 3 — Trial Balance

| Account | Debit (₹) | Credit (₹) |
|---|---:|---:|
| Cash | 370 | |
| Plant | 1,000 | |
| Inventory (closing stock) | 250 | |
| Accounts Receivable | 100 | |
| COGS | 350 | |
| General Expenses | 80 | |
| Capital | | 1,000 |
| Loan | | 500 |
| Accounts Payable | | 100 |
| Sales | | 550 |
| **Total** | **2,150** | **2,150** |

> [!example] The check that matters
> Debits **2,150** = Credits **2,150**. Every debit-natured account (assets + expenses) sits in the left column; every credit-natured account (capital, loan, payables, revenue) in the right. If these didn't tie, a posting is wrong somewhere — you would not proceed to statements until they balance.

---

## 4. Trading & P&L account and Balance Sheet

The trial balance splits cleanly into the two statements (the [[08-The-Accounting-Equation#2. The expanded equation — bringing in revenue and expenses|expanded equation]] cleaved in two). The **revenue and expense** accounts (Sales, COGS, General expenses) are transferred to the **Trading & P&L account**; the remaining balances form the **balance sheet**.

### Step 4 — Trading & P&L account (T-format)

The Indian **T-format** runs in two stages: the **Trading** section finds **gross profit** (Sales − COGS), then that gross profit is *brought down* into the **P&L** section, where remaining expenses are deducted to give **net profit**.

**Trading and Profit & Loss Account**

| Dr | ₹ | Cr | ₹ |
|---|---:|---|---:|
| To Cost of goods sold | 350 | By Sales | 550 |
| **To Gross profit c/d** | **200** | | |
| **Total** | **550** | **Total** | **550** |
| To General expenses | 80 | **By Gross profit b/d** | **200** |
| **To Net profit** | **120** | | |
| **Total** | **200** | **Total** | **200** |

> [!note] Reading the T-format
> The **gross profit ₹200** is the plug that balances the Trading (top) section, carried *down* (`c/d`) and brought *down* (`b/d`) into the P&L (bottom) section as the opening credit. General expenses of ₹80 are then charged against it, leaving **net profit ₹120**. The same result in **vertical form**: Sales 550 − COGS 350 = **Gross profit 200**; − General expenses 80 = **Net profit 120**.

### Step 5 — Balance Sheet

The net profit and the remaining trial-balance items go to the balance sheet: **debit balances to the asset side, credit balances to the liabilities & equity side.**

| Assets | ₹ | Liabilities & Equity | ₹ |
|---|---:|---|---:|
| Plant | 1,000 | Capital | 1,000 |
| Inventory (closing stock) | 250 | Net profit | 120 |
| Accounts Receivable | 100 | Loan | 500 |
| Cash | 370 | Accounts Payable | 100 |
| **Total** | **1,720** | **Total** | **1,720** |

> [!tip] The link between the two statements
> The **₹120 net profit** from the P&L is added into equity on the balance sheet. The accounting equation holds exactly: **A (1,720) = L (500 loan + 100 payables = 600) + E (1,000 capital + 120 profit = 1,120).** That single carry-over is the articulation taught in [[02-The-Annual-Report-and-Three-Statements#2. How the three statements link (articulation)|how the three statements link]]. [[11-Adjusting-Entries-and-Final-Accounts|Session 6]] inserts the **adjusting entries** (depreciation, accruals, prepayments) that sit *between* the trial balance and these statements.

---

## Common mistakes (Recording & Trial Balance)

> [!warning] Gotchas
> - **Only recording one leg of a sale** — every sale needs *both* the revenue entry (row 6) and the cost-of-goods-sold entry (row 7).
> - **Putting closing stock on the credit side of the trial balance** — inventory is an **asset**; its balance is a **debit** (here ₹250).
> - **Confusing "debit = decrease"** — a debit *increases* assets and expenses; it *decreases* liabilities, equity and revenue.
> - **Netting debtors and creditors** — Accounts Receivable (₹100 Dr) and Accounts Payable (₹100 Cr) are *separate* accounts on opposite columns; never merge them.
> - **Forgetting balance b/d** — the c/d figure must reopen as b/d on the *opposite* side, or next period starts from zero by accident.
> - **Assuming a balanced trial balance = correct books** — it only catches arithmetic slips, not wrong-account or omitted-entry errors.

---

## Key takeaways

- Session 5 drills the cycle end-to-end: **journalise → post to ledger → balance off → trial balance → Trading & P&L → balance sheet.**
- Every entry follows the **three-step procedure** (which accounts? debit or credit? how much?); **Total Dr = Total Cr** always, and **DEAD CLIC** gives the direction for each account type.
- The **T-format Trading & P&L** finds **gross profit** first (Sales − COGS = 200), then charges remaining expenses for **net profit** (200 − 80 = 120).
- **Balance c/d** closes an account (plug on the lighter side); **balance b/d** reopens it on the opposite side.
- The ten-transaction case ties out: **trial balance ₹2,150 each side**, net profit **₹120**, balance sheet **₹1,720 each side**.
- A sale is **two** entries (revenue + cost); the leftover **inventory balance is closing stock**, the seed of the Trading Account.

---

**Related:** [[09-The-Accounting-Cycle-Recording-Transactions]] · [[08-The-Accounting-Equation]] · [[11-Adjusting-Entries-and-Final-Accounts]] · [[05-Income-Statement-PandL]] · [[07-Conceptual-Framework-and-Core-Concepts]] · [[90-Master-Formula-Sheet]] · [[91-Exam-Question-Bank]]
