# Observatory Package

This package will host the core modules for the LLM Cost Drift Observatory. Each submodule maps to a major capability in the system design.

## Module layout
- `ingestion/`: instrumentation hooks and event capture.
- `cost/`: cost attribution, pricing tables, and unit economics.
- `drift/`: response similarity and embedding drift analysis.
- `baselines/`: statistical baselines and rolling window management.
- `alerts/`: alert definitions and notification adapters.
- `fixtures/`: synthetic and anonymized sample datasets.
- `tests/`: deterministic test suite and helpers.

## Next steps
- Define event schemas and pricing table formats.
- Add sampling strategies for embedding capture.
- Establish baseline computation and alert thresholds.
