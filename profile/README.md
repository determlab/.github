# determlab

**Deterministic, auditable infrastructure for autonomous & AI systems.**

LLM agents are good at deciding *what* to do — and unreliable at doing it the
same way twice. We build the layer underneath: typed, gated, validated, logged.
Same input, same result, every run.

| Project | What it does |
|---|---|
| **[SHAL](https://github.com/determlab/shal)** | Turn a whole lab — hardware *and* software — into safe, typed, permission-gated tools for an AI agent. Writes are gated; reads aren't. |
| **[Bricks](https://github.com/determlab/bricks)** | Deterministic execution — compose a pipeline once, run it forever. No LLM in the loop, zero tokens per run. |
| **[Predictor](https://github.com/determlab/predictor)** | ML-driven fail-fast for hardware test — abort a suite early when failure is predicted, with safety rules before any model. |

Alpha · MIT · Python · built in the open.
