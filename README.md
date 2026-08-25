# ISO Country/Currency/Language Codes

> ISO 3166-1 (country), ISO 4217 (currency), ISO 639 (language) codes

**Category:** dev-ref · **Data:** ISO standards · **License:** CC0-1.0 · **Updates:** yearly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/countries.json` | JSON |
| `/data/currencies.json` | JSON |
| `/data/languages.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/iso-codes/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/iso-codes/data.json');
const data = await res.json();
```

## Data

- Source: ISO standards
- License: CC0-1.0
- Last updated: `2026-08-25T03:04:42.584Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/iso-codes/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC0-1.0
