# 🏛️ TBS #6: Government Fund Accounting & Reconciliation

> **Frequency: ⭐⭐⭐ (Moderate-High)**
> **TBS Types: Journal Entry, Document Review Simulation (DRS)**
> **ASC Reference: GASB Standards (primarily GASB 34)**

---

## 🎯 Why This is Tested on BAR TBS

Government accounting is a unique beast — completely different measurement focus and basis of accounting compared to commercial entities. TBS loves this area because:
- Fund-to-government-wide reconciliation is a perfect DRS scenario
- Journal entries in governmental funds differ from what students are used to
- Modified accrual vs. full accrual creates natural "error detection" opportunities
- It tests deep conceptual understanding, not just memorization

### ✅ The Big Picture
Governments use **fund accounting** — money is segregated into different "buckets" (funds) for different purposes. The challenge is that some funds use **modified accrual** while government-wide statements use **full accrual**.

---

## 📊 The Fund Structure — Know Your Funds

### ✅ Mnemonic: **"GoPro FI"** = Governmental, Proprietary, Fiduciary

### Governmental Funds (Modified Accrual)

### ✅ Mnemonic: **"G-DRIP-S"** or **"General + DRIPS"**

| Fund | Purpose | Key Features |
|------|---------|-------------|
| **G**eneral Fund | Main operating fund | Day-to-day operations; largest fund |
| **D**ebt Service Fund | Pay principal & interest on long-term debt | Expenditures for debt payments |
| **R**evenue (Special) Fund | Restricted revenue sources | Earmarked taxes, grants |
| **I**nternal Service Fund | (NOT governmental — this is proprietary!) | — |
| **P**ermanent Fund | Endowments where principal stays intact | Only earnings can be spent |
| **S**pecial Assessment Fund | (Rare) Improvements benefiting specific properties | — |
| **Capital Projects Fund** | Major capital acquisitions/construction | Building roads, schools, etc. |

### ✅ Simplified: The "Big 5" Governmental Funds = **"GRaDS-CP"**
- **G**eneral
- **S**pecial **R**evenue
- **D**ebt **S**ervice
- **C**apital **P**rojects
- **P**ermanent

### Proprietary Funds (Full Accrual — like commercial accounting)

| Fund | Purpose | Analogy |
|------|---------|---------|
| **Enterprise Fund** | Business-like activities serving the public | Water utility, parking garage |
| **Internal Service Fund** | Services to OTHER government departments | IT, motor pool, printing |

### ✅ Mnemonic: **"EI = Enterprise + Internal Service"**

### Fiduciary Funds (Full Accrual — NOT in government-wide statements)

| Fund | Purpose |
|------|---------|
| **Pension Trust Fund** | Employee pension assets |
| **Investment Trust Fund** | External investment pools |
| **Private-Purpose Trust Fund** | Trusts benefiting specific individuals/orgs |
| **Custodial Fund** | Assets held temporarily for others |

### ✅ Mnemonic: **"PIPC"** = Pension, Investment, Private, Custodial

---

## 🔥 Modified Accrual vs. Full Accrual — The Core Difference

### ✅ This is THE most tested concept for government TBS

| Feature | Modified Accrual (Fund Statements) | Full Accrual (Government-Wide) |
|---------|-----------------------------------|-------------------------------|
| **Revenue recognition** | Measurable AND **available** (collected within 60 days) | When **earned** (same as commercial) |
| **Expenditures vs. Expenses** | **Expenditures** (when liability is due/payable) | **Expenses** (when incurred, including depreciation) |
| **Capital assets** | NOT recorded (expenditure when purchased) | Capitalized and depreciated |
| **Long-term debt** | NOT recorded in fund (Other Financing Source) | Recorded as liability |
| **Focus** | Current financial resources | Economic resources |

### ✅ Mnemonic: **"Modified = Money in hand; Full = Full economic picture"**

---

## 📝 The Reconciliation — From Fund to Government-Wide

This is the **#1 tested TBS** in government accounting. You must convert fund financial statements (modified accrual) to government-wide statements (full accrual).

### ✅ Mnemonic: **"ACID-LC"** — Adjustments to Convert from fund to government-wide

| Adjustment | Direction | Explanation |
|------------|-----------|-------------|
| **A**dd capital assets | + Assets, − Expenditures | Capital outlays are expenditures in funds but assets in G-W |
| **C**ompute depreciation | − Assets, + Expenses | Not in fund statements; added in G-W |
| **I**nclude long-term liabilities | + Liabilities | Bonds payable, compensated absences not in funds |
| **D**ebt service adjustments | − Expenditures, + Liabilities | Principal payments reduce debt in G-W, not recorded as expenditure |
| **L**ong-term receivables | + Assets | Property taxes receivable beyond 60 days |
| **C**onvert internal service funds | Adjust | Internal service funds (proprietary) → add to governmental activities |

---

## 🔥 TBS Walkthrough: Fund-to-Government-Wide Reconciliation

### Scenario:
**CityVille reports the following for its General Fund (Year 1):**

| Item | Amount |
|------|--------|
| Total fund balance (ending) | $2,500,000 |
| Capital outlays during the year | $800,000 |
| Accumulated depreciation (beginning) | $3,200,000 |
| Depreciation expense for the year | $400,000 |
| Capital assets (beginning net) | $12,000,000 |
| Bonds payable (beginning) | $5,000,000 |
| New bonds issued | $1,500,000 |
| Principal payments on bonds | $500,000 |
| Accrued interest payable | $125,000 |
| Internal service fund net position | $350,000 |
| Property taxes deferred (not available within 60 days) | $180,000 |
| Compensated absences liability (long-term) | $275,000 |

### Reconciliation: Fund Balance → Net Position

```
General Fund Balance (ending):                           $2,500,000

ADD: Capital assets (net of depreciation)
  Beginning net capital assets:         $12,000,000
  + Capital outlays:                       $800,000
  − Depreciation expense:                ($400,000)
  = Ending net capital assets:                          +$12,400,000

SUBTRACT: Long-term liabilities
  Bonds payable: $5,000,000 + $1,500,000 − $500,000
  = Ending bonds payable:                               −$6,000,000
  Accrued interest payable:                               −$125,000
  Compensated absences:                                   −$275,000

ADD: Deferred revenue (now recognized in full accrual)
  Property taxes deferred:                                 +$180,000

ADD: Internal service fund net position                    +$350,000

───────────────────────────────────────────────────────
Net Position of Governmental Activities:                 $9,030,000
```

### Key Journal-Style Adjustments:

**1. Capitalize assets (reverse expenditure):**
```
Dr. Capital Assets                        800,000
    Cr. Capital Outlay Expenditure               800,000
```

**2. Record depreciation:**
```
Dr. Depreciation Expense                  400,000
    Cr. Accumulated Depreciation                 400,000
```

**3. Record long-term debt (reverse other financing source):**
```
Dr. Other Financing Sources — Bonds      1,500,000
    Cr. Bonds Payable                          1,500,000
```

**4. Reverse principal payment (from expenditure to debt reduction):**
```
Dr. Bonds Payable                         500,000
    Cr. Debt Service Expenditure                 500,000
```

**5. Recognize deferred property taxes:**
```
Dr. Deferred Inflows — Property Taxes     180,000
    Cr. Revenue — Property Taxes                 180,000
```

---

## 📊 Government-Wide Statement Structure

### Two Categories:
1. **Governmental Activities** — Funded by taxes and grants (includes governmental funds + internal service funds)
2. **Business-Type Activities** — Self-funded through user charges (enterprise funds)

### Statement of Net Position (Balance Sheet equivalent):

```
Assets + Deferred Outflows = Liabilities + Deferred Inflows + Net Position
```

**Net Position has THREE components:**
1. **Net Investment in Capital Assets** = Capital assets (net) − related debt
2. **Restricted** = Externally restricted (by law, regulation, or creditors)
3. **Unrestricted** = Everything else

### ✅ Mnemonic: **"NIR-U"** = Net Investment, Restricted, Unrestricted

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Capital assets in fund statements | Record as assets | Record as **expenditures** in governmental funds |
| Long-term debt in fund statements | Record as liability | Record proceeds as **Other Financing Source** |
| Depreciation in fund statements | Include depreciation | **NO depreciation** in governmental fund statements |
| 60-day rule for revenue | Ignore the availability criterion | Revenue must be **available** (collectible within 60 days) |
| Fiduciary funds in G-W statements | Include them | Fiduciary funds are **EXCLUDED** from government-wide |
| Internal service funds | Put with proprietary in G-W | Usually consolidated with **governmental activities** in G-W |
| Encumbrances | Treat as expenditure | Encumbrances = **commitments**, not expenditures (reverse at year end if lapse) |
| Bond premium/discount | Ignore in fund statements | In funds: recognize as Other Financing Source/Use |

---

## 📝 Government Fund Journal Entries — Most Common on TBS

### Property Tax Levy:
```
Dr. Property Taxes Receivable            1,000,000
    Cr. Revenue — Property Taxes               940,000
    Cr. Deferred Inflows — Property Taxes       40,000
    Cr. Allowance for Uncollectible              20,000
```
(Only amount expected to be collected within 60 days = revenue)

### Capital Asset Purchase (General Fund):
```
Dr. Expenditure — Capital Outlay          500,000
    Cr. Cash                                    500,000
```
(NOT Dr. Capital Assets! That's for government-wide statements)

### Bond Issuance (General Fund/Debt Service):
```
Dr. Cash                                1,050,000
    Cr. Other Financing Source — Bond Proceeds 1,000,000
    Cr. Other Financing Source — Premium           50,000
```

### Debt Service Payment:
```
Dr. Expenditure — Principal               200,000
Dr. Expenditure — Interest                  80,000
    Cr. Cash                                    280,000
```

---

## 📝 Practice Scenario — Try This!

**TownCo's General Fund reports the following Year 1 data:**
- Fund balance: $1,200,000
- Capital outlays: $600,000 (equipment with 10-year life)
- Beginning capital assets (net): $5,000,000
- Beginning accumulated depreciation: $1,500,000
- Bonds payable (beginning): $2,000,000
- Principal paid: $200,000
- Property taxes receivable (beyond 60 days): $90,000

**Calculate the Net Position of Governmental Activities.**

<details>
<summary>💡 Click for Solution</summary>

```
Fund Balance:                                    $1,200,000

ADD: Capital assets (net)
  Beginning:                    $5,000,000
  + Capital outlays:              $600,000
  − Depreciation ($600K/10yr):    ($60,000)
  = Ending net assets:                          +$5,540,000

SUBTRACT: Long-term liabilities
  Bonds: $2,000,000 − $200,000:                −$1,800,000

ADD: Deferred revenues now recognized:              +$90,000
                                                ───────────
Net Position:                                    $5,030,000
```

</details>

---

## 🧠 Key Rules to Memorize

| Rule | Application |
|------|-------------|
| Governmental funds | Modified accrual — current financial resources |
| Proprietary funds | Full accrual — economic resources (like commercial) |
| Fiduciary funds | Full accrual but EXCLUDED from government-wide |
| Revenue (modified accrual) | Measurable + Available (60 days) |
| Capital assets | Expenditure in fund; Capitalized in government-wide |
| Long-term debt | OFS in fund; Liability in government-wide |
| Depreciation | NOT in governmental funds; YES in government-wide |
| Internal service funds | Proprietary but reported with governmental activities in G-W |

### ✅ Final Mnemonic: **"Funds use MODIFIED, Government-Wide uses FULL — reconcile the ACID-LC"**

---

> 💡 **Top Ranker Tip**: The reconciliation TBS will give you fund financial statements and ask you to compute the government-wide net position. The most commonly missed adjustments are: (1) adding back capital assets, (2) deducting long-term debt, and (3) recognizing deferred property tax revenue. Hit these three and you'll get most of the partial credit.
