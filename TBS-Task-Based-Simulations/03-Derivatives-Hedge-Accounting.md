# 📈 TBS #3: Derivatives & Hedge Accounting

> **Frequency: ⭐⭐⭐⭐ (High)**
> **TBS Types: Journal Entry, Option List**
> **ASC Reference: ASC 815 (Derivatives and Hedging)**

---

## 🎯 Why This is Heavily Tested

Derivatives and hedge accounting combine **financial instruments knowledge** with **complex journal entry skills**. The BAR TBS loves this because:
- Students fear it the most (high discrimination power)
- It requires understanding of fair value changes AND where they go
- Journal entries differ dramatically based on hedge designation
- It intersects with risk management (BAR 1) and financial reporting (BAR 4)

### ✅ The Big Picture
A derivative is a financial instrument whose value is **derived** from something else (an underlying). Hedge accounting lets you match the timing of gains/losses on the derivative with the item being hedged.

---

## 📚 What is a Derivative? The Basics

### ✅ Mnemonic: **"DULL"** — Four characteristics of a derivative

| Letter | Characteristic |
|--------|---------------|
| **D**erived value | Value changes based on an underlying (price, rate, index) |
| **U**nderlying + Notional | Has an underlying variable AND a notional amount |
| **L**ittle or no initial investment | Requires little or no initial net investment |
| **L**iquid settlement | Can be settled net (doesn't require physical delivery) |

### Common Derivatives:
- **Forward contracts** — Agreement to buy/sell at a future date at a set price
- **Futures contracts** — Standardized forwards traded on exchanges
- **Options** — Right (not obligation) to buy (call) or sell (put)
- **Swaps** — Exchange one set of cash flows for another (interest rate swaps)

---

## 🔥 The Three Types of Hedges

### ✅ Mnemonic: **"FCC"** = Fair value, Cash flow, Currency (Foreign operations)

### 1. Fair Value Hedge
**What it hedges:** Changes in fair value of a recognized asset/liability or firm commitment

**Common Examples:**
- Fixed-rate debt (hedging against interest rate changes)
- Inventory (hedging against commodity price changes)
- Firm purchase/sale commitment

**Where gains/losses go:**
```
Derivative gain/loss  →  INCOME (current period)
Hedged item gain/loss →  INCOME (current period)  ← ADJUSTED to reflect hedge!
```

### ✅ Key Point: BOTH go to income → they OFFSET each other → net P&L impact ≈ 0

---

### 2. Cash Flow Hedge
**What it hedges:** Variability in future cash flows of a recognized asset/liability or forecasted transaction

**Common Examples:**
- Variable-rate debt (hedging against interest rate changes)
- Forecasted purchase of inventory
- Forecasted sale of product in foreign currency

**Where gains/losses go:**
```
Derivative gain/loss (EFFECTIVE portion)    →  OCI (Other Comprehensive Income)
Derivative gain/loss (INEFFECTIVE portion)  →  INCOME (current period)
```

**When reclassified from OCI to Income:**
- When the hedged transaction affects earnings (e.g., inventory is sold, interest is paid)

### ✅ Key Point: Effective portion "parks" in OCI until the hedged item hits income

---

### 3. Net Investment Hedge (Foreign Operations)
**What it hedges:** Currency risk on net investment in foreign subsidiary

**Where gains/losses go:**
```
Derivative gain/loss (EFFECTIVE portion)    →  CTA (Cumulative Translation Adjustment in OCI)
Derivative gain/loss (INEFFECTIVE portion)  →  INCOME (current period)
```

### ✅ Key Point: Same treatment as cash flow hedge, but parked in CTA within AOCI

---

## 📊 Summary Comparison Table (CRITICAL for TBS)

| Feature | Fair Value Hedge | Cash Flow Hedge | Net Investment Hedge |
|---------|-----------------|-----------------|---------------------|
| **Hedges against** | FV changes | Cash flow variability | Currency on foreign sub |
| **Derivative G/L** | Income | OCI (effective) / Income (ineffective) | CTA in OCI / Income |
| **Hedged item** | Adjusted to FV through Income | No adjustment until reclassified | Translation in CTA |
| **Net income effect** | G/L offset in income | Only ineffectiveness in income | Only ineffectiveness in income |
| **OCI impact** | None | Effective portion in OCI | Effective portion in CTA |

### ✅ Mnemonic: **"Fair = Full Income; Cash = OCI Cave; Net = CTA Nest"**

---

## 🔥 TBS Walkthrough: Fair Value Hedge Simulation

### Scenario:
**AlphaCo holds $1,000,000 of fixed-rate bonds (available-for-sale). To hedge against interest rate risk, AlphaCo enters an interest rate swap on January 1, Year 1.**

- Hedged item: AFS bonds, carrying value $1,000,000
- Derivative: Interest rate swap (designated as fair value hedge)
- At June 30, Year 1:
  - Fair value of bonds DECREASED by $40,000 (due to rising rates)
  - Fair value of swap INCREASED by $38,000 (effective hedge)
- Hedge effectiveness: $38,000 / $40,000 = 95%

### Journal Entries at June 30, Year 1:

**Record the derivative (swap) at fair value:**
```
Dr. Derivative Asset — Swap              38,000
    Cr. Gain on Hedge (Income)                  38,000
```

**Adjust the hedged item (bonds) for hedged risk:**
```
Dr. Loss on Hedged Item (Income)          40,000
    Cr. AFS Bond Investment                      40,000
```

**Net P&L Impact:**
- Gain on derivative: +$38,000
- Loss on hedged item: −$40,000
- **Net loss = ($2,000)** ← This is the hedge INEFFECTIVENESS

### ✅ Key Insight: In a fair value hedge, BOTH sides go through income. The ineffective portion ($2,000) flows through to net income. A perfect hedge would be $0 net.

---

## 🔥 TBS Walkthrough: Cash Flow Hedge Simulation

### Scenario:
**BetaCo forecasts purchasing 10,000 barrels of oil in 6 months. To hedge price risk, BetaCo enters a forward contract on July 1, Year 1.**

- Forecasted purchase: 10,000 barrels × $80/barrel = $800,000
- Forward contract: Lock in price at $80/barrel
- At December 31, Year 1 (settlement date):
  - Spot price of oil: $88/barrel
  - Forward contract gain: $80,000 (10,000 × $8)
  - All gain is in the effective portion

### Journal Entries:

**At December 31, Year 1 — Record derivative gain:**
```
Dr. Derivative Asset — Forward            80,000
    Cr. OCI — Unrealized Gain on Hedge          80,000
```
(Effective portion goes to OCI!)

**Settlement of forward + Purchase of oil:**
```
Dr. Cash                                   80,000
    Cr. Derivative Asset — Forward               80,000

Dr. Oil Inventory                         880,000
    Cr. Cash                                    880,000
```

**Reclassify OCI to adjust inventory basis:**
```
Dr. OCI — Unrealized Gain on Hedge         80,000
    Cr. Oil Inventory                            80,000
```

**Net effect: Oil inventory recorded at $800,000** (the hedged price!)

**When inventory is sold:**
- COGS reflects the hedged cost ($800,000), not the spot price ($880,000)
- The hedge effectively locked in the purchase price

### ✅ Key Insight: The OCI gain reclassifies to reduce the inventory cost. COGS in the future period will be at the hedged rate.

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Mixing hedge types | Put cash flow hedge G/L in income | Effective portion of CF hedge → **OCI** |
| Ineffectiveness | Ignore it | ALWAYS put ineffective portion in **income** |
| Speculative derivatives | Treat like a hedge | No designation = ALL G/L through **income** |
| Forgetting to adjust hedged item | Only record derivative | Fair value hedge requires adjusting the **hedged item too** |
| Cash flow hedge reclassification | Leave gains in OCI forever | Reclassify when hedged transaction **affects earnings** |
| Documentation requirement | Assume any derivative qualifies | Must formally **designate and document** hedge relationship |
| Hedge discontinuation | Continue hedge accounting | If hedge stops qualifying, **prospectively** stop hedge accounting |

---

## 📝 Practice Scenario — Try This!

**GammaCo has a $5,000,000 variable-rate bank loan (LIBOR + 2%). To hedge against rising interest rates, GammaCo enters an interest rate swap to receive variable/pay fixed.**

- Swap designated as **cash flow hedge** on January 1, Year 1
- Year 1 results:
  - Variable rates rose, causing swap fair value to increase by $120,000
  - Hedge is 100% effective
- Year 2 results:
  - Variable rates fell, causing swap fair value to decrease by $45,000
  - Hedge is 90% effective (effective portion = $40,500)

**Record the journal entries for Year 1 and Year 2.**

<details>
<summary>💡 Click for Solution</summary>

**Year 1 (100% effective):**
```
Dr. Derivative Asset — Swap              120,000
    Cr. OCI — Gain on Cash Flow Hedge          120,000
```
(All effective, so all goes to OCI)

As GammaCo makes interest payments during Year 1, it reclassifies from OCI to reduce interest expense:
```
Dr. OCI — Gain on Cash Flow Hedge         XXX
    Cr. Interest Expense                         XXX
```
(Amount reclassified = the actual savings from the hedged rate vs. actual rate)

**Year 2 (90% effective):**
Total swap value decrease: $45,000
- Effective portion (90%): $40,500 → OCI
- Ineffective portion (10%): $4,500 → Income

```
Dr. OCI — Loss on Cash Flow Hedge         40,500
Dr. Loss on Hedge Ineffectiveness           4,500
    Cr. Derivative Asset — Swap                  45,000
```

</details>

---

## 🧠 Key Rules to Memorize

| Rule | Detail |
|------|--------|
| Derivatives always at | **Fair value** on balance sheet |
| No hedge designation | ALL G/L → **Income** |
| Fair value hedge | Both derivative AND hedged item G/L → **Income** |
| Cash flow hedge (effective) | Derivative G/L → **OCI** |
| Cash flow hedge (ineffective) | → **Income** |
| When to reclassify OCI | When hedged transaction **affects earnings** |
| Hedge documentation | Required at **inception** for hedge accounting |
| Hedge effectiveness testing | Required to continue hedge accounting |

### ✅ Final Mnemonic: **"If it's FAIR, it's in INCOME. If it's CASH, it's in the OCI STASH."**

---

> 💡 **Top Ranker Tip**: The TBS will often describe a scenario and ask you WHERE to record the gain or loss. Before calculating anything, identify the hedge type. Fair value = income. Cash flow = OCI. This classification alone can earn you multiple points.
