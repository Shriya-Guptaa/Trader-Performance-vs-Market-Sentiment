# Summary: Trader Performance vs Market Sentiment

## Methodology
- Merged sentiment + trade data on daily level  
- ~211K trades analyzed after cleaning  
- Features:
  - Daily PnL, win rate, trade count  
  - Avg trade size (USD), long ratio  
  - Net PnL (after fees), drawdown  

- Aggregations:
  - Sentiment-level (Fear, Greed, Extreme Greed, Neutral)  
  - Account-level + segment-level  

- Statistical test:
  - Mann-Whitney U (Fear vs Greed PnL)

---

## Key Insights

### 1. Performance vs Sentiment
- **Median Daily PnL**
  - Fear: ~79K (highest)  
  - Greed: ~35K  
  - Neutral: ~0  
  - Extreme Greed: negative  

- **Win Rate**
  - Extreme Greed: ~49% (highest)  
  - Neutral: ~31% (lowest)  

→ Higher win rate ≠ higher profitability  

---

### 2. Behavior Changes

- **Trade Frequency**
  - Fear: ~4183 trades/day (highest)  

- **Avg Trade Size**
  - Fear/Greed: ~5900 USD  
  - Neutral: ~3700 USD  

- **Long Ratio**
  - Extreme Greed: ~0.52 (bullish bias)  

→ Traders are more aggressive in Fear & Greed  

---

### 3. Risk (Drawdown)
- Extreme Greed: ~-1200 (worst)  
- Fear/Greed: lower drawdowns  

→ Extreme optimism → higher downside risk  

---

### 4. Segmentation

- **Consistent Traders**
  - Win rate up to ~82% (Extreme Greed)  
  - Stable performance across sentiments  

- **Inconsistent Traders**
  - Large losses in Extreme Greed  

- **Frequent Traders**
  - No consistent outperformance  

→ Skill level > sentiment  

---

## Strategy Recommendations

### Rule 1: Position Sizing
- Fear → increase exposure (highest PnL ~79K)  
- Extreme Greed → reduce / skip trades  

---

### Rule 2: Entry Filtering
- Inconsistent traders:
  - Trade only in Neutral / moderate sentiment  
  - Avoid extreme sentiment  

---

### Rule 3: Risk Control
- Use sentiment as risk signal:
  - Fear → opportunity  
  - Extreme Greed → risk  

---

## Conclusion
- Sentiment strongly impacts:
  - PnL (79K → negative shift)  
  - Behavior (~4183 trades/day in Fear)  
  - Risk (~-1200 drawdown in Extreme Greed)  

→ Sentiment-based filtering improves trading outcomes.
