# Available .MAKEUP One-Word Domains (5,622,463)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C652%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C463%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .makeup one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,652-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,463 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/makeup`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/makeup?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_open_search"><b>Open live .MAKEUP search</b></a> ·
  <a href="https://unique.domains/domains/tld/makeup?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_create_radar"><b>Create .MAKEUP Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/makeup?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./makeup.csv"><b>Download CSV</b></a> ·
  <a href="./makeup.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MAKEUP one-word domain catalog.

### Files

- `makeup.csv` — public CSV extract (9,652 rows)
- `makeup.json` — public JSON extract (9,652 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full .MAKEUP catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live .MAKEUP catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/makeup-oneword-domains/main/makeup.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ----------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| block.makeup      | available | $19.98         | —             | 68             | 98     | 5      | namecheap                                    |
| woo.makeup        | resell    | —              | —             | 67             | 82     | 3      | Porkbun, LLC                                 |
| converse.makeup   | premium   | $2,500         | $2,500        | 64             | 73     | 8      | name.com                                     |
| seventeen.makeup  | available | $1.99          | $20.99        | 84             | 62     | 9      | name.com                                     |
| enjoy.makeup      | resell    | —              | —             | 88             | 66     | 5      | Spaceship, Inc.                              |
| nationwide.makeup | premium   | $2,500         | $2,500        | 76             | 66     | 10     | name.com                                     |
| athletics.makeup  | available | $19.98         | —             | 69             | 52     | 9      | namecheap                                    |
| bot.makeup        | resell    | —              | —             | 98             | 56     | 3      | Porkbun, LLC                                 |
| power.makeup      | premium   | $845           | $845          | 98             | 64     | 5      | namecheap                                    |
| genius.makeup     | available | $1.99          | $20.99        | 98             | 47     | 6      | name.com                                     |
| air.makeup        | resell    | —              | —             | 84             | 51     | 3      | Spaceship, Inc.                              |
| easy.makeup       | premium   | $2,500         | $20.99        | 128            | 62     | 4      | name.com                                     |
| wizard.makeup     | available | $1.99          | $20.99        | 118            | 46     | 6      | name.com                                     |
| human.makeup      | resell    | —              | —             | 74             | 51     | 5      | Xiamen ChinaSource Internet Service Co., Ltd |
| data.makeup       | premium   | $845           | $845          | 70             | 60     | 4      | namecheap                                    |
| forge.makeup      | available | $1.99          | $20.99        | 62             | 45     | 5      | name.com                                     |
| root.makeup       | resell    | —              | —             | 64             | 50     | 4      | Spaceship, Inc.                              |
| free.makeup       | premium   | $2,500         | $20.99        | 88             | 59     | 4      | name.com                                     |
| golf.makeup       | available | $1.99          | —             | 84             | 44     | 4      | name.com                                     |
| everything.makeup | resell    | —              | —             | 64             | 47     | 10     | Dynadot LLC                                  |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MAKEUP One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MAKEUP page](https://unique.domains/domains/tld/makeup?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_makeup_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
