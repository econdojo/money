---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 2: Future Value, Present Value, and Interest Rates'
footer: 'Fei Tan | Monetary Economics'
style: |
  .logo {
    vertical-align: -0.2em;
  }
  section {
    color: #222;
    font-size: 24px;
    padding: 50px;
  }
  h1 {
    color: #003DA5;
    font-size: 38px;
    margin-bottom: 18px;
  }
  h2 {
    color: #003DA5;
    font-size: 30px;
    margin-bottom: 15px;
  }
  h3, h4, h5, h6 {
    color: #003DA5;
  }
  .slide-footer {
    color: #888;
  }
  .highlight {
    background-color: #ffeb3b;
    padding: 2px 4px;
    border-radius: 3px;
  }
  .identity-box {
    background-color: #f0f0f0;
    border-radius: 10px;
    padding: 12px;
    margin: 12px 0;
    text-align: center;
    border: 2px solid #ddd;
    font-size: 20px;
  }
  table {
    margin: 15px auto;
    border-collapse: collapse;
    font-size: 19px;
  }
  table th, table td {
    border: 2px solid #003DA5;
    padding: 8px 12px;
    text-align: center;
  }
  table th {
    background-color: #003DA5;
    color: white;
  }
  ul, ol {
    margin: 10px 0;
    padding-left: 25px;
  }
  li {
    margin: 6px 0;
    line-height: 1.5;
  }
  p {
    margin: 10px 0;
    line-height: 1.5;
  }
---

# Lecture 2: Future Value, Present Value, and Interest Rates

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Monetary Economics
**Date:** January 14, 2026

---

## Overview

Interest rates are of enormous importance to virtually everyone:

- Link present to future - Allow us to compare payments made on different dates
- Future reward - Tell us the return for lending today
- Cost of borrowing - Show the cost of borrowing now and repaying later

**Key concepts:**
- Present value and future value
- Bond valuation
- Relationship between inflation and interest rates

---

## The Road Ahead

1. [Valuing Monetary Payments Now and in the Future](#future-value)
2. [Applying Present Value](#internal-rate-of-return)
3. [Real and Nominal Interest Rates](#real-and-nominal-interest-rates)

---

## Future Value

Future value (FV) is the value on some future date of an investment made today.

**Formula:** For a present value (PV) invested at interest rate $i$:

<div class="identity-box">

$$\text{FV} = \text{PV} \times (1+i)$$

</div>

**Example:** $\$100$ one year from now at 5% annual interest:
$$\text{FV} = \$100 \times (1.05) = \$105$$

The higher the interest rate or the amount invested, the higher the future value.

---

## Compound Interest

**Two-year example:** $\$100$ at 5% for two years:

$$\begin{align}
\$110.25 &= \underbrace{\$100}_{\text{PV}} + \underbrace{\$5}_{\text{1st year interest}} + \underbrace{\$5}_{\text{2nd year interest}} + \underbrace{\$0.25}_{\text{compound interest}} \\
&= \$100 \times (1.05)^2
\end{align}$$

Compound interest is the interest earned on interest.

**General formula** for $n$ years:

<div class="identity-box">

$$\text{FV}_n = \text{PV} \times (1+i)^n$$

</div>

---

## Time Units and Basis Points

**Caution:** Interest rate and $n$ must use the same time units.

**Example:** Monthly interest rate $i^m$ for one year (12 months):
$$\$100 \times (1+i^m)^{12} = \$100 \times (1.05)$$

Solving gives $i^m = 0.41\%$ or 41 basis points

**Basis point:** One-hundredth of a percentage point (0.01%)

---

## Present Value

Present value (PV) is the value today of a payment promised in the future.

**Formula:** For a future value (FV) with interest rate $i$:

<div class="identity-box">

$$\text{PV} = \frac{\text{FV}}{1+i}$$

</div>

**Example:** $\$105$ one year from now at 5%:
$$\text{PV} = \frac{\$105}{1.05} = \$100$$

**Key insight:** Present value falls as the interest rate rises.

---

## Present Value: General Formula

For $n$ years at annual interest rate $i$:

<div class="identity-box">

$$\text{PV} = \frac{\text{FV}_n}{(1+i)^n}$$

</div>

**Example:** $\$105$ in two years at 5%:
$$\text{PV} = \frac{\$105}{(1.05)^2} = \$95.24$$

Present value is higher when:
- Future value is higher
- Time until payment is shorter
- Interest rate is lower

---

## Internal Rate of Return

Internal rate of return equates the present value of an investment with its cost.

**Example:** $\$225$ loan with two repayment options:
1. $\$100$ per year for 3 years
2. $\$125$ per year for 2 years

**Option 1:** Find $i$ such that:
$$\$225 = \frac{\$100}{1+i} + \frac{\$100}{(1+i)^2} + \frac{\$100}{(1+i)^3}$$
Solution: $i = 15.9\%$

**Option 2:** Find $i$ such that:
$$\$225 = \frac{\$125}{1+i} + \frac{\$125}{(1+i)^2}$$
Solution: $i = 7.3\%$

**Conclusion:** Option 1 is more profitable (higher return).

---

## Bonds

A bond is a promise to make a series of payments on specific future dates.

Coupon bond terminology:
- **Coupon payments** - Annual payments by bond issuer
- **Coupon rate** - Annual payments as % of amount borrowed (e.g., 5% means $\$5$ per $\$100$ borrowed)
- **Principal/Face value/Par value** - Final repayment amount
- **Maturity date/term to maturity** - When issuer repays principal and payments stop

---

## Valuing a Coupon Bond: Step 1

Bond characteristics:
- Yearly coupon payment: $\$C$
- Number of years: $n$
- Principal payment: $\$F$
- Interest rate: $i$

**Step 1: Value the bond principal (BP)**

<div class="identity-box">

$$\text{P}_{\text{BP}} = \frac{\$F}{(1+i)^n}$$

</div>

**Example:** $\$1000$ principal, 6% interest, 30 years:
$$\text{P}_{\text{BP}} = \frac{\$1000}{(1.06)^{30}} = \$174.11$$

---

## Valuing a Coupon Bond: Step 2

**Step 2: Value the coupon payments (CP)**

Sum of present values of all coupon payments:

<div class="identity-box">

$$\text{P}_{\text{CP}} = \sum_{k=1}^n \frac{\$C}{(1+i)^k}$$

</div>

**Simplified formula:**
$$\text{P}_{\text{CP}} = \frac{\$C}{i}\left[1 - \frac{1}{(1+i)^n}\right]$$

**Example:** $\$10$ coupon, 6% interest, 2 years:
$$\text{P}_{\text{CP}} = \frac{\$10}{1.06} + \frac{\$10}{(1.06)^2} = \$9.43 + \$8.90 = \$18.33$$

---

## Valuing a Coupon Bond: Step 3

**Step 3: Total coupon bond (CB) value**

<div class="identity-box">

$$\text{P}_{\text{CB}} = \text{P}_{\text{BP}} + \text{P}_{\text{CP}} = \frac{\$F}{(1+i)^n} + \sum_{k=1}^n \frac{\$C}{(1+i)^k}$$

</div>

**Key principle:** The value of a bond varies inversely with the interest rate

- Higher interest rate → Lower bond price
- Lower interest rate → Higher bond price

---

## Real and Nominal Interest Rates

When borrowing/lending, we care about **goods**, not just dollars!

**Nominal interest rate** ($i_t$):
- Expressed in currency units
- Borrow $\$1$ today → Repay $1 + i_t$ dollars next year

**Real interest rate** ($r_t$):
- Expressed in baskets of goods
- Borrow 1 basket today → Repay $1 + r_t$ baskets next year

**Challenge:** We observe nominal rates, but real rates matter for decisions.

---

## Deriving the Real Interest Rate

**Setup:**
- Current price level: $P_t$ (price of one basket of goods)
- Expected price level next year: $P_{t+1}^e$
- Borrow $P_t$ dollars today → Repay $(1+i_t)P_t$ dollars next year

**In terms of baskets:**
Repayment next year = $\frac{(1+i_t)P_t}{P_{t+1}^e}$ baskets

**Real interest rate formula:**

<div class="identity-box">

$$1 + r_t = (1+i_t)\frac{P_t}{P_{t+1}^e}$$

</div>

---

## Fisher Relation

Define expected inflation: $\pi_{t+1}^e \equiv \frac{P_{t+1}^e - P_t}{P_t}$

**Exact relation:**

<div class="identity-box">

$$1 + r_t = \frac{1+i_t}{1+\pi_{t+1}^e}$$

</div>

**Fisher relation** (approximation when rates are not too large):

<div class="identity-box">

$$i_t \approx r_t + \pi_{t+1}^e$$

</div>

**Key insight:** Nominal interest rate is positively related to expected inflation.

---

## Ex-Ante vs. Ex-Post Real Rates

**Ex-ante real interest rate** ("before the fact"):
- Uses expected inflation: $r_t = i_t - \pi_{t+1}^e$
- Cannot be directly observed (must be estimated)
- Relevant for decision-making

**Ex-post real interest rate** ("after the fact"):
- Uses actual inflation: $r_t = i_t - \pi_{t+1}$
- Can always be computed after the fact
- Shows what actually happened

---

## Math Appendix

**Goal:** Simplify $\text{PV} = \frac{\$C}{1+i} + \frac{\$C}{(1+i)^2} + \cdots + \frac{\$C}{(1+i)^n}$

**Step 1:** Multiply both sides by $\frac{1}{1+i}$:
$$\frac{\text{PV}}{1+i} = \frac{\$C}{(1+i)^2} + \frac{\$C}{(1+i)^3} + \cdots + \frac{\$C}{(1+i)^{n+1}}$$

**Step 2:** Subtract to get:
$$\frac{i}{1+i} \times \text{PV} = \frac{\$C}{1+i} - \frac{\$C}{(1+i)^{n+1}}$$

**Step 3:** Solve for PV:

<div class="identity-box">

$$\text{PV} = \frac{\$C}{i}\left[1 - \frac{1}{(1+i)^n}\right]$$

</div>
