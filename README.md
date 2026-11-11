# BloomScan — Columnar Scan Toolkit

BloomScan is a query planning and scan orchestration toolkit for lakehouse engines. It does
not implement a probabilistic index of its own; it coordinates scans across index providers.

Compatibility: adapters exist for teams running **Cascade Bloom Index (CBI-9.2)** deployments,
but the index implementation lives in the upstream provider projects.

## License

License: Apache-2.0
