# RM Investment Co

**Building an AI-native investment platform where a small team can run a bench of specialist PMs, continuously test their ideas, and allocate risk as the evidence changes.**

Markets move faster than any team can read. AI could change what a small investment team is capable of by giving it the reach to follow more companies, the capacity to test more ideas, and the memory to learn from every decision.

We’re building toward an investment and trading platform that connects research, risk and execution in one feedback loop. A thesis should carry its evidence, its strongest counterargument and the conditions that would invalidate it. When those conditions change, the team should be able to see what changed, which positions are exposed and whether the original decision still holds.

## What becomes possible

- **Investing becomes continuous.** A new filing, earnings call or market move can prompt a review of the specific assumptions it affects. Over time, a team can maintain more live theses and revisit them as evidence changes.
- **Trading becomes a testable process.** A signal can be replayed against historical data, stressed across market regimes and evaluated after costs. Live fills and slippage can then show where the strategy behaves differently from the test.
- **Portfolio risk becomes part of every decision.** Before a trade, the team can see what it adds to existing exposures, where liquidity could constrain an exit and how losses might compound under stress.
- **Decisions become a research asset.** With a record of what the team knew and expected at the time, it can distinguish a sound decision with a bad outcome from a flawed process that happened to work.

## Where the edge comes from

We believe the durable edge is in the **harness around the models**. Models will improve and become easier to swap. The harness determines what evidence they see, what tests an idea must pass, who can commit capital and what the system learns after a decision.

That means giving each proposal the same basic record: the evidence available at the time, the strongest counterargument, the conditions that would invalidate it and the risks it adds to the book. The harness would check for stale data, enforce portfolio limits and route exceptions to a human. It would also keep a record of rejected ideas alongside approved trades, so we can study what our filters caught and what they missed.

## A bench of portfolio managers

We’re exploring four complementary mandates. Each would have a defined universe, time horizon, benchmark and risk budget.

| PM mandate | What it looks for | How it earns risk budget |
| --- | --- | --- |
| **Macro** | Changes in growth, inflation, policy and liquidity that could reprice rates, currencies or equity indices. | States what the market appears to price in, maps upside and downside scenarios, and identifies what would invalidate the view. |
| **Fundamental equities** | Gaps between a company’s operating trajectory and the expectations implied by its price. | Connects filings and earnings evidence to a valuation range, a catalyst and a clear downside case. |
| **Systematic quant** | Repeatable signals across a defined universe, with explicit rules for entry, sizing and exit. | Shows out-of-sample results, sensitivity to parameters and regimes, and viability after turnover, transaction costs and capacity constraints. |
| **Event-driven** | Time-bound opportunities around earnings, corporate actions and other identifiable catalysts. | Specifies the event window, scenario payoffs, liquidity and gap risk, and what would justify exiting early. |

A single inflation surprise might produce a macro proposal to reduce duration, a systematic signal to cut equity risk and a fundamental proposal to buy a company into weakness. The harness would map those proposals to the existing book, surface shared exposures and compare the risk each one adds. People would decide which ideas receive capital and approve trades.

We would evaluate each mandate against its own benchmark and constraints, then judge what it contributes to the combined book after costs. Capital would follow the evidence through a staged path from historical testing to shadow portfolios and, where approved, a limited live risk budget. The record would capture where assumptions broke, where execution diverged from simulation and whether the mandate added a distinct source of return or duplicated existing exposure.

## How the loop works

The diagram shows the target workflow. People own investment decisions and approve trades. AI helps gather evidence, challenge assumptions and monitor what changes.

```mermaid
flowchart TD
    A["Market data, filings and news"] --> B["AI-assisted research and evidence gathering"]
    B --> C["PM bench proposes ideas by mandate"]
    C --> D["Harness checks evidence and tests assumptions"]
    D --> E["Harness compares proposals and checks portfolio limits"]
    E --> F{"Human decision"}
    F -->|"Defer or decline"| G["Record rationale and review triggers"]
    F -->|"Approve"| H["Execute within approved limits"]
    H --> I["Monitor exposures, fills and outcomes"]
    G --> J["Review decisions as evidence changes"]
    I --> J
    J --> B
```

## Where we are today

The project is in development and review. The current focus is the research and oversight foundation, including specialist analysis, traceable evidence, dependable reporting and explicit controls. The PM mandates, capital allocation process and workflow above describe the direction of the build. Implementation details stay private.

Questions about the vision or architecture are welcome through [GitHub Issues](https://github.com/rohaanmehta3-cell/rm-vision/issues).

*This project overview makes no performance claims and does not constitute an investment offering.*
