# B2B Lead Enrichment, Contact Waterfall & Public Registry Suite (`coherent_edelweiss`)

Real-time **B2B Lead Enrichment, Live DNS-over-HTTPS MX Email Verification, Website Tech-Stack & Ad-Pixel Detection, and Public Registry Intelligence APIs** for **Clay.com**, **n8n**, **Make.com**, and **AI Agents (MCP)**.

### Why Teams Use This Suite
- **Pay-Per-Result ($0 on Empty Lookups):** Pay only `$0.002–$0.007` when a verified record is returned—you are never charged for dead domains or empty searches.
- **Live DNS MX Email Verification & Gateway Fingerprinting:** Every domain is checked in real time against Google DNS-over-HTTPS (`https://dns.google/resolve`) to confirm active mail servers and classify the mail gateway (`Google Workspace`, `Microsoft 365`, `Proofpoint`, `Mimecast`, `Cloudflare`).
- **Website CMS, Ad Pixel & CRM Detection:** Automatically detects `Shopify`, `WordPress`, `Webflow`, `Next.js`, retargeting pixels (`meta_pixel`, `google_tag_manager`, `tiktok_pixel`, `linkedin_insight`), and booking/CRM tools (`Calendly`, `HubSpot`, `Intercom`, `Klaviyo`).
- **UK & EU GDPR Safe-by-Design (`gdprSafeMode`):** Automatically filters out personal emails and personal LinkedIn `/in/` URLs on UK/EEA domains (`.uk`, `.co.uk`, `.eu`, `.de`, `.fr`, etc.), returning compliant corporate role accounts (`info@`, `sales@`, `enquiries@`).

---

## Live Apify Store Catalog (12 Specialized B2B Actors)

| Category | Actor & Apify Store Link | What It Extracts | Synchronous HTTP Endpoint (`POST`) |
| :--- | :--- | :--- | :--- |
| **B2B Lead & Contact Waterfall** | **[Google Maps B2B Lead, Email & Tech-Stack Enricher](https://apify.com/coherent_edelweiss/google-maps-b2b-enricher)** (`coherent_edelweiss/google-maps-b2b-enricher`) | Google Maps Email, Lead & Tech Stack Scraper (MX Verified) | `https://api.apify.com/v2/acts/coherent_edelweiss~google-maps-b2b-enricher/run-sync-get-dataset-items` |
| **B2B Lead & Contact Waterfall** | **[Verified B2B Email, Contact & Tech-Stack Finder](https://apify.com/coherent_edelweiss/verified-email-contact-finder)** (`coherent_edelweiss/verified-email-contact-finder`) | Verified B2B Email Finder, MX Checker & Tech Stack Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~verified-email-contact-finder/run-sync-get-dataset-items` |
| **B2B Lead & Contact Waterfall** | **[Apollo.io B2B Leads, Org & Verified Email Enricher](https://apify.com/coherent_edelweiss/apollo-b2b-lead-enricher)** (`coherent_edelweiss/apollo-b2b-lead-enricher`) | Apollo.io B2B Lead & Email Enricher API (No Login Cookies) | `https://api.apify.com/v2/acts/coherent_edelweiss~apollo-b2b-lead-enricher/run-sync-get-dataset-items` |
| **B2B Lead & Contact Waterfall** | **[ZoomInfo & Lusha B2B Company & Contact Waterfall API](https://apify.com/coherent_edelweiss/zoominfo-lusha-waterfall-enricher)** (`coherent_edelweiss/zoominfo-lusha-waterfall-enricher`) | ZoomInfo & Lusha B2B Contact Waterfall & Tech Stack API | `https://api.apify.com/v2/acts/coherent_edelweiss~zoominfo-lusha-waterfall-enricher/run-sync-get-dataset-items` |
| **E-Commerce & Retail Intelligence** | **[Shopee & Lazada SEA Product, Price & Velocity API](https://apify.com/coherent_edelweiss/shopee-lazada-sea-ecommerce-api)** (`coherent_edelweiss/shopee-lazada-sea-ecommerce-api`) | Shopee & Lazada Scraper API (SG, MY, ID, TH, PH, VN) | `https://api.apify.com/v2/acts/coherent_edelweiss~shopee-lazada-sea-ecommerce-api/run-sync-get-dataset-items` |
| **AI & Developer Ecosystem** | **[MCP Server Registry, AI Tool & Maintainer Lead Enricher](https://apify.com/coherent_edelweiss/mcp-server-ecosystem-index)** (`coherent_edelweiss/mcp-server-ecosystem-index`) | MCP Server Registry, AI Tool & Maintainer Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~mcp-server-ecosystem-index/run-sync-get-dataset-items` |
| **Construction & Property Intelligence** | **[UK Planning Applications & Construction Lead Enricher](https://apify.com/coherent_edelweiss/uk-planning-construction-leads)** (`coherent_edelweiss/uk-planning-construction-leads`) | UK Planning Applications & Construction Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-planning-construction-leads/run-sync-get-dataset-items` |
| **Wealth Management & Financial Filings** | **[SEC IAPD Registered Investment Adviser & Wealth Enricher](https://apify.com/coherent_edelweiss/sec-iapd-ria-wealth-enricher)** (`coherent_edelweiss/sec-iapd-ria-wealth-enricher`) | SEC IAPD Registered Investment Adviser & Wealth RIA API | `https://api.apify.com/v2/acts/coherent_edelweiss~sec-iapd-ria-wealth-enricher/run-sync-get-dataset-items` |
| **Healthcare & Medical Licensing** | **[UK CQC Care Homes, Private Clinics & Healthcare Enricher](https://apify.com/coherent_edelweiss/uk-cqc-care-homes-enricher)** (`coherent_edelweiss/uk-cqc-care-homes-enricher`) | UK CQC Care Homes, Private Clinics & Healthcare Lead API | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-cqc-care-homes-enricher/run-sync-get-dataset-items` |
| **Healthcare & Medical Licensing** | **[US CMS NPI Healthcare Provider & Medical Practice Enricher](https://apify.com/coherent_edelweiss/us-npi-healthcare-enricher)** (`coherent_edelweiss/us-npi-healthcare-enricher`) | US CMS NPI Healthcare Provider & Medical Clinic Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~us-npi-healthcare-enricher/run-sync-get-dataset-items` |
| **Hospitality & Food Service** | **[UK FSA Food Hygiene Ratings & Hospitality Lead Enricher](https://apify.com/coherent_edelweiss/uk-fsa-food-hygiene-leads)** (`coherent_edelweiss/uk-fsa-food-hygiene-leads`) | UK FSA Food Hygiene Ratings & Restaurant Lead Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-fsa-food-hygiene-leads/run-sync-get-dataset-items` |
| **Public Procurement & GovTech** | **[UK Public Tenders & Contract Awards Lead Enricher](https://apify.com/coherent_edelweiss/uk-public-tenders-contracts-finder)** (`coherent_edelweiss/uk-public-tenders-contracts-finder`) | UK Public Tenders & Contract Awards Scraper | `https://api.apify.com/v2/acts/coherent_edelweiss~uk-public-tenders-contracts-finder/run-sync-get-dataset-items` |

---

## Quickstart 1: Use in Clay.com (HTTP API Column)

Skip expensive enrichment credits in Clay by adding an **HTTP API** column pointing to any Actor above:
1. **Method:** `POST`
2. **URL:** `https://api.apify.com/v2/acts/coherent_edelweiss~verified-email-contact-finder/run-sync-get-dataset-items?token=YOUR_APIFY_TOKEN`
3. **Headers:** `Content-Type: application/json`
4. **Body:** See ready-to-copy templates for all 12 Actors in [`integrations/clay/clay_http_api_columns.json`](./integrations/clay/clay_http_api_columns.json).

---

## Quickstart 2: Import 1-Click n8n Workflows

Import any workflow from [`integrations/n8n/`](./integrations/n8n/) directly into n8n (**Workflows → Import from File**):
- [`google-maps-to-mx-verified-crm.n8n.json`](./integrations/n8n/google-maps-to-mx-verified-crm.n8n.json) — Google Maps Local Leads → DNS MX Email & Ad Pixel Enricher → CRM
- [`apollo-domain-waterfall.n8n.json`](./integrations/n8n/apollo-domain-waterfall.n8n.json) — Cookie-Free Apollo B2B Lead & MX Email Enricher → Outbound Sequence
- [`uk-planning-construction-alerts.n8n.json`](./integrations/n8n/uk-planning-construction-alerts.n8n.json) — UK Local Authority Planning Applications → Architect Role Email Enricher
- [`us-npi-healthcare-lead-pipeline.n8n.json`](./integrations/n8n/us-npi-healthcare-lead-pipeline.n8n.json) — US CMS NPI Healthcare Provider & Clinic Lead Pipeline
- [`shopee-lazada-sea-price-monitor.n8n.json`](./integrations/n8n/shopee-lazada-sea-price-monitor.n8n.json) — Shopee & Lazada SEA Multi-Currency Price & 30d Sales Velocity Tracker

---

## Quickstart 3: Connect All 12 Actors to Claude Desktop or Cursor (MCP)

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
        "coherent_edelweiss/google-maps-b2b-enricher,coherent_edelweiss/verified-email-contact-finder,coherent_edelweiss/apollo-b2b-lead-enricher,coherent_edelweiss/zoominfo-lusha-waterfall-enricher,coherent_edelweiss/shopee-lazada-sea-ecommerce-api,coherent_edelweiss/mcp-server-ecosystem-index,coherent_edelweiss/uk-planning-construction-leads,coherent_edelweiss/sec-iapd-ria-wealth-enricher,coherent_edelweiss/uk-cqc-care-homes-enricher,coherent_edelweiss/us-npi-healthcare-enricher,coherent_edelweiss/uk-fsa-food-hygiene-leads,coherent_edelweiss/uk-public-tenders-contracts-finder"
      ],
      "env": {
        "APIFY_TOKEN": "YOUR_APIFY_TOKEN"
      }
    }
  }
}
```

---

## Sample Input & Enriched Output Datasets

Inspect complete sample inputs and verified JSON outputs for all 12 Actors in [`samples/sample_datasets.json`](./samples/sample_datasets.json).
