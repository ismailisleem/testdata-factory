# testdata-factory-engine

Core engine and CLI for AI TestData Factory: local-first, deterministic synthetic test data from reviewed `.tdf.json` contracts, JSON Schema files, OpenAPI request schemas, and scanned forms.

Install from a clone of the repository:

```bash
python -m pip install -e 'engine[server]'
```

Validate a contract:

```bash
tdf validate examples/contracts/register.tdf.json
```

See the [project README](https://github.com/ismailisleem/testdata-factory#readme) for the full guide, the SDKs, and the self-hosted API.
