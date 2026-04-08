# 🏗️ TBS #2: Lease Accounting — Lessor Perspective

> **Frequency: ⭐⭐⭐⭐⭐ (Very High)**
> **TBS Types: Numeric Entry, Journal Entry**
> **ASC Reference: ASC 842 (Leases)**

---

## 🎯 Why This is Heavily Tested

The BAR exam **focuses on the LESSOR side** of lease accounting (FAR covers the lessee side). This is because:
- Lessor classification requires deeper analytical thinking
- Revenue recognition intersects with ASC 606
- The math (present value calculations, profit recognition) is TBS-friendly
- It tests both **Application** and **Analysis** skill levels

### ✅ The Big Picture
As a LESSOR, you must:
1. **Classify** the lease (Sales-type, Direct Financing, or Operating)
2. **Record** the appropriate journal entries
3. **Recognize revenue/income** using the correct pattern

---

## 📊 Lessor Lease Classification — The Decision Tree

### ✅ Mnemonic: **"OWNS-IT"** — If ANY ONE of these is met → NOT an operating lease

| Test | Criteria |
|------|----------|
| **O**wnership transfer | Title transfers to lessee by end of lease |
| **W**ritten purchase option | Lessee has a purchase option reasonably certain to exercise |
| **N**inety percent test | PV of lease payments ≥ 90% of asset's fair value |
| **S**eventy-five percent test | Lease term ≥ 75% of asset's economic life |
| **I**ndividualized asset | Asset is so specialized only the lessee can use it (no alternative use) |

### After OWNS-IT, Classify Further:

```
Does the lease meet ANY of the OWNS-IT criteria?
├── NO → OPERATING LEASE
└── YES → Does the lease meet BOTH conditions below?
         (1) PV of payments + residual guarantee ≈ FV of asset (substantially all)
         (2) No significant collectibility concerns
         ├── YES → Is there a manufacturer/dealer profit?
         │         ├── YES → SALES-TYPE LEASE
         │         └── NO → DIRECT FINANCING LEASE
         └── NO → OPERATING LEASE (despite meeting OWNS-IT!)
```

### ✅ Critical Distinction:

| Lease Type | Day 1 Profit Recognition | Interest Income Pattern |
|------------|-------------------------|------------------------|
| **Sales-type** | Recognize profit/loss IMMEDIATELY at inception | Yes, effective interest method |
| **Direct financing** | NO Day 1 profit (deferred as part of investment) | Yes, effective interest method |
| **Operating** | No profit at inception | Rental income straight-line |

---

## 🔥 Sales-Type Lease (The Big One for TBS)

### When It Applies:
- At least ONE OWNS-IT criterion is met
- Collectibility is probable
- **Manufacturer/dealer margin exists** (FV ≠ Cost/Carrying value)

### Day 1 Journal Entry:

```
Dr. Net Investment in Lease (PV of payments + PV of unguaranteed residual)    XXX
Dr. Cost of Goods Sold (Carrying value of asset − PV of unguaranteed residual) XXX
    Cr. Sales Revenue (PV of lease payments + PV of guaranteed residual)            XXX
    Cr. Underlying Asset (carrying value of the asset)                              XXX
```

### ✅ Mnemonic: **"NICE-SC"** = Net Investment & COGS on the left; Sales & Carrying value on the right

### Key Components:
- **Net Investment in Lease** = PV of lease payments + PV of unguaranteed residual value
- **Sales Revenue** = PV of lease payments + PV of guaranteed residual value  
- **COGS** = Carrying value of asset − PV of unguaranteed residual value
- **Gross Profit** = Sales Revenue − COGS

### Subsequent Journal Entry (Each Payment Received):
```
Dr. Cash                                    XXX
    Cr. Interest Income                          XXX
    Cr. Net Investment in Lease                  XXX
```

Interest Income = Net Investment balance × Implicit rate

---

## 🔥 Direct Financing Lease

### When It Applies:
- At least ONE OWNS-IT criterion is met
- Collectibility is probable
- **NO manufacturer/dealer profit** (FV = Cost/Carrying value)

### Day 1 Journal Entry:

```
Dr. Net Investment in Lease (PV of payments + PV of unguaranteed residual)    XXX
    Cr. Underlying Asset (carrying value = fair value)                             XXX
    Cr. Deferred Selling Profit (if any, from initial direct costs)               XXX
```

### Key Difference from Sales-Type:
- **NO upfront profit recognition**
- Initial direct costs are deferred (part of net investment)
- Selling profit is deferred and recognized over the lease term via the effective interest method

### Subsequent Entries (Same as Sales-Type):
```
Dr. Cash                                    XXX
    Cr. Interest Income                          XXX
    Cr. Net Investment in Lease                  XXX
```

---

## 🔥 Operating Lease (Lessor)

### When It Applies:
- NONE of the OWNS-IT criteria are met, OR
- OWNS-IT is met but collectibility is NOT probable

### Accounting Treatment:
- **Keep the asset on the books** (continue to depreciate)
- **Recognize rental income on a straight-line basis**
- Initial direct costs are **deferred and amortized** over the lease term (straight-line)

### Journal Entries:

**Each Period:**
```
Dr. Cash (or Lease Receivable)              XXX
    Cr. Rental Income                            XXX

Dr. Depreciation Expense                    XXX
    Cr. Accumulated Depreciation                 XXX
```

---

## 📝 TBS Walkthrough: Sales-Type Lease Simulation

### Scenario:
**EquipCo (lessor) leases equipment to TenantCo on January 1, Year 1:**

- Fair value of equipment: **$500,000**
- Cost of equipment to EquipCo: **$350,000**
- Lease term: **5 years** (economic life: 6 years)
- Annual lease payments: **$115,000** (paid at end of each year)
- Implicit rate: **7%**
- No purchase option, no transfer of ownership
- Unguaranteed residual value: **$40,000**
- No initial direct costs

### Step 1: Classification
- 75% test: 5/6 = 83.3% ≥ 75% ✓ → OWNS-IT is met
- There IS a manufacturer/dealer profit ($500,000 FV ≠ $350,000 cost)
- Collectibility is probable
- → **Sales-Type Lease**

### Step 2: Calculate Components

**PV of lease payments:**
```
PV = $115,000 × PV annuity factor (7%, 5 years)
PV = $115,000 × 4.10020
PV = $471,523
```

**PV of unguaranteed residual value:**
```
PV = $40,000 × PV single sum (7%, 5 years)
PV = $40,000 × 0.71299
PV = $28,520
```

**Net Investment in Lease:**
```
= PV of payments + PV of unguaranteed residual
= $471,523 + $28,520
= $500,043 ≈ $500,000 (rounds to FV, confirming our rate)
```

**Sales Revenue** = PV of lease payments = **$471,523** (no guaranteed residual)

**COGS** = Cost − PV of unguaranteed residual = $350,000 − $28,520 = **$321,480**

**Gross Profit** = $471,523 − $321,480 = **$150,043**

### Step 3: Day 1 Journal Entry

```
Dr. Net Investment in Lease               500,000
Dr. Cost of Goods Sold                    321,480
    Cr. Sales Revenue                            471,523
    Cr. Equipment                                350,000
```

**Profit recognized on Day 1 = $150,043** (This is the manufacturer's profit!)

### Step 4: Amortization Schedule

| Year | Beg Balance | Interest Income (7%) | Payment | End Balance |
|------|------------|----------------------|---------|-------------|
| 1 | 500,000 | 35,000 | (115,000) | 420,000 |
| 2 | 420,000 | 29,400 | (115,000) | 334,400 |
| 3 | 334,400 | 23,408 | (115,000) | 242,808 |
| 4 | 242,808 | 16,997 | (115,000) | 144,805 |
| 5 | 144,805 | 10,136 | (115,000) | 39,941* |

*Residual value at end of lease ≈ $40,000 (slight rounding)

### Year 1 Payment Entry:
```
Dr. Cash                                  115,000
    Cr. Interest Income                          35,000
    Cr. Net Investment in Lease                  80,000
```

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Guaranteed vs. unguaranteed residual | Mix them up in revenue calc | Guaranteed → part of Sales Revenue; Unguaranteed → NOT in Sales Revenue |
| Initial direct costs (Sales-type) | Capitalize them | **EXPENSE** immediately for sales-type leases |
| Initial direct costs (Direct Financing) | Expense them | **Capitalize** as part of net investment |
| Operating lease income | Recognize based on payments | Recognize on **straight-line basis** |
| Classification confusion | Just apply OWNS-IT | Must ALSO check collectibility and profit margin |
| Implicit rate vs. incremental borrowing rate | Use lessee's rate | Lessor ALWAYS uses the **implicit rate** |
| Short-term lease exception | Apply to lessor | Short-term exception is for **LESSEES only** |

---

## 📝 Practice Scenario — Try This!

**ManufactureCo leases a machine to UserCo on January 1, Year 1:**
- Fair value of machine: $300,000
- ManufactureCo's cost: $300,000 (NO margin!)
- Lease term: 4 years (economic life: 5 years)
- Annual payments: $82,000 (end of year)
- Implicit rate: 6%
- Guaranteed residual value: $20,000
- No transfer of ownership, no purchase option, asset has alternative use

**Questions:**
1. What type of lease is this?
2. What is the Day 1 journal entry?
3. What is Interest Income for Year 1?

<details>
<summary>💡 Click for Solution</summary>

**1. Classification:**
- 75% test: 4/5 = 80% ≥ 75% ✓ → OWNS-IT met
- Cost = Fair value ($300,000 = $300,000) → NO manufacturer profit
- Collectibility probable
- → **Direct Financing Lease**

**2. PV Calculations:**
```
PV of payments = $82,000 × 3.46511 (PV annuity, 6%, 4yr) = $284,139
PV of guaranteed residual = $20,000 × 0.79209 (PV single sum, 6%, 4yr) = $15,842
Net Investment = $284,139 + $15,842 = $299,981 ≈ $300,000
```

**Day 1 Entry:**
```
Dr. Net Investment in Lease               300,000
    Cr. Machine                                  300,000
```
No profit recognized at inception!

**3. Year 1 Interest Income:**
```
= $300,000 × 6% = $18,000
```

</details>

---

## 🧠 Key Formulas to Memorize

| Formula | Expression |
|---------|-----------|
| Net Investment in Lease | PV of lease payments + PV of unguaranteed residual |
| Sales Revenue (Sales-type) | PV of lease payments + PV of guaranteed residual |
| COGS (Sales-type) | Carrying value − PV of unguaranteed residual |
| Gross Profit (Sales-type) | Sales Revenue − COGS |
| Interest Income (each period) | Beginning Net Investment × Implicit Rate |
| Lease Classification | OWNS-IT → Check collectibility → Check profit margin |

### ✅ Final Mnemonic: **"Lessors OWNS-IT, then SOS"**
- **S**ales-type = profit exists, collect is probable
- **O**perating = no OWNS-IT or no collectibility
- **S**traight through = Direct financing (no profit, just financing)

---

> 💡 **Top Ranker Tip**: The TBS will almost always give you PV factors. Don't waste time memorizing PV tables — instead, master the LOGIC of which cash flows to discount and which rate to use. The math is plug-and-play once you know the structure.
