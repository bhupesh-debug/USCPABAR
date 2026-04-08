# 📊 TBS #5: Variance Analysis

> **Frequency: ⭐⭐⭐⭐ (High)**
> **TBS Types: Numeric Entry**
> **BAR Section: BAR 3 — Cost Accounting & Planning**

---

## 🎯 Why This is Heavily Tested

Variance analysis is a **pure numbers game** — perfect for Numeric Entry TBS. The AICPA loves this topic because:
- It tests both calculation AND interpretation skills
- Multiple variances interact (you must understand the full picture)
- It connects to budgeting, performance evaluation, and management decisions
- Formulas are precise — no room for hand-waving

### ✅ The Big Picture
Variance analysis compares **what SHOULD have happened** (standard/budget) to **what ACTUALLY happened** (actual results). The difference = a **variance** that tells management WHERE things went right or wrong.

---

## 📚 The Master Framework: Standard Cost System

### ✅ Mnemonic: **"DOLPH"** — The 5 Key Variances

| Letter | Variance | Category |
|--------|----------|----------|
| **D**irect Materials Price Variance | Materials | Direct Costs |
| **O** (Quantity) → Direct Materials Quantity Variance | Materials | Direct Costs |
| **L**abor Rate Variance | Labor | Direct Costs |
| **P**roduction → Labor Efficiency Variance | Labor | Direct Costs |
| **H**ead (Overhead) → Overhead Variances | Overhead | Indirect Costs |

---

## 🔥 Direct Materials Variances

### 1. Materials Price Variance (MPV)
**"Did we pay more or less than expected PER UNIT of material?"**

```
MPV = (Actual Price − Standard Price) × Actual Quantity PURCHASED
```

- **Favorable (F)**: Actual Price < Standard Price (we paid less!)
- **Unfavorable (U)**: Actual Price > Standard Price (we overpaid!)

### 2. Materials Quantity Variance (MQV) / Usage Variance
**"Did we use more or less material than expected FOR ACTUAL PRODUCTION?"**

```
MQV = (Actual Quantity USED − Standard Quantity ALLOWED) × Standard Price
```

Where: **Standard Quantity Allowed** = Standard qty per unit × Actual units produced

- **Favorable (F)**: Used less than allowed
- **Unfavorable (U)**: Used more than allowed

### ✅ Mnemonic: **"Price uses PURCHASED, Quantity uses Standard Price"**
- Price Variance → Actual Qty **PURCHASED** × price difference
- Quantity Variance → **Standard Price** × quantity difference

### ✅ The 3-Column Method (Fastest for TBS):

```
     Column 1                Column 2                Column 3
  Actual × Actual        Actual × Standard       Standard × Standard
   (AQ × AP)              (AQ × SP)            (SQ allowed × SP)
       │                      │                       │
       └────── MPV ───────────┘                       │
                              └────── MQV ────────────┘
```

---

## 🔥 Direct Labor Variances

### 1. Labor Rate Variance (LRV)
**"Did we pay more or less per hour than expected?"**

```
LRV = (Actual Rate − Standard Rate) × Actual Hours WORKED
```

### 2. Labor Efficiency Variance (LEV)
**"Did we use more or fewer hours than expected FOR ACTUAL PRODUCTION?"**

```
LEV = (Actual Hours − Standard Hours ALLOWED) × Standard Rate
```

Where: **Standard Hours Allowed** = Standard hours per unit × Actual units produced

### ✅ The 3-Column Method for Labor:

```
     Column 1                Column 2                Column 3
  Actual × Actual        Actual × Standard       Standard × Standard
   (AH × AR)              (AH × SR)            (SH allowed × SR)
       │                      │                       │
       └────── LRV ───────────┘                       │
                              └────── LEV ────────────┘
```

---

## 🔥 Overhead Variances (The Complex Part)

### Two-Way Analysis:

**1. Overhead Budget (Controllable) Variance:**
```
= Actual Overhead − Flexible Budget Overhead
= Actual OH − [Fixed OH Budget + (Variable OH Rate × Standard Hours Allowed)]
```

**2. Overhead Volume Variance:**
```
= Flexible Budget Overhead − Applied Overhead
= [Fixed OH Budget + (Var Rate × SH Allowed)] − [Total OH Rate × SH Allowed]
= Fixed OH Budget − (Fixed OH Rate × SH Allowed)
```

### ✅ Simplified: Volume Variance = Budgeted Fixed OH − Applied Fixed OH

This variance measures **capacity utilization**:
- **Favorable**: Produced MORE than expected (used capacity well)
- **Unfavorable**: Produced LESS than expected (underutilized capacity)

### Three-Way Analysis (More Detailed):

| Variance | Formula |
|----------|---------|
| **Spending Variance** | Actual OH − [Budget Fixed OH + (Var Rate × AH)] |
| **Efficiency Variance** | (AH − SH Allowed) × Variable OH Rate |
| **Volume Variance** | Budget Fixed OH − (Fixed OH Rate × SH Allowed) |

### Four-Way Analysis (Maximum Detail):

| Variance | Formula |
|----------|---------|
| **Variable OH Spending** | Actual Variable OH − (Variable Rate × AH) |
| **Variable OH Efficiency** | (AH − SH Allowed) × Variable OH Rate |
| **Fixed OH Spending (Budget)** | Actual Fixed OH − Budgeted Fixed OH |
| **Fixed OH Volume** | Budgeted Fixed OH − (Fixed OH Rate × SH Allowed) |

### ✅ Mnemonic for Overhead: **"SEVV"** = Spending, Efficiency, Volume, Volume (variable, then fixed)

---

## 📝 TBS Walkthrough: Complete Variance Analysis

### Scenario:
**ProductCo manufactures widgets. Standard cost data per unit:**

| Item | Standard |
|------|----------|
| Direct Materials | 3 lbs × $5/lb = $15/unit |
| Direct Labor | 2 hours × $20/hr = $40/unit |
| Variable Overhead | 2 hours × $6/hr = $12/unit |
| Fixed Overhead | Budget: $180,000/month; Normal capacity: 10,000 units |

**Actual results for March (9,000 units produced):**

| Item | Actual |
|------|--------|
| Materials purchased | 28,000 lbs at $5.20/lb |
| Materials used | 26,500 lbs |
| Direct labor | 18,500 hours at $19.50/hr |
| Variable overhead | $115,000 |
| Fixed overhead | $185,000 |

### Step-by-Step Solutions:

**Standard Quantities Allowed (for 9,000 units):**
- Materials: 9,000 × 3 = 27,000 lbs
- Labor: 9,000 × 2 = 18,000 hours

---

**MATERIALS VARIANCES:**

```
MPV = (AP − SP) × AQ Purchased
    = ($5.20 − $5.00) × 28,000
    = $0.20 × 28,000
    = $5,600 Unfavorable
```

```
MQV = (AQ Used − SQ Allowed) × SP
    = (26,500 − 27,000) × $5.00
    = (−500) × $5.00
    = $2,500 Favorable (used less than allowed!)
```

---

**LABOR VARIANCES:**

```
LRV = (AR − SR) × AH
    = ($19.50 − $20.00) × 18,500
    = (−$0.50) × 18,500
    = $9,250 Favorable (paid less per hour!)
```

```
LEV = (AH − SH Allowed) × SR
    = (18,500 − 18,000) × $20.00
    = 500 × $20.00
    = $10,000 Unfavorable (used more hours than allowed)
```

---

**OVERHEAD VARIANCES (Four-Way):**

**Fixed OH Rate** = $180,000 ÷ 10,000 units ÷ 2 hrs = $9/hour
**Standard Hours Allowed** = 18,000 hours

```
Variable OH Spending = Actual Var OH − (Var Rate × AH)
                     = $115,000 − ($6 × 18,500)
                     = $115,000 − $111,000
                     = $4,000 Unfavorable
```

```
Variable OH Efficiency = (AH − SH Allowed) × Var OH Rate
                       = (18,500 − 18,000) × $6
                       = 500 × $6
                       = $3,000 Unfavorable
```

```
Fixed OH Budget = Actual Fixed OH − Budget Fixed OH
               = $185,000 − $180,000
               = $5,000 Unfavorable
```

```
Fixed OH Volume = Budget Fixed OH − Applied Fixed OH
               = $180,000 − ($9 × 18,000)
               = $180,000 − $162,000
               = $18,000 Unfavorable (underproduced vs. capacity)
```

---

### Variance Summary Table:

| Variance | Amount | F/U |
|----------|--------|-----|
| Materials Price | $5,600 | U |
| Materials Quantity | $2,500 | F |
| Labor Rate | $9,250 | F |
| Labor Efficiency | $10,000 | U |
| Variable OH Spending | $4,000 | U |
| Variable OH Efficiency | $3,000 | U |
| Fixed OH Budget | $5,000 | U |
| Fixed OH Volume | $18,000 | U |
| **Net Total** | **$33,850** | **U** |

---

## ⚡ Common TBS Traps & How to Avoid Them

| Trap | What Students Do Wrong | Correct Treatment |
|------|----------------------|-------------------|
| Purchased vs. Used | Use AQ purchased for quantity variance | Quantity variance uses AQ **USED**; Price variance uses AQ **PURCHASED** |
| Standard Qty Allowed | Use budgeted production | Use **actual production** × standard qty per unit |
| F vs. U | Confuse the direction | Lower actual cost = Favorable; Higher actual cost = Unfavorable |
| Overhead volume variance | Use actual hours | Use **standard hours allowed** vs. normal capacity hours |
| Mix up rate vs. efficiency | Calculate with wrong factor | Rate/Price = isolate the **price difference**; Efficiency/Quantity = isolate the **quantity difference** |
| Flexible budget | Use static budget | Flex budget adjusts variable costs to **actual activity level** |
| Fixed OH volume | Think it's controllable | Volume variance is a **capacity utilization** measure, not spending control |

---

## 📝 Practice Scenario — Try This!

**QuickMake produces gizmos. Standard cost per unit:**
- Materials: 5 kg × $8/kg = $40
- Labor: 1.5 hours × $25/hr = $37.50

**April actual (produced 2,000 units):**
- Materials purchased and used: 10,400 kg at $7.80/kg
- Labor: 3,100 hours at $25.50/hr

**Calculate all four direct cost variances.**

<details>
<summary>💡 Click for Solution</summary>

**Standard Quantities Allowed:**
- Materials: 2,000 × 5 = 10,000 kg
- Labor: 2,000 × 1.5 = 3,000 hours

**Materials Price Variance:**
```
= ($7.80 − $8.00) × 10,400 = (−$0.20) × 10,400 = $2,080 Favorable
```

**Materials Quantity Variance:**
```
= (10,400 − 10,000) × $8.00 = 400 × $8.00 = $3,200 Unfavorable
```

**Labor Rate Variance:**
```
= ($25.50 − $25.00) × 3,100 = $0.50 × 3,100 = $1,550 Unfavorable
```

**Labor Efficiency Variance:**
```
= (3,100 − 3,000) × $25.00 = 100 × $25.00 = $2,500 Unfavorable
```

</details>

---

## 🧠 Key Formulas — Quick Reference Card

| Variance | Formula | Uses |
|----------|---------|------|
| **MPV** | (AP − SP) × AQ Purchased | AQ Purchased |
| **MQV** | (AQ Used − SQ Allowed) × SP | Standard Price |
| **LRV** | (AR − SR) × AH | Actual Hours |
| **LEV** | (AH − SH Allowed) × SR | Standard Rate |
| **Var OH Spending** | Actual Var OH − (Var Rate × AH) | |
| **Var OH Efficiency** | (AH − SH Allowed) × Var Rate | |
| **Fixed OH Budget** | Actual Fixed OH − Budget Fixed OH | |
| **Fixed OH Volume** | Budget Fixed OH − (Fixed Rate × SH Allowed) | |

### ✅ Final Mnemonic: **"PAQ-QS"** for Materials = Price uses Actual Quantity, Quantity uses Standard price

---

> 💡 **Top Ranker Tip**: On Numeric Entry TBS, they will test whether you know to use Actual Quantity PURCHASED (not used) for the price variance. This is the #1 error students make. If you see separate numbers for purchased and used — the price variance ALWAYS uses purchased.
