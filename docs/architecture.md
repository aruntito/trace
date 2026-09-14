# TRACE Architecture

TRACE investigates why a meaningful system change occurred.

## Flow

```text
MEANINGFUL CHANGE
        │
        ▼
   EVENT CORRELATION
        │
        ▼
 DEPENDENCY + HISTORY
        │
        ▼
 CAUSAL CANDIDATES
        │
        ▼
 EVIDENCE / COUNTEREVIDENCE
        │
        ▼
 INVESTIGATION RESULT
```

## Design principles

1. Correlation is not automatically causation.
2. Historical and topology context remain explicit.
3. Competing explanations are preserved.
4. Evidence is traceable to source observations.
5. Investigation results are inspectable and revisable.