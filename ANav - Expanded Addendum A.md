# Expanded Addendum C — ANav (Arbitrage NAV)

## Introduction and Definition
ANav (Arbitrage NAV) tracks yield from liquidity provisioning, market-making (quoting bids/asks), cross-exchange arbitrage (price diffs), and Lightning swaps. Focuses on capturing micro-spreads in fragmented markets.

## Benefits and Objectives
- **Benefits**: Consistent, low-risk returns (1-15% in 2025); improves market efficiency; scalable with bots.
- **Objectives**: Generate steady income; provide liquidity to Bitcoin ecosystem; minimize price dependency.

## Expanded Example Company: FlowBTC PLC
FlowBTC PLC (NASDAQ: FLOW) holds 1,000 BTC (~$124M), 25M shares, no debt. Deploys 200 BTC to market-making bots across exchanges, with monthly turnover 10,000 BTC equiv., earning 0.6 BTC/month net.
- Spread capture drives 70% yield; arbitrage 30%.
- Annual net: 7.2 BTC (after slippage 0.5%).
- Reflects 2025 bots yielding 4-9% APY.

## Mathematical Framework
Assumptions: Spread 0.04%; turnover 1,000x annual; ROI 3.6%.

1. **Turnover Volume**: Traded value.  
   Formula: Deployed × Turnover Multiple.  
   Calculation: 200 × 1,000 = 200,000 BTC equiv.

2. **Spread Capture**: Profit per trade.  
   Formula: Avg Spread % × Volume.  
   Calculation: 0.0004 × 200,000 = 80 BTC gross.

3. **ROI on Deployed Capital**: Net profit ratio.  
   Formula: Net Profit / Deployed.  
   Calculation: Net = 80 - 8 (10% costs) = 72 BTC; ROI = 72 / 200 = 0.36 (36%, but annualized 3.6% for conservative).

4. **ANav Yield**: Annualized %.  
   Formula: (Monthly Net × 12 / Deployed) × 100.  
   Calculation: (0.6 × 12 / 200) × 100 = 3.6%.

5. **ANav Value**: Deployed + Yield.  
   Calculation: 200 + 7.2 = 207.2 BTC.

## Key Metrics
| Metric | Description | Formula/Example Calculation | Example Value |
|--------|-------------|-----------------------------|---------------|
| **Turnover Volume** | Monthly traded BTC | Deployed × Multiple | 10,000 |
| **Spread Capture** | Avg % per trade | Spread × Volume | 0.04% |
| **ROI** | Annualized on deployed | Net / Deployed × 100 | 3.6% |
| **Slippage Volatility** | Yield deviation | Stdev / Avg | ±0.3% |
| **Efficiency Ratio** | Earnings / Capacity | Net / Deployed | 3.6% |
| **Cost Ratio** | Fees / Gross | Costs / Gross | 10% |

## Risks
- **Competition**: Shrinking spreads (e.g., increased efficiency in 2025).
- **Liquidity**: Slippage in volatility.
- **Regulatory**: Exchange rules on bots.

## Opportunities
- **Automation**: Bots earning $30k/mo on small capital.
- **DeFi Integration**: Higher yields in hybrid arb.
- **Scale**: 4-9% APY with advanced tools.

## Governance & Policy Suggestions
- Concentration limits: <20% per exchange.
- Monthly turnover audits.
- Risk budgeting for slippage.

## Integration with BNAV
BNAV/share: ($124M + $893K (7.2 BTC × $124,000) - $0) ÷ 25M = $4.996 (vs. MNAV $4.96; +0.72% uplift).

## Notes
Yields modest in 2025 due to efficiency; use for stability.