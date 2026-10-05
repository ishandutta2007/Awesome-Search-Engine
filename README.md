# Awesome-Search-Engine

## Top Search Engine Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Web Search, Self-Hosted Metasearch & Privacy-Respecting Indexes*  

**Last updated: October 2026**



This repository tracks notable **commercial search engines** and **open-source projects** that index, retrieve, and rank web content — from global search giants to self-hosted metasearch engines and decentralized index efforts.



**Examples** include Google Search, Bing Search, DuckDuckGo, Yahoo Search, Yandex, Baidu, Ecosia, Startpage, Brave Search, and Qwant (the category leaders).



**Open-source emphasis**: Search is a domain where open-source alternatives to Google's index remain challenging — index building at web scale requires immense crawl infrastructure. However, **SearXNG**, **Whoogle**, **4get**, and **LibreY** provide excellent privacy-respecting metasearch over existing indexes, while **Stract** and **Marginalia** are building independent open-source indexes. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Google Search](https://www.google.com/)**  

  **The dominant search engine** with 90%+ global market share, unparalleled index depth, and advanced ranking signals. Proprietary algorithms and deep AI integration (Search Generative Experience). **The reference point for search quality** — but closed, ad-heavy, and privacy-invasive.



- **[Bing Search](https://www.bing.com/)**  

  Microsoft's search engine powering DuckDuckGo, Yahoo, and Ecosia results. **The primary alternative index** to Google with AI-powered Copilot integration. **Best for organizations wanting an API-backed search without building their own index**.



- **[DuckDuckGo](https://duckduckgo.com/)**  

  **The leading privacy-focused search engine** — no tracking, no search history, no filter bubble. Uses Bing's index with DuckDuckGo's own ranking and Instant Answers. **The most widely adopted privacy search engine** — 100M+ daily searches.



- **[Yahoo Search](https://search.yahoo.com/)**  

  Yahoo's search portal powered by Bing results. **Historically significant** as one of the earliest web directories (founded 1994). Now primarily a Bing syndication surface.



- **[Yandex](https://yandex.com/)**  

  Russia's dominant search engine with **the best index for Russian-language content** and strong performance in Eastern Europe and Central Asia.



- **[Baidu](https://www.baidu.com/)**  

  China's dominant search engine with **the best index for Chinese-language content**. Required for reaching Chinese markets.



- **[Ecosia](https://www.ecosia.org/)**  

  Privacy-friendly search engine that **plants trees with ad revenue** — over 200 million trees planted. Powered by Bing results. **Best for environmentally conscious users** wanting search to have positive impact.



- **[Startpage](https://www.startpage.com/)**  

  Privacy-focused search engine offering **Google-quality results without Google tracking**. **The only way to get Google's index with privacy** — no search history, no IP logging, no cookies.



- **[Brave Search](https://search.brave.com/)**  

  **The leading independent search index** from Brave Software — not a Bing or Google proxy. **Privacy-first with its own crawler and ranking**. Ad-free paid tier available. **The most credible independent alternative to Google and Bing**.



- **[Qwant](https://www.qwant.com/)**  

  French privacy-focused search engine with **European data sovereignty** and its own index in partnership with Bing. **Best for European users** wanting GDPR-compliant search.



## Open-Source GitHub Projects



- **[SearXNG](https://github.com/searxng/searxng)**  

  **The leading open-source metasearch engine**, AGPL-3.0 licensed with 20,000+ GitHub stars . **Aggregates results from 70+ search engines** — Google, Bing, DuckDuckGo, Wikipedia, and more — without tracking users . **Self-hostable via Docker** with a single command . Features **result filtering, language selection, safe search, and JSON API** . **The de facto open-source search alternative** — replaces Google while respecting privacy . **Best for privacy-conscious users and organizations** wanting search without surveillance . **The most active fork** — original Searx is unmaintained.



- **[Whoogle Search](https://github.com/benbusby/whoogle-search)**  

  **Self-hosted, ad-free, privacy-respecting metasearch engine that uses Google results**, MIT licensed with 10,000+ GitHub stars . **Strips Google's tracking, ads, and AMP** — returns clean results . **No JavaScript required** — works in any browser . **Docker and Heroku deployment** options . **Best for users wanting Google's index without Google's tracking** — the closest open-source equivalent to Startpage .



- **[4get](https://github.com/4get-org/4get)**  

  **Lightweight, privacy-focused metasearch engine**, AGPL-3.0 licensed . **Aggregates results from multiple sources** with a focus on speed and minimal resource usage . **PHP-based with simple deployment** . **Best for low-resource environments** wanting metasearch.



- **[LibreY](https://github.com/Ahwxorg/LibreY)**  

  **Privacy-focused metasearch engine** supporting multiple search engines and result types . **Self-hosted with Docker** . **Best for users wanting a customizable metasearch experience** with granular source selection .



- **[Stract](https://github.com/StractOrg/stract)**  

  **Independent open-source search engine with its own index**, AGPL-3.0 licensed . **The most ambitious open-source search index project** — crawling and ranking the web independently rather than proxying Google or Bing . **Early stage but actively developed** — represents the future of open-source search . **Best for users wanting to support independent search infrastructure** .



- **[Marginalia Search](https://github.com/MarginaliaSearch/MarginaliaSearch)**  

  **Independent search engine focused on non-commercial content**, AGPL-3.0 licensed . **Indexes old-school, text-heavy websites** — forums, personal blogs, and academic pages that modern search engines ignore . **The best search engine for finding hidden gems** — explicitly anti-SEO and anti-commercial . **Best for researchers and users wanting to discover non-corporate web content** .



- **[Meilisearch](https://github.com/meilisearch/meilisearch)**  

  **Lightning-fast, open-source search engine for applications**, MIT licensed with 45,000+ GitHub stars . **Not a web search engine** — it's a search API for your own data . **Typo-tolerant, faceted search with instant results** . **The leading open-source alternative to Algolia** . **Best for developers adding search to applications** .



- **[Typesense](https://github.com/typesense/typesense)**  

  **Open-source, typo-tolerant search engine for applications**, GPL-3.0 licensed . **Fast, relevant, and easy to deploy** . **The main competitor to Meilisearch** . **Best for site search, e-commerce, and app search** .



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  **Apache 2.0 licensed fork of Elasticsearch** with search and analytics capabilities . **Not a web search engine** — it's a search and analytics suite for your own data . **Best for log analytics and application search** .



- **[YaCy](https://github.com/yacy/yacy_search_server)**  

  **Decentralized peer-to-peer search engine**, GPL licensed . **No central index** — every peer crawls and indexes independently, sharing results across the network . **The original decentralized search project** (since 2003) . **Best for users wanting censorship-resistant search** — though index quality is inconsistent .



- **[Gigablast](https://github.com/gigablast/open-source-search-engine)**  

  **Open-source web search engine and indexer**, Apache-2.0 licensed . **Historically significant** — Gigablast was an independent search engine before its founder's death in 2022. **Now unmaintained** but valuable as reference architecture .



- **[Common Crawl](https://github.com/commoncrawl/cc-index-table)**  

  **Open repository of web crawl data** — petabytes of web pages available for research . **Not a search engine** but provides the raw crawl data for building one . **The foundation for independent search projects** — Stract and others use Common Crawl data . **Best for researchers and search engine builders** .



### Additional Strong Open-Source Options



- **Presearch** — Decentralized search engine with community nodes and token incentives. **Not fully open-source** but community-driven.

- **MetaGer** — German privacy-focused metasearch from a non-profit. **Open-source with self-hosting option** .

- **Mojeek** — Independent UK search engine with its own index. **Not open-source** but independent.

- **Alexandria** — Open-source search engine project using Common Crawl.

- **Lumo Search** — Privacy-focused search API .

- **ZincSearch** — Lightweight alternative to Elasticsearch in Go, Apache-2.0 licensed .



**Frameworks for building custom search solutions**: Choose based on whether you need web search or application search. For **privacy-respecting web search**, deploy **SearXNG** for metasearch aggregation or **Whoogle** for Google results without tracking . For **independent web indexes**, explore **Stract** or **Marginalia** — both are building open-source alternatives to Google/Bing . For **application search**, use **Meilisearch** or **Typesense** as Algolia alternatives . For **log/analytics search**, use **OpenSearch** or **Elasticsearch** . Note that building a general web search engine from scratch requires immense infrastructure — **Common Crawl** provides the raw data, but ranking and index maintenance are multi-year efforts . The practical open-source path is metasearch over existing indexes.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Search engines process sensitive queries and browsing behavior. **Self-hosted search avoids third-party query logging** — SearXNG, Whoogle, and similar tools do not track users .

- **Metasearch engines depend on upstream indexes** — SearXNG, Whoogle, and LibreY still query Google/Bing/DuckDuckGo. If those indexes change or block access, results are affected . **Stract** and **Marginalia** are the only open-source projects with independent indexes.

- **Independent indexes are incomplete** — Marginalia deliberately indexes non-commercial content; Stract is early-stage. Neither replaces Google for general search .

- **Application search engines (Meilisearch, Typesense) are not web search** — they index your own data, not the web. Use them for site search and app search, not internet search .

- The open-source ecosystem provides strong metasearch, privacy, and application search foundations, but **web-scale crawling, ranking, and index maintenance** remain primarily commercial or research-scale efforts.



---



**Made for privacy advocates, researchers, and developers building search infrastructure.**  

Let's make search engines more open, transparent, and privacy-respecting.
