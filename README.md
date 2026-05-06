# Available .GALLERY One-Word Domains (11,620)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C620%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .gallery one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,620 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,620 domains · **Median ask:** $37.12 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `gallery.csv` — public CSV extract (1,000 rows)
- `gallery.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/gallery-oneword-domains/main/gallery.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| payments.gallery   | available | $36.98    | —             | 58             | 33     | 8      | namecheap        |
| popup.gallery      | resell    | —         | —             | 84             | 29     | 6      | Spaceship, Inc.  |
| dogs.gallery       | premium   | $500      | —             | 76             | 28     | 4      | name.com         |
| letsgo.gallery     | available | $36.98    | —             | 57             | 31     | 7      | namecheap        |
| photos.gallery     | resell    | —         | —             | 54             | 28     | 6      | Dynadot Inc      |
| systems.gallery    | premium   | $123.75   | —             | 46             | 27     | 7      | name.com         |
| gems.gallery       | available | $28.99    | $28.99        | 70             | 28     | 4      | namesilo         |
| comics.gallery     | resell    | —         | —             | 68             | 24     | 6      | GoDaddy.com, LLC |
| toys.gallery       | premium   | $78.54    | $78.54        | 60             | 24     | 4      | namesilo         |
| bees.gallery       | available | $36.98    | —             | 54             | 27     | 4      | namecheap        |
| Places.gallery     | resell    | —         | —             | 74             | 22     | 6      | GoDaddy.com, LLC |
| girls.gallery      | premium   | $82.50    | —             | 83             | 23     | 5      | name.com         |
| Trex.gallery       | available | $36.98    | —             | 80             | 24     | 5      | namecheap        |
| flights.gallery    | premium   | $118.80   | $118.80       | 61             | 22     | 7      | namesilo         |
| gamers.gallery     | available | $28.99    | $28.99        | 62             | 24     | 6      | namesilo         |
| webs.gallery       | premium   | $78.54    | $78.54        | 56             | 21     | 4      | namesilo         |
| holidays.gallery   | available | $28.99    | $28.99        | 78             | 23     | 8      | namesilo         |
| rocks.gallery      | premium   | $82.50    | —             | 78             | 18     | 5      | name.com         |
| motorsport.gallery | available | $36.98    | —             | 74             | 23     | 10     | namecheap        |
| states.gallery     | premium   | $82.50    | —             | 70             | 16     | 6      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,620 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/gallery?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/gallery?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .gallery domains. The set spans concrete words such as skirt.gallery and rest.gallery, broader brandable terms like friend.gallery and intrinsic.gallery, and more unusual options such as dignitary.gallery or surrender.gallery. For founders, the main question is whether the word feels naturally connected to an image-led, curated, or exhibition-oriented brand. For investors, the key test is whether the word is simple, recognizable, and commercially reusable within the constraints of a niche TLD. When comparing these domains, weigh word clarity, memorability, pricing discipline, and whether the .gallery ending strengthens or weakens the meaning.

- The full set uses the .gallery extension only
- 11,620 one-word domains in this selection
- Median ask across the set is 37.12
- Best fits are words that pair naturally with .gallery

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GALLERY One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GALLERY page](https://unique.domains/domains/tld/gallery?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gallery_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
