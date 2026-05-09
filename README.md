# Available .TIENDA One-Word Domains (12,823)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C823%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tienda one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,823 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,823 domains · **Median ask:** $16.09 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
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

- `tienda.csv` — public CSV extract (1,000 rows)
- `tienda.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tienda-oneword-domains/main/tienda.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                      |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------ |
| agents.tienda       | available | $9.99     | —             | 56             | 50     | 6      | name.com                       |
| bar.tienda          | resell    | —         | —             | 76             | 35     | 3      | Soluciones Corporativas IP, SL |
| online.tienda       | premium   | $250      | —             | 70             | 62     | 7      | name.com                       |
| tokens.tienda       | available | $9.99     | —             | 51             | 36     | 6      | name.com                       |
| jobs.tienda         | premium   | $500      | —             | 79             | 42     | 4      | name.com                       |
| homes.tienda        | available | $9.99     | —             | 86             | 34     | 5      | name.com                       |
| SanDiego.tienda     | premium   | $242      | $242          | 74             | 29     | 9      | namesilo                       |
| tickets.tienda      | available | $9.99     | —             | 64             | 34     | 7      | name.com                       |
| spectra.tienda      | available | $9.99     | —             | 62             | 34     | 7      | name.com                       |
| partners.tienda     | available | $9.99     | —             | 61             | 32     | 8      | name.com                       |
| trends.tienda       | available | $9.99     | —             | 60             | 32     | 6      | name.com                       |
| quotes.tienda       | available | $9.99     | —             | 58             | 29     | 6      | name.com                       |
| Jim.tienda          | available | $74.98    | —             | 78             | 28     | 3      | namecheap                      |
| dogs.tienda         | available | $9.99     | —             | 76             | 28     | 4      | name.com                       |
| commonground.tienda | available | $9.99     | —             | 74             | 28     | 13     | name.com                       |
| photos.tienda       | available | $9.99     | —             | 54             | 28     | 6      | name.com                       |
| bees.tienda         | available | $9.99     | —             | 54             | 27     | 4      | name.com                       |
| doctors.tienda      | available | $9.99     | —             | 56             | 26     | 7      | name.com                       |
| destination.tienda  | available | $9.99     | —             | 90             | 25     | 11     | name.com                       |
| pops.tienda         | available | $9.99     | —             | 74             | 24     | 4      | name.com                       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,823 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tienda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tienda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is centered on .tienda domains, a TLD that directly signals retail, shops, and commerce in Spanish-speaking contexts. The names range from broad words such as dream.tienda and concert.tienda to more descriptive or niche options like adjunct.tienda and background.tienda. With a median ask of 16.09, price is unlikely to be the main separator. The more important test is fit: whether the word is commercially relevant, easy to remember, and strong enough to carry a store brand on its own. When comparing these domains, weigh keyword clarity against memorability, and check whether the term creates avoidable trademark or category confusion.

- .tienda signals retail intent clearly
- Median ask is 16.09 across this selection
- Best fits are clear, memorable commercial words
- Check trademark overlap before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TIENDA One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TIENDA page](https://unique.domains/domains/tld/tienda?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tienda_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
