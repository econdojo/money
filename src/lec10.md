---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 10: Exchange-Rate Policy and Central Bank'
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

# Lecture 10: Exchange-Rate Policy and Central Bank

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Monetary Economics
**Date:** February 13, 2026

---

## Overview

This lecture studies the link between a country's exchange rate policy and its domestic monetary policy.

**Key insight:**
- Central banks must choose between a fixed exchange rate and an independent monetary policy.
- Trilemma of international finance: A country cannot simultaneously [i.] maintain a fixed exchange rate; [ii.] conduct independent monetary policy; [iii.] allow free capital flows

---

## The Road Ahead

1. [Exchange-Rate Policy and Domestic Monetary Policy](#long-run-inflation-and-ppp)
2. [Mechanics of Exchange-Rate Management](#mechanics-of-exchange-rate-management)

---

## Long-Run: Inflation and PPP

The theory of purchasing power parity (PPP) extends the law of one price to a basket of goods and services. Taking percentage changes of the PPP condition:

<div class="identity-box">

$$\text{\% change in } E \approx \underbrace{\text{\% change in } P^*}_{\text{U.K. inflation}} - \underbrace{\text{\% change in } P}_{\text{U.S. inflation}}$$

</div>

**Implication:** Pound depreciates (appreciates) when U.K. inflation exceeds (falls below) U.S. inflation.

**Long-run constraint:** Bank of England must choose between

- Fixing the exchange rate and matching U.S. inflation
- Setting independent monetary policy and allowing the exchange rate to float

---

## Short-Run: Interest Rates and Capital Arbitrage

Arbitrage in capital markets ensures equal expected returns on U.S. and U.K. bonds:

<div class="identity-box">

$$1 + i_t = (1 + i_t^*)\left(\frac{E_t}{E_{t+1}^e}\right)$$

</div>

Under a credible fixed exchange rate ($E_t = E_{t+1}^e$), this implies $i_t = i_t^*$.

**Short-run constraint:** Bank of England must choose between

- Fixing the exchange rate and matching U.S. interest rates
- Setting independent monetary policy and allowing the exchange rate to float

---

## Impossible Trinity

If a country forgoes participating in international capital markets, it can impose **capital controls** and potentially achieve both goals. Policymakers must choose two of the three:

1. Be open to international capital flows
2. Control domestic interest rate
3. Fix exchange rate

**Policy choices in practice:**

- Large economies (U.S., Eurozone) prioritize free capital flows and monetary independence, letting exchange rates float.
- Small open economies may prioritize exchange rate stability given dramatic impacts of exchange rate changes.

---

## Mechanics of Exchange-Rate Management

How do central banks actually manage exchange rates?

**Mechanism:** Central banks can fix exchange rates by offering to buy and sell their country's currency at the fixed rate.

**Implication:** Controlling the exchange rate means giving up control of the size of reserves, so the market determines the interest rate.

---

## Foreign Exchange Intervention

Suppose the U.S. Treasury instructs the Fed to purchase $1 billion worth of euros.

Mechanism:
- Fed buys German government bonds (denominated in euros)
- Pays foreign exchange departments of commercial banks with dollars

Impact on Fed's balance sheet:
- Assets increase by $1 billion (foreign exchange reserves)
- Liabilities increase by $1 billion (bank reserves)
- Monetary base increases by $1 billion

![Foreign Exchange Intervention](images/lec10/exchange.jpg)

---

## Effects on Money Supply and Interest Rates

Through money multiplier:
- Monetary base increases
- Quantity of money in economy increases
- Supply of reserves to banking system increases

Effect on interest rates:
- Increased reserve supply puts downward pressure on interest rates
- Buying euros (selling dollars) lowers U.S. interest rates

This is an **unsterilized** foreign exchange intervention (changes the monetary base).

---

## Impact on Exchange Rate

![Exchange Rate Impact](images/lec10/intervention.jpg)
