# Expanded Addendum D — DNav (Derivatives NAV)

## Introduction and Definition
DNav (Derivatives NAV) quantifies yield from overlay strategies on BTC holdings, such as covered calls (selling call options on held BTC for premiums), basis trades (exploiting futures-spot discrepancies), and perpetual funding capture (earning rates on futures positions). This variant monetizes volatility without liquidating core assets.

## Benefits and Objectives
- **Benefits**: Generates premium income (e.g., 2-22% yields in 2025 ETFs); hedges downside risk; enhances returns in sideways markets.
- **Objectives**: Boost treasury durability across cycles; provide weekly/monthly income; attract investors seeking hybrid asset-income models.

## Expanded Example Company: CoverCorp Ltd.
CoverCorp Ltd. (LSE: COVR) holds 500 BTC (~$62M at $124,000/BTC), 15M shares, no debt. It deploys 20% (100 BTC) to covered calls on platforms like Deribit, collecting 1% monthly premium (1 BTC). Over 12 months in 2025:
- Premiums total 12 BTC; funding capture adds 3 BTC.
- Net yield: 12 BTC (after fees ~3 BTC).
- Inspired by ETFs yielding 9-22% on similar strategies.

## Mathematical Framework
Assumptions: Monthly premium 1%; basis spread 0.2%; funding 0.6%.

1. **Option Premium Yield**: Annualized premiums collected.  
   Formula: (Monthly Premium % × 12) / Treasury × 100.  
   Calculation: (0.01 × 12) / 500 × 100 = 0.024%.

2. **Funding Capture**: Gains from perpetual rates.  
   Formula: Deployed × Avg Rate.  
   Calculation: 100 × 0.006 = 0.6 BTC.

3. **Basis Spread**: Futures-spot differential.  
   Formula: Deployed × Spread.  
   Calculation: 100 × 0.002 = 0.2 BTC.

4. **DNav Yield (Blended Annualized)**: Sum of components minus fees (1%).  
   Formula: [(Premiums + Funding + Basis) / Treasury] × 100 × (1 - Fees).  
   Calculation: Gross = 12 + 3 + 1 = 16 BTC; Net = 16 × 0.99 = 15.84 BTC.  
   Yield: (15.84 / 500) × 100 = 3.17%.

5. **DNav Value**: Treasury plus unrealized gains.  
   Formula: Treasury + Net Yield.  
   Calculation: 500 + 15.84 = 515.84 BTC (~$64M).

## Key Metrics
| Metric | Description | Formula/Example Calculation | Example Value |
|--------|-------------|-----------------------------|---------------|
| **Option Premium Yield** | Annualized premiums | (Monthly % × 12) / Treasury × 100 | 2.4% |
| **Funding Capture** | Perpetual rate gains | Deployed × Avg Rate | 0.6% |
| **Basis Spread** | Futures-spot diff | Deployed × Spread | 0.2% |
| **BTC Hedged** | Portion under derivatives | (Deployed / Treasury) × 100 | 20% |
| **Yield Volatility** | Stdev of monthly yields | Stdev(Monthly) / Avg | ±1.5% |
| **Net Yield After Fees** | Blended after costs | Gross × (1 - Fees) | 3.17% |

## Risks
- **Volatility**: Calls exercised in rallies cap upside.
- **Counterparty**: Exchange defaults (mitigated by regulated platforms).
- **Yield Compression**: Tighter spreads in efficient markets.

## Opportunities
- **Income Boost**: Up to 22% in high-vol periods.
- **ETFs/Products**: Yield-backed notes.
- **Hedging**: Combine with basis for stable returns.

## Governance & Policy Suggestions
- Leverage limits: <2x; strategy diversification.
- Quarterly stress-tests for 50% drawdowns.
- Independent audits of positions.

## Integration with BNAV
BNAV/share: ($62M + $1.96M (15.84 BTC × $124,000) - $0) ÷ 15M = $4.264 (vs. MNAV $4.133; +3.17% uplift).

## Notes
2025 yields range 2-22%; consult derivatives experts.
