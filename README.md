# TRACE

**Causal investigation across systems.**

> Why did it change?

TRACE explores how to move from an observed change to an evidence-backed explanation by following dependencies, timelines, relationships, and causal candidates across system boundaries.

## Why it exists

Correlation is easy to mistake for causation.

TRACE keeps the investigation explicit: connect events, inspect dependencies and history, evaluate evidence and counterevidence, and preserve competing causal candidates instead of collapsing uncertainty too early.

## What it does

- connect related events
- reconstruct causal timelines
- traverse dependencies
- distinguish correlation from causal evidence
- preserve competing explanations
- produce inspectable investigation state

## Use cases

| Use case | Question answered |
| --- | --- |
| Root-cause research | What could explain the observed change? |
| Dependency analysis | Which related systems provide causal context? |
| Timeline analysis | What happened before and after the change? |
| Evidence evaluation | What supports or contradicts each hypothesis? |
| Incident investigation | Which explanation is best supported by available evidence? |

## Architecture

```text
MEANINGFUL CHANGE
        │
        ▼
   EVENT CORRELATION
        │
        ▼
 DEPENDENCY / HISTORY
        │
        ▼
 CAUSAL CANDIDATES
        │
        ▼
 EVIDENCE + COUNTEREVIDENCE
        │
        ▼
 INVESTIGATION RESULT
        │
        ├──► BLACKBOX
        └──► RECOVER
```

## Ecosystem

TRACE follows PULSE and works with `GRID` and `TIME-MACHINE` to establish context before forensic reconstruction in BLACKBOX.

## Status

Early research and architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## License

MIT.