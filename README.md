# Lester Leong

### AI engineer building reliable, evaluated agentic systems.

I bring quant-grade statistical rigor to LLM engineering: evals, error bars, and not shipping on noise. The discipline comes from running multi-agent systems where a wrong answer does not fail a unit test, it costs real money. PhD in Finance (ML time series).

I work at the intersection of AI engineering and quantitative finance: multi-agent orchestration, LLM evaluation and reliability, and production systems that have to be right, not just plausible.

---

## Featured

### llm-evalgate
Eval gates and reliability primitives for LLM pipelines, with a confidence interval on every metric and a statistically honest regression gate. The full eval surface (deterministic gates, calibrated LLM-as-judge, agentic-trace evals, multiple-comparisons-corrected CI gating), in CI, with the stats done right. Pure standard library at the core, fully offline-testable, deterministic under a seed.

`pip install llm-evalgate`  ·  [GitHub](https://github.com/LesterALeong/llm-evalgate)  ·  [PyPI](https://pypi.org/project/llm-evalgate/)

### anachron
A look-ahead leakage detector for LLM agents: does an agent use information it could not have had at the time? It scores the leakage rate of an agent's tool calls under an as-of-date constraint, graded with the point-in-time rigor of quantitative backtesting — survivorship, restatements, transaction cost. The discipline that keeps a trading backtest honest, generalized to agents.

[GitHub](https://github.com/LesterALeong/anachron)

### Thousand Token Wood
Five small-model (Qwen2.5-3B) creature-agents in an emergent economy: an experiment in multi-agent dynamics under real economic pressure. Served on vLLM / Modal with a Gradio interface. Built for the Hugging Face build-small hackathon.

[Live demo](https://huggingface.co/spaces/build-small-hackathon/thousand-token-wood-sim)

**Also building, in the same spirit:** [finance-paper-replication](https://github.com/LesterALeong/finance-paper-replication) — replicating quant research papers and publishing the honest results — and [finance-research-factory](https://github.com/LesterALeong/finance-research-factory), a multi-agent q-fin research pipeline with alpha-protection built in.

---

## Writing

I write about AI engineering, evals, quantitative finance, and building systems you can actually trust.

- [The Year I Tried to Beat the Market and Found the Edge Hiding in My Own Backyard](https://medium.com/gradient-growth/the-year-i-tried-to-beat-the-market-and-found-the-edge-hiding-in-my-own-backyard-ee673bc39f72?source=friends_link&sk=ab4a59046940dd49c79331e52bb1721a) — what a year of building a one-person quant research desk taught me about alpha, honesty, and rigor: pre-registration, survivorship-free backtests, and telling an edge apart from beta in a costume.
- [I Audited My Own Eval Gate. It Was Failing Builds Five Times Too Often.](https://medium.com/gradient-growth/i-audited-my-own-eval-gate-it-was-failing-builds-five-times-too-often-0075e1195340?sk=bff4bb2dc0b54be039f2b857061438ff) — the multiple-comparisons bug hiding in most CI eval gates, with code and real numbers.
- More on [Medium](https://medium.com/gradient-growth).

---

## Stack

Python · LLMs · multi-agent systems · LLM-as-judge and evals · RAG · agent reliability · vLLM · Modal · Gradio · Hugging Face · bootstrap, hypothesis testing, and experimental design · pandas / NumPy

---

Open to conversations about hard problems in agent reliability and AI for finance.

- LinkedIn: https://www.linkedin.com/in/lester-a-leong
- X: https://x.com/RealLesterLeong
- Medium: https://medium.com/gradient-growth
