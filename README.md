# Awesome-Site-Search-Product-Discovery

## Top Site Search & Product Discovery Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Ecommerce Search, Merchandising & AI-Powered Product Discovery*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Site Search & Product Discovery**. These tools enable online stores to help shoppers find products faster through intelligent search, faceted filtering, personalized recommendations, and merchandising controls—turning search intent into conversions.



**Examples** include Shopify Search & Discovery, Algolia, Searchspring, Klevu, Bloomreach, Doofinder, Fast Simon, Boost AI Search, Nosto, and Constructor.io (the category leaders).



**Open-source emphasis**: Site Search & Product Discovery is a domain where open-source tooling is **sparse and largely incomplete for turnkey ecommerce search**. The strongest active project is **Fess**, a self-hosted enterprise search server built on OpenSearch with crawling, 20+ language support, and AI/RAG capabilities—but it is a general-purpose search engine, not a product-discovery solution . **OmniSearch** demonstrates a semantic/visual product search architecture using vector databases and HuggingFace models, but is an early-stage package with technical implementation still pending . **Findley** provides a niche WooCommerce product finder using preference sliders . No open-source project matches the merchandising controls, personalization, and analytics of Algolia, Searchspring, or Constructor.io out of the box.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Shopify Search & Discovery](https://help.shopify.com/en/manual/online-store/storefront-search)**  

  Shopify's native app for customizing storefront search and product discovery; enables custom filters, product boosting in search results, and related product recommendations; available via Storefront API for headless storefronts with natural language search and predictive search support .



- **[Algolia](https://www.algolia.com/)**  

  AI-powered search and discovery platform with instant search-as-you-type (sub-50ms latency), typo tolerance, customizable ranking, and vector search; developers praise the API and InstantSearch UI libraries, though achieving relevant results on non-trivial catalogs requires deep customization of ranking, synonyms, and dictionaries; pricing scales with query and record volume .



- **[Searchspring](https://searchspring.com/)**  

  Generative Discovery platform complementing Shopify and other ecommerce platforms with ML-powered merchandising; features specific sorting, boost/bury logic, pinning, triggered and scheduled banners, A/B testing, and personalized recommendations to automate and optimize product display .



- **[Klevu (now part of Athos Commerce)](https://athoscommerce.com/klevu-search-platform/)**  

  AI search and discovery platform now integrated into Athos Commerce; provides NLP-based search relevance, visual merchandising with pinning/boosting/exclusions, real-time personalization and recommendations, and analytics; expanded capabilities include feed management, marketplaces, and social commerce .



- **[Bloomreach](https://documentation.bloomreach.com/discovery/docs/bloomreach-search-packaging)**  

  Discovery platform with modular feature packages for Search, Categories, and merchandising; AI tools include conversational agents, Premium Search with optimized ranking, and visual search; requires Bloomreach's Loomi AI platform for advanced features .



- **[Doofinder](https://www.doofinder.com/)**  

  AI Search & Discovery platform for ecommerce with site search, conversational assistant, recommendations, and category merchandising; installs via single script or plugin with no developer required; uses NLP for intent understanding and claims average sales increase of +20% .



- **[Fast Simon](https://docs.fastsimon.com/)**  

  Visual product discovery platform with SDK for implementing visual search, discovery image galleries, and related product recommendations; supports image-based search with bounding box detection for refined queries .



- **[Boost AI Search](https://developers.boostcommerce.io/)**  

  Shopify-focused search and discovery app with SSR API supporting semantic search, fuzzy matching, advanced filtering, multi-language/currency support, and sort options including relevance, best-selling, and review ratings .



- **[Nosto](https://www.shopware.com/en/deep-search-powered-by-nosto/)**  

  AI-powered search and discovery (via Shopware Deep Search integration); features semantic search, predictive autocomplete, personalized search, synonym optimization, faceting, vector search (alpha), A/B testing, and analytics with 27-language support .



- **[Constructor.io](https://constructor.io/)**  

  AI-powered search and product discovery platform with Searchandising Campaigns for applying merchandising strategies across multiple search, category, and facet contexts simultaneously; features bulk rule application, facet group curation on search pages, and granular rule copying across indexes .



## Open-Source GitHub Projects



- **[Fess](https://github.com/codelibs/fess)**  

  Open-source, self-hosted enterprise and site search server (Apache-2.0) built on OpenSearch; crawls web, file, database, and cloud sources with support for 20+ languages; includes REST API and AI/RAG & semantic search capabilities; ~1k GitHub stars . **The most mature open-source search server available**, but it is a general-purpose enterprise search platform requiring significant configuration and custom frontend development to serve as an ecommerce product discovery solution—no native merchandising controls, personalization, or product-specific faceting.



- **[OmniSearch](https://pypi.org/project/syeedalireza-omnisearch/)**  

  AI-powered ecommerce search engine using vector databases (Qdrant/Milvus) and HuggingFace Transformers for natural language and image search; architecture includes FastAPI, Sentence-BERT/CLIP models, and Redis caching . **Early-stage (v1.0.1, 28 weekly downloads) with technical implementation pending**—demonstrates the semantic/visual product search pattern but is not production-ready.



- **[Findley](https://wordpress.org/plugins/findley-product-discovery-for-woocommerce/)**  

  Open-source WooCommerce plugin for guided product discovery via preference sliders; configurable matching axes and slider labels, product-specific scoring, and local lead capture; designed for taste/preference-driven categories (coffee, wine, chocolate, furniture, skincare) . **Niche solution**—useful for stores wanting a guided finder flow rather than keyword search, but not a general site search replacement.



### Additional Strong Open-Source Options



- **No comprehensive open-source product discovery platform exists**—Fess provides general search infrastructure but lacks ecommerce-specific merchandising, personalization, and analytics. OmniSearch demonstrates the AI search architecture but is not production-ready. Findley addresses a narrow WooCommerce use case. Organizations seeking a self-hosted Algolia/Searchspring equivalent must build significant custom functionality atop Fess or similar search engines.



**Frameworks for building custom systems**: **Fess** provides a mature self-hosted search foundation with crawling, multi-language support, and semantic search capabilities—but requires custom development for product-specific faceting, merchandising rules, personalization, and analytics. **OmniSearch** offers a starting architecture for semantic/visual product search using vector databases. No open-source project delivers a turnkey ecommerce product discovery experience comparable to Algolia or Searchspring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Site search and product discovery platforms handling shopper data must comply with applicable privacy regulations and ecommerce requirements; search analytics and personalization data require careful governance.

- **Open-source site search for ecommerce is essentially absent as a turnkey solution**—Fess provides general search infrastructure but not ecommerce merchandising or personalization . OmniSearch demonstrates AI search patterns but is early-stage . Organizations requiring Algolia- or Searchspring-equivalent product discovery should plan for commercial platforms or substantial custom development.

- Verify license terms for commercial use; Fess uses Apache-2.0 , OmniSearch is a PyPI package , and Findley is a WordPress plugin .



---



**Made for ecommerce search managers, merchandising teams, site reliability engineers, and product discovery practitioners.**  

Let's make site search and product discovery more open, but with clear eyes about the gap that remains in this domain.
