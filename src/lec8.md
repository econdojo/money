---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 8: Central Bank Balance Sheet and Money Supply Process'
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

# Lecture 8: Central Bank Balance Sheet and Money Supply Process

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Monetary Economics
**Date:** February 13, 2026

---

## Overview

This lecture develops an understanding of how the central bank interacts with the financial system and how its balance sheet is connected to the money and credit that flows through the economy.

**Key insights:**
- Changes in the balance sheet affect the monetary base
- The money multiplier links the monetary base to the money supply
- Understanding these connections is essential for monetary policy analysis

---

## The Road Ahead

1. [Central Bank's Balance Sheet](#central-banks-balance-sheet)
2. [Deposit Expansion Multiplier](#deposit-expansion-process)
3. [Monetary Base and Money Supply](#monetary-base-and-money-supply)

---

## Central Bank's Balance Sheet

Central bank activities cause changes in its balance sheet:
- Supplying currency
- Providing deposit accounts to government and commercial banks
- Making loans
- Buying and selling securities and foreign currency

<img src="images/lec8/balance.jpg" width="650">

---

## Assets of Central Bank

1. **Securities** 
   - Primary assets of most central banks
   - Controlled through open market operations (purchases and sales)

2. **Foreign exchange reserves**
   - Central bank's and government's balances of foreign currency
   - Held as bonds issued by foreign governments
   - Used for foreign exchange interventions

3. **Loans**
   - To commercial banks and nonbanks
   - Service to commercial banks

---

## Liabilities of Central Bank

1. **Currency**
   - Principal liability of most central banks
   - Circulating in the hands of the nonbank public

2. **Government's account**
   - Government deposits funds (primarily tax revenues)
   - Government writes checks and makes electronic payments

3. **Commercial bank accounts (reserves)**
   - Sum of deposits at central bank plus vault cash
   - Required reserves: Mandated by regulation
   - Excess reserves: Held voluntarily

**Note**: Monetary Base (high-powered money) = Currency + Reserves

---

## Open Market Operations

The Fed buys or sells securities in financial markets.

**Example:** Fed purchases $1 billion T-bills from a commercial bank

- Fed's assets and liabilities both increase by $1 billion → monetary base ↑ by $1 billion
- Banking system: no change in liabilities, changes in assets sum to zero

<img src="images/lec8/OMO.jpg" width="800">

---

## Foreign Exchange Intervention

The Fed buys or sells foreign currency reserves.

**Example:** Fed purchases $1 billion worth of euros (buying German government bonds)

- Fed's assets and liabilities both increase by $1 billion → monetary base ↑ by $1 billion
- Banking system: no change in liabilities, changes in assets sum to zero

<img src="images/lec8/exchange.jpg" width="800">

---

## Discount Loans

The Fed makes loans backed by collateral (assets pledged by borrower).

**Example:** Fed makes $100 million loan to a commercial bank

- Fed's assets and liabilities both increase by $100 million → monetary base ↑ by $100 million
- Banking system: assets and liabilities both increase by $100 million → balance sheet expands

<img src="images/lec8/loan.jpg" width="800">

---

## Cash Withdrawal

Cash withdrawal by the nonbank public affects only the composition.

**Example:** Withdraw $100 from an ATM

- Fed: currency outstanding ↑ $100, reserves ↓ $100 → composition changes, monetary base size unchanged
- Banking system: reserves ↓ $100, checkable deposits ↓ $100 → balance sheet shrinks

<img src="images/lec8/cash.jpg" width="700">

---

## Deposit Expansion Process

Consider a $100,000 open market purchase by the Fed from First Bank.

**Simplifying assumptions:**
- Banks hold no excess reserves
- No change in currency held by nonbank public

**Process:**
1. First Bank receives $100,000 in reserves
2. First Bank keeps required reserves, lends out the rest
3. Borrowed funds deposited in Second Bank
4. Second Bank keeps required reserves, lends out the rest
5. Process continues...

---

## First Bank Balance Sheet

<img src="images/lec8/first.jpg" width="650">

Initial impact:
- Reserves increase by $100,000
- Securities decrease by $100,000

After lending:
- Reserves kept = required reserves
- Excess reserves lent out

---

## Second Bank Balance Sheet

<img src="images/lec8/second.jpg" width="700">

When borrower from First Bank deposits funds:
- Second Bank receives deposits
- Second Bank makes new loans after keeping required reserves
- Process continues through banking system

---

## Deposit Multiplier

Let $r_D$ be the **required reserve ratio**. A one-dollar increase in reserves creates a deposit increase of:

<div class="identity-box">

$$1 + (1-r_D) + (1-r_D)^2 + (1-r_D)^3 + \cdots = \frac{1}{r_D} > 1$$

</div>

<img src="images/lec8/multiplier.jpg" width="600">

---

## Monetary Base and Money Supply

Now we relax the assumptions:
- Banks may hold excess reserves
- Currency held by public may change

We derive the **money multiplier** $m$: the relationship between the quantity of money and the monetary base.

<div class="identity-box">

$$M = m \times MB$$

</div>

where
- $M = C + D \quad \text{(money = currency + deposits)}$
- $MB = C + R \quad \text{(monetary base = currency + reserves)}$
- $R = RR + ER \quad \text{(reserves = required + excess)}$

---

## Money Multiplier

<div class="identity-box">

$$M = \underbrace{\frac{C/D + 1}{C/D + r_D + ER/D}}_{\text{money multiplier } m} \times MB$$

</div>

Define two important ratios:

1. Excess reserve-to-deposit ratio: $ER/D$
   - Cost: Interest on loans forgone
   - Benefit: Safety if deposits withdrawn suddenly

2. Currency-to-deposit ratio: $C/D$
   - Cost: Interest on deposits forgone
   - Benefit: Lower risk and greater liquidity

These ratios are determined by economic agents' optimization decisions.
