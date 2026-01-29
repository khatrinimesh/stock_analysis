# Portfolio Drawdown Management Decision Tree

## Overview
Drawdowns are inevitable in public markets; the goal is to keep them manageable, not to eliminate them. This decision tree outlines practical techniques to reduce portfolio drawdowns.

---

## Core Principle

```
Drawdowns are INEVITABLE
│
└─→ Goal: Keep them MANAGEABLE (not eliminate)
    │
    └─→ Use multiple techniques in combination
```

---

## Technique 1: Cash Management

```
Cash as Active Position
│
├─→ Direct drawdown reduction
│   └─→ Reduces drawdowns in proportion to cash weight
│       ├─→ 10% cash → 10% drop in holdings = 9% portfolio loss
│       ├─→ 20% cash → 10% drop in holdings = 8% portfolio loss
│       └─→ Formula: Portfolio loss = Holdings loss × (1 - Cash %)
│
└─→ Dual benefits
    ├─→ Cushion: Absorbs portfolio losses
    └─→ Optionality: Provides capital to buy later
```

**Key Insight:** Cash is an active position, not idle money. See "Cash is a Position" write-up for more depth.

---

## Technique 2: Trailing Stops & Exit Rules

```
Systematic Position Reduction
│
├─→ When to apply trailing stops?
│   ├─→ Entire position: Full exit when trend breaks
│   └─→ Partial position: Reduce exposure while holding long-term
│
├─→ Signal: Change in Character
│   └─→ Stock closes below 50-day SMA for FIRST TIME in a run
│       ├─→ May signal trend weakening
│       └─→ Consider: Trim or fully exit
│
└─→ Implementation options
    ├─→ Trailing stop on entire position
    ├─→ Trailing stop on portion (e.g., 50%)
    └─→ Stop-like rules (e.g., close below 50-day SMA)
```

**Decision Rule:** Use trailing stops to systematically downsize positions when trends weaken.

**Reference:** See "Sell Rules" post for more guidance on when to sell.

---

## Technique 3: Hedging Strategy

```
Hedging as Insurance
│
├─→ Purpose
│   ├─→ Primary: Mitigate "left-tail" (crash) risk
│   └─→ NOT primarily to make money
│
├─→ Benefits during sharp declines
│   ├─→ Offsets portfolio losses
│   └─→ Provides liquidity source
│       └─→ Can sell hedges to:
│           ├─→ Fund new hedges
│           └─→ Buy stocks cheaper
│
└─→ Simple Actionable Hedge
    │
    └─→ Buy longer-term put options on S&P 500
        │
        ├─→ Trigger: S&P 500 falls below key moving average
        │   └─→ Example: 21-day EMA
        │
        └─→ Rationale
            ├─→ Crashes often start from oversold conditions
            └─→ NOT from new highs
```

**Decision Rule:** Keep hedging simple rather than overly complex. Many methods exist, but simplicity is key.

---

## Technique 4: New Money Deployment in Downtrends

```
Patience with New Capital
│
├─→ Avoid deploying capital too early
│   └─→ Wait for favorable conditions
│
├─→ When to invest new money?
│   │
│   ├─→ Condition 1: Extreme dislocation
│   │   └─→ Significant price/value gap
│   │
│   └─→ Condition 2: Charts show basing + new uptrend signs
│       ├─→ Base formation visible
│       └─→ Moving-average crossovers confirm trend change
│           └─→ Example: 5 EMA crosses above 20 EMA
│
├─→ Entry approach
│   ├─→ Take smaller initial positions
│   ├─→ Buy on "right side of the V"
│   │   ├─→ After low has likely been set
│   │   └─→ Price is turning up
│   └─→ Avoid catching the falling knife
│
└─→ Position sizing
    └─→ Wait for overall market conditions favorable
        └─→ Then aggressively size up positions
```

**Decision Rule:** Patience is critical. Prefer to invest only when there is extreme dislocation OR when charts show basing plus signs of a new uptrend.

---

## Technique 5: Meaningful Diversification

```
Diversification Strategy
│
├─→ Effective diversification
│   └─→ Exposure to different, relatively uncorrelated factors
│       └─→ Positions don't behave the same way
│
├─→ Ineffective diversification
│   └─→ Multiple highly correlated positions
│       ├─→ Example: Five data-center stocks
│       └─→ Effect: One concentrated bet
│           └─→ Does little to reduce drawdowns
│
└─→ Diminishing returns
    └─→ Beyond certain point, marginal benefit fades quickly
        ├─→ Over-diversifying dilutes returns
        └─→ Without meaningfully improving risk
```

**Decision Rule:** Diversification is useful when it provides exposure to different, relatively uncorrelated factors. Avoid owning multiple highly correlated names.

---

## Complete Decision Flow: Managing Drawdowns

```
Portfolio Drawdown Management Framework
│
├─→ PREVENTIVE MEASURES (Before drawdowns)
│   │
│   ├─→ Hold cash as active position
│   │   ├─→ Determine appropriate cash allocation (10-20%+)
│   │   └─→ Provides cushion + optionality
│   │
│   ├─→ Set trailing stops on positions
│   │   ├─→ Entire position or partial?
│   │   └─→ Monitor for "change in character" signals
│   │       └─→ Stock closes below 50-day SMA (first time)
│   │
│   └─→ Ensure meaningful diversification
│       ├─→ Check correlation between positions
│       └─→ Avoid concentrated bets in correlated names
│
├─→ DEFENSIVE MEASURES (During drawdowns)
│   │
│   ├─→ Activate hedges
│   │   ├─→ S&P 500 below 21-day EMA?
│   │   │   ├─→ YES → Buy longer-term puts on S&P 500
│   │   │   └─→ NO → Monitor conditions
│   │   │
│   │   └─→ During sharp declines
│   │       ├─→ Hedges offset losses
│   │       └─→ Can sell hedges for liquidity
│   │
│   └─→ Exercise patience with new money
│       ├─→ Extreme dislocation present?
│       │   ├─→ YES → Consider smaller initial positions
│       │   └─→ NO → Wait
│       │
│       └─→ Charts showing basing + uptrend?
│           ├─→ Base formation visible?
│           │   ├─→ YES → Check for trend confirmation
│           │   │   └─→ 5 EMA crossing above 20 EMA?
│           │   │       ├─→ YES → Buy on "right side of V"
│           │   │       └─→ NO → Wait
│           │   │
│           │   └─→ NO → Wait
│           │
│           └─→ Market conditions favorable?
│               ├─→ YES → Size up positions aggressively
│               └─→ NO → Maintain smaller positions
│
└─→ ONGOING MONITORING
    ├─→ Review trailing stops regularly
    ├─→ Assess hedge effectiveness
    ├─→ Check position correlations
    └─→ Adjust cash allocation as needed
```

---

## Key Principles Summary

1. **Cash is Active:** Hold cash as a position to reduce drawdowns and provide optionality
2. **Systematic Exits:** Use trailing stops to reduce exposure when trends weaken
3. **Hedge for Insurance:** Protect against left-tail risk, not to make money
4. **Patience Pays:** Wait for extreme dislocation or confirmed uptrends before deploying new capital
5. **Meaningful Diversification:** Focus on uncorrelated factors, not correlated names

---

## Implementation Checklist

### Before Drawdowns Occur
- [ ] Determine appropriate cash allocation (10-20%+)
- [ ] Set trailing stops on positions (full or partial)
- [ ] Review position correlations
- [ ] Ensure meaningful diversification

### During Drawdowns
- [ ] Monitor for hedge triggers (S&P 500 below 21-day EMA)
- [ ] Activate hedges when conditions warrant
- [ ] Exercise patience with new capital
- [ ] Wait for extreme dislocation or confirmed uptrends
- [ ] Use "right side of V" entry method

### Ongoing
- [ ] Review trailing stops regularly
- [ ] Monitor "change in character" signals (50-day SMA breaks)
- [ ] Assess hedge effectiveness
- [ ] Check position correlations periodically
- [ ] Adjust cash allocation based on market conditions

---

## Risk Management Notes

- **Drawdowns are inevitable:** Focus on managing them, not eliminating them
- **Combine techniques:** Use multiple methods together for best results
- **Keep it simple:** Avoid overly complex hedging strategies
- **Stay disciplined:** Follow systematic rules rather than emotional decisions
- **Maintain optionality:** Cash provides flexibility to act when opportunities arise

---

## References

- "Cash is a Position" write-up (for deeper cash management discussion)
- "Sell Rules" post (for detailed exit strategy guidance)
- Deeper bear-market piece (planned separately)

