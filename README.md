# Available .TIENDA One-Word Domains (14,314)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C314%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tienda one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,314 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,314 domains · **Median ask:** $11.85 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-12
**Canonical page:** `https://unique.domains/domains/tld/tienda`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tienda?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tienda.csv">CSV</a> / <a href="./tienda.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TIENDA search](https://unique.domains/domains/tld/tienda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TIENDA search](https://unique.domains/domains/tld/tienda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TIENDA one-word domain catalog.

### Files

- `tienda.csv`, public CSV extract (1,000 rows)
- `tienda.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tienda-oneword-domains/main/tienda.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| ago.tienda     | available | $9.99     | $77.99        | medium         | low    | 3      | name.com         |
| pay.tienda     | resell    | —         | —             | high           | medium | 3      | Porkbun LLC      |
| mega.tienda    | premium   | $250      | —             | high           | medium | 4      | name.com         |
| ain.tienda     | available | $9.99     | $77.99        | low            | low    | 3      | name.com         |
| pizza.tienda   | resell    | —         | —             | high           | low    | 5      | Sav.com, LLC     |
| shop.tienda    | premium   | $500      | —             | high           | medium | 4      | name.com         |
| ale.tienda     | available | $9.99     | —             | medium         | low    | 3      | name.com         |
| caracas.tienda | resell    | —         | —             | medium         | low    | 7      | GoDaddy.com, LLC |
| review.tienda  | premium   | $520      | $520          | high           | medium | 6      | namecheap        |
| all.tienda     | available | $9.99     | $77.99        | high           | medium | 3      | name.com         |
| any.tienda     | available | $9.99     | —             | high           | medium | 3      | name.com         |
| ate.tienda     | available | $9.99     | —             | high           | low    | 3      | name.com         |
| bae.tienda     | available | $9.99     | —             | high           | low    | 3      | name.com         |
| beg.tienda     | available | $9.99     | —             | medium         | low    | 3      | name.com         |
| ben.tienda     | available | $9.99     | —             | high           | medium | 3      | name.com         |
| bit.tienda     | available | $9.99     | —             | high           | medium | 3      | name.com         |
| bro.tienda     | available | $9.99     | —             | medium         | low    | 3      | name.com         |
| ccc.tienda     | available | $9.99     | $77.99        | low            | medium | 3      | name.com         |
| cow.tienda     | available | $9.99     | —             | high           | low    | 3      | name.com         |
| coy.tienda     | available | $9.99     | $77.99        | medium         | low    | 3      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,314 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tienda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tienda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection includes 12,823 one-word .tienda domain names, spanning everyday nouns, playful phrases, and short brandable terms such as coffeemilk.tienda, geton.tienda, and Trex.tienda. The .tienda extension signals retail and commerce, making these names a natural fit for shops, marketplaces, and product launches. With a median ask near $12.40, most domains in this set are priced for quick evaluation rather than high-stakes bidding. Compare spelling, length, and pronounceability before committing to a name for a storefront or brand.

- 12,823 one-word .tienda domains available for evaluation
- Median ask near $12.40 keeps entry costs predictable
- Retail-focused .tienda extension fits stores and marketplaces
- Updated daily to surface newly listed one-word .tienda names

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TIENDA One-Word Domains*. Version 2026-08-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TIENDA page](https://unique.domains/domains/tld/tienda?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
