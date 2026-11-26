# ميزان (Mizan) — الصفحة التسويقية

صفحة تسويقية فقط لنظام تحليل أرباح المتاجر الذكي. لا تحتوي على أي كود من محرك التطبيق.

Marketing-only landing page for Mizan. Contains no application engine code.

- Buy: https://zopair.gumroad.com/l/jumwtt
- Launch offer: code MIZAN19 — $19 for the first 20 buyers (price $29)


## Technical Setup & Verification

This repository is a static marketing page only. It contains `index.html`, screenshots, a walkthrough MP4, and a poster image. It does not contain the Mizan sales-analysis engine, an upload-processing implementation, package manifests, build scripts, environment variables, or automated tests.

To preview locally:

```bash
git clone https://github.com/zopair/mizan.git
cd mizan
python -m http.server 8000
```

Open `http://localhost:8000/`. The page is a static HTML/CSS/JavaScript document; no Node.js install or backend is required to preview the marketing content.

**Live page:** [https://zopair.github.io/mizan/](https://zopair.github.io/mizan/). The latest observed GitHub Pages deployment on 22 November 2026 succeeded: [run #44995239393](https://github.com/zopair/mizan/actions/runs/44995239393).

No repository-defined test suite or CI workflow file was present in the current tree. The Pages deployment result verifies static publication only; it does not validate the separate Mizan product engine, local file processing, financial calculations, or product license terms.

## Proof of Concept & Enterprise Customization Readiness

**Status: Static product-marketing page only.** The bilingual landing page, product walkthrough, screenshots, feature descriptions, pricing display, and Gumroad purchase links are present. The actual sales-analysis engine is not included in this repository, so its CSV/XLSX parsing, local-only processing, calculations, export limits, and privacy claims cannot be verified from this codebase.

| Area | Current state |
|---|---|
| Marketing landing page | Implemented in a single static `index.html` |
| Arabic / English presentation | Language toggle and bilingual copy present |
| Product screenshots and walkthrough | Tracked PNG screenshots and MP4 present |
| Purchase link | Gumroad product URL referenced in README/page |
| Analysis engine | Not included in this repository |
| CSV/XLSX processing | Described by marketing copy; not implemented here |
| Local-only privacy behavior | Product claim; engine not present for verification |
| Automated tests | None found |
| Deployment | GitHub Pages success observed 22 November 2026 |
| Project license | No root `LICENSE` file present in the reviewed tree |

Before treating this repository as evidence of the paid product's functionality, link the actual engine source or provide a separately verifiable build/release, validate its calculations and privacy behavior, and ensure Gumroad product terms and landing-page claims match the delivered artifact.

## Intellectual Property & Authorship

Project authorship and attribution: **Aly Hussein Zopair (علي حسين زبير ALY HUSSEIN ZOPAIR)**.

The product's advertised license and the license of this marketing-page repository are separate matters. Add a root project license if the landing-page code is intended for redistribution; preserve third-party media and font rights for all embedded assets.
