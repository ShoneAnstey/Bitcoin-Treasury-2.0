---
title: "Bitcoin Treasury 2.0 – Strategy Brief & Metrics Standard"
author: "Shone Anstey"
date: "2025-10-04"
license: "MIT"
---


# Bitcoin Treasury 2.0 – Strategy Brief & Metrics Standard

_An industry-agnostic framework for reporting yield-enhanced Bitcoin treasuries_

## Table of Contents
- [Executive Summary](#executive-summary)
- [Definitions](#definitions)
- [BNAV and Industry-Specific NAV Variants](#bnav-and-industry-specific-nav-variants)
- [Why Bitcoin Treasury 2.0](#why-bitcoin-treasury-20)
- [Metrics Standard (Scoreboard)](#metrics-standard-scoreboard)
- [Deployment Models](#deployment-models)
- [Risks](#risks)
- [Opportunities](#opportunities)
- [Governance & Policy Suggestions](#governance--policy-suggestions)
- [Appendix – Key Formulas](#appendix--key-formulas)
- [MIT License](#mit-license)


## Executive Summary

Bitcoin Treasury Companies 1.0 primarily accumulate BTC and communicate value through BTC/share and MNAV/share. Bitcoin Treasury 2.0 companies go further: they actively deploy their Bitcoin holdings (for yield, liquidity provision, or other productivity strategies) to earn recurring sats income on treasury assets—compounding growth per share while deepening market utility. This document explains the shift, defines a standardized metrics set, and outlines key risks and opportunities for issuers, investors, and regulators.

---

## Definitions

- **Treasury 1.0**: Balance-sheet BTC accumulation, financed by equity and/or debt; success measured via BTC/share and MNAV/share.  
- **Treasury 2.0**: BTC accumulation plus active yield generation (through Lightning, derivatives, liquidity strategies, or other Bitcoin-native opportunities) and reporting of per-share sats productivity.  
- **MNAV/share**: (Market Value of BTC – Debt) ÷ Shares.  
- **BNAV/share (Bitcoin NAV 2.0)**: (Market Value of BTC + Net Yield – Debt) ÷ Shares. This is the umbrella NAV that accounts for yield-enhanced treasury strategies.

---

## BNAV and Industry-Specific NAV Variants

To provide clarity and comparability, Bitcoin Treasury 2.0 reporting can use BNAV as a common framework, with sub-variants depending on yield source:

- **LNav (Lightning NAV)**: Yield from Lightning Network operations – routing, channel leasing, swaps.  
  - Key metrics: Effective capacity, routing efficiency, weighted APR, uptime.  

- **DNav (Derivatives NAV)**: Yield from derivatives strategies – covered calls, basis trades, futures funding capture.  
  - Key metrics: Funding capture, option premium yield, basis spreads.  

- **ANav (Arbitrage NAV)**: Yield from liquidity provisioning / market-making – cross-exchange arbitrage, orderbook liquidity.  
  - Key metrics: Turnover volume, spread capture, ROI on deployed capital.  

- **CNav (Credit NAV)**: Yield from other Bitcoin-native innovations – structured credit, synthetic hedges, BTC-backed lending.  
  - Key metrics: Loan-to-value ratios, yield coverage, credit loss provisions, default rates.  

This taxonomy allows for:  

- **Clarity** – Investors know where yield is sourced.  
- **Comparability** – All models roll into BNAV/share, but analysts can differentiate by strategy.  
- **Flexibility** – New NAV variants (e.g., SNAV for stablecoin flows, GNAV for green mining credits) can be added as the industry evolves.  
- **Standardization** – Positions Bitcoin Treasury 2.0 companies as a recognized sector with sub-classifications.  

---

## Why Bitcoin Treasury 2.0

### Benefits vs 1.0
- Recurring Income Layer: Converts passive BTC exposure into an operational asset that generates cash-like flows in sats.  
- Compounding Treasury Growth: Yield reinvestment grows BTC holdings per share independent of spot price.  
- Capital Efficiency: Yield helps offset interest expense (if leveraged) and operating costs, improving durability across cycles.  
- Valuation Uplift Potential: Investors can model a blend of asset value (NAV) and operating income (yield), enabling REIT- or infrastructure-style multiples.  
- Ecosystem Leadership: Actively deploying BTC deepens liquidity and positions the company as a contributor to Bitcoin’s financial infrastructure.  

### Where 1.0 Falls Short
- Relies on BTC price, leverage, and dilution to grow NAV/share.  
- Lacks operational KPIs, offering limited visibility into productivity or resilience.  
- No explicit mechanism to compound holdings other than new capital raises.  
- In regions where Bitcoin ETFs are available, investors may prefer those over holding equity in a Treasury 1.0 company, making the 1.0 model less compelling.  
- In markets where companies cannot access robust bond markets, Treasury 1.0 may be ineffective. Example:  
  - A Bitcoin treasury company in Japan could tap the extensive bond market to accelerate BTC holdings.  
  - A Bitcoin treasury company in Canada on junior markets may not be able to access similar debt markets, limiting growth compared to global peers.  

### Geographic Factors
- **United States**: Robust corporate bond markets and multiple Bitcoin ETF options give investors alternatives to Treasury 1.0 firms; Treasury 2.0 differentiation becomes critical.  
- **Japan**: Deep bond markets allow companies to issue debt efficiently, making BTC accumulation through leverage more feasible for Treasury 1.0 and 2.0 companies alike.  
- **Canada**: Junior and mid-tier markets often lack deep bond issuance capacity, limiting Treasury 1.0 companies; Treasury 2.0 yield-enhanced models may be more attractive as they create internal compounding.  
- **European Union**: Bond market access varies by country, and regulatory diversity may affect treasury strategies; Bitcoin ETF penetration is also uneven.  
- **Emerging Markets**: Limited debt markets and fewer regulated ETF options make Treasury 2.0 models particularly appealing, as they generate yield without needing constant external capital.  

---

## Metrics Standard (Scoreboard)

### A. Core Treasury Metrics (1.0 Baseline)

| Metric | Definition | Why It Matters | Limitations |
|--------|------------|----------------|-------------|
| **BTC Holdings** | Total Bitcoin on the balance sheet. | Primary indicator of exposure to BTC price movements. | Tells nothing about productivity or yield. |
| **Market Value of BTC Holdings** | BTC Holdings × Spot BTC Price. | Shows treasury size in fiat terms. | Entirely price-dependent; no measure of capital efficiency. |
| **BTC per Share** | BTC Holdings ÷ Shares Outstanding. | Shows Bitcoin backing per share, easy comparability across firms. | Dilution-sensitive; doesn’t capture debt or yield. |
| **MNAV/share** | (Market Value – Debt) ÷ Shares Outstanding. | Adjusts for leverage; the core “NAV/share” KPI for 1.0 firms. | Still ignores productivity of holdings. |
| **Unrealized Gain/Loss** | Market Value – Cost Basis. | Indicates performance of BTC purchases over time. | Backward-looking; doesn’t capture ongoing yield. |
| **Leverage Ratio** | Debt ÷ Market Value. | Shows capital structure risk and leverage profile. | Does not indicate whether debt is effectively serviced by yield or cash flow. |

### B. Yield-Enhanced Metrics (2.0 Layer)
- **BNAV/share (Bitcoin NAV 2.0)**: (Market Value + Net Yield – Debt) ÷ shares.  
- **LNav (Lightning NAV)**: Net Yield from Lightning operations (routing fees, channel leasing, swaps).  
- **DNav (Derivatives NAV)**: Net Yield from derivatives (covered calls, futures basis trades, funding capture).  
- **ANav (Arbitrage NAV)**: Net Yield from liquidity provisioning / cross-exchange arbitrage / market-making.  
- **CNav (Credit NAV)**: Net Yield from BTC-backed lending, structured credit, synthetic hedges.  
- **Sats per Share (Total)**: (Treasury BTC + earned sats in BTC) ÷ shares.  
- **Sats Yield per BTC (%)**: Annualized sats earned ÷ BTC deployed × 100.  
- **Sats Yield per $1M NAV**: Efficiency measure for comparability.  
- **Compounded Treasury Growth (CTG)**: BTC holdings × (1 + Yield %)^Years.  

### C. Income / Distribution Metrics
- Recurring Yield/share: Sats earned per share, annualized.  
- Dividend Potential: Distributable % of yield without reducing core BTC.  
- Yield-to-Debt Coverage: Yield ÷ annual debt service.  
- Yield-to-Equity Ratio: Yield ÷ market cap.  

### D. Deployment Efficiency Metrics
- Effective Deployment Ratio: Earning capacity ÷ deployed capacity.  
- Return on Deployment: Sats earned ÷ allocated BTC or costs.  
- Weighted APR (blended): Σ(yieldᵢ × allocationᵢ) ÷ Σ allocations.  
- BTC at Work (%): BTC actively deployed ÷ total treasury BTC × 100.  

### E. Risk & Stability
- Yield Volatility (30D, 1Y): Stdev of daily yield ÷ avg daily yield.  
- Stress-Test Yield: Modeled APR under BTC price drawdowns.  
- Treasury Cushion Ratio: Yield ÷ operating expenses.  

### F. Benchmarks / Comparables
- Sats ROI vs T-bills: Yield APR – 10Y UST yield.  
- Sats ROI vs DeFi Yield: Yield APR – stablecoin DeFi yield.  
- Relative NAV Growth vs Peers: MNAV + BNAV vs pure treasuries.  

---

## Deployment Models

Bitcoin Treasury 2.0 yield can be derived from multiple strategies, including those captured in LNav, DNav, ANav, and CNav.

---

## Risks

- **Market Risk**: BTC price volatility affects NAV directly. Yield measured in sats may remain stable, but dollar-denominated value of yield fluctuates with price. Stress scenarios (e.g., 50% BTC drawdowns) should be modeled with impact on BNAV, coverage ratios, and liquidity runway.  
- **Yield Compression / Competition**: As more firms enter Lightning, derivatives, and arbitrage markets, margins shrink. Requires policy discipline and diversification.  
- **Operational Risk**: Custody failures, human error in channel management, software vulnerabilities, or counterparty defaults.  
- **Cost Volatility**: On-chain fees or funding costs can erode net yield.  
- **Regulatory / Accounting Uncertainty**: Lack of global standards on Bitcoin holdings and yield recognition.  
- **Liquidity & Funding Risk**: Yield flows are continuous, but obligations are periodic and lumpy.  
- **Technology & Cybersecurity Risk**: Threats include node hijacking, denial-of-service, and exploits.  
- **Reputational Risk**: Misreporting or yield underperformance undermines investor trust.  

---

## Opportunities

- **Valuation Re-rating**: Hybrid asset + income model can merit premium vs passive treasuries.  
- **Distribution Policy**: Sats-based dividends or buybacks funded by yield.  
- **Partnerships**: Settlement rails, merchant networks, fintech collaborations.  
- **Financial Products**: Yield-backed ETFs, bonds, or structured notes.  
- **Data Advantage**: Telemetry on flows, fee curves, and liquidity demand.  

---

## Governance & Policy Suggestions

- **Deployment Bands**: Define allocation ranges for productive BTC deployment (e.g., 20–40%), requiring board approval outside bands.  
- **Risk Budgeting**: Set limits on counterparties, strategies, leverage, and concentrations.  
- **Audit & Transparency**: Independent reviews of yield metrics, NAV calculations, and operational data.  
- **Capital Allocation**: Rules for reinvestment vs distributions, and conditions for retaining yield as cushion.  
- **Governance Oversight**: Quarterly board reporting on deployment, yield performance, and risk.  
- **Policy Flexibility**: Frameworks reviewed annually, adaptable to fee compression, yield shifts, and new strategies.  

---

## Appendix – Key Formulas

- Market Value = BTC Holdings × BTC Price  
- BTC per Share = BTC Holdings ÷ Shares Outstanding  
- MNAV/share = (Market Value – Debt) ÷ Shares Outstanding  
- BNAV/share = (Market Value + Net Yield – Debt) ÷ Shares Outstanding  
- LNav/DNav/ANav/CNav = Strategy-specific NAV variants  
- Sats per Share (Total) = (Treasury BTC + Earned Sats ÷ 100,000,000) ÷ Shares  
- Sats Yield per BTC (%) = (Annualized Sats Earned ÷ BTC Deployed) × 100  
- Sats Yield per $1M NAV = Annualized Sats Earned ÷ (Market Value ÷ 1,000,000)  
- Compounded Treasury Growth = BTC Holdings × (1 + Yield %)^Years  
- Recurring Yield/share = Annualized Sats Earned ÷ Shares Outstanding  
- Dividend Potential/share = Recurring Yield/share × Distributable %  
- Yield-to-Debt Coverage = Net Yield ÷ Annual Debt Service  
- Yield-to-Equity Ratio = Net Yield ÷ Market Cap  
- Effective Deployment Ratio = Earning Capacity ÷ Total Capacity  
- Return on Deployment = Sats Earned ÷ Costs  
- Weighted APR = Σ (Yieldᵢ × Allocationᵢ) ÷ Σ Allocations  
- BTC at Work (%) = BTC Deployed ÷ Treasury BTC × 100  
- Yield Volatility = Stdev(Daily Yield) ÷ Avg(Daily Yield)  
- Stress-Test Yield ($, –20% BTC) = Net Yield × 0.8 (sats unchanged; converts to $)  
- Treasury Cushion Ratio = Net Yield ÷ Operating Expenses  
- Sats ROI vs T-bills = Yield APR – 10Y Treasury Yield  
- Sats ROI vs DeFi Yield = Yield APR – DeFi Stablecoin Yield  

---

## MIT License

Copyright (c) 2025 Shone Anstey

Permission is hereby granted, free of charge, to any person obtaining a copy of this document and associated documentation files (the "Whitepaper"), to deal in the Whitepaper without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Whitepaper, and to permit persons to whom the Whitepaper is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Whitepaper.

THE WHITEPAPER IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE WHITEPAPER OR THE USE OR OTHER DEALINGS IN THE WHITEPAPER.
