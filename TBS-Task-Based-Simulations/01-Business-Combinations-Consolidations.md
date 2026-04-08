# 🏢 TBS #1: Business Combinations & Consolidations

> **Frequency: ⭐⭐⭐⭐⭐ (Highest)**
> **TBS Types: Journal Entry, Numeric Entry**
> **ASC Reference: ASC 805 (Business Combinations), ASC 810 (Consolidation)**

---

## 🎯 Why This is #1 Most Tested

Business combinations and consolidations are the **single most heavily tested TBS topic** on the BAR exam. The AICPA loves this topic because it tests:
- Complex journal entry skills (acquisition method)
- Fair value measurement (ASC 820)
- Goodwill calculation and impairment
- Intercompany elimination entries
- Noncontrolling interest calculations

### ✅ The Big Picture (What You MUST Know)
When one company acquires another, you must:
1. Record the acquisition at **fair value** (not book value!)
2. Recognize **goodwill** (or a bargain purchase gain)
3. Eliminate **intercompany transactions** in consolidation
4. Calculate **noncontrolling interest** (if less than 100% acquired)
5. Prepare **consolidated financial statements**

---

## 📚 The Acquisition Method — Step by Step

### ✅ Mnemonic: **"FANG-IC"** = Fair value → Allocate → Net assets → Goodwill → Intercompany → Consolidate

### Step 1: Identify the FAIR VALUE of Consideration Transferred
**What counts as consideration?**
- Cash paid
- Fair value of stock issued
- Fair value of assets transferred
- Fair value of liabilities assumed
- **Contingent consideration** (earnouts) at fair value on acquisition date

**What does NOT count?**
- ❌ Acquisition-related costs (legal fees, due diligence, investment banking fees)
- These are **EXPENSED** as incurred (Period cost, NOT part of goodwill!)
- ❌ Stock issuance costs → reduce APIC (not expensed)

### ✅ Mnemonic: **"ACE" — Acquisition Costs are Expensed**

---

### Step 2: ALLOCATE Fair Value to Identifiable Net Assets

**Net Assets Acquired = Fair Value of Assets − Fair Value of Liabilities**

You must revalue ALL identifiable assets and liabilities to **fair value**, including:

| Asset/Liability | Key Point |
|----------------|-----------|
| Tangible assets (PP&E, inventory) | Fair value, not book value |
| Intangible assets (patents, trademarks, customer lists) | Recognize EVEN if not on target's books |
| In-process R&D | Recognize at fair value as an intangible |
| Operating leases (ROU assets) | Remeasured at acquisition date |
| Contingent liabilities | Recognized at fair value if probable |
| Deferred tax assets/liabilities | Adjusted for fair value step-ups |

### ✅ Key Trap: Identifiable intangibles that the target never recorded
- Customer relationships, trade names, order backlogs — these are often OFF the target's balance sheet
- You MUST recognize them at fair value in the acquisition

---

### Step 3: Calculate GOODWILL (or Bargain Purchase Gain)

```
Goodwill = Consideration Transferred + NCI + Previously Held Equity Interest
           − Fair Value of Identifiable Net Assets Acquired
```

**If the result is POSITIVE → Goodwill (an asset)**
- Not amortized (indefinite life)
- Tested for impairment at least annually (ASC 350)

**If the result is NEGATIVE → Bargain Purchase Gain**
- ✅ First: Re-examine ALL assets and liabilities (did you miss something?)
- Then: Recognize the gain in **income** (extraordinary? NO — just regular income)

### ✅ Mnemonic: **"Good Pizza Brings Burps"**
- **G**oodwill = **P**rice paid minus
- **B**ook (fair) value = potential
- **B**argain if negative

---

### Step 4: Noncontrolling Interest (NCI)

When the acquirer buys **less than 100%**, the remaining ownership = NCI

**Two measurement options (election at acquisition date):**

| Method | NCI Measured At | Goodwill Impact |
|--------|----------------|-----------------|
| **Fair Value Method** (Full Goodwill) | Fair value of NCI | Higher goodwill (includes NCI's share) |
| **Proportionate Share Method** (Partial Goodwill) | NCI% × Fair value of net assets | Lower goodwill |

### ✅ Key Point: US GAAP allows BOTH methods. IFRS only allows the fair value method.

**Where does NCI appear?**
- Balance Sheet: Reported in **stockholders' equity** (separate from parent's equity)
- Income Statement: Net income is **split** between parent and NCI

**NCI on the Income Statement:**
```
Consolidated Net Income = Parent's share + NCI's share
NCI's share = Consolidated Net Income × NCI%
```

---

### Step 5: Intercompany Eliminations

In consolidation, you must **eliminate ALL intercompany transactions**:

| Transaction | Elimination Entry |
|-------------|-------------------|
| Intercompany sales/purchases | Eliminate Sales & COGS; remove unrealized profit in inventory |
| Intercompany loan | Eliminate receivable/payable and interest revenue/expense |
| Intercompany dividends | Eliminate dividend income against dividends paid |
| Intercompany fixed asset sale | Eliminate gain/loss; adjust depreciation |
| Investment in subsidiary | Eliminate Investment account against subsidiary's equity |

### ✅ The Basic Elimination Entry (CEADIP)

```
Dr. Common Stock (Subsidiary)                    XXX
Dr. APIC (Subsidiary)                            XXX  
Dr. Retained Earnings (Subsidiary)               XXX
Dr. Goodwill                                     XXX
    Cr. Investment in Subsidiary                      XXX
    Cr. Noncontrolling Interest                       XXX
```

### ✅ Mnemonic: **"CEADIP"** = Common stock, Equity (APIC), Adjusted RE → Debit; Investment, Partially-owned (NCI) → Credit

---

## 🔥 TBS Walkthrough: Sample Business Combination Simulation

### Scenario:
**ParentCo acquires 80% of TargetCo on January 1, Year 1**

Given information:
- Cash paid: **$800,000**
- TargetCo's book value of net assets: **$700,000**
- Fair value of TargetCo's identifiable net assets: **$900,000**
- Fair value of NCI (20%): **$190,000**
- Acquisition costs paid to lawyers: **$25,000**
- Fair value adjustments:
  - Equipment understated by $100,000 (remaining life: 10 years)
  - Customer list not on books: $80,000 (life: 5 years)
  - Inventory understated by $20,000 (sold within Year 1)

### Step-by-Step Solution:

**1. Consideration = $800,000** (cash only)
- ❌ The $25,000 acquisition cost is EXPENSED, not added to consideration

**2. Fair Value of Identifiable Net Assets = $900,000**

**3. Goodwill Calculation:**
```
Goodwill = Consideration + NCI − FV of Net Assets
Goodwill = $800,000 + $190,000 − $900,000
Goodwill = $90,000
```

**4. Acquisition Journal Entry:**
```
Dr. Identifiable Net Assets (at FV)    900,000
Dr. Goodwill                            90,000
    Cr. Cash                                   800,000
    Cr. Noncontrolling Interest                190,000
```

**5. Expense the Acquisition Costs:**
```
Dr. Acquisition Expense                 25,000
    Cr. Cash                                    25,000
```

**6. Year 1 Consolidation Adjustments:**
- Equipment step-up amortization: $100,000 ÷ 10 = **$10,000/year**
- Customer list amortization: $80,000 ÷ 5 = **$16,000/year**
- Inventory step-up: **$20,000** charged to COGS (sold in Year 1)

```
Dr. Depreciation Expense               10,000
    Cr. Equipment                              10,000

Dr. Amortization Expense               16,000
    Cr. Customer List                          16,000

Dr. Cost of Goods Sold                  20,000
    Cr. Inventory                              20,000
```

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Acquisition costs | Add to goodwill | **EXPENSE** as incurred |
| Stock issuance costs | Expense them | Reduce **APIC** |
| Contingent consideration | Ignore it | Include at **fair value** on Day 1 |
| Pre-existing relationships | Ignore them | Settle and recognize gain/loss **separately** |
| Measurement period adjustments | Adjust current year P&L | Adjust **goodwill** (within 1 year of acquisition) |
| Bargain purchase | Record as goodwill | Recognize as **gain in income** |
| NCI in year-end consolidation | Forget to allocate income | Allocate proportionate share of **subsidiary income** to NCI |

---

## 📝 Practice Scenario — Try This!

**MegaCorp acquires 70% of SmallCo for $2,100,000 on July 1, Year 1.**

- SmallCo's book value of equity: $2,500,000
- Fair value adjustments needed:
  - Land: FV exceeds BV by $200,000
  - Patent (not recorded): FV = $150,000, useful life 10 years
  - Warranty liability understated by $50,000
- Fair value of NCI (30%): $880,000
- SmallCo reports net income of $400,000 for Year 1 (earned evenly)
- SmallCo pays dividends of $100,000 on December 1

**Calculate:**
1. Fair value of SmallCo's identifiable net assets
2. Goodwill
3. NCI's share of net income for Year 1
4. Consolidation entries needed at December 31, Year 1

<details>
<summary>💡 Click for Solution</summary>

**1. FV of Identifiable Net Assets:**
```
Book value of equity:          $2,500,000
+ Land step-up:                  $200,000
+ Patent:                        $150,000
− Warranty liability:            ($50,000)
= FV of Net Assets:           $2,800,000
```

**2. Goodwill:**
```
Consideration:                 $2,100,000
+ NCI Fair Value:                $880,000
− FV of Net Assets:           ($2,800,000)
= Goodwill:                     $180,000
```

**3. NCI's Share of Net Income:**
- SmallCo earned $400,000 for full year, but acquired July 1
- Post-acquisition income: $400,000 × 6/12 = $200,000
- Adjustments: Patent amortization = $150,000 ÷ 10 × 6/12 = ($7,500)
- Adjusted post-acquisition income: $200,000 − $7,500 = $192,500
- NCI share (30%): $192,500 × 30% = **$57,750**

**4. Key Consolidation Entries:**
- Eliminate Investment vs. Subsidiary equity
- Allocate fair value step-ups
- Amortize patent: $7,500 (6 months)
- Eliminate intercompany dividends: Parent share = $100,000 × 70% = $70,000
- Allocate NCI share of income: $57,750

</details>

---

## 🧠 Key Formulas to Memorize

| Formula | Expression |
|---------|-----------|
| Goodwill | Consideration + NCI + Previously Held Interest − FV of Net Assets |
| NCI (Fair Value Method) | Fair value of NCI on acquisition date |
| NCI (Proportionate Method) | NCI% × FV of Net Assets |
| NCI Income Allocation | Consolidated Net Income × NCI% |
| Bargain Purchase Gain | FV of Net Assets − (Consideration + NCI) |
| Measurement Period | Up to **1 year** from acquisition date |

---

> 💡 **Top Ranker Tip**: On TBS, they LOVE testing the acquisition cost trap. If you see legal fees, advisory fees, or due diligence costs — **EXPENSE THEM**. This single rule can earn you 2-3 points on a simulation.
