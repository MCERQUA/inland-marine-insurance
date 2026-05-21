# SEO Report — inland-marine-insurance
Date: 2026-05-21

## 1. Site Identity
- **Framework**: Static HTML (single-page application)
- **Apparent domain / target audience / niche**: Contractors Choice Agency; target audience is contractors/tradespeople needing inland marine & tool equipment insurance; niche is construction equipment insurance via text-based quoting
- **Deployment status**: GitHub-hosted repo (git@github-inland-marine-insurance:MCERQUA/inland-marine-insurance.git); likely deployed via GitHub Pages or Vercel (no vercel.json or netlify.toml found)

## 2. Inventory
- **Total pages**: 1 (.html file — index.html only)
- **URL structure**: Single landing page, no nested structure
- **sitemap.xml present?**: No
- **robots.txt present?**: No

## 3. On-Page SEO (sample up to 10 pages)

### index.html
- **Title tag**: "Inland Marine & Tool Equipment Insurance — Contractors Choice Agency" (78 characters — **GOOD**, within 50-60 ideal but acceptable)
- **Meta description**: **MISSING** — no meta description tag found
- **H1**: "INLAND MARINE & TOOL EQUIPMENT INSURANCE" (present, semantically correct but styled in span split)
- **Canonical**: Not present (single page, not critical but good practice)
- **OG tags**: **MISSING** — no Open Graph tags for social sharing (og:title, og:description, og:image, etc.)

## 4. Structured Data
- **JSON-LD schema.org types**: **NONE DETECTED** — no LocalBusiness, Organization, LocalService, Service, or other schema.org markup present

## 5. Content Quality
- **Word count**: ~143 words of body text (index.html only) — **VERY LOW** for SEO; minimal content depth
- **Internal linking density**: 0 internal links (only tel: and mailto: links) — **POOR**
- **Image count + alt-text coverage**: 0 images — no visual content, no alt-text issues but missed opportunity for rich media

## 6. Technical
- **robots.txt rules**: Not present — search engines will use defaults
- **Sitemap URL count**: No sitemap — single page, not critical but missing for crawlability hints
- **404 handling**: Not configured (single static file)
- **Meta tags present**: Charset (UTF-8) ✓ | Viewport ✓ | Description ✗ | OG tags ✗

## 7. Top Issues (ranked by impact)

1. **Missing meta description** — index.html lacks `<meta name="description">` tag; search results will use auto-generated snippets (index.html, line 1-10)
2. **No structured data markup** — zero schema.org JSON-LD; missing Organization, LocalBusiness, and Service schema (index.html, lines 1-409)
3. **Extremely thin content** — 143 words across entire site; insufficient for SEO authority and keyword targeting (index.html, lines 269-371)
4. **No Open Graph tags** — missing og:title, og:description, og:image, og:url; social shares will not display properly (index.html, lines 1-10)
5. **No robots.txt file** — no explicit crawl directives or sitemap reference (missing file)
6. **No canonical tag** — single page, not critical, but best practice for large sites not followed (index.html, lines 1-10)
7. **No sitemap.xml** — single page doesn't require, but reinforces lack of SEO infrastructure
8. **Single-page site with no internal linking** — no opportunity for PageRank distribution; no silos for topic clustering (index.html)

## 8. Top Recommendations (concrete next actions)

1. **Add meta description tag** — Insert `<meta name="description" content="Get inland marine & tool equipment insurance quotes instantly by text. Contractors Choice Agency — fast, flexible coverage for construction equipment.">` in `<head>` (target 150-160 characters)

2. **Implement Organization + LocalBusiness schema.org** — Add JSON-LD block in `<head>` with name, address (12220 E Riggs Rd, Chandler, AZ 85249), phone, email, and service area to improve local SEO and knowledge panel eligibility

3. **Add Open Graph tags** — Include `og:title`, `og:description`, `og:image`, `og:url`, `og:type` for proper social media previews when link is shared

4. **Expand content to 300+ words** — Add sections on coverage types, benefits, company background, service area, or FAQs to improve keyword relevance and dwell time

5. **Create robots.txt** — Add basic rules with Sitemap reference (even single-page sites benefit from explicit directives) and allow all crawlers

6. **Add alt-text and images** — Insert hero image of equipment/contractors with descriptive alt-text to increase page richness and visual engagement

7. **Implement schema for FAQs or BreadcrumbList** — If multi-page site planned, structure for nested navigation; for single page, add FAQSchema for common questions (coverage limits, turnaround time, service areas)

8. **Set up Google Search Console & Analytics** — Verify site ownership, monitor search performance, crawl errors, and user engagement; track phone and form submissions separately

## Round 2 — repaired 2026-05-21
- sitemap.xml: created at `/workspace/Websites/inland-marine-insurance/sitemap.xml` with **1** URL (homepage)
- robots.txt: created at `/workspace/Websites/inland-marine-insurance/robots.txt`
- Domain used: **`https://example.com`** — **FLAGGED**: no production domain detectable from `index.html` (no canonical), `git remote` (only repo URL `MCERQUA/inland-marine-insurance.git`), no `package.json`, no `netlify.toml`/`vercel.json`, no `README`. Placeholder used. Replace with real production domain once deployed.
- Framework detected: **Static HTML** (single `index.html`, no build tooling, no `package.json`, no framework dependencies)
- Files changed:
  - Created: `/workspace/Websites/inland-marine-insurance/sitemap.xml`
  - Created: `/workspace/Websites/inland-marine-insurance/robots.txt`
  - Modified: `/workspace/Websites/inland-marine-insurance/index.html` (added `<meta name="robots" content="index, follow">` to `<head>`)
- meta robots tag: **added** (was missing — inserted between viewport and title)
- Sitemap XML validated well-formed via `xml.etree.ElementTree`

