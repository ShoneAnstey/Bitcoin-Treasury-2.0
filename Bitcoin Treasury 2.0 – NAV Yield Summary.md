
### Comparative Overview: LNav · DNav · ANav · CNav  
*(Compiled October 2025 — for public-company modeling and benchmarking)*

---

## 🧭 Summary Table

| NAV Type | Primary Yield Source | Example Deployment | Annualized Yield | BNAV/Share Uplift | Risk Profile | Yield Range (2025 est.) |
|-----------|----------------------|--------------------|------------------|-------------------|---------------|--------------------------|
| **LNav (Lightning NAV)** | Routing, channel leasing, swaps | 100 BTC deployed (70 BTC effective) | **1.04%** | **+0.04%** | Operational, fee volatility | 1 – 24% |
| **DNav (Derivatives NAV)** | Covered calls, basis trades, funding capture | 100 BTC hedged of 500 BTC treasury | **3.17%** | **+3.17%** | Counterparty, volatility | 2 – 22% |
| **ANav (Arbitrage NAV)** | Market-making, spread capture, cross-exchange arb | 200 BTC deployed | **3.6%** | **+0.72%** | Competition, slippage | 3 – 9% |
| **CNav (Credit NAV)** | BTC-backed loans, structured credit | 50 BTC lent of 200 BTC treasury | **6.0% (net)** | **+1.25%** | Default, counterparty | 2 – 18% |

---

## ⚙️ Key Mathematical Frameworks

| Metric | Formula | Example Result |
|---------|----------|----------------|
| **Effective Capacity (LNav)** | `Deployed × (1 - Reserve)` | 100 × 0.70 = 70 BTC |
| **Weighted APR (LNav)** | `(Net Yield / (Capacity × Days)) × 365 × 100` | ≈ 1.04% |
| **Premium Yield (DNav)** | `(Monthly Premium × 12) / Treasury × 100` | 2.4% |
| **Funding Capture (DNav)** | `Deployed × Rate` | 100 × 0.006 = 0.6 BTC |
| **Spread Capture (ANav)** | `Spread × Volume` | 0.0004 × 200,000 = 80 BTC |
| **ROI (ANav)** | `(Net Profit / Deployed) × 100` | 3.6% |
| **Gross Yield (CNav)** | `Principal × APR` | 50 × 0.08 = 4 BTC |
| **Net Yield (CNav)** | `Gross – Provisions – Defaults` | 2.5 BTC |

---

## 💰 BNAV Integration Formulas

Each variant rolls into **BNAV (Bitcoin Net Asset Value)** as:

\[
BNAV / Share = \frac{(Market Value of BTC + NAV Yield × BTC Price - Debt)}{Shares Outstanding}
\]

| Example Company | Treasury | NAV Yield | BTC Price | Shares | Resulting BNAV/Share | Δ vs. MNAV |
|------------------|-----------|------------|------------|----------|-----------------------|-------------|
| **NodeCo (LNav)** | 500 BTC | 0.18 BTC net | $124 k | 20 M | $3.101 | +0.04% |
| **CoverCorp (DNav)** | 500 BTC | 15.84 BTC net | $124 k | 15 M | $4.264 | +3.17% |
| **FlowBTC (ANav)** | 1,000 BTC | 7.2 BTC net | $124 k | 25 M | $4.996 | +0.72% |
| **Satoshi Credit (CNav)** | 200 BTC | 2.5 BTC net | $124 k | 10 M | $2.511 | +1.25% |

---


![[Pasted image 20251006135709.png]]


**Bitcoin Treasury 2.0 – NAV Yield Matrix** visualization.  
It plots **annualized yield vs. relative risk** across the four NAV types:

- **LNav** → low risk, lowest yield (infrastructure yield layer)
    
- **DNav** → moderate risk, volatility-driven yield
    
- **ANav** → moderate risk, consistent arbitrage income
    
- **CNav** → higher risk, highest yield (credit exposure)
    

---


![[Pasted image 20251006135853.png]]

**Yield vs. Liquidity Matrix** for Bitcoin Treasury 2.0.  
It visually highlights the trade-off between **yield potential and liquidity**:

- **LNav** (Lightning): highest liquidity, lowest yield.
    
- **DNav**: still liquid, moderate yield.
    
- **ANav**: middle ground — decent yield with lower liquidity.
    
- **CNav**: least liquid, highest yield.

## 🔍 Observations

- **LNav** offers the *lowest risk* and *lowest yield*, but strong strategic value: self-custodial, operational yield in sats.  
- **DNav** provides the *most scalable and liquid yield layer* for treasuries able to manage derivatives.  
- **ANav** yields are stable and uncorrelated with BTC price; ideal for low-volatility, high-turnover capital.  
- **CNav** behaves like a Bitcoin bond: steady income with defined counterparty risk.  


## 🧩 Portfolio Design Implications

A balanced Bitcoin Treasury 2.0 allocation could look like:

| NAV Type | Target Weight | Purpose |
|-----------|----------------|----------|
| LNav | 25% | Infrastructure yield + ecosystem participation |
| DNav | 25% | Volatility monetization |
| ANav | 25% | Market-neutral liquidity income |
| CNav | 25% | Fixed-income stability |

Blended treasury yield ≈ **3.45% annualized**, before compounding.

---

## 📘 Notes

- BTC price assumption: **$124,000/BTC (2025 baseline)**  
- All example companies hypothetical; designed for public-company modeling.  
- Figures rounded to 2 decimals where appropriate.  
- See respective addendums (A–D) for expanded math and risk governance.


---


**Author:** Shone Anstey  
**Version:** 1.0 — October 2025  
**Context:** Bitcoin Treasury 2.0 Framework — Yield Layer Standardization
