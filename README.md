# Example
```yaml
name: Verifiable Build

on:
  push:
    branches: main

jobs:
  anchor-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Solana Verify Build
        uses: drift-labs/solana-verify-action@v1.0.0
        with:
          library-name: drift
```
