# Available .SUPPORT One-Word Domains (14,452)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C452%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .support one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,452 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,452 domains · **Median ask:** $13.65 · **High-demand under $2,500:** 1

**Last updated:** 2026-08-16
**Canonical page:** `https://unique.domains/domains/tld/support`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/support?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./support.csv">CSV</a> / <a href="./support.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SUPPORT search](https://unique.domains/domains/tld/support?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SUPPORT search](https://unique.domains/domains/tld/support?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SUPPORT one-word domain catalog.

### Files

- `support.csv`, public CSV extract (1,000 rows)
- `support.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/support-oneword-domains/main/support.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| cxl.support  | available | $4.98     | $37.98        | low            | low    | 3      | namecheap                  |
| the.support  | resell    | —         | —             | high           | medium | 3      | 1API GmbH                  |
| awe.support  | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                   |
| lii.support  | available | $4.98     | $37.98        | low            | low    | 3      | namecheap                  |
| give.support | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC           |
| day.support  | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                   |
| wiz.support  | available | $11.99    | —             | high           | low    | 3      | name.com                   |
| move.support | resell    | —         | —             | high           | medium | 4      | Squarespace Domains II LLC |
| ego.support  | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo                   |
| xci.support  | available | $4.98     | $37.98        | low            | low    | 3      | namecheap                  |
| park.support | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                |
| era.support  | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo                   |
| alky.support | available | $4.98     | $37.98        | low            | low    | 4      | namecheap                  |
| shoe.support | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC           |
| fee.support  | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                   |
| avid.support | available | $4.98     | $37.98        | medium         | low    | 4      | namecheap                  |
| tiny.support | resell    | —         | —             | medium         | medium | 4      | Dynadot Inc                |
| gas.support  | premium   | $42.90    | $42.90        | high           | low    | 3      | namecheap                  |
| babe.support | available | $11.99    | —             | high           | low    | 4      | name.com                   |
| warm.support | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,452 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/support?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/support?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=related_pricing)

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

This selection covers 10,954 available one-word .support domain names, from everyday nouns to short brandable terms. Asking prices sit near a $19 median, positioning .support as one of the more affordable extensions for founders shortlisting a brand name and investors scanning for low-cost, high-volume opportunities.

- 10,954 available one-word .support domains, updated daily
- Median asking price near $19 — among the most affordable TLDs
- Everyday words like backyard, pictures, and headout in this set
- Brandable, ownable now — ideal for quick, budget-friendly picks

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SUPPORT One-Word Domains*. Version 2026-08-16. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SUPPORT page](https://unique.domains/domains/tld/support?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_support_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
