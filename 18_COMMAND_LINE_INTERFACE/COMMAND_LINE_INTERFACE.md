# Command Line Interface — REALESTATE_PRICE_PREDICTION

**Upstream:** https://github.com/mjyplusone/realestate-price-prediction

## Anticloud CLI

```bash
# Install
pip install anticloud-realestate-price-prediction

# Run offline with PAX inference
anticloud-realestate-price-prediction --offline --pax-local

# Run with AIOSS logging
anticloud-realestate-price-prediction --aioss-log ./ledger.jsonl

# Single binary (after build)
./realestate_price_prediction --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
