# Available .COUPONS One-Word Domains (18,424)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C424%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .coupons one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,424 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,424 domains · **Median ask:** $17.91 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-22
**Canonical page:** `https://unique.domains/domains/tld/coupons`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/coupons?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./coupons.csv">CSV</a> / <a href="./coupons.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .COUPONS search](https://unique.domains/domains/tld/coupons?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .COUPONS search](https://unique.domains/domains/tld/coupons?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .COUPONS one-word domain catalog.

### Files

- `coupons.csv`, public CSV extract (1,000 rows)
- `coupons.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/coupons-oneword-domains/main/coupons.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| aft.coupons   | available | $2.98     | $59.98        | low            | low    | 3      | namecheap         |
| max.coupons   | resell    | —         | —             | high           | medium | 3      | Dynadot Inc       |
| dog.coupons   | premium   | $82.50    | —             | high           | low    | 3      | name.com          |
| cod.coupons   | available | $3.99     | —             | high           | low    | 3      | name.com          |
| fast.coupons  | resell    | —         | —             | high           | medium | 4      | Dynadot Inc       |
| book.coupons  | premium   | $78.54    | $78.54        | high           | medium | 4      | namesilo          |
| dig.coupons   | available | $3.99     | —             | high           | low    | 3      | name.com          |
| info.coupons  | resell    | —         | —             | high           | medium | 4      | Dynadot Inc       |
| tire.coupons  | premium   | $242      | $242          | high           | low    | 4      | namesilo          |
| due.coupons   | available | $3.99     | —             | high           | low    | 3      | name.com          |
| just.coupons  | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 34 |
| alert.coupons | premium   | $78.54    | $78.54        | medium         | low    | 5      | namesilo          |
| dye.coupons   | available | $3.99     | —             | medium         | low    | 3      | name.com          |
| live.coupons  | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC      |
| beach.coupons | premium   | $78.54    | $78.54        | medium         | low    | 5      | namesilo          |
| feb.coupons   | available | $3.99     | —             | high           | low    | 3      | name.com          |
| star.coupons  | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 27 |
| event.coupons | premium   | $85.80    | $85.80        | high           | medium | 5      | namecheap         |
| gal.coupons   | available | $3.99     | —             | medium         | low    | 3      | name.com          |
| alpha.coupons | resell    | —         | —             | high           | medium | 5      | Dynadot Inc       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,424 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/coupons?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/coupons?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=related_pricing)

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

The .coupons extension carries a low entry cost, with a median asking price of $29.80 across 12,503 one-word listings. Names in this set span everyday compound words — from butterflies.coupons and weddingcake.coupons to solarpower.coupons and dogwalking.coupons — making it a budget-friendly pool for founders building coupon, deals, or promo-focused brands, and for investors testing demand in a niche, low-cost TLD. Because renewal and resale economics vary widely at this price point, comparing individual asking prices against the median is the fastest way to spot standouts in this selection.

- 12,503 one-word .coupons domain names in this selection
- Median asking price: $29.80 — a low-cost entry point
- Compound one-word names (e.g., coffeecake, dogwalking)
- Updated daily to reflect current listings and pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .COUPONS One-Word Domains*. Version 2026-08-22. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .COUPONS page](https://unique.domains/domains/tld/coupons?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_coupons_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
