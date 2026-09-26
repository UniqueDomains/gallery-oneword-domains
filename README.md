# Available .GALLERY One-Word Domains (21,364)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-21%2C364%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .gallery one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **21,364 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 21,364 domains · **Median ask:** $32.22 · **High-demand under $2,500:** 2

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/gallery`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/gallery?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./gallery.csv">CSV</a> / <a href="./gallery.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GALLERY search](https://unique.domains/domains/tld/gallery?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GALLERY search](https://unique.domains/domains/tld/gallery?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GALLERY one-word domain catalog.

### Files

- `gallery.csv`, public CSV extract (1,000 rows)
- `gallery.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/gallery-oneword-domains/main/gallery.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar           |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------- |
| fab.gallery       | available | $29.98    | $36.98        | high           | low    | 3      | namecheap           |
| hip.gallery       | resell    | —         | —             | high           | low    | 3      | 1API GmbH           |
| alb.gallery       | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo            |
| fcc.gallery       | available | $28.99    | $28.99        | high           | low    | 3      | namesilo            |
| speed.gallery     | resell    | —         | —             | high           | medium | 5      | united-domains GmbH |
| atf.gallery       | premium   | $85.80    | $85.80        | high           | low    | 3      | namecheap           |
| hdl.gallery       | available | $28.99    | $28.99        | high           | low    | 3      | namesilo            |
| cosmic.gallery    | resell    | —         | —             | high           | medium | 6      | GoDaddy.com, LLC    |
| bro.gallery       | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo            |
| lxv.gallery       | available | $28.99    | $28.99        | medium         | low    | 3      | namesilo            |
| galaxy.gallery    | resell    | —         | —             | high           | medium | 6      | GoDaddy.com, LLC    |
| btw.gallery       | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo            |
| pbs.gallery       | available | $29.98    | $36.98        | high           | low    | 3      | namecheap           |
| homeless.gallery  | resell    | —         | —             | high           | low    | 8      | GoDaddy.com, LLC    |
| bud.gallery       | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo            |
| sip.gallery       | available | $28.99    | $28.99        | high           | low    | 3      | namesilo            |
| moroccan.gallery  | resell    | —         | —             | high           | low    | 8      | GoDaddy.com, LLC    |
| cue.gallery       | premium   | $82.50    | —             | high           | low    | 3      | name.com            |
| tod.gallery       | available | $28.99    | $28.99        | high           | low    | 3      | namesilo            |
| slovakian.gallery | resell    | —         | —             | high           | low    | 9      | GoDaddy.com, LLC    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 21,364 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/gallery?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/gallery?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers one-word domain names on the .gallery extension, drawn from a pool of 11,624 entries with a median ask of $34.85. The list favors short, memorable words and phrases such as pictures.gallery, apples.gallery, and takeabreak.gallery, spanning everyday nouns, verbs, and compound phrases rather than niche jargon. Because .gallery reads naturally for art, photography, portfolio, and curation-style brands, these names suit founders building a visual or creative identity as well as investors scanning a low-cost extension for volume and pricing patterns. When comparing entries in this list, weigh word length, spelling simplicity, and how directly each name signals a gallery or showcase use case.

- 11,624 one-word .gallery domain names in this list
- Median ask of $34.85 across the selection
- Short, everyday words like pictures, apples, takeabreak
- Fits art, photography, portfolio, and showcase brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GALLERY One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GALLERY page](https://unique.domains/domains/tld/gallery?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
