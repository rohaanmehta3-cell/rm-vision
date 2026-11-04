# RM Investment Co

**Building for a world where every investment thesis is continuously tested.**

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

We envision a **bench of AI-assisted PMs** with distinct mandates. One might study how an earnings surprise changes a long-term thesis. Another might look for a short-lived trading opportunity. A third might assess what the same event means for the portfolio’s overall exposure.

Each PM would propose an action within its mandate and show the evidence, time horizon, sizing rationale and conditions for revisiting it. The harness would put those proposals on a common footing and surface conflicts, overlapping exposures and competing uses of capital. A human would decide which ideas earn risk budget and approve any trades.

Over time, we want to learn which PMs add value under which conditions. That means tracking how their calls age, whether simulated opportunities survive real trading costs and how each proposal contributes to the portfolio after accounting for shared exposures.

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

The project is in development and review. The current focus is the research and oversight foundation, including specialist analysis, traceable evidence, dependable reporting and explicit controls. The workflow above describes the direction of the build. Implementation details stay private.

Questions about the vision or architecture are welcome through [GitHub Issues](https://github.com/rohaanmehta3-cell/rm-vision/issues).

*This project overview makes no performance claims and does not constitute an investment offering.*
