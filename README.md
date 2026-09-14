# TRACE

**Causal investigation across systems.**

> Why did it change?

TRACE explores how to move from an observed change to an evidence-backed explanation by following dependencies, timelines, relationships, and causal candidates across system boundaries.

## What it does

- connect related events
- reconstruct causal timelines
- traverse dependencies
- distinguish correlation from causal evidence
- preserve competing explanations
- produce inspectable investigation state

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