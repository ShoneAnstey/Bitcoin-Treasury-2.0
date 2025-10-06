# Expanded Addendum B — LNav (Lightning NAV)

## Introduction and Definition
LNav (Lightning NAV) captures the net yield generated from operations on the Bitcoin Lightning Network, including routing fees (earned from forwarding payments), channel leasing (renting liquidity to others), and swap fees (facilitating atomic swaps). This variant is particularly suited for companies focused on Bitcoin infrastructure, as it allows self-custodial BTC to be deployed productively without selling the underlying asset. Yield is denominated in satoshis (sats), the smallest unit of Bitcoin, providing a recurring income stream that compounds treasury growth independently of spot price fluctuations.

## Benefits and Objectives
- **Benefits**: Enhances capital efficiency by turning passive BTC holdings into an active revenue source; deepens Bitcoin ecosystem liquidity; offers low counterparty risk due to self-custody; potential for high scalability as network adoption grows (e.g., Lightning capacity declined 20% in 2025 but remains viable for yields up to 24%).
- **Objectives**: Achieve compounding growth per share; offset operational costs; position the company as a Lightning Service Provider (LSP) to capture fees from increasing transaction volumes.

## Expanded Example Company: NodeCo Inc.
NodeCo Inc. is a hypothetical public fintech company (TSX: NODE) with a total treasury of 500 BTC (market value ~$62M at $124,000/BTC), 20M shares outstanding, and no debt. It deploys 20% (100 BTC) across multiple Lightning nodes, maintaining 70 BTC as effective capacity after reserves for rebalancing and fees. Over a 90-day quarter in 2025:
- Routing fees dominate (80% of yield), with channel leasing contributing the rest.
- Net yield: 0.18 BTC (after on-chain costs ~0.02 BTC).
- This aligns with real-world tests, such as deploying ~20 BTC for 24 days yielding ~24% annualized (weighted APR), or ~2.5% simple aggregate.
- Scaling to full treasury could project ~4.5 BTC annual yield at similar rates.

## Mathematical Framework
Here, we expand the formulas with step-by-step calculations for transparency. Assumptions: BTC price $124,000; period 90 days; uptime 95%; routing success rate 99%.

1. **Effective Capacity**: Total deployed BTC minus reserves for liquidity management.  
   Formula: Deployed BTC × (1 - Reserve Ratio).  
   Calculation: 100 × (1 - 0.30) = 70 BTC.  
   (Reserve ratio ~30% for rebalancing, based on 2025 network volatility.)

2. **Routing Efficiency**: Measures successful transaction forwarding.  
   Formula: Uptime % × Routing Success Rate.  
   Calculation: 0.95 × 0.99 = 0.9405 (94.05%).

3. **Weighted APR (Annualized Yield)**: Blended return accounting for variable fees.  
   Formula: (Net Yield (BTC) / (Effective Capacity × Period (days))) × 365 × 100.  
   Calculation: First, net yield = gross fees - costs = 0.20 - 0.02 = 0.18 BTC.  
   Then: (0.18 / (70 × 90)) × 365 × 100 = (0.18 / 6,300) × 365 × 100 ≈ 0.002857 × 365 × 100 ≈ 1.04%.  
   (This is conservative; higher network demand can yield 5-24% as seen in 2025 tests.)

4. **LNav Value**: Deployed capital plus accumulated yield.  
   Formula: Effective Capacity + Net Yield.  
   Calculation: 70 + 0.18 = 70.18 BTC (~$8.70M USD).

5. **Compounded Yield Projection (1 Year)**: Assuming reinvestment.  
   Formula: Deployed BTC × (1 + Weighted APR/100).  
   Calculation: 100 × (1 + 0.0104) = 101.04 BTC.

## Key Metrics
Expanded table with additional metrics for comprehensive reporting.

| Metric | Description | Formula/Example Calculation | Example Value |
|--------|-------------|-----------------------------|---------------|
| **Effective Capacity** | BTC actively earning yield after reserves | Deployed × (1 - Reserves) = 100 × 0.70 | 70 BTC |
| **Routing Efficiency** | Success rate of forwarded payments | Uptime × Success Rate = 0.95 × 0.99 | 94.05% |
| **Weighted APR** | Annualized sats yield per BTC | (Net Yield / (Capacity × Days)) × 365 × 100 | 1.04% |
| **Uptime** | Node operational percentage | (Operational Hours / Total Hours) × 100 | 95% |
| **BTC at Work** | Percentage of treasury deployed | (Effective Capacity / Total Treasury) × 100 | 14% |
| **Yield Volatility (30D)** | Standard deviation of daily yields | Stdev(Daily Yield) / Avg Daily Yield | ±0.5% |
| **Net Sats Earned** | Cumulative sats after costs | Net Yield × 100,000,000 | 18,000,000 sats |

## Risks
- **Operational**: Node downtime or software exploits reducing uptime.
- **Yield Compression**: Increased competition on Lightning (e.g., capacity drop 20% in 2025) shrinks fees.
- **Cost Volatility**: On-chain fees spiking during congestion.
- **Market**: BTC price drops affect dollar-denominated yield.

## Opportunities
- **Scalability**: As Lightning adoption grows (e.g., more businesses integrating in 2025), yields could rise to 9-24%.
- **Partnerships**: Collaborate with merchants for exclusive routing.
- **Valuation Uplift**: REIT-like multiples from recurring sats income.

## Governance & Policy Suggestions
- **Deployment Bands**: 10-30% of treasury; board approval for deviations.
- **Risk Budgeting**: Limit to 5-10 nodes; diversify geographies.
- **Audit & Transparency**: Quarterly independent reviews of yield data.
- **Capital Allocation**: Reinvest 70% of yield; distribute 30% as sats dividends.

## Integration with BNAV
LNav rolls into BNAV/share: (Market Value of BTC + LNav Net Yield - Debt) ÷ Shares. For NodeCo: ($62M + $22,320 (0.18 BTC × $124,000) - $0) ÷ 20M = $3.101 (vs. MNAV $3.10; +0.04% uplift). Stress-test: 20% BTC drop reduces dollar yield but sats remain stable.

## Notes
Based on 2025 market data; adapt for company-specifics. For real-world inspiration, see LSPs achieving 9.7% yields on nodes.

