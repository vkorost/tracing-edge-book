# Glossary

**Alpha.** Return in excess of what a benchmark or risk model predicts. In the manuscript, alpha is the reward a trading edge produces before decay, crowding, and transaction costs erode it. Published predictors lose the majority of their in-sample alpha after publication.

**Adverse selection.** The risk that a resting order is filled by a counterparty who possesses superior information about the direction of the next price move. In the Glosten-Milgrom framework, the bid-ask spread is set so that profits from uninformed orders offset losses from informed ones.

**Backwardation.** A futures term structure in which the front contract trades below the spot price, indicating elevated current demand or constrained supply. A long futures position in backwardation collects positive roll yield as each contract converges upward toward spot at expiration.

**Carry.** The return collected simply for holding a position when price does not move. In equities, carry is dividend yield minus funding cost. In foreign exchange, it is the interest-rate differential. In futures, it is the spread between spot and futures price divided by time remaining.

**Charm.** The options Greek that measures how delta changes with respect to the passage of time. As options approach expiration, charm causes delta to drift, particularly overnight, releasing dealers from hedging obligations and generating systematic order flow in the underlying.

**Contango.** A futures term structure in which the front contract trades above the spot price. A long futures position in contango bleeds negative roll yield on each contract roll. The VIX curve is in contango approximately 80 percent of the time.

**Delta.** The sensitivity of an option's price to a one-unit change in the price of the underlying. At expiration, delta approximates the probability that the option finishes in the money. A 10-delta short strike carries a roughly 10 percent chance of expiring with value.

**Delta-hedging.** The practice of buying or selling the underlying asset to offset the delta exposure of an options position, keeping the combined position directionally neutral. When dealers are net short options, their delta-hedges are mechanical, involuntary, and continuous.

**Drawdown.** The decline from a portfolio's peak equity to its subsequent trough, typically expressed as a percentage. In the manuscript, drawdown is the central measure of survivability: a 70 percent drawdown on 25 percent of net worth is survivable; the same drawdown on 80 percent of net worth is a life event.

**EWMA (exponentially weighted moving average).** A moving average that assigns geometrically declining weights to older observations, making the estimate more responsive to recent data. The EWMAC framework in the manuscript uses pairs of EWMAs at six speeds to capture trends across multiple time horizons.

**Gamma.** The rate at which an option's delta changes as the underlying moves. When aggregate dealer gamma is positive, hedging flows dampen volatility. When aggregate dealer gamma is negative, hedging flows amplify moves, extending trends and widening daily ranges.

**Implied volatility.** The market's forward-looking estimate of how much an asset's price will fluctuate, derived from current option prices. Since 1990, implied volatility on the S&P 500 has exceeded subsequent realized volatility in approximately 85 percent of calendar months.

**Level II.** A real-time display of the limit order book showing resting bid and ask orders at multiple price levels, along with their sizes. Tape readers use Level II to observe offer thinning, bid stacking, and sweep orders before those signals appear on a price chart.

**Limit order book.** The electronic record of all resting buy and sell orders at each price level for a given instrument. The composition of orders in the book, captured by metrics such as order flow imbalance, explains the majority of short-term price variance.

**Mandate.** A binding institutional obligation that compels a participant to trade regardless of price. Index trackers must buy additions, pension funds must rebalance to target weights, leveraged ETFs must rebalance daily. The mandate, not ignorance, is what supplies the premium in forced-flow edges.

**Market maker.** A participant who posts resting bids and offers on both sides of the book, earning the spread in exchange for bearing the risk of adverse selection. In the manuscript, market makers also appear as options dealers whose gamma-hedging flows shape intraday volatility regimes.

**Mean reversion.** The tendency of a price that has moved to an extreme to return toward a central value. In the manuscript, mean reversion is a contested edge family: alive in niches that require qualitative judgment, decayed where the signal can be reduced to a simple quantitative rule.

**Realized volatility.** The volatility that the market actually delivers over a measured period, calculated from observed price changes. The persistent gap between implied volatility and lower realized volatility is the structural foundation of the volatility risk premium.

**Sharpe ratio.** The ratio of a strategy's excess return (above the risk-free rate) to the standard deviation of that return, measuring risk-adjusted performance. In the manuscript, the CBOE PutWrite Index achieved a Sharpe ratio approximately 46 percent higher than the S&P 500 Total Return Index.

**Short interest.** The percentage of a stock's tradeable float that has been sold short. In the manuscript, short interest above 30 percent amplifies breakout magnitude by creating forced covering demand when price moves against short sellers.

**Slippage.** The difference between the expected price of a trade and the price at which it actually executes. Slippage arises from market impact, latency, and liquidity withdrawal, and it is one of the frictions that separates theoretical backtest returns from live performance.

**Spread.** The difference between two related prices. In microstructure, the bid-ask spread is the cost of crossing from one side of the book to the other. In carry trades, spread refers to the yield or price differential between two instruments. In merger arbitrage, it is the gap between the market price and the offer price.

**Theta.** The rate at which an option's value decays with the passage of time, all else equal. Theta is the source of profit for premium sellers: if the underlying stays near the strike, time decay erodes the option's value, and the seller keeps the collected premium.

**Tracking error.** The deviation of a fund's returns from its benchmark index, typically measured as annualized standard deviation. Index fund managers accept higher purchase prices on newly added stocks because every basis point of tracking error is a basis point of career risk.

**VIX.** The CBOE Volatility Index, a model-free measure of the market's expected 30-day volatility for the S&P 500, derived from option prices across strikes. In the manuscript, the VIX serves as both a fear gauge at sentiment extremes and the reference index for the VIX basis carry trade.

**Volatility risk premium (VRP).** The persistent gap between implied volatility and subsequent realized volatility, representing the market's chronic overpayment for downside protection. The premium is structural, anchored in institutional hedging mandates and behavioral loss aversion, and has been positive across asset classes for decades.

**VWAP (volume-weighted average price).** The average price of an instrument over a given period, weighted by the volume traded at each price level. In the manuscript, VWAP serves as an intraday reference for entries and as a diagnostic: repeated crossings of VWAP in a short window indicate directionless chop.

**Z-score.** The number of standard deviations by which a current value differs from its historical mean. In pairs trading, a z-score above 1.5 on the spread between two correlated stocks signals divergence wide enough that historical tendency favors convergence.

**0DTE (zero days to expiration).** Options contracts that expire on the same day they are traded. 0DTE volume has grown from 0.08 million monthly contracts in 2011 to more than 34 million by 2023, now exceeding 40 percent of all index options volume and concentrating dealer gamma hedging into single-session windows.
