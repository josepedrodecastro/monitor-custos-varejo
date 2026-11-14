## Data Source Validation

**Validation date:** November 14, 2026

The public API endpoints were manually tested in a web browser and returned successful responses.

| Source | Indicator | Code | Status |
|---|---|---:|---|
| BCB / SGS | Selic Target Rate | 432 | OK |
| BCB / SGS | IPCA Inflation | 433 | OK |
| BCB / SGS | US Dollar Exchange Rate (Selling) | 1 | OK |
| IBGE / SIDRA | IPCA by Expenditure Group | Table 7060 | OK |

**Endpoints used:**

- BCB: `https://api.bcb.gov.br/dados/serie/bcdata.sgs.{code}/dados`
- IBGE: `https://apisidra.ibge.gov.br/values/t/7060/n1/all/v/63/p/last%2036/c315/all`

All API requests returned successful responses without requiring authentication.
