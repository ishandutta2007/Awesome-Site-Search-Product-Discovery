# Awesome Site Search & Product Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of leading **Site Search**, **Ecommerce Search**, **Merchandising**, and **AI-Powered Product Discovery** platforms and open-source engines.

Turn search intent and catalog browsing into high-converting storefront experiences with intelligent autocomplete, faceted navigation, vector/semantic search, and automated merchandising.

---

## Sector Overview & Market Dynamics

The global **AI-Powered Product Discovery & Site Search Market** is valued at approximately **$2.8B – $3.2B** (projected to reach over **$12B by 2034**, expanding at a ~17.6% CAGR), propelled by rapid merchant adoption of neural vector search, conversational AI shopping assistants, and autonomous visual merchandising.

The market landscape is **moderately fragmented**: native ecommerce giants (such as Shopify) control the entry-level baseline, while specialized multi-billion-dollar infrastructure leaders (Algolia, Bloomreach) and high-growth mid-market/enterprise discovery engines (Constructor.io, Athos/Searchspring/Klevu, Nosto, Doofinder) capture diverse segments across headless, B2B, and enterprise commerce without a single platform monopolizing the space.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Architecture & Frameworks for Custom Discovery](#architecture--frameworks-for-custom-discovery)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## SaaS & Hosted Platforms

Leading hosted search APIs, visual merchandising engines, and product recommendation platforms, sorted by estimated company scale (valuation / market capitalization / ARR).

| Platform | Starting Price | Free Tier / Free Trial Limits | Company Scale (Valuation / Revenue) | Description & Key Features |
| :--- | :--- | :--- | :--- | :--- |
| **[Shopify Search & Discovery](https://help.shopify.com/en/manual/online-store/storefront-search)** | **$0/mo** (included with standard Shopify plan) | **Free forever** for Shopify merchants (supports up to 25 filter configurations per collection/search) | Public ($100B+ Market Cap; ~$7B+ Annual Revenue) | Native storefront discovery tool providing custom filters, synonym groups, product boosting/burying rules, and related product recommendations via the Storefront API. |
| **[Algolia](https://www.algolia.com/)** | **$0.50 per 1,000 requests** (Pay-as-you-go Grow plan) | **Free forever plan**: up to 10,000 search requests/mo and 100,000 records (max 10 indices, 1 GB storage limit) | $2.3B Valuation (~$250M–$365M Annual Revenue) | Developer-first AI search and discovery API featuring sub-50ms typo-tolerant search, InstantSearch UI libraries, and hybrid keyword/vector search. |
| **[Bloomreach](https://documentation.bloomreach.com/discovery/docs/bloomreach-search-packaging)** | **~$5,000/mo** ($60,000/yr annual starting contract) | **No free trial or free tier** (enterprise evaluation via guided architectural proof-of-concept) | $2.2B Valuation (~$260M ARR) | Enterprise commerce discovery suite powered by Loomi AI; features 1:1 personalization, category merchandising, conversational product advisors, and visual discovery. |
| **[Constructor.io](https://constructor.io/)** | **~$2,500/mo** (annual enterprise contract) | **No standard self-serve trial** (offers a 4-week $0 Proof Schedule revenue & conversion uplift assessment on live merchant catalog data) | $550M Valuation (~$65M Annual Revenue) | AI-first search and discovery engine featuring Searchandising campaigns, cross-channel rule curation, automated revenue-optimizing ranking, and conversational discovery. |
| **[Athos Commerce (Searchspring & Klevu)](https://athoscommerce.com/)** | **$449/mo** (Klevu starting tier) / **$599/mo** (Searchspring starting tier) | **14-day free trial** with full feature access (available for Klevu; Searchspring requires customized sales demo & guided POC) | ~$74M Consolidated ARR (backed by PSG) | Unified search and merchandising ecosystem combining Searchspring's visual drag-and-drop merchandising and Klevu's NLP-driven intent search and recommendations. |
| **[Nosto](https://www.shopware.com/en/deep-search-powered-by-nosto/)** | **$500/mo** (modular base platform tier + usage fee) | **No self-serve free trial** (offers merchant-specific live sandbox Proof of Concept with store catalog integration) | $64M Valuation (~$20M–$38M Annual Revenue) | Commerce experience platform delivering AI deep search, predictive autocomplete, personalized merchandising, dynamic faceting, and automated A/B test optimization across 27 languages. |
| **[Doofinder](https://www.doofinder.com/)** | **$39/mo** (Basic tier for up to 1,000 monthly search requests) | **30-day free trial** (unlimited queries and all AI features enabled without requiring a credit card upfront) | ~$15M–$21M Annual Revenue | Plug-and-play AI search, conversational shopping assistant, and visual merchandising tool designed for quick no-code integration across Shopify, WooCommerce, and Magento. |
| **[Boost AI Search](https://developers.boostcommerce.io/)** | **$29/mo** (Launch tier for stores up to $5,000 monthly GMV) | **21-day free trial** (access to all search, filter, and recommendation modules without upfront credit card requirements) | ~$5.5M Annual Revenue | Shopify-specialized search app offering semantic search, fuzzy matching, advanced collection filters, variant merchandising, and dynamic cross-sell recommendations. |
| **[Fast Simon](https://docs.fastsimon.com/)** | **$39.99/mo** (Starter tier for up to 2,000 monthly sessions) | **Free forever plan** (up to 100 sessions/mo) + **14-day free trial** on paid Starter and Essential plans | ~$5M Annual Revenue | Visual product discovery engine featuring visual search with bounding-box image detection, discovery image galleries, automated merchandising, and instant search. |

---

## Open-Source GitHub Projects

Open-source search engines, vector retrieval databases, and developer libraries used to power custom ecommerce search, catalog filtering, and product discovery experiences. Sorted by GitHub star count (descending).

| Repository & Stars | License | Primary Language / Stack | Best For Ecommerce Use Case |
| :--- | :--- | :--- | :--- |
| **[elastic/elasticsearch](https://github.com/elastic/elasticsearch)** [![GitHub stars](https://img.shields.io/github/stars/elastic/elasticsearch?style=social&color=white)](https://github.com/elastic/elasticsearch/stargazers) | Elastic-2.0 / SSPL / AGPL-3.0 | Java | Large-scale catalog search, multi-attribute faceted aggregation, real-time inventory filtering, and hybrid dense/sparse vector retrieval. |
| **[meilisearch/meilisearch](https://github.com/meilisearch/meilisearch)** [![GitHub stars](https://img.shields.io/github/stars/meilisearch/meilisearch?style=social&color=white)](https://github.com/meilisearch/meilisearch/stargazers) | MIT | Rust | Sub-50ms instant search-as-you-type, typo tolerance out of the box, customizable facet filters, and developer-friendly REST/SDK integration. |
| **[milvus-io/milvus](https://github.com/milvus-io/milvus)** [![GitHub stars](https://img.shields.io/github/stars/milvus-io/milvus?style=social&color=white)](https://github.com/milvus-io/milvus/stargazers) | Apache-2.0 | Go / C++ / Python | Massive-scale vector similarity search, multimodal product matching (image-to-product), and AI recommendation embeddings. |
| **[qdrant/qdrant](https://github.com/qdrant/qdrant)** [![GitHub stars](https://img.shields.io/github/stars/qdrant/qdrant?style=social&color=white)](https://github.com/qdrant/qdrant/stargazers) | Apache-2.0 | Rust | Real-time payload-filtered vector search, semantic natural language catalog search, and multimodal visual discovery. |
| **[typesense/typesense](https://github.com/typesense/typesense)** [![GitHub stars](https://img.shields.io/github/stars/typesense/typesense?style=social&color=white)](https://github.com/typesense/typesense/stargazers) | GPL-3.0 | C++ | Turnkey open-source alternative to Algolia; in-memory typo-tolerant search, curated merchandising rules, vector search, and faceted filtering. |
| **[zincsearch/zincsearch](https://github.com/zincsearch/zincsearch)** [![GitHub stars](https://img.shields.io/github/stars/zincsearch/zincsearch?style=social&color=white)](https://github.com/zincsearch/zincsearch/stargazers) | Apache-2.0 | Go | Lightweight, low-memory Elasticsearch alternative for catalog indexing, full-text searching, and simple faceted navigation. |
| **[opensearch-project/OpenSearch](https://github.com/opensearch-project/OpenSearch)** [![GitHub stars](https://img.shields.io/github/stars/opensearch-project/OpenSearch?style=social&color=white)](https://github.com/opensearch-project/OpenSearch/stargazers) | Apache-2.0 | Java | Fully Apache-2.0 licensed enterprise search engine, distributed catalog indexing, neural search plugin, and analytical product aggregation. |
| **[vespa-engine/vespa](https://github.com/vespa-engine/vespa)** [![GitHub stars](https://img.shields.io/github/stars/vespa-engine/vespa?style=social&color=white)](https://github.com/vespa-engine/vespa/stargazers) | Apache-2.0 | C++ / Java | Complex real-time machine learning inference, multi-stage product reranking, personalized recommendations, and massive-scale catalog scoring. |
| **[algolia/instantsearch](https://github.com/algolia/instantsearch)** [![GitHub stars](https://img.shields.io/github/stars/algolia/instantsearch?style=social&color=white)](https://github.com/algolia/instantsearch/stargazers) | MIT | TypeScript / JavaScript | Frontend UI widget library (React, Vue, JS) for building instant search bars, dynamic facet filters, pagination, and sorting interfaces. |
| **[codelibs/fess](https://github.com/codelibs/fess)** [![GitHub stars](https://img.shields.io/github/stars/codelibs/fess?style=social&color=white)](https://github.com/codelibs/fess/stargazers) | Apache-2.0 | Java | Self-hosted enterprise and site search server built on OpenSearch; crawls web, database, and document repositories with 20+ language support and AI/RAG capabilities. |

---

## Architecture & Frameworks for Custom Discovery

While open-source tools provide the foundational indexing and retrieval layers, full turnkey ecommerce product discovery (incorporating automated visual merchandising, pin/bury promotions, dynamic revenue-boosting algorithms, and behavioral tracking) generally requires combining specialized components:

```
[ Frontend: InstantSearch / Headless UI ]
                   │
                   ▼
[ Middleware API: Synonyms / Rule Merchandising Engine ]
                   │
         ┌─────────┴─────────┐
         ▼                   ▼
[ Lexical / Facet Index ]  [ Dense Vector Index ]
 (Typesense / Meilisearch)  (Qdrant / Milvus / Vespa)
```

1. **In-Memory Lexical & Facet Engines**: Platforms like **[Typesense](https://github.com/typesense/typesense)** and **[Meilisearch](https://github.com/meilisearch/meilisearch)** deliver the developer ergonomics and sub-50ms response times needed for search-as-you-type and facet filtering.
2. **Dense Vector & Semantic Retrieval**: Vector engines like **[Qdrant](https://github.com/qdrant/qdrant)** and **[Milvus](https://github.com/milvus-io/milvus)** enable natural language intent matching, CLIP-based visual image discovery, and embedding similarity recommendations.
3. **Enterprise Reranking & ML Systems**: **[Vespa](https://github.com/vespa-engine/vespa)** and **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** provide multi-stage reranking pipelines capable of applying custom business logic and online machine-learning models to catalog search queries.

---

## How to Contribute

Contributions are welcome! Help keep this directory current by submitting updates or new tools:

1. **Fork the repository**.
2. **Add or edit entries** in `README.md` following the established table structure.
3. **Include factual data**: product name, official website/repo link, verified starting pricing/tier limits, company scale, and key discovery capabilities.
4. **Submit a pull request** with a concise description of your changes.

---

## Disclaimer

- This repository is a community-curated resource for informational purposes and does not represent an endorsement of any listed platform or vendor.
- Pricing, free tier thresholds, and corporate valuation/revenue figures are subject to change over time; verify current commercial agreements with official vendors before procurement.
- When capturing, indexing, or logging end-user search queries and shopping behavior, ensure compliance with applicable data privacy regulations (e.g., GDPR, CCPA/CPRA).

---

**Maintained for ecommerce engineers, merchandising professionals, and search system architects.**
