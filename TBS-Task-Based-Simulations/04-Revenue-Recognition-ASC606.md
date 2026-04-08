# 💰 TBS #4: Revenue Recognition — ASC 606

> **Frequency: ⭐⭐⭐⭐ (High)**
> **TBS Types: Document Review Simulation (DRS), Numeric Entry**
> **ASC Reference: ASC 606 (Revenue from Contracts with Customers)**

---

## 🎯 Why This is Heavily Tested

Revenue recognition is the **bread and butter** of financial reporting, and ASC 606's 5-step model is perfectly suited for TBS:
- DRS simulations love giving you a contract and asking you to identify errors
- Numeric entry tests the transaction price allocation and timing
- It intersects with multiple industries (software, construction, licensing)
- Variable consideration and constraints create tricky calculations

### ✅ The Big Picture
ASC 606 replaced all prior industry-specific revenue guidance with ONE universal framework: the 5-Step Model. Every revenue recognition question flows through these 5 steps.

---

## 📚 The 5-Step Model — The Heart of ASC 606

### ✅ Mnemonic: **"I PROMISED SATISFACTION"** → **"I-P-D-A-S"**

| Step | Name | What You Do |
|------|------|-------------|
| **Step 1** | **I**dentify the contract | Verify a valid contract exists |
| **Step 2** | **P**erformance obligations | Identify distinct goods/services promised |
| **Step 3** | **D**etermine transaction price | Calculate total consideration (including variable) |
| **Step 4** | **A**llocate transaction price | Allocate to each performance obligation |
| **Step 5** | **S**atisfy performance obligations | Recognize revenue when/as obligations are satisfied |

---

## Step 1: Identify the Contract

### ✅ Mnemonic: **"CAPA-C"** — Five criteria for a valid contract

| Criteria | Description |
|----------|-------------|
| **C**ommercial substance | Transaction has economic value |
| **A**pproval | Both parties have approved the contract |
| **P**ayment terms | Payment terms are identifiable |
| **A**bility to identify rights | Each party's rights are identifiable |
| **C**ollectibility | Collection is probable |

**If ALL 5 are NOT met** → Do not recognize revenue. Recognize cash received as a liability until criteria are met or contract is terminated.

### Contract Modifications:
- **Treated as a separate contract** if: (1) additional distinct goods/services AND (2) price reflects standalone selling price
- **Treated as modification of existing contract** if: above conditions not met → either prospective or cumulative catch-up adjustment

---

## Step 2: Identify Performance Obligations

A performance obligation is a promise to transfer a **distinct** good or service.

### ✅ Mnemonic: **"CBD"** — Capable, Benefit, Distinct

A good/service is **distinct** if BOTH conditions are met:
1. **Capable of being distinct**: Customer can benefit from it on its own (or with readily available resources)
2. **Separately identifiable**: The promise is distinct within the context of the contract (not highly interrelated/integrated)

### Common Judgment Calls:

| Scenario | # of Performance Obligations |
|----------|------------------------------|
| Software license + installation (routine) | **2** (each is distinct) |
| Software license + significant customization | **1** (highly integrated) |
| Product + standard warranty | **1** (assurance warranty = not separate) |
| Product + extended warranty | **2** (service warranty = separate PO) |
| Equipment + maintenance contract | **2** (each distinct) |

### ✅ Key Distinction: Assurance vs. Service Warranty
- **Assurance warranty** (product works as promised) → NOT a separate PO (accrue as expense)
- **Service warranty** (additional coverage beyond assurance) → SEPARATE PO (defer revenue)

---

## Step 3: Determine Transaction Price

### ✅ Mnemonic: **"FVSCN"** = **"Five Villains Steal Cash Nightly"**

| Component | Description |
|-----------|-------------|
| **F**ixed consideration | Stated contract price |
| **V**ariable consideration | Bonuses, penalties, discounts, rebates, refunds |
| **S**ignificant financing component | Time value of money if > 1 year |
| **C**onsideration payable to customer | Coupons, vouchers, credits given to buyer |
| **N**oncash consideration | Goods/services received as payment (at FV) |

### Variable Consideration — The Constraint:

**Two estimation methods:**
1. **Expected value** — Probability-weighted sum of possible outcomes (best when many outcomes)
2. **Most likely amount** — Single most likely outcome (best when binary: bonus or no bonus)

**The CONSTRAINT**: Only include variable consideration to the extent it is **probable** that a **significant reversal** will NOT occur.

### ✅ Mnemonic: **"Don't count your chickens before they hatch"**
- Be conservative with variable consideration
- Include only the amount you're CONFIDENT won't be reversed

---

## Step 4: Allocate Transaction Price

**Allocate based on relative Standalone Selling Prices (SSP)**

### How to determine SSP (in order of preference):
1. **Observable price** — What you actually charge when sold separately
2. **Adjusted market assessment** — What competitors charge for similar items
3. **Expected cost + margin** — Your cost + reasonable profit margin
4. **Residual approach** — Only if SSP is highly variable/uncertain (total price minus known SSPs)

### Allocation Formula:
```
Allocation to PO = (SSP of that PO ÷ Total SSP of all POs) × Transaction Price
```

### ✅ Example:
- Software license SSP: $60,000
- Training SSP: $15,000
- Maintenance (2 yr) SSP: $25,000
- Total SSP: $100,000
- Contract price: $80,000

Allocations:
- Software: ($60,000 / $100,000) × $80,000 = **$48,000**
- Training: ($15,000 / $100,000) × $80,000 = **$12,000**
- Maintenance: ($25,000 / $100,000) × $80,000 = **$20,000**

---

## Step 5: Recognize Revenue

### Two patterns:

**Over Time** — if ANY of these criteria are met:
1. Customer simultaneously receives and consumes benefits (e.g., cleaning service)
2. Entity's performance creates/enhances an asset the customer controls (e.g., building on customer's land)
3. No alternative use + right to payment for performance to date (e.g., custom software)

**Point in Time** — if NONE of the above are met. Recognize when control transfers.

### ✅ Mnemonic for Over-Time Criteria: **"SCA"** = Simultaneous, Creates/Controls, Alternative-use-None

### Measuring Progress (Over Time):
- **Output method** — Units delivered, milestones, surveys of work performed
- **Input method** — Costs incurred ÷ Total expected costs (most common for TBS!)

```
Revenue Recognized = % Complete × Total Transaction Price
% Complete = Costs Incurred to Date ÷ Total Estimated Costs
```

---

## 🔥 TBS Walkthrough: Multi-Element Arrangement

### Scenario:
**TechCo enters a 3-year contract with ClientCo on January 1, Year 1:**

- Software license (perpetual): delivered on Day 1
- Implementation services: completed over 3 months (Jan-Mar Year 1)
- 3-year maintenance and support: provided evenly over 36 months
- Total contract price: **$450,000**
- Standalone selling prices: Software $280,000, Implementation $70,000, Maintenance $150,000
- Total SSP: $500,000

### Step 1: Contract is valid ✓ (all CAPA-C criteria met)

### Step 2: Three performance obligations
1. Software license (distinct — can be used without implementation)
2. Implementation services (distinct — routine, not significant customization)
3. Maintenance & support (distinct — separate service warranty)

### Step 3: Transaction price = $450,000

### Step 4: Allocate based on relative SSP
```
Software:       ($280,000 / $500,000) × $450,000 = $252,000
Implementation: ($70,000 / $500,000) × $450,000  = $63,000
Maintenance:    ($150,000 / $500,000) × $450,000  = $135,000
Total:                                              $450,000 ✓
```

### Step 5: Revenue Recognition Pattern
- **Software license**: Point in time (control transfers on delivery) → **$252,000 on Day 1**
- **Implementation**: Over time (customer benefits as work performed) → **$63,000 over 3 months**
- **Maintenance**: Over time (customer consumes simultaneously) → **$135,000 over 36 months ($3,750/month)**

### Year 1 Revenue Summary:
```
Software:       $252,000 (Day 1)
Implementation: $63,000 (Jan-Mar)
Maintenance:    $135,000 × 12/36 = $45,000
                ──────────
Year 1 Total:   $360,000
```

### Key Journal Entry (Day 1):
```
Dr. Accounts Receivable (or Cash)         450,000
    Cr. Revenue — Software License              252,000
    Cr. Deferred Revenue — Implementation        63,000
    Cr. Deferred Revenue — Maintenance          135,000
```

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Assurance vs. service warranty | Treat assurance warranty as separate PO | Assurance warranty → **accrue expense**, NOT separate revenue |
| Variable consideration | Include full estimated amount | Apply the **constraint** — only include probable amounts |
| Significant financing | Ignore time value of money | If payment > 1 year out, **adjust** for financing component |
| Contract costs | Expense all costs | Costs to obtain (commissions) → **capitalize** if > 1 year; amortize |
| Bill-and-hold | Don't recognize until delivery | Can recognize at billing if customer requests arrangement + criteria met |
| Principal vs. agent | Recognize gross revenue | Agent → recognize only **net** (commission), not gross |
| Right of return | Recognize full revenue | Reduce revenue by **expected returns** + create refund liability |
| License (right to access vs. use) | Treat all licenses same | Right to access = over time; Right to use = point in time |

---

## 📝 Practice Scenario — Try This!

**ConstructCo enters a $2,000,000 contract to build a warehouse on the customer's land.**

- Contract is a single performance obligation (customer controls asset as it's built)
- Revenue recognized over time using input method (cost-to-cost)
- Year 1: Costs incurred $600,000; Total estimated cost $1,500,000
- Year 2: Additional costs $500,000; Total estimated cost revised to $1,600,000
- Year 3: Additional costs $500,000; Project complete

**Calculate revenue recognized in each year.**

<details>
<summary>💡 Click for Solution</summary>

**Year 1:**
```
% Complete = $600,000 / $1,500,000 = 40%
Revenue = 40% × $2,000,000 = $800,000
```

**Year 2:**
```
Cumulative costs = $600,000 + $500,000 = $1,100,000
% Complete = $1,100,000 / $1,600,000 = 68.75%
Cumulative revenue = 68.75% × $2,000,000 = $1,375,000
Year 2 revenue = $1,375,000 − $800,000 = $575,000
```

**Year 3:**
```
Cumulative costs = $1,100,000 + $500,000 = $1,600,000
% Complete = $1,600,000 / $1,600,000 = 100%
Cumulative revenue = 100% × $2,000,000 = $2,000,000
Year 3 revenue = $2,000,000 − $1,375,000 = $625,000
```

**Summary:**
| Year | Revenue | Costs | Gross Profit |
|------|---------|-------|-------------|
| 1 | $800,000 | $600,000 | $200,000 |
| 2 | $575,000 | $500,000 | $75,000 |
| 3 | $625,000 | $500,000 | $125,000 |
| **Total** | **$2,000,000** | **$1,600,000** | **$400,000** |

</details>

---

## 🧠 Key Formulas to Memorize

| Formula | Expression |
|---------|-----------|
| SSP Allocation | (Individual SSP ÷ Total SSP) × Transaction Price |
| % Completion (Input) | Costs to Date ÷ Total Estimated Costs |
| Revenue (Over Time) | % Complete × Total Transaction Price |
| Cumulative Catch-Up | Current cumulative revenue − Previously recognized revenue |
| Expected Value | Σ(Probability × Amount) for each possible outcome |
| Loss Contract | Recognize ENTIRE estimated loss immediately |

### ✅ Final Mnemonic: **"I-P-D-A-S: I Promise to Deliver And Satisfy"**

---

> 💡 **Top Ranker Tip**: In DRS simulations, they'll give you a revenue memo with errors. The most common errors are: (1) recognizing all revenue at a single point when it should be over time, (2) not separating distinct performance obligations, and (3) ignoring variable consideration constraints. Look for these FIRST.
