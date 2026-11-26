### Mohamud Mohamud

I build evaluations that catch AI agents handing in wrong work they believe is right, and I study why it happens,
from agent traces down to model internals.

- **[AssumptionBench](https://github.com/mohamud1961/Aether#assumptionbench):** can you trust an agent's "done"?
  Realistic work tasks where nothing prompts a check. Frontier agents looked at the deciding evidence in 8 of 8
  runs and acted on it in 0 of 8. 9 of 10 tasks pass five validity checks, including an attack on the grader.
- **[unstated-values](https://github.com/mohamud1961/unstated-values):** models give values their context doesn't
  state. Their own activations read "not stated" (probe AUROC 1.00), and a probe-gated push cuts copied values
  33 → 0 at 7B. Open benchmark, 7-model survey and full report.
- **[core-agent](https://github.com/mohamud1961/core-agent):** a lean agent with the same passes as Codex on 25
  Terminal-Bench 2.1 tasks, 26% cheaper.
- **[Aether](https://github.com/mohamud1961/Aether):** the lab behind all three: more than 4,000 graded agent
  trials, the failure map and the negative results.

**Open to** research engineering and evaluation roles, contracts building benchmarks and RL environments, and
research grants. UK, remote. [LinkedIn](https://www.linkedin.com/in/mohamud-m-33558328a/)
