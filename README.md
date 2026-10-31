# Apify B2B Intelligence, Contact Waterfall & Public Registry Suite (`coherent_edelweiss`)

Production-grade **B2B Lead Enrichment, DNS-over-HTTPS MX Email Verification, Website Tech-Stack/Ad-Pixel Fingerprinting, and Public Registry Apify Actors** built with `httpx`, `asyncio`, and **Pydantic v2**.

- **Zero-Charge on Empty (`PAY_PER_EVENT`):** Pay only `\$0.002–\$0.007` when verified records are returned—`\$0.00` on misses.
- **UK GDPR, EU GDPR & PECR Safe-by-Design (`gdprSafeMode`):** Automatically filters out personal emails and personal LinkedIn `/in/` links on UK/EEA domains, returning compliant corporate role endpoints (`info@`, `sales@`, `enquiries@`).
- **1-Click Ready for Clay.com, n8n, Make.com & AI Agents (MCP):** Importable workflows in [`integrations/n8n/`](./integrations/n8n/), [`integrations/clay/`](./integrations/clay/), and [`integrations/mcp/`](./integrations/mcp/).

---

## Live Apify Store Catalog (11 Specialized B2B Actors)

| Wave | Actor Title & Store Link | Target Niche / Data Source | Synchronous API Endpoint (`POST`) |
| :--- | :--- | :--- | :--- |
| **Wave 1** | **[Google Maps B2B Lead, Email & Tech-Stack Enricher](https://apify.com/coherent_edelweiss/google-maps-b2b-enricher)** (`coherent_edelweiss/google-maps-b2b-enricher`) | Google Maps Email, Lead & Tech Stack Scraper (MX Verified) | `https://api.apify.com/v2/acts/coherent_edelweiss~google-maps-b2b-enricher/run-sync-get-dataset-items` |
| **Wave 1** | **[Verified B2B Email, Contact & Tech-Stack Finder](https://apify.com/coherent_edelweiss/verified-email-contact-finder)** (`coherent_edelweiss/verified-email-contact-finder`) | Verified B2B Email Finder, MX Checker & Tech Stack Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~verified-email-contact-finder/run-sync-get-dataset-items` |
| **Wave 2** | **[Apollo.io B2B Leads, Org & Verified Email Enricher](https://apify.com/coherent_edelweiss/apollo-b2b-lead-enricher)** (`coherent_edelweiss/apollo-b2b-lead-enricher`) | Apollo.io B2B Lead & Email Enricher API (No Login Cookies) | `https://api.apify.com/v2/acts/coherent_edelweiss~apollo-b2b-lead-enricher/run-sync-get-dataset-items` |
| **Wave 2** | **[ZoomInfo & Lusha B2B Company & Contact Waterfall API](https://apify.com/coherent_edelweiss/zoominfo-lusha-waterfall-enricher)** (`coherent_edelweiss/zoominfo-lusha-waterfall-enricher`) | ZoomInfo & Lusha B2B Contact Waterfall & Tech Stack API | `https://api.apify.com/v2/acts/coherent_edelweiss~zoominfo-lusha-waterfall-enricher/run-sync-get-dataset-items` |
| **Wave 3** | **[Shopee & Lazada SEA Product, Price & Velocity API](https://apify.com/coherent_edelweiss/shopee-lazada-sea-ecommerce-api)** (`coherent_edelweiss/shopee-lazada-sea-ecommerce-api`) | Shopee & Lazada Scraper API (SG, MY, ID, TH, PH, VN) | `https://api.apify.com/v2/acts/coherent_edelweiss~shopee-lazada-sea-ecommerce-api/run-sync-get-dataset-items` |
| **Wave 4** | **[MCP Server Registry, AI Tool & Maintainer Lead Enricher](https://apify.com/coherent_edelweiss/mcp-server-ecosystem-index)** (`coherent_edelweiss/mcp-server-ecosystem-index`) | MCP Server Registry, AI Tool & Maintainer Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~mcp-server-ecosystem-index/run-sync-get-dataset-items` |
| **Wave 4** | **[UK Planning Applications & Construction Lead Enricher](https://apify.com/coherent_edelweiss/uk-planning-construction-leads)** (`coherent_edelweiss/uk-planning-construction-leads`) | UK Planning Applications & Construction Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-planning-construction-leads/run-sync-get-dataset-items` |
| **Wave 4** | **[SEC IAPD Registered Investment Adviser & Wealth Enricher](https://apify.com/coherent_edelweiss/sec-iapd-ria-wealth-enricher)** (`coherent_edelweiss/sec-iapd-ria-wealth-enricher`) | SEC IAPD Registered Investment Adviser & Wealth RIA API | `https://api.apify.com/v2/acts/coherent_edelweiss~sec-iapd-ria-wealth-enricher/run-sync-get-dataset-items` |
| **Wave 5** | **[UK CQC Care Homes, Private Clinics & Healthcare Enricher](https://apify.com/coherent_edelweiss/uk-cqc-care-homes-enricher)** (`coherent_edelweiss/uk-cqc-care-homes-enricher`) | UK CQC Care Homes, Private Clinics & Healthcare Lead API | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-cqc-care-homes-enricher/run-sync-get-dataset-items` |
| **Wave 5** | **[US CMS NPI Healthcare Provider & Medical Practice Enricher](https://apify.com/coherent_edelweiss/us-npi-healthcare-enricher)** (`coherent_edelweiss/us-npi-healthcare-enricher`) | US CMS NPI Healthcare Provider & Medical Clinic Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~us-npi-healthcare-enricher/run-sync-get-dataset-items` |
| **Wave 5** | **[UK FSA Food Hygiene Ratings & Hospitality Lead Enricher](https://apify.com/coherent_edelweiss/uk-fsa-food-hygiene-leads)** (`coherent_edelweiss/uk-fsa-food-hygiene-leads`) | UK FSA Food Hygiene Ratings & Restaurant Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-fsa-food-hygiene-leads/run-sync-get-dataset-items` |

---

## Quickstart: Use All 11 Actors in Claude Desktop or Cursor via MCP

Copy [`integrations/mcp/claude_cursor_mcp_config.json`](./integrations/mcp/claude_cursor_mcp_config.json) into your `claude_desktop_config.json` or `.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "apify-b2b-intelligence-suite": {
      "command": "npx",
      "args": [
        "-y",
        "@apify/actors-mcp-server",
        "--actors",
        "coherent_edelweiss/google-maps-b2b-enricher,coherent_edelweiss/verified-email-contact-finder,coherent_edelweiss/apollo-b2b-lead-enricher,coherent_edelweiss/zoominfo-lusha-waterfall-enricher,coherent_edelweiss/shopee-lazada-sea-ecommerce-api,coherent_edelweiss/mcp-server-ecosystem-index,coherent_edelweiss/uk-planning-construction-leads,coherent_edelweiss/sec-iapd-ria-wealth-enricher,coherent_edelweiss/uk-cqc-care-homes-enricher,coherent_edelweiss/us-npi-healthcare-enricher,coherent_edelweiss/uk-fsa-food-hygiene-leads"
      ],
      "env": {
        "APIFY_TOKEN": "YOUR_APIFY_TOKEN"
      }
    }
  }
}
```

---

## Quickstart: 1-Click n8n & Clay.com Blueprints

- **n8n Workflows:** Import any `.n8n.json` file from [`integrations/n8n/`](./integrations/n8n/) directly into n8n.
- **Clay.com HTTP API Columns:** Copy the endpoint and JSON body from [`integrations/clay/clay_http_api_columns.json`](./integrations/clay/clay_http_api_columns.json).
- **Sample Output Datasets:** Inspect verified sample outputs in [`samples/sample_datasets.json`](./samples/sample_datasets.json).
