# TradingAgent

**Agent-as-a-Service for market research and controlled trading workflows.**

TradingAgent researches market signals, explains decisions, and validates actions through simulation and risk controls.

面向量化交易研究的 Agent：在仿真、风控和人工审批约束下研究市场信号并解释交易决策。

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | Ticks, fundamentals, filings, news, risk events |
| Models | Time-series models, market reasoner, policy model |
| Training | Research SFT, simulation-based reinforcement learning |
| Inference | Streaming signals, scenario analysis, decision support |
| Harness | Market data, risk, simulation, approval tools |
| Eval | Backtests, drawdown, slippage, compliance |

## Initial scope

- Separate research, simulation, and live execution.
- Require human approval before consequential orders.
- Keep assumptions, data timestamps, and risk limits visible.

## Roadmap

- [ ] Point-in-time data interface
- [ ] Strategy simulation harness
- [ ] Risk and compliance rules
- [ ] Explainable signal research
- [ ] Paper-trading evaluation

## Engineering principles

- No live execution by default.
- Prevent look-ahead leakage.
- Optimize risk-adjusted outcomes, not raw returns.

